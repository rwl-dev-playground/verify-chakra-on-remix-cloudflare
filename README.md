# Verify Chakra UI in Remix on Cloudflare

## 本リポジトリの目的
Remix上のChakra UIがCloudflare(PagesやWorker)で動くか検証する。  
比較対象としてRemix App Serverでの動作検証も行なう。

## 本リポジトリの達成目標
Cloudflare上でChakra UIがエラーなく動作すること。

## タスクリスト
- [x] 初期起動試験（`pnpm dev`）
  - [x] Remix App Server
  - [x] Cloudflare Pages
  - [x] Cloudflare Workers
- [ ] Chakra UI起動試験（`pnpm dev`）
  - [ ] Remix App Server
  - [ ] Cloudflare Pages
  - [ ] Cloudflare Workers

## 構成
### Remix App Server
![起動時の選択オプション](./assets/node.png)

### Cloudflare Pages
![起動時の選択オプション](./assets/cloudflare-pages.png)

### Cloudflare Workers
![起動時の選択オプション](./assets/cloudflare-workers.png)

## 参考資料
- 特になし
