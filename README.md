# ガルバファイト（GarbaFight）

60秒のボケキャッチボール × シャンパンスロットのブラウザゲーム。
インストール不要・単一HTMLで動く、深夜の歌舞伎町を舞台にしたミニアクション。

**▶ 今すぐ遊ぶ:** https://obake0000.github.io/garbafight/

*A 60-second browser mini-game: catch conversation "balls", fire back the right reply, fill the Vibe meter, and hit the champagne slot. Pure single-file HTML — no install.*

---

## あらすじ

20歳の新人ガルバ嬢アヤメが、客の闇トーク（玉）を打ち返し、シャンパン1本で家賃を勝ち取る60秒の生存ゲーム。3万円を超えれば「今夜のNo.1」。

## 遊び方

1. アヤメを左右に動かして、客の会話の「玉」を取りに行く
2. 玉を取ったら **3択（共感／オウム返し／ボケる）** で返球する
3. 返しが客タイプに合えば機嫌アップ＆**ガルバヴァイブ**が貯まる
4. ヴァイブ100%で 🍾 **シャンパンチャンス** 発動 → スロット
5. スロット結果（×1／×3／×5／JACKPOT×10）で大金GET
6. 60秒勝負。CPU2人（新人ミナ・ママ静子）と玉を取り合う

## 操作

- **← →**：移動
- **クリック / タップ**：玉を取る・3択を選ぶ

## 技術

- 依存ライブラリなしの **単一HTML**（`game.html`）。サーバー不要、ブラウザで開くだけ。
- `index.html`：ランディング兼ランチャー
- `GAME_SPEC_v10.md`：ゲーム仕様書
- `LP_CONTENT.md`：LP用コピー素材

## ローカルで動かす

```bash
git clone https://github.com/obake0000/garbafight.git
cd garbafight
# game.html をブラウザで開くだけ。簡易サーバーで開くなら:
python -m http.server 8000   # → http://localhost:8000/
```

## ライセンス

[MIT License](LICENSE) © 2026 Fumihiro Asai (obake0000)

> 注：本作はブラックユーモアを含むフィクションです。登場する人物・店舗・出来事はすべて架空のものです。
