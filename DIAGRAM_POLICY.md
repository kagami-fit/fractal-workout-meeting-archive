# 図解作成ルール

## 絶対ルール

この議事録アーカイブに掲載する図解は、必ず image-gen2 で作成する。

## 運用

- 各議事録フォルダに `diagram.png` または `diagram-imagegen2.png` として保存する
- `public/records.json` の `diagramUrl` は image-gen2で作成したPNGだけを指定する
- SVG、HTML、CSS、Canvasで作った図解は最終掲載物にしない
- 図解内にはロゴを入れない。ロゴを使うのはサイトUIや正式資料だけにする
- 図解のトンマナは正式ロゴに合わせ、黒、チャコール、シルバーグレー、白を基調にする
- 文字崩れや誤字がある場合は、image-gen2で再生成して直す
- 図解プロンプトは、必要に応じて該当議事録フォルダへ `imagegen2-diagram-prompt.md` として残す

## 保存例

```text
public/records/2026-05-25-ai-mtg/diagram.png
```

## 確認方法

```bash
npm run check
```

ブラウザで `http://localhost:3000` を開き、該当議事録の図解画像が表示されることを確認する。
