# OpenH264 and ffmpeg for Windows x64 野良ビルド

## OpenH264

- ビルドオプション

> make ARCH=x86_64 LDFLAGS="-static-libgcc -static-libstdc++"

## ffmpeg

- ビルドオプション

> $ ./configure --prefix=/home/mao/ffmpeg-build --disable-logging --disable-gpl --enable-version3 --enable-static --enable-shared --disable-doc --disable-htmlpages --disable-manpages --disable-podpages --disable-txtpages --disable-avdevice --disable-postproc --disable-bzlib --disable-iconv --enable-libopenh264 --disable-debug --enable-cuda --enable-cuvid --enable-nvenc --enable-hwaccel=h264_dxva2 --enable-libmfx --enable-optimizations --extra-ldflags="-static"

## その他

- ビルド手順
  - [Qiita](https://qiita.com/maosec/items/dd2a3cab64579a008c20)



