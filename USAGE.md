<!-- Start SDK Example Usage -->


```typescript
import { APITest } from "APITest";

(async () => {
    const sdk = new APITest();

    const res = await sdk.apiTest.patchPets();

    if (res.statusCode == 200) {
        // handle response
    }
})();

```
<!-- End SDK Example Usage -->