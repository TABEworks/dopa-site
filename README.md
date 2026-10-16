# Dopa site

Dopa for Vibe Codersの公式サイト。ビルド・依存パッケージ・JavaScript不要。GitHub Pagesはmainブランチのルートを配信する。

- Home: https://tabeworks.github.io/dopa-site/
- 始め方: https://tabeworks.github.io/dopa-site/getting-started.html
- Support: https://tabeworks.github.io/dopa-site/support.html
- Privacy: https://tabeworks.github.io/dopa-site/privacy.html
- English: https://tabeworks.github.io/dopa-site/#english
- Sitemap: https://tabeworks.github.io/dopa-site/sitemap.xml

ローカル確認: `python3 -m http.server 8765`

## 本文の方針

トップは短い紹介と3作品のイメージ、App Storeへの入口に絞る。比較表・利用条件・操作手順は始め方へ置く。始め方は準備から停止までの手順、Supportは問題別の復旧、Privacyは情報の扱いを所有する。装飾だけの英語見出し、機能説明の繰り返し、架空のAI応答や差分、未検証の成果・数字は追加しない。口調はキャッチコピーとDopa君に残し、機能と費用は具体的に書く。

機能を変更するときはagentpadの現行コード・docs/UX-MVP.mdと照合し、日英の説明も更新する。古いUI検証画像は現在の画面や実サービスの動作を示す証拠として扱わない。公開用に確認した画面が用意できたら、撮影版とデモ条件を添えて掲載する。

本文の正本はこのリポジトリのHTML。agentpadのdocs/SUPPORT.mdとdocs/PRIVACY_POLICY.mdは公開先・更新手順を案内する。

## 公開と検索・共有

- ページのtitle・descriptionは内容が判断できる固有の文言にする。トップと始め方はOGP／Twitterカードを持つ。
- canonicalはクエリなしの公開URL。新規ページはsitemap.xmlとサイト内リンクに追加する。プロジェクト配下のrobots.txtはホストの制御に使えないため置かない。
- CSSを変更したら、全HTMLの`style.css?v=`をstyle.cssのSHA-256先頭12桁に更新する。公開確認ではHTMLだけでなく、そのHTMLが参照するCSSもローカル版と一致するか確認する。
- App Storeの`id0000000000`は依頼に基づく仮リンク。公開時は正式URLへ差し替え、公開準備中の表示と日英FAQを同時に更新する。
- Search Consoleの登録やsitemap送信はアカウント所有者の運用作業。検索流入とApp Storeへの遷移は別の指標として確認する。現時点では計測基盤を導入していない。

外部フォント、追跡コード、問い合わせフォームは使わず、メールは利用者のメールアプリで作成する。吹き出しは共通CSSで階段状の角・しっぽを描画する。

検索向け文言の基準は[Googleのタイトル指針](https://developers.google.com/search/docs/appearance/title-link)と[ユーザーを第一に考えたコンテンツ](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)。順位・流入数を保証する文言や架空の評価・レビューは追加しない。
