<!-- Start SDK Example Usage [usage] -->
```typescript
import { APITest } from "APITest";

async function run() {
    const sdk = new APITest();

    const res = await sdk.patchPets();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->