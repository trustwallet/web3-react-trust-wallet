# web3-react-trust-wallet

Trust Wallet connector for [web3-react](https://www.npmjs.com/package/web3-react)

# Usage

```
import { TrustWallet } from "@trustwallet/web3-react-trust-wallet";

  const [trustWallet, hooks] = initializeConnector<TrustWallet>(
    (actions) => new TrustWallet({ actions })
  );
    
  trustWallet.activate();
```