```mermaid
graph LR
A[Start] --> B{Decide what to order}
B --> C{Choose size}
C --> D{Select milk/cream?}
D --> E{Yes} --> F{Add milk/cream}
D --> G{No} --> H{Skip milk/cream}
E --> F --> I{Pay}
G --> H --> I
I --> J{Enjoy coffee}
