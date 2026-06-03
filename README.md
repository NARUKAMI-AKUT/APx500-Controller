# APx500 Controller

Audio Precision APx500 / APx515 測定器を遠隔制御する Windows デスクトップアプリです。

---

## ダウンロード / Download

`APx-Controller_v0.11.1.zip` をダウンロードして任意のフォルダに解凍してください。

---

## 起動方法 / How to Run

解凍したフォルダ内の `APx-Controller.exe` を実行します。  
Python のインストールは不要です。

```
APx-Controller\
└── APx-Controller.exe  ← これをダブルクリック
```

### デモモード

APx500 が接続・インストールされていない環境でも GUI を起動できます。  
接続ボタン等は「デモ」として動作します。

### 実機制御モード

`C:\Program Files\Audio Precision\` に APx500 ソフトウェアがインストールされていれば、  
起動時に自動的に実機と接続します。

---

## 動作環境 / Requirements

| 項目 | 内容 |
|------|------|
| OS | Windows 10 / 11 (64-bit) |
| APx500 | 実機制御には Audio Precision APx500 ソフトウェアが必要 |

---

## 主な機能 / Features

- APx500 への接続・切断・自動再接続
- 測定プロジェクトの選択と実行（AGL / Sweep シーケンス）
- プロセス死活監視（自動ポーリング）
- ダークテーマ UI

---

## バージョン / Version

**v0.11.1**

---

## ライセンス / License

MIT License
