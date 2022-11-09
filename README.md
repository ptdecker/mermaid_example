# Examples of Mermaid Markdown in GitHub

Here are some examples illustrating how GitHub markdown supports Mermaid code blocks for embedded graphs.  For more information, see the [Mermaid project pages](https://mermaid-js.github.io/mermaid/#/) and [repository](https://github.com/mermaid-js/mermaid).

## Graphs

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Sequence Diagrams

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

## Entity Relationship Diagrams 

```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```
