# XLibre for VOID linux  ![void](https://github.com/sofijacom/yandex-browser/assets/107557749/0cb14595-dcea-4f79-84a4-0185b1df379d)


> _**repository provides binary packages for:** x86_64-glibc_


> [!NOTE]
>>  _How to use_
>>> _type in the terminal_

```
printf "repository=https://github.com/sofijacom/xlibre/releases/latest/download/\n" | sudo tee /etc/xbps.d/99-repository-xlibre.conf
```

> [!IMPORTANT]
> 
> _Synchronize the repository `sudo xbps-install -S` and accept the fingerprint (Y)_

```shell
sudo xbps-install -S
```

You should now be able search through all xlibre related packages provided by this repository, and install packages as usual:
```
sudo xbps-query -Rs xlibre
sudo xbps-install -S xlibre xlibre-server xlibre-xf86-input-evdev xlibre-xf86-input-libinput
```

<img width="750" height="517" alt="Снимок экрана_20251123_231301" src="https://github.com/user-attachments/assets/1f708abb-1fc3-40c8-bdb8-41788ac35caf" />


_These packages will now be in your **OctoXBPS** package manager. When a new version of the packages is released, you will update it along with all the other packages._


# Available packages
| package | source | automatic update |
|:--------|:-------|:-----------------|
| xlibre                              | https://github.com/X11Libre/xserver/                    | :heavy_check_mark: |
| xlibre server                       | https://github.com/X11Libre/xserver/                    | :heavy_check_mark: |
| xlibre-server-common                | https://github.com/X11Libre                             | :heavy_check_mark: |
| xlibre-server-devel                 | https://github.com/X11Libre                             | :heavy_check_mark: |
| xlibre-server-xephyr                | https://github.com/X11Libre                             | :heavy_check_mark: |
| xlibre-server-xnest                 | https://github.com/X11Libre                             | :heavy_check_mark: |
| xlibre-server-xvfb                  | https://github.com/X11Libre                             | :heavy_check_mark: |
| xlibre-xf86-input-evdev             | https://github.com/X11Libre/xf86-input-evdev            | :heavy_check_mark: |
| xlibre-xf86-input-evdev-devel       | https://github.com/X11Libre/xf86-input-evdev            | :heavy_check_mark: |
| xlibre-xf86-input-libinput          | https://github.com/X11Libre/xf86-input-libinput         | :heavy_check_mark: |
| xlibre-xf86-input-libinput-devel    | https://github.com/X11Libre/xf86-input-libinput         | :heavy_check_mark: |
| xlibre-xf86-input-synaptics         | https://github.com/X11Libre/xf86-input-synaptics        | :heavy_check_mark: |
| xlibre-xf86-input-synaptics-devel   | https://github.com/X11Libre/xf86-input-synaptics        | :heavy_check_mark: |
| xlibre-xf86-input-joystick          | https://github.com/X11Libre/xf86-input-joystick         | :heavy_check_mark: |
| xlibre-xf86-input-joystick-devel    | https://github.com/X11Libre/xf86-input-joystick         | :heavy_check_mark: |
| xlibre-xf86-input-elographics       | https://github.com/X11Libre/elographics                 | :heavy_check_mark: |
| xlibre-xf86-input-wacom             | https://github.com/X11Libre/xf86-input-wacom            | :heavy_check_mark: |
| xlibre-xf86-input-wacom-devel       | https://github.com/X11Libre/xf86-input-wacom            | :heavy_check_mark: |
| xlibre-xf86-input-vmmouse           | https://github.com/X11Libre/xf86-input-vmmouse          | :heavy_check_mark: |
| xlibre-xf86-input-void              | https://github.com/X11Libre/xf86-input-void             | :heavy_check_mark: |
| xlibre-xf86-video-amdgpu            | https://github.com/X11Libre/xf86-video-amdgpu           | :heavy_check_mark: |
| xlibre-xf86-video-ati               | https://github.com/X11Libre/xf86-video-ati              | :heavy_check_mark: |
| xlibre-xf86-video-nouveau           | https://github.com/X11Libre/xf86-video-nouveau          | :heavy_check_mark: |
| xlibre-xf86-video-intel             | https://github.com/X11Libre/xf86-video-intel            | :heavy_check_mark: |
| xlibre-xf86-video-dummy             | https://github.com/X11Libre/xf86-video-dummy            | :heavy_check_mark: |
| xlibre-xf86-video-fbdev             | https://github.com/X11Libre/xf86-video-fbdev            | :heavy_check_mark: |
| xlibre-xf86-video-vesa              | https://github.com/X11Libre/xf86-video-vesa             | :heavy_check_mark: |
| xlibre-xf86-video-vmware            | https://github.com/X11Libre/xf86-video-vmware           | :heavy_check_mark: |
| xlibre-xf86-video-sisusb            | https://github.com/X11Libre/xf86-video-sisusb           | :heavy_check_mark: |
| xlibre-xf86-video-qxl               | https://github.com/X11Libre/xf86-video-qxl              | :heavy_check_mark: |
| xlibre-xf86-video-voodoo            | https://github.com/X11Libre/xf86-video-voodoo           | :heavy_check_mark: |
| xlibre-xf86-video-cirrus            | https://github.com/X11Libre/xf86-video-cirrus           | :heavy_check_mark: |
| xlibre-xf86-video-r128              | https://github.com/X11Libre/xf86-video-r128             | :heavy_check_mark: |
| xlibre-xf86-video-mga               | https://github.com/X11Libre/xf86-video-mga              | :heavy_check_mark: |
