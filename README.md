## Windows
  
Windows wallpapers  
  
Automatic install/update:
  
```shell
bash -c "$(curl -LSs https://github.com/wallpapermgr/Windows/raw/master/install.sh)"
```
  
Manual install:
  
```shell
git clone https://github.com/wallpapermgr/Windows "$HOME/.local/share/wallpapers/Windows"
```
  
Manual update
  
```shell
git -C "$HOME/.local/share/wallpapers/Windows" pull https://github.com/wallpapermgr/Windows  
```
