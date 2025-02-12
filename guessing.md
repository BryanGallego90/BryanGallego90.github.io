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
```
---

## Flow Chart Explanation
    1. Generate and store a random number
    2. Ask user to input their guess
    3. Determine if input value is correct
    4. Provide results if number is too low, too high or correct.
    5. If guess is too low or high, request new user input for new guess.
    6. If guess is correct the game ends and lets user know guess was correct
