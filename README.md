# Linux Customization

|                                                                                                                          |                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| ![Desktop](https://res.cloudinary.com/dtdhmbtcg/image/upload/v1726353481/Screenshot_from_2024-09-15_04-06-35_a97pmb.png) | ![Terminal](https://res.cloudinary.com/dtdhmbtcg/image/upload/v1726353474/Screenshot_from_2024-09-15_04-07-35_nyjovk.png) |

## Step 1 - [Terminal Customization](https://youtu.be/b3W7Ky_aaaY?si=NJU-NSETV0JueL6O)

- Open Terminal (Ctrl+Shift+T)
- Download and Install fastfetch.

```bash
sudo add-apt-repository ppa:zhangsongcui3371/fastfetch
sudo apt update
sudo apt install fastfetch git curl zoxide
sudo apt update && sudo apt upgrade
```

```bash
mkdir github && cd github
git clone https://github.com/christitustech/mybash
```

```bash
cd ./mybash/ && sudo ./setup.sh
```

- Apply any nerd font in terminal.

## Step 2 - [Update ~/.bashrc](https://gist.github.com/rohitprofc/8f82fc044cfd3051c8679e12c336b69b)

- Open Terminal (Ctrl+Shift+T)

```bash
sudo apt install gedit && sudo gedit ~/.bashrc # if not exist before
```

- Replace that text with [this](https://gist.githubusercontent.com/rohitprofc/8f82fc044cfd3051c8679e12c336b69b/raw/6e66e69b77e40dfbfc5dd31604aa7872d676620b/bashrc.md) text.

- Save (Ctrl+s) and close.

## Step 3 - [Clone this Repository]()

- Open Terminal (Ctrl+Shift+T)

```bash
mkdir customization && cd customization
git clone && cd ./linux-customization/
```

- Unzip zip files in subfolders to directly use upcoming commands.

```bash
sudo apt install unzip
unzip ./cursors/Bibata-Modern-Ice.tar.xz
unzip ./grub-theme/ubuntu-1080p.zip
unzip ./grub-theme/Vimix-1080p.tar.xz
unzip ./gtk-theme/Material-Black-Blueberry-2.9.9-07.tar
unzip ./icons/kora-1-6-7.tar.xz
unzip ./shell-theme/01-Flat-Remix-Blue-20240813.tar.xz
```

## Step 4 - [GNOME Customization](https://www.gnome-look.org/browse/)

### 1 - [Wallpaper](./wallpapers/)

- Open Terminal (Ctrl+Shift+T).

```bash
sudo /home/$USER/customization/linux-customization/wallpapers/Easy_Install.sh
```

### 2 - [Icons](./icons/)

- Open Terminal (Ctrl+Shift+T).

```bash
mkdir .icons # if not exist before
```

```bash
sudo cp -r /home/$USER/customization/linux-customization/icons/kora-1-6-7/kora /home/$USER/.icons
```

### 3 - [Cursors](./cursors/)

<!-- - make sure you have `index.theme` file in folder which you are going to copy. -->

- Open Terminal (Ctrl+Shift+T).

```bash
sudo cp -r /home/$USER/customization/linux-customization/cursors/Bibata-Modern-Ice /home/$USER/.icons
```

### 4 - [Shell Theme](./shell-theme/)

- Open Terminal (Ctrl+Shift+T).

```bash
mkdir .themes # if not exist before
```

```bash
sudo cp -r /home/$USER/customization/linux-customization/shell-theme/01-Flat-Remix-Blue-20240813/Flat-* /home/$USER/.themes
```

### 5 - [GTK Theme](./gtk-theme/)

- Open Terminal (Ctrl+Shift+T).

```bash
sudo cp -r /home/$USER/customization/linux-customization/gtk-theme/Material-Black-Blueberry-2.9.9-07/Material-Black-Blueberry /home/$USER/.themes
```

### 6 - [GRUB Theme](./grub-theme/)

- Open Terminal (Ctrl+Shift+T).

```bash
sudo /home/$USER/customization/linux-customization/grub-theme/grub-theme/Vimix-1080p/install.sh
```

- Copy theme in grub directory.

```bash
sudo cp -r /home/$USER/customization/linux-customization/grub-theme/Vimix-1080p/Vimix /boot/grub/themes/
```

- Edit GRUB file.

```bash
sudo gedit /etc/default/grub
```

- Goto end of the file.

```bash
GRUB_THEME="/boot/grub/themes/Vimix/theme.txt"
```

- Update GRUB.

```bash
sudo update-grub
```

## Step 5 - [GNOME Tweaking](https://extensions.gnome.org/)

### Install [Extensions](https://extensions.gnome.org/)

- User Themes
- User Themes X
- Blur my shell
- Burn My Windows (Glide)
- Compiz alike magic lamp effect
- Coverflow Alt-Tab (Customize)
- Emoji Copy
- Net Speed
- RunCat

### Open `extensions` app and tweak User Themes X.

![User Theme X](https://res.cloudinary.com/dtdhmbtcg/image/upload/v1726352372/Screenshot_from_2024-09-15_03-47-15_ea403f.png)

## Step 6 - Finishing Touch

### Goto Settings > Accessibility > Seeing >

![Accessibility Settings](https://res.cloudinary.com/dtdhmbtcg/image/upload/v1726354588/Screenshot_from_2024-09-15_04-26-11_n4hvrd.png)

### Goto Tweaks > [Fonts]() >

![Gnome Tweaks](https://res.cloudinary.com/dtdhmbtcg/image/upload/v1726356268/Screenshot_from_2024-09-15_04-54-10_rftpfa.png)

# Linux🐧 Love❤️
