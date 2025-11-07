
### INSTALLER UPDATE
git add Mojo-installer.exe
git commit -m "update: new version v0.0.1"
git push origin main
git tag v0.0.1
git push origin v0.0.1

### remove tag
local: git tag -d v0.0.1
remote server: git push origin :refs/tags/v0.0.1

create release manually