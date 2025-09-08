# cf-worker-call-redirect-docs

```mermaid
flowchart TD
USER --> PAGE --> KV --> PHONES --> |YES| PHONE_TS --> |"Còn hạn dưới 4h"| DISPLAY

PHONES -->|NO| FETCH --> |OK| SAVE --> DISPLAY

FETCH --> |NO| FAIL

```
