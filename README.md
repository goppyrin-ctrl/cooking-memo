# cooking-memo

家族で使う手料理メモアプリ。作った料理の記録、改善メモの引き継ぎ、ジャンル別のメニュー表を iPhone と Android で使えるようにします。

## 手元のスマホで動かす

1. スマホに「Expo Go」アプリを入れる（App Store / Google Play）
2. パソコンで `npm install` のあと `npx expo start` を実行する
3. 表示された QR コードを、iPhone はカメラ、Android は Expo Go で読み取る

## 技術

- アプリ: Expo（React Native + TypeScript）
- クラウド（ログイン・同期・写真）: Supabase（これから接続）
