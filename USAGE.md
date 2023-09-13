<!-- Start SDK Example Usage -->


```typescript
import { APITest } from "APITest";
import { PatchPetsResponse } from "APITest/dist/sdk/models/operations";

const sdk = new APITest();

sdk.patchPets().then((res: PatchPetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->