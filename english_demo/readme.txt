# STORYEM – AI Gamebook Engine

**STORYEM** is a lightweight story game engine that lets you create playable story games in minutes.  
It runs in a single HTML file, uses CSV for scenario data, and works on both PC and smartphones.

![Gameplay Screenshot](examples/sealed_cave/img/bgi1.png)

---

## Features

- Runs in a single HTML file – no installation required
- Scenario written in CSV for easy editing
- Supports battles, items, BGM, and background images
- Works offline and on smartphones
- Lightweight (~1300 lines of JavaScript)

---

## Example Game

**Adventure in the Sealed Cave** – a short horror dungeon adventure.

- Explore a mysterious sealed cave
- Face a guardian ogre in battle
- Collect items and manage your HP
- Multiple branching paths and endings

**Play the demo:** [Open in Browser](examples/sealed_cave/index.html)

---

## How to Create Your Own Game

1. Edit the CSV scenario file (`examples/your_game/scenario.csv`)  
2. Open `storyem.html` in your browser  
3. Play and test your game instantly  
4. Share your HTML file with others  

> CSV Example:
> ```
> id,type,text,options,e_name,e_skill,e_hp,next,bgm,bgi,effect
> 1,normal,"You enter the sealed cave. Three paths lie ahead: left, middle, right.","Left→2,Middle→11,Right→3",,,,,bgm/bgm1.mp3,img/bgi1.png,
> ```

---

## Why STORYEM?

STORYEM is designed to make story creation **fast, fun, and flexible**.  
It is perfect for:

- Interactive fiction creators
- Game jam participants
- AI-generated story experiments
- Educational workshops

---

## License

MIT License – free to use and modify.
