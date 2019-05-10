# T4GenericsExample
Example of T4 generation of multiple versions of a generic interface.
There is the `IGeneric<T>` interface.
T4 is used to generate specific implementation of this interface for `UInt64`, `UInt32`, `UInt16` and `Byte` types.
All implementation share single base template `GenericClassGenerator.tt`.

## Setup
Requires .NET Core 2.2 SDK and Runtime.

https://dotnet.microsoft.com/download

## Run
```
dotnet run
```