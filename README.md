# Netcafe Seat Watch

漫画喫茶・ネットカフェ空席/シャワー通知

## Repository

Recommended repository name: `netcafe-seat-watch`

## Domain candidates

Confirmed domain: `netcafeseat.jp`

Other candidates:

- `netcafeseat.jp`
- `mangaseat.jp`
- `showercafe.jp`
- `netcafealert.jp`

## Concept

空席、シャワー、鍵付き個室、料金、女性専用エリアを通知し、店舗送客とクーポンへつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 店舗送客
- クーポン
- 掲載課金
- 宿泊代替送客
- 広告

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
