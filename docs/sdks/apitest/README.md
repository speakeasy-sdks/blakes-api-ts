# APITest SDK


## Overview

### Available Operations

* [patchPets](#patchpets)

## patchPets

### Example Usage

```typescript
import { APITest } from "APITest";

(async() => {
  const sdk = new APITest();

  const res = await sdk.patchPets();


  if (res.statusCode == 200) {
    // handle response
  }
})();
```

### Parameters

| Parameter                                                    | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `config`                                                     | [AxiosRequestConfig](https://axios-http.com/docs/req_config) | :heavy_minus_sign:                                           | Available config options for making requests.                |


### Response

**Promise<[operations.PatchPetsResponse](../../models/operations/patchpetsresponse.md)>**

