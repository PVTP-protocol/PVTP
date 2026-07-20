# Examples

Conceptual example:

```text
Request:
PVTP/1.0 GET pvtp://images/mountains

Response:
- metadata
- preview layer
- progressive image chunks
- final image
```

Example client idea:

```javascript
import { PVTP } from "pvtp-sdk";

const image = await PVTP.load("pvtp://images/mountains");
```
