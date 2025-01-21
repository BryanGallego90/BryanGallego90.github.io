# BryanGallego90.github.io
## First GitHub Lab

### Welcome to My GitHub Page
Hi! My name is Bryan Gallego.  
**Email:** [Bgallego@my.waketech.edu](mailto:Bgallego@my.waketech.edu)  

This is my first GitHub Pages website.

<!-- Added an about me sectio using Mark down headings-->

   # About Me
   -  I am a contractor and started my company at the end of 2018. 
   -  I’m interested in Cyber Security.

   ## Interests
   - I enjoy gaming
   - I plan my traveling around the food I'm going to try when I get there.

   ## Website I Recommend
   Visit: [Over the Wire] (https://overthewire.org/wargames/) A website that teaches security concepts as an interactive game.

---

### Check Out My Page
Visit: [Bryan's GitHub Page](https://bryangallego90.github.io/)

---

### Inspiration from Rick & Morty
![Alt Text: Cyber Security Design](https://i.etsystatic.com/13439930/r/il/f96e66/3826105261/il_1588xN.3826105261_toll.jpg)

---

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
