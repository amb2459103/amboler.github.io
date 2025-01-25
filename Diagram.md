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
```mermaid

The flowchart entities are:

  - A: Start
  - B: Decide what to order
  - C: Choose size
  - D: Select milk/cream?
  - E: Yes
  - F: Add milk/cream
  - G: No
  - H: Skip milk/cream
  - I: Pay
  - J: Enjoy coffee

The relationships show the decision points and the flow of the process.

**7. Documentation:**

Here's a brief description of each entity and relationship:

  - **Start:** This is the beginning of the coffee ordering process.
  - **Decide what to order:** The customer decides what coffee they want.
  - **Choose size:** The customer chooses the size of their coffee.
  - **Select milk/cream?:** The customer is asked if they want milk or cream in their coffee.
  - **Yes/No:** These are the possible answers to the milk/cream question.
  - **Add milk/cream:** Milk or cream is added to the coffee.
  - **Skip milk/cream:** No milk or cream is added to the coffee.
  - **Pay:** The customer pays for their coffee.
  - **Enjoy coffee:** The customer enjoys their coffee.

