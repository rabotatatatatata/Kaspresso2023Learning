[kaspresso](../../index.md) / [com.kaspersky.kaspresso.device.server](../index.md) / [AdbServerImpl](index.md) / [performShell](./perform-shell.md)

# performShell

`fun performShell(vararg commands: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`

Overrides [AdbServer.performShell](../-adb-server/perform-shell.md)

Performs shell commands blocking current thread.
Please be aware! If any command that is in @param commands failed then AdbServerException will be thrown

Required Permissions: INTERNET.

### Parameters

`commands` - commands to execute.

### Exceptions

`AdbServerException` - if a result status of any command in @param commands is Failed

**Return**
list of answers of commands' execution
