# Campus Mandarin

I'm applying for CSC Scholarship to study in China, and I realized one problem early -

I don't speak Mandarin. At all.

I kept thinking, what if I actually get selected and I land in China and I can't even say "no spicy" or "where is my delivery"? I don't want to be that person just pointing at the menu and hoping for the best.

So I started building this app to prepare myself. It's my survival kit before I even go.

### Live Demo
[Click here to try it] https://gojosatoru3182-droid.github.io/campus-mandrin/

### What it does

- **Flashcards** - Flip cards, listen to pronunciation, mark words as "Got it" when you learn them
- **Translator** - Type in English, get Chinese instantly. Uses MyMemory API so no key needed
- **Save words by day** - When you save a new word, it gets grouped under today's date. So tomorrow you get a new group, but you don't lose yesterday's words
- **Saved words stay saved** - Uses LocalStorage, so they don't disappear when you close the tab

### Why I built it like this

Most Mandarin apps teach textbook words like "apple" and "cat". That's not what I need first.

I need to survive on campus - food, delivery, library, dorm. So I focused on words I know I'll need in my first week there.

### Tech I used

- HTML / CSS / JavaScript - no framework, kept it simple on purpose
- MyMemory Translation API
- LocalStorage for saving words
- Web Speech API for pronunciation

### How to run it

1. Download / clone this repo
2. Just open `index.html`
3. That's it, no npm install, no setup

### What I learned

- How to use a real API without a key
- How to group data by date in JS
- How to make LocalStorage actually persist stuff
- How to build something for a real problem I have, not just for marks

### What's next

- Add pinyin auto-generation
- Add a "quiz me" mode for words I keep forgetting
- Add more canteen words - I already know I'll forget "no coriander"


