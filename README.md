# ezmobile_publishpromo

ez Mobile アプリDL用のLP（2種類）。

| ページ | フォルダ | 公開URL（GitHub Pages） |
|---|---|---|
| 旅行者向け | `travelers/` | https://ezindonesia.github.io/ezmobile_publishpromo/travelers/ |
| LPK生向け | `lpk/` | https://ezindonesia.github.io/ezmobile_publishpromo/lpk/ |

## 公開前に編集する場所
各 `index.html` の下の方にある `CONFIG` だけ。
- `promoCode`: 10%割引コード
- `waUrl`: WhatsAppサポートURL（例: `https://wa.me/62xxxxxxxxxx`）

## 言語
自動判定（ブラウザが英語ならEN、それ以外はID）。URLに `?lang=id` / `?lang=en` を付けると固定できます。

## 公開手順
Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
