# Notion for Linux

This is a meta repo that contains scripts / stuff needed to build Notion for Linux

## How?

The electron sources are pulled out of the Mac OSX dmg and then ran with a Linux version of Electron, yeah, it's that easy.

## Building

Run `./build.sh [--no-compress]`

## Customizing

Modify `config.sh` before running `build.sh` or `makepkg -si`

```bash
ELECTRON_VERSION=x.x.x electron version to use
NOTION_VERSION=x.x.x notion dmg to download
```

## License

MIT