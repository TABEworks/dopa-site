# Dopa site

Dopa for Vibe Codersの公式サイト。トップページで制作の流れ、初回作品、開発ツール、Dopa君、利用環境・Free／Proを紹介し、日英サポートとプライバシーへ案内する。

- Home: https://tabeworks.github.io/dopa-site/
- Support: https://tabeworks.github.io/dopa-site/support.html
- Privacy: https://tabeworks.github.io/dopa-site/privacy.html
- English: https://tabeworks.github.io/dopa-site/support.html#english

ビルド・依存パッケージ・JavaScript不要。GitHub Pagesはmainブランチのルートを配信。

ローカル確認: `python3 -m http.server 8765`

本文の正本はこのリポジトリのHTML。agentpadのdocs/SUPPORT.mdは公開先と更新手順を案内する。アプリの動作変更時は日英FAQを一緒に更新する。
プライバシー本文の正本はprivacy.html。日英を一緒に更新し、agentpadのdocs/PRIVACY_POLICY.mdとops/store.ymlに公開先を記録する。
外部フォント、追跡コード、問い合わせフォームは使わず、メールは利用者のメールアプリで作成する。

トップページの会話・差分と作品の図は説明用のイメージ。実画面のスクリーンショットではない。吹き出しは共通CSSで階段状の角・しっぽを描画し、全ページで同じ形を使う。機能の説明を更新するときはagentpadの現行実装・docs/UX-MVP.mdと照合し、トップページの英語説明も更新する。
