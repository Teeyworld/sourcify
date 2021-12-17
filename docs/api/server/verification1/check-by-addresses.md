# Check by addresses

Checks if contract with the desired chain and address is verified and in the repository. It will only search for perfect matches.

**URL** : `check-by-addresses?addresses={address}&chainIds={chainIds}`

**URL (deprecated)** : `checkByAdd?addresses={address}&chainIds={chainIds}`

**Method** : `GET`

## Response

**Code** : `200 OK`

**Content** : 

```json
[
    {
        "address: "0x4424109B9890B6b4b02a8d4C5D699c801b6dad75
        "status": "perfect",
        "chains": ["3"]
    },
    {
        "address": "0x4424109B9890B6b4b02a8d4C5D699c801b6dad75
        "status": "perfect",
        "chains": ["5", "3"]
    },
    {
        "address": "0x4424109B9890B6b4b02a8d4C5D699c801b6dad75 ",
        "status": "false"
    },
    {
        "address": 0x4424109B9890B6b4b02a8d4C5D699c801b6dad75,
        "status": "perfect",
        "chains": ["5"
```
