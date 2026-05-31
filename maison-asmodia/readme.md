# Maison Asmodia — 公式ウェブサイト

## プロジェクト概要
コンセプトカフェバー「Maison Asmodia」の公式ホームページ。  
コンセプト：**悪魔と夜の宴** — ゴシック×ラグジュアリーの非日常体験。

## 完成済み機能
- [x] ファーストビュー（Hero）— ロゴ大表示（560px幅）＋多重グロー＋バウンスアニメーション
- [x] 回転二重魔法陣・光条・煙・180粒子パーティクル背景
- [x] ロゴ3Dティルト（マウスホバー）
- [x] ローディング演出（回転ペンタグラム）
- [x] カスタムカーソル（ラグ付きトレース）
- [x] スクロールリビールアニメーション
- [x] ヘッダー（固定ナビ・スクロール時背景変化）
- [x] Concept セクション（4枚カード）
- [x] Seats セクション（8席：Boudoir / Absinthe / Obscura / Noctuelle / Orangerie / Roselier / Velours / Reveris）
  - 各席に実画像を設定（images/seat-*.jpg）
  - 席ごとに専用カラーテーマ（theme-aqua / theme-bluenight / theme-obsidian / theme-navysalon / theme-garden / theme-floral / theme-ivory / theme-gothic）
- [x] Cast セクション（6名キャスト紹介）
- [x] Menu セクション（タブ切り替え：カクテル/モクテル/ウイスキー/フード）
- [x] Reserve セクション（バリデーション付き予約フォーム）
- [x] Atmosphere セクション（ギャラリー）
- [x] Access セクション（営業時間・SNSリンク）
- [x] フッター（ロゴ・ナビ・年齢制限表記）
- [x] スマホ対応（ハンバーガーメニュー）

## ファイル構成
```
index.html              — メインHP（全セクション統合）
images/logo.png         — Maison Asmodiaロゴ
images/seat-boudoir.jpg   — Boudoir席（アクアファンタジーサロン）
images/seat-absinthe.jpg  — Absinthe席（ブルーナイトラウンジ）
images/seat-obscura.jpg   — Obscura席（深紫の書斎）
images/seat-noctuelle.jpg — Noctuelle席（青薔薇サロン）
images/seat-orangerie.jpg — Orangerie席（ガーデンテラス）
images/seat-roselier.jpg  — Roselier席（スイートガーデン）
images/seat-velours.jpg   — Velours席（クラシックティーサロン）
images/seat-reveris.jpg   — Reveris席（ゴシック晩餐ホール）
README.md
```

## 主要URI
| パス | 内容 |
|------|------|
| `index.html` | トップページ（全セクション） |
| `index.html#concept` | コンセプト |
| `index.html#seats` | 席ランク |
| `index.html#cast` | キャスト |
| `index.html#menu` | メニュー |
| `index.html#reserve` | 予約フォーム |
| `index.html#access` | アクセス |

## デザイン仕様
- **カラー**: 黒 × ピンクグラデーション（#e87ea1） × ゴールド（#d4af7a）
- **フォント**: Cinzel Decorative / Cormorant Garamond / Noto Serif JP
- **ロゴ表示サイズ**: ファーストビュー 560px幅（最大）、ヘッダー 48px高、フッター 80px高

## 未実装・推奨次ステップ
- [ ] 実際の店舗住所・電話番号の入力
- [ ] Google Maps 埋め込み
- [ ] キャスト実写真の設定
- [ ] ギャラリー実写真の設定
- [ ] SNSリンクの実URL設定
- [ ] オンライン予約システムの本格連携
- [ ] キャンペーン・イベント情報ページ

## 公開方法
**Publishタブ** からワンクリックでデプロイできます。
