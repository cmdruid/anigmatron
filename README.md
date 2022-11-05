# Anigmatron

An electron clone of anigma, which is a clone of telegram, built on nostr.

## How to Use

```bash
## Clone this repository and install packages.
git clone <this repo url>
cd anigmatron
npm install || yarn install

## Start via Electron-Forge.
yarn start

## Or install via a native binary. Example:
dpkg -i out/make/deb/x64/anigmatron_x.x.x_amd64.deb

## If you have trouble installing the .deb, 
## you may need additional dependencies.
sudo apt install zstd # needed for decompressing the .deb

## If you don't see a binary for your OS, make one!
yarn make

## Follow instructions on how to make a binary for 
## your own operating system here:
https://www.electronforge.io
```

## Resources

**Electron**  
https://www.electronjs.org

**Electron Forge**  
https://www.electronforge.io

**Anigma**  
https://anigma.io

**Nostrgram**  
https://github.com/brilliancebitcoin/nostrgram
