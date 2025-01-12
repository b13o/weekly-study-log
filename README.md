<img width="1440" alt="スクリーンショット 2025-01-08 23 45 34" src="https://github.com/user-attachments/assets/1968f949-1c9d-4954-b24f-0eab0fd883d0" />

# 学習記録アプリ

## 概要

このプロジェクトでは、1 週間の学習時間を管理・可視化するアプリを構築します。

作業時間をグラフで可視化し、カテゴリー別や全体での合計作業時間を算出します。

## 学習目標

useMemo と useCallback を使用したパフォーマンスの最適化について学習します。

不要な再計算・再レンダリングをなくす方法と、実際のユーザーケースを確認してください。

### 推奨技術

このプロジェクトの難易度と趣旨を踏まえて、以下の使用をお勧めします。

- useMemo による計算処理の最適化
- useCallback と React.memo の組み合わせ
- Recharts を用いたグラフ表示
- Vite を用いた React 環境構築
- TypeScript による型チェック
- Tailwind CSS を用いたスタイリング
- GitHub Pages へのデプロイ

---

## 🎯 お題

- 「ユーザーストーリー」を全て満たすアプリを構築してください。
- 必要に応じて、スクリーンショットやデモサイトの URL を参照してください。
- スタイルは、あなた自身で独自にカスタマイズすることが可能です。

### 必須機能

1. **学習ログの記録**：
   - 曜日、カテゴリー、作業時間、メモを入力し記録する
   - モチベーション（3 段階の自己評価）を設定する
2. **学習データの可視化**：
   - 日別の学習時間をグラフ表示する
   - カテゴリー別の合計時間を表示する
   - 先週のカテゴリー別の合計時間を表示する
   - 全体の合計時間を表示する
   - 自己評価の総計を表示する
3. **データ管理**：
   - 学習ログの一覧表示
   - 不要なログの削除

## ユーザーストーリー

- [ ] ユーザーがサイトにアクセスすると、新しい学習ログを入力できるフォームが表示されている
- [ ] 学習カテゴリーを、ドロップダウンリストから選択できる
- [ ] 曜日を選択し、学習時間（分）とメモを入力できる
- [ ] モチベーションレベルを 3 段階（ネガティブ、普通、ポジティブ）で設定できる
- [ ] 必要な情報を入力し、「追加」ボタンをクリックすると、学習ログが一覧で表示される
- [ ] 学習ログは削除できる
- [ ] 日別の学習時間がグラフで視覚的に表示される
- [ ] カテゴリー別の合計時間が表示される
- [ ] 先週のカテゴリー別の合計時間も表示する
- [ ] 週間の総学習時間が表示される
- [ ] 自己評価の総計が表示される
- [ ] アプリケーションがデプロイされており、誰でもアクセス可能である。
