# Number Guessing Game Mermaid Flow Chart

<!-- Added Mermaid syntax for a number guessing game using flowchart -->

```mermaid
graph TD
    A[Start] --> B[Generate random number]
    B --> C[Prompt user for input]
    C --> D{Is input valid?}
    D -- No --> C
    D -- Yes --> E{Is input correct?}
    E -- Too High --> F[Display Too high]
    E -- Too Low --> G[Display Too low]
    E -- Correct --> H[Display You guessed it!]
    F --> C
    G --> C
    H --> I[End]
