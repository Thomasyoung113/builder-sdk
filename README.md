
## 📦 Builder SDK

### Installation
```bash
npm install @nouns-builder/sdk
```

### Quick Start
```typescript
import { BuilderSDK } from '@nouns-builder/sdk';

const sdk = new BuilderSDK({
  chainId: 1,
  rpcUrl: process.env.RPC_URL,
});

// Fetch DAO details
const dao = await sdk.getDAO(daoAddress);
```

### Features
- DAO creation and management
- Proposal lifecycle handling
- Token and auction interactions

