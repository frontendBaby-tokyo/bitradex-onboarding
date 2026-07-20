# Trust WalletからBitradeXにXRPを送金する手順

## 事前準備

送金を始める前に、次の準備が完了していることを確認してください。

- BitradeXのアカウントを開設している
- スマートフォンにBitradeXアプリをインストールし、ログインしている
- Trust Walletアプリをインストールしている
- Trust Walletのシークレットリカバリーフレーズをバックアップしている
- Trust WalletにXRPの残高がある

> [!IMPORTANT]
> XRPの送金には、<strong>受取アドレス</strong>と<strong>MEMO（宛先タグ）</strong>の両方が必要です。入力内容とネットワークをよく確認してから送金してください。

## 送金時の注意点

> [!WARNING]
> ブロックチェーン上で完了した送金は、原則として取り消すことができません。受取アドレスやMEMO（宛先タグ）を間違えると、送金した資産を失う可能性があります。

Trust WalletからBitradeXへ初めて送金する場合は、最初から全額を送らず、次の流れで<strong>少額のテスト送金</strong>を行うことをおすすめします。

1. 少額のXRPを送金する
2. BitradeXへの着金を確認する
3. 問題がなければ、残りのXRPを送金する

## 送金手順

### 1. BitradeXでXRPの入金情報を確認する

1. BitradeXアプリを開く
2. ホーム画面にある、総資産評価額の右側の<strong>「入金」</strong>をタップする
3. <strong>「オンチェーン入金」</strong>をタップする
4. 検索欄に「XRP」と入力し、表示された<strong>XRP</strong>をタップする
5. 入金に使用するネットワークを選択する

   > 国内取引所（例：GMOコイン）からTrust Walletを経由して送金する場合は、<strong>「XRP Ledger」</strong>を選択します。

6. 表示された次の情報を確認する
   - XRPの受取アドレス
   - MEMO

この2つが、Trust Walletで入力する送金先情報です。

### 2. Trust Walletに送金先情報を入力する

1. Trust Walletを開く
2. <strong>「送信」</strong>をタップする
3. コイン一覧から<strong>XRP</strong>をタップする
4. 「アドレス」に、BitradeXの<strong>XRP受取アドレス</strong>を貼り付ける
5. 送金するXRPの数量を入力する

   > 全額を送金する場合は、<strong>「全額」</strong>をタップします。

6. 「宛先タグ」に、[BitradeXで確認したMEMO](#1-bitradexでxrpの入金情報を確認する)を貼り付ける
7. 入力内容を確認し、送金を確定する
8. パスワードを入力して署名する

### 3. BitradeXで着金を確認する

送金後、通常は数分〜数十分程度で着金します。

1. BitradeXアプリ下部の<strong>「資産」</strong>をタップする
2. 画面上部の<strong>「現物」</strong>をタップする
3. 資産一覧にXRPの残高が反映されていることを確認する
