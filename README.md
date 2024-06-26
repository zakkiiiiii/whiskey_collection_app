# whiskey_collection_app
RUNTEQ卒業制作アプリ

# サービス概要
ウイスキー愛好家のためのコレクション管理、ウイスキーライフを便利で豊かにするアプリです。
自分のウイスキーコレクションの整理、テイスティングノートの保存、在庫の把握を簡単に行えます。
さらに、他の愛好家とのノート共有やレビュー交換を通じて、コミュニティ形成と新しいウイスキーとの発見や出会いを提供します。


# このサービスへの思い・作りたい理由
私は、ウイスキーの"製造する国や産地の気候や風土で変化する風味の奥深さ"に面白さと魅力を感じ、様々な銘柄を収集することにハマりました。
「他の人はどんなウイスキーを飲んでいるのだろう？、オススメは？、これ飲んだことあったっけ？、持ってたっけ？、どのボトルが残り少なかったっけ？、どのボトルを飲み切ってたっけ？」、「自宅の保管庫を手軽に持ち運び、外出先でも確認できたら良いのにな。」、「他の愛好家の保管庫を覗けたらな。」
という思いから、自分のコレクションを管理、共有しながら、他の愛好家にも気軽に連絡、意見交換できるプラットフォームを作りたいと思いました。


# ユーザー層について
性別や年齢問わず、ウイスキー好きの方で、自身の所有欲を満たしたい人、所有物を自慢したい人、他人の保有物に興味がある人など。


# サービスの利用イメージ
ウイスキーコレクションアプリは、ユーザーが自身のウイスキーコレクションを簡単にカタログ化し、管理できるアプリです。
ユーザーは、保有しているウイスキーのボトル写真や詳細情報、テイスティングノート、メモを登録し、アプリ上でカード形式に表示できます。
これにより、自宅の保管庫を仮想的に簡単に再現できます。
また、各ボトルの残量を記録することで、買い足すタイミングを把握しやすく、在庫管理を楽にします。
さらに、自分のコレクションを他のユーザーと共有できるため、他のユーザーのコレクションを見て新しいウイスキーを発見することも可能です。
これらの機能により、ユーザーは自宅の保管庫を丸ごと持ち運び、いつでもどこでもコレクションを閲覧・管理できるようになります。


# ユーザーの獲得について
家族や知人にまずは使用して貰い、フィードバックを得ようと思っています。

# サービスの差別化ポイント・推しポイント
簡単な写真と銘柄情報の登録で管理するアプリはありますが、残量表示や他のユーザーの保有物を確認できるアプリは見当たりませんでした。

## ポータブルコレクション
    自宅のウイスキー保管庫をデジタル化し、外出先でもコレクションを簡単に閲覧・管理できるようにします。
## 在庫管理
    ボトル情報の登録に加えて、各ボトルの「残量」を追跡する機能です。これにより、買い足すタイミングを把握し、効率的に在庫を管理できます。
## コレクションシェア
    自分のコレクションを他のユーザーと共有することができ、他のユーザーのコレクションも閲覧することが可能で、新しいウイスキーに出会うきっかけを提供します。

# 機能候補
・ユーザー登録機能
・ログイン・ログアウト機能
・新規コレクション登録
・検索機能(銘柄名、熟年数、蒸溜所名、産地、種類等複数検索)
・コレクション一覧(マイページ)
・コレクション詳細
・テイスティング等のメモ機能
・コレクションの残量表示
・お気に入り機能("飲みたい!"等で表示)
・お気に入り一覧
・レビュー機能(星で表示)
・SNSシェア機能


■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。
残量の表示をインジケーターを使用し行おうと考えています。