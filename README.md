# Vesktop (uncute edition)

### Downloads for linux can be found [here](https://github.com/aapelix/Vesktop/releases/latest)
### for other operating systems see [building from source](#building-from-source) below

Vesktop is a custom Discord desktop app

**Main features**:
- Vencord preinstalled
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & wayland
- Much better privacy, since Discord has no access to your system

**Not yet supported**:
- Global Keybinds
- see the [Roadmap](https://github.com/Vencord/Vesktop/issues/324)

![](https://github.com/Vencord/Vesktop/assets/45497981/8608a899-96a9-4027-9725-2cb02ba189fd)
![](https://github.com/Vencord/Vesktop/assets/45497981/8701e5de-52c4-4346-a990-719cb971642e)

## Installing

### Building from Source

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/aapelix/Vesktop
cd Vesktop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --windows
# Or package to a directory only
pnpm package:dir
```

# Huge thanks to https://github.com/Covkie for making the icons. Hoping I can even use them :skull:
