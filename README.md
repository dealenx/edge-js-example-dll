# An example of calling C# DLLs from a Node.js with edge-js

## Requirements

- Microsoft .NET Framework v4.0
- Node.js v14

## Install

```
git clone https://github.com/dealenx/edge-js-example-dll
cd edge-js-example-dll
npm install
```

## Compiling .cs file to DLL

```
cvs /target:library Sample105.cs
```

or

```
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /target:library Sample105.cs

```

If path not found then replace `v4.0.30319` on other version

So you will get a DLL file `Sample105.dll`

## Running index.js

```
node index.js
```

out:

```
22
```
