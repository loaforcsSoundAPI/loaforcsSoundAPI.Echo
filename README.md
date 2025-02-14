# Echo Loader
Ports mods from CustomSounds to SoundAPI

## Development
In order to fetch CustomSounds you must run:
```shell
dotnet build -t:FetchCustomSounds
```
then run restore to make sure the publicizer has worked correctly.
```shell
dotnet restore
```