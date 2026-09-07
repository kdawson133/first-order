# first-order
First Order is an sddm theme with a Star Wars motif.

It is based on the [pixie-sddm theme by XCaptaiN09](https://github.com/xCaptaiN09/pixie-sddm).

## Installation

### Dependencies

- sddm
- qt6-declarative 
- qt6-svg 

See the above link for legacy distro requirements. 

To install these in Arch Linux for example;

```
sudo pacman -S sddm qt6-declarative qt6-svg
```

### Copy The Theme

Copy the `first-order` directory to `/usr/share/sddm/themes/` directory by;

```
sudo cp -R first-order/ /usr/share/sddm/themes/
```
### Set The theme

Edit the `/etc/sddm.conf` file to look like;

```
[Theme]
Current=first-order
```
***Make sure you have enabled the `sddm.service` with `sudo systemctl enable sddm.service` and then reboot.***

