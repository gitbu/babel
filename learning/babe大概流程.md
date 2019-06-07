```mermaid
graph LR
code --> |Babylon|AST
AST --> |babel-traverse|CRUD[对AST的CRUD]
CRUD --> |babel-generateor|code1

```

