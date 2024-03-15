# JON DOCUMENTATION

## System Requirement

- Node 20.x.x

## Configuration TS

- Pastikan typescript sudah terinstal secara global. Untuk mengecek apakah typescript sudah terinstal secara global adalah dengan sintak berikut di terminal(powerhsell/git base):
  - $ tsc --version
- Jika typescript belum terinstal secara global, install dulu seperti ini:
  -$ npm i -g typescript
- Setelah itu baru lakukan init untuk typescript nya dengan cara di terminal:
  - $ tsc --init
- Setelah itu, nanti akan ada file "tsconfig.json".
- Kemudian pada file "tsconfig.json", silahkan aktifkan sintak berikut dan samakan seperti berikut:
  - "rootDir": "./src",
  - "outDir": "./bundle",

## Running project

- Untuk melakukan running, bosa melakukan dengan sintak di terminal(powerhsell/git base) seperti ini:
  - $ tsc
  - atau
  - $ tsc && node bundle/index.js
