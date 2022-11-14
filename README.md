# mermaid
Mermaid experiments

## Graphs and Flowcharts

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

```mermaid
graph TD;
  a --> b;
  a --> c;
  b --> c;
  b --> d;
  c --> d;
  c --> e;
  d --> e;
  d --> a;
  e --> a;
  e --> b;
```

## Sequence diagrams

```mermaid
sequenceDiagram
  participant Alice
  participant Bob
  
  Alice->>John: Hello John, how are you?
  
  loop Healthcheck
    John->>John: fight against hypochondria
  end
  
  Note right of John: Rational toughts <br/>prevail!
  
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```
