```bash
dotnet publish -c Release -r win10-x64 /p:PublishSingleFile=true /p:PublishTrimmed=true

sudo dotnet publish -c Release -r linux-x64 --self-contained true /p:PublishTrimmed=true
```