# ZExtract

Steam .z file extraction utility.  Useful for those who download workshop files for servers using the steamcmd CLI.

## Download

See [Releases](https://github.com/davidruhmann/ZExtract/releases) for the CLI.

Or [Packages](https://github.com/davidruhmann/ZExtract/packages) for the NuGet package. (Also available at [NuGet.org](https://www.nuget.org/packages/ZExtract/))

Or build your own from source.

```bash
dotnet add package ZExtract
```

## Usage

```bash
dotnet ZExtractCLI myFile.asset.z outputDirectory\
```

Will extract the .z file to `outputDirectory\myFile.asset`

## Build

Checkout and run...

```bash
dotnet publish -c Release -o publish
```

then execute `publish/ZExtractCLI`
