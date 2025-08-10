# Fonts
> For my personal use only.  

## Patched Fonts
- [SF Mono](./patched/SFMono/)
- [Hack 4.000](./patched/Hack/)

## Patch

```shell
mkdir patch && cd patch

# clone nerd-fonts/font-patcher
git clone --depth=1 https://github.com/ryanoasis/nerd-fonts.git

# clone patch-font
git clone https://github.com/zzhaolei/fonts.git

cd fonts/patched
mkdir -p tmp/patched
cp ~/Library/Fonts/SF-Mono-* ./tmp
./patch-sfmono
```
