# JPEG→WebP画像変換ライブラリをWebAssemblyでブラウザ上で動かすサンプル

## 参照元

https://developer.mozilla.org/ja/docs/WebAssembly/existing_C_to_wasm

## ライブラリのソースコードを取得

```
> cd src/webp
> git clone https://github.com/webmproject/libwebp
```

## emccでWASMにコンパイル

```
> ./compile.sh
```

## 簡易Webサーバーを起動してブラウザで動作確認

```
./serve.sh
```

http://localhost:5000



