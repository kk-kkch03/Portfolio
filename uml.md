```puml
@startuml
A -> B
@enduml
```

```mermaid
sequenceDiagram
    A ->> B : install
```

```puml
@startuml
A -> B : instantinate
activate B
A <-- B : dispose
deactivate B
@enduml
```

```mermaid
sequenceDiagram
    A ->>  + B : instantinate
    B -->> - A : dispose
```


```puml
@startuml

A -> B
note right: 注釈
@enduml
```

```mermaid
sequenceDiagram
    % この行コメントは描画されません
    A ->> B : message
    Note right of B : 注釈
```
