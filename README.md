
```mermaid
sequenceDiagram
    Admin ->> System: how he doing ?
    System -->> Admin: am fine boss
    loop aws
    System ->> System: this is loop guys
    end
    Note right of System: how do you do
    System ->> Aws: are ok child
    Aws-->> System: yes am

```
