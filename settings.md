## 輸入法
```
sudo pacman -S fcitx5-im fcitx5-chewing fcitx5-qt fcitx5-gtk fcitx5-chinese-addons

```

編輯環境變數 ： `sudo vim /etc/environment`，加入以下內容
```
GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
SDL_IM_MODULE=fcitx
GLFW_IM_MODULE=fcitx

```
在 System Settings -> Input Method 中加入 chewing
