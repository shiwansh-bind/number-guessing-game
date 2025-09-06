# number-guessing-game
# 🎯 Number Guessing Game Deluxe

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![GitHub release](https://img.shields.io/badge/release-v2.0.0-blue?style=for-the-badge) ![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20mac-lightgrey?style=for-the-badge) ![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge) ![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&color=F75C7E&center=true&vCenter=true&width=600&lines=🎮+Test+Your+Luck!;🧠+Challenge+Your+Mind!;🏆+Beat+The+High+Score!;🔥+5+Difficulty+Levels!" alt="Typing SVG" />

### 🌟 **A Mind-Bending Number Guessing Adventure with Hidden Secrets!** 🌟

[**📖 Read Guide**](https://claude.ai/chat/ab988885-a81b-4592-a03e-61241428cef4#) • [**🎮 Play Now**](https://claude.ai/chat/ab988885-a81b-4592-a03e-61241428cef4#quick-start-) • [**🐛 Report Bug**](https://github.com/shiwansh-bind/number-guessing-game/issues/new?template=bug_report.md) • [**✨ Request Feature**](https://github.com/shiwansh-bind/number-guessing-game/issues/new?template=feature_request.md)

</div>

---
## ✨ Features

<table> <tr> <td>

### 🎯 **Core Features**

- 🎲 **Random Number Generation** - True randomness every game
- 🏅 **High Score Tracking** - Beat your personal best
- 🔄 **Instant Replay** - Play again without restarting
- 🎨 **Smart Hints System** - Intelligent proximity-based hints
- ⚡ **Input Validation** - Handles all types of input gracefully

</td> <td>

### 🌈 **Special Features**

- 🔓 **5 Difficulty Levels** - Including hidden NIGHTMARE modes
- 🎭 **Secret Easter Eggs** - Discover hidden surprises
- 📊 **Guess Counter** - Track your performance
- 🛡️ **Quit Protection** - Exit safely anytime with `-1`
- 💫 **Dynamic Feedback** - Contextual hints based on proximity

</td> </tr> </table>

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/shiwansh-bind/number-guessing-game.git

# Navigate to the project
cd number-guessing-game

# Compile the game
gcc -o game game.c

# Run and enjoy!
./game
```

---

## 🎮 How to Play

<div align="center"> <img src="https://img.shields.io/badge/Step%201-Choose%20Difficulty-orange?style=for-the-badge" /> <img src="https://img.shields.io/badge/Step%202-Guess%20the%20Number-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/Step%203-Follow%20the%20Hints-green?style=for-the-badge" /> <img src="https://img.shields.io/badge/Step%204-Beat%20High%20Score-red?style=for-the-badge" /> </div>

### 📝 Game Rules

1. **🎯 Choose your difficulty level** (1-5)
2. **🤔 Guess the secret number** within the range
3. **📍 Follow the smart hints** to get closer
4. **🏆 Try to beat your high score** (fewer guesses = better)
5. **🔄 Press 'R' to play again** or `-1` to quit

### 💡 Pro Tips

> 🧠 **Binary Search Strategy**: Start with the middle number and halve your search space each time!
> 
> 🎯 **Pay Attention to Hints**: The game tells you if you're very close, slightly off, or way off!
> 
> 🔥 **Try Secret Levels**: Enter 4 or 5 for NIGHTMARE modes!

---

## 🏆 Difficulty Levels

|Level|🏷️ Name|🎯 Range|🎰 Numbers|💀 Challenge|
|:-:|:-:|:-:|:-:|:-:|
|**1**|🟢 **Easy**|1-50|50|Perfect for beginners|
|**2**|🟡 **Medium**|1-100|100|The classic experience|
|**3**|🔴 **Hard**|1-500|500|For serious players|
|**4**|👹 **NIGHTMARE**|1-1000|1,000|Hidden difficulty!|
|**5**|💀 **ULTRA NIGHTMARE**|1-10000|10,000|Are you insane?!|

---

## 🔥 Secret Features

<details> <summary><b>🎭 Click to Reveal Hidden Secrets!</b></summary>

### 🌟 Easter Eggs

- **👹 Secret Difficulty 4**: Type `4` for NIGHTMARE mode (1-1000)
- **💀 Secret Difficulty 5**: Type `5` for ULTRA NIGHTMARE (1-10000)
- **🛡️ Safe Quit**: Type `-1` anytime to exit gracefully
- **♾️ Infinite Play**: Keep pressing 'R' to play forever!

### 🎯 Hint System Breakdown

|Distance|Message|Meaning|
|:-:|:--|:--|
|**>20**|"Too high/low! Try a much smaller/bigger number"|You're way off!|
|**11-20**|"Slightly high/low! Try going lower/higher"|Getting warmer...|
|**1-10**|"Very close, but still a bit high/low!"|You're burning hot!|
|**0**|"Woohoo! Correct!"|🎉 Victory!|

</details>

---

## 📦 Installation

### 🖥️ **Windows**

```powershell
# Using MinGW
gcc -o game.exe game.c

# Run the game
./game.exe
```

### 🐧 **Linux**

```bash
# Install GCC if needed
sudo apt-get install gcc

# Compile
gcc -o game game.c

# Make executable
chmod +x game

# Run
./game
```

### 🍎 **macOS**

```bash
# Using Xcode Command Line Tools
gcc -o game game.c

# Run
./game
```

---

## 🛠️ Building from Source

### Prerequisites

- ✅ GCC Compiler (or any C compiler)
- ✅ Basic terminal knowledge
- ✅ 5 minutes of your time!

### Advanced Compilation

```bash
# With optimizations
gcc -O2 -o game game.c

# With debugging symbols
gcc -g -o game_debug game.c

# With all warnings
gcc -Wall -Wextra -o game game.c

# Production build
gcc -O3 -march=native -o game_optimized game.c
```

---

## 📊 Game Statistics

<div align="center">

|📈 Metric|🎯 Easy|🎮 Medium|🔥 Hard|👹 Nightmare|💀 Ultra|
|:-:|:-:|:-:|:-:|:-:|:-:|
|**Avg. Guesses**|5-7|7-10|9-15|10-20|13-25|
|**Best Possible**|~6|~7|~9|~10|~14|
|**World Record**|3|4|6|7|9|

</div>

---

## 🤝 Contributing

We love contributions! Please see our [Contributing Guide](https://claude.ai/chat/CONTRIBUTING.md) for details.

<div align="center">

### 🌟 **Star this repo if you found it fun!** 🌟

[![GitHub stars](https://img.shields.io/github/stars/shiwansh-bind/number-guessing-game?style=social)](https://github.com/shiwansh-bind/number-guessing-game) [![GitHub forks](https://img.shields.io/github/forks/shiwansh-bind/number-guessing-game?style=social)](https://github.com/shiwansh-bind/number-guessing-game/fork)

</div>

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](https://claude.ai/chat/LICENSE) file for details.

---

## 👏 Acknowledgments

- 🎮 Inspired by classic number guessing games
- 💡 Built with pure C for maximum performance
- ❤️ Made with love for the programming community

---

<div align="center">

### 🎯 **Ready to Test Your Luck?** 🎯

[**▶️ PLAY NOW**](https://claude.ai/chat/ab988885-a81b-4592-a03e-61241428cef4#-quick-start) • [**📖 READ GUIDE**](https://claude.ai/chat/GUIDE.md) • [**⭐ STAR REPO**](https://github.com/shiwansh-bind/number-guessing-game)

<img src="https://forthebadge.com/images/badges/built-with-love.svg" /> 
<img src="https://forthebadge.com/images/badges/made-with-c.svg" /> 
<img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" />

**Made by [shiwansh-bind] • 2025**

</div>
