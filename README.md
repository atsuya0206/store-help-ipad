# 店舗ヘルプ（iPad画面）

店舗の iPad から LINE WORKS の社員グループにヘルプを呼ぶ画面。GitHub Pages で公開し、処理は店舗連絡Bot（GAS）が行う。

- このリポジトリには合言葉もウェブアプリのURLも入っていない。iPad で開くURLの `#` の後ろ（g=ウェブアプリID、k=合言葉 / s=QRの共有キー）にだけ入る
- 中身は store-bot-gas の `tools/build-ipad-page.js` で storeBot_ipad.gs から作る。直接編集しない
- qrcode.js は qrcode-generator 1.4.4（MIT License, Kazuhiko Arase）
