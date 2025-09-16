<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=00BFFF&center=true&vCenter=true&width=850&height=70&lines=Hi%2C+I'm+Alexandru+Chetrean!;14-year-old+Developer+from+Germany;Frontend+Dev+%7C+Future+C%2B%2B+System+Programmer" alt="Typing SVG" />
</div>

<h1 align="center" style="color:#00BFFF;">👋 Welcome!</h1>
<h3 align="center" style="color:#7FDBFF;">💻 Young Developer | 🌍 Germany | 🚀 Passionate about Coding</h3>

<hr style="border:1px solid #00BFFF;" />

<div align="center">

## 👨‍💻 About Me

<span style="color:#00FFFF;">✨ 14 years old</span>  
<span style="color:#00FFFF;">🌍 Based in Germany</span>  
<span style="color:#00FFFF;">🖥️ Focused on Frontend Development (HTML, CSS, JS, TS, React)</span>  
<span style="color:#00FFFF;">⚡ Currently learning C++ to become a System Programmer</span>  
<span style="color:#00FFFF;">🎯 Love creating projects & constantly improving</span>

<hr style="border:1px solid #00BFFF;" />

## 🚀 Tech Stack

<img src="https://skillicons.dev/icons?i=html,css,sass,js,ts,react,nodejs,cpp,git,github,vscode&perline=7" />

<hr style="border:1px solid #00BFFF;" />

## 📂 Featured Projects

| 🌍 Website                                                                                                                                                                                 | 🎮 TicTacToe                                                                                                                                                                                   | ⚔️ C-RPG                                                                                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://github.com/AlexandruChet/WebSite"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=WebSite&theme=tokyonight&hide_border=true" /></a> | <a href="https://github.com/AlexandruChet/TicTacToe"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=TicTacToe&theme=tokyonight&hide_border=true" /></a> | <a href="https://github.com/AlexandruChet/C-RPG"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=C-RPG&theme=tokyonight&hide_border=true" /></a> |

| 💱 Currency                                                                                                                                                                                  | 💲 convert-currency                                                                                                                                                                                          | 📂 File-Manager                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://github.com/AlexandruChet/Currency"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=Currency&theme=tokyonight&hide_border=true" /></a> | <a href="https://github.com/AlexandruChet/convert-currency"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=convert-currency&theme=tokyonight&hide_border=true" /></a> | <a href="https://github.com/AlexandruChet/File-Manager"><img src="https://github-readme-stats.vercel.app/api/pin/?username=AlexandruChet&repo=File-Manager&theme=tokyonight&hide_border=true" /></a> |

<hr style="border:1px solid #00BFFF;" />

## 🏆 Achievements

✅ Built multiple **frontend projects**  
⚙️ Learned **Node.js** & created a **file manager**  
🎮 Developing **games & apps** in JavaScript and C++  
📈 Always improving, always learning 🚀

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=AlexandruChet&theme=tokyonight&row=1&column=6&no-frame=true&no-bg=true" />
</p>

<hr style="border:1px solid #00BFFF;" />

## 🎯 Goals

<span style="color:#7FDBFF;">🔹 Become a professional C++ System Programmer</span>  
<span style="color:#7FDBFF;">🔹 Grow as a Frontend & Fullstack Developer</span>  
<span style="color:#7FDBFF;">🔹 Contribute to Open Source & build large projects</span>

<hr style="border:1px solid #00BFFF;" />

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AlexandruChet&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexandruChet&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" height="140"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=AlexandruChet&theme=tokyonight&hide_border=true&background=0D1117" height="140"/>
</p>

<hr style="border:1px solid #00BFFF;" />

# 📚 Skills

## 🕒 At the time of writing this README

---

## 🌐 Frontend

- ✅ I know **HTML** completely  
- ✅ I also fully know **basic CSS and SCSS** for creating websites  
- ✅ I know **JavaScript** and **TypeScript** at a good level to solve complex problems and create websites  

### ✨ Example: Binary Search in TypeScript

```ts
function guessNumber(
  target: number,
  min: number = 1,
  max: number = 1000
): void {
  let attempts = 0;

  while (min <= max) {
    const guess = Math.floor((min + max) / 2);
    attempts++;
    console.log(`Computer guesses: ${guess}`);

    if (guess === target) {
      console.log(
        `Computer found the number ${target} in ${attempts} attempts!`
      );
      return;
    } else if (guess > target) {
      console.log("Too high! Trying lower...");
      max = guess - 1;
    } else {
      console.log("Too low! Trying higher...");
      min = guess + 1;
    }
  }

  console.log("Number not found!");
}

guessNumber(456);
````

---

### ⚛️ React

* I am fully capable of working with **JSX / TSX** in React
* I know the hooks:
  `useState`, `useEffect`, `useCallback`, `useMemo`, `useRef`, `useReducer`, `useContext`
* I can also create **custom hooks**

```tsx
import React, {
  useState,
  useEffect,
  useCallback,
  useMemo,
  useRef,
  useReducer,
  useContext,
  createContext,
} from "react";

// 1. useState
const [count, setCount] = useState<number>(0);

// 2. useEffect
useEffect(() => {
  console.log("Component mounted");

  return () => {
    console.log("Cleanup on unmount");
  };
}, [count]);

// 3. useCallback
const handleClick = useCallback(() => {
  console.log("Button clicked");
}, []);

// 4. useMemo
const doubled = useMemo(() => count * 2, [count]);

// 5. useRef
const inputRef = useRef<HTMLInputElement>(null);

// 6. useReducer
type State = { value: number };
type Action = { type: "increment" } | { type: "decrement" };

const reducer = (state: State, action: Action): State => {
  switch (action.type) {
    case "increment":
      return { value: state.value + 1 };
    case "decrement":
      return { value: state.value - 1 };
    default:
      return state;
  }
};

const [state, dispatch] = useReducer(reducer, { value: 0 });

// 7. useContext
const MyContext = createContext<string>("default");
const contextValue = useContext(MyContext);
```

* ✅ I can create **forms with validation**
* ✅ I can also work with **fetch**
* ✅ I know how to work with **class components** and the **React lifecycle**

---

## ⚙️ Backend

* 🌱 At a basic level, I know how to work with **Node.js**
* Example: creating a **server for React** and a **file manager**

```js
// Example of a simple Node.js server
const http = require("http");

const server = http.createServer((req, res) => {
  res.writeHead(200, { "Content-Type": "text/plain" });
  res.end("Hello from Node.js server!");
});

server.listen(3000, () => {
  console.log("Server is running on http://localhost:3000");
});
```

---

## 🖥️ C++

* 🚀 I am actively learning **C++**
* ✅ I already know how to work very well with **OOP**
* ✅ I know **basic libraries**
* ✅ I know how to work with **memory**

📌 You can see everything in detail in my repository
(Originally created for simple games, but now used for studying **C++**)

```cpp
#include <iostream>
#include <string>
using namespace std;

class Player {
private:
    string name;
    int health;

public:
    Player(string n, int h) : name(n), health(h) {}

    void takeDamage(int amount) {
        health -= amount;
        cout << name << " took " << amount << " damage! Health: " << health << endl;
    }

    void heal(int amount) {
        health += amount;
        cout << name << " healed " << amount << " points! Health: " << health << endl;
    }
};

int main() {
    Player hero("Kratos", 100);
    hero.takeDamage(30);
    hero.heal(20);

    return 0;
}
```


## 📫 Contact Me

<a href="https://github.com/AlexandruChet"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:chetreanalexandru63@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<h3 align="center" style="color:#00BFFF;">✨ Thanks for visiting! ✨</h3>
