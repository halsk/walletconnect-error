## Getting Started

WalletConnect で switch network するとエラーになるリポジトリ。

.env.local に Thirdweb の Client ID (`NEXT_PUBLIC_TEMPLATE_CLIENT_ID`) と、WalletConnect の ProjectID (`NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID`) を入れてください。(`.env.example` を参考に)

その後
```
yarn -i
yarn dev
```

で動くはず

で、Connect Wallet ボタンを押してWalletを接続して、`switch network`ボタンを押すとエラーになります。

![Alt text](image.png)

ちなみに、このリポジトリは

```bash
npx thirdweb create 
```

で作ってから、最低限の追加実装だけしています。

