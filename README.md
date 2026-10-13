# larch-buchan-art

Larch 視覺小說《仙泉．香布纏》第一卷到第五卷用到的 CG，以及《續》使用的圖像與音效。這裡只放素材，產線與劇本在私有的
[larch-taoyuan](https://github.com/yazelin/larch-taoyuan)。

Larch 的卡片經 jsDelivr 取用這裡的素材。網址固定指定一個只含該組檔案的 tag，避免整個 repo 超過 CDN 套件大小限制：

    https://cdn.jsdelivr.net/gh/yazelin/larch-buchan-art@<tag>/cg/<檔名>

## 目錄

| | |
|---|---|
| `cg/` | 五卷用到的 CG、地圖與動圖（webp、avif），檔名跟產線裡的檔名相同 |
| `stickers/r2/` | 《仙泉．香布纏．表情包》64 張透明 WebP 與封面（Larch 素材包 `pack-aee50bb9-5197-4fc0-8353-c2c7b62b7c8b`，產線 `larch-taoyuan/buchan/stickers.py`） |
| `thumbs/` | CG 縮圖（720px），公開資料站的 CG 圖廊用 |
| `sfx/` | Larch 內建音效沒有的自製音效 |
| `bgm/` | 混了環境音的配樂（火聲、風聲）；原聲帶本身在 [larch-buchan-canon](https://github.com/yazelin/larch-buchan-canon) 的 `music/` |
| `xu/assets/` | 《仙泉．香布纏．續》使用的圖像、音效與新增配樂；以 SHA-256 檔名保存，按遊戲卡片分組打 tag，經 jsDelivr 載入 |
| `larch_r2_map.json` | 第一、二卷原本放在 Larch 素材庫的網址，對到這裡的檔名（圖是 `cg/` 檔名，音樂寫明 `music/` 或 `bgm/`） |

圖是產生出來的，不要直接在這裡改；換圖從 `larch-taoyuan` 重新同步。

## 授權

CC BY-NC 4.0 © 林亞澤 (Yaze Lin)。圖像、音效與配樂是作品素材，不是程式碼。

---

到 Larch 市集玩《仙泉．香布纏》：<https://larch.ink/play/market/458c5e49-9746-41a9-b0a3-5eae2fb8d584>
