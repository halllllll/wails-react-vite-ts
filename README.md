# README

- [wails](https://wails.io/)

## About
wailsのフロントエンドをviteで`react-swc-ts`にしたテンプレート
|||
|-|-|
|Vite|v5|
|React|v18|
|TypeScript|v5|


フロントエンドのパッケージインストールおよび実行に`bun`を使っているので，`bun`が無い環境では動かないかもしれません。またESLintを剥がして`biome`を使っています

## useage

vscodeの場合`-ide vscode`オプションを使うと便利です

```
wails init -n sample -t https://github.com/halllllll/wails-react-vite-ts -ide vscode
```

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend`
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this in your
browser and connect to your application.

## Building

To build a redistributable, production mode package, use `wails build`.
