# NUMBERS TELEPATHY GAME

> Hi friend, this is a fun little game where you try to **read the computer's mind** by guessing its secret number!

Edit: I thought to create a web version for it but that idea has been discarded as I've moved on to bigger pursuits.
---

## How to Play

1. **Start the game**
   - The computer picks a secret whole number between **1 and 365** (yes, like guessing a birthday!).

2. **Make a guess**
   - Type in a number and press **Enter**.

3. **Get hints**
   - If your guess is **too low**, the computer will say:
     > `"Too small bro, ask for more."`
   - If your guess is **too high**, it'll say:
     > `"Jokes on you, that's too much bro, don't be greedy."`

4. **Keep guessing**
   - Use the hints to narrow it down within range.

5. **Win!**
   - When you guess it right, the computer celebrates:
     > `"God of Telepathy, we hail thee! [number] is RIGHT!"`
   - Then you can choose to **Restart** (type `R`) or **Exit** (type `E`).

---

## Fun Features

- **Playful personality** – The computer talks like a buddy, not a robot.
- **Forgiving** – Type letters by mistake? No problem! Just try again.
- **Big range** – Guessing from 1–365 is trickier and more fun than 1–100.
- **Quick to play** – Perfect for a short break or a fun challenge with friends.
- **Restart option** – Keep playing without relaunching the game!

---

## Example Round

```
WELCOME TO OBOT'S NUMBERS TELEPATHY GAME!
I'm Thinking Of A WHOLE NUMBER BETWEEN 1 AND 365
You Can Now Make Your Wildest Guesses

150
150's too small bro, ask for more.

300
Jokes on you, 300's too much bro, don't be greedy.

225
225's too small bro, ask for more.

275
God of Telepathy, we hail thee!
275 is RIGHT!

Type capital R to restart OR capital E to end the game
R
Restarting the game...
```

---

## Great For...

- **Complete beginners** – No gaming experience needed!
- **Quick fun** – Play during a coffee break
- **Friends & family** – See who has the best "telepathic" skills
- **Learning about computers** – See how guessing games work behind the scenes
- **Learning Rust** – See modular code organization in action!

---

## Tip

Play it like "Hot & Cold" with a computer friend. The smartest move: start in the middle (around 180) and use the hints to zero in on the secret number!

**Ready to test your mind-reading abilities?**

---

## Project Structure (Modular Design)

```
numbers_telepathy_game/
├── Cargo.toml
├── Cargo.lock (automatically generated)
├── README.md
└── src/
    ├── main.rs
    ├── game.rs
    ├── input.rs
    └── restart.rs
```

### Module Breakdown

| File | Responsibility |
|------|----------------|
| `main.rs` | Entry point - starts the game |
| `game.rs` | Core game logic, secret number, win/loss conditions |
| `input.rs` | User input handling, parsing, error messages |






## How to Run

1. Install Rust (if you haven't already)
2. Create the project folder with the files above
3. Open terminal in the project folder
4. Run:
   ```bash
   cargo run
   ```
5. Start guessing!

---

## OR: Quick Installation

**Clone the repository:**

```bash
git clone https://github.com/oboobotenefiok/numbers_telepathy_game.git
```

**Enter the game directory:**

```bash
cd numbers_telepathy_game
```

**Run the game:**

```bash
cargo run
```

When you run the game for the first time, Cargo will automatically create a `Cargo.lock` file.

---

## What Makes This Special?

This Rust project demonstrates:

- **Modular architecture** – Clean separation of concerns across 4 modules
- **Random number generation** – Using the `rand` crate
- **User input handling** – Robust parsing with error recovery
- **Game logic** – Loops, conditionals, and match statements
- **Flow control** – Restart/exit functionality without recursion issues
- **Clean code practices** – Single responsibility principle in action

---

## Learning Rust Through This Game

| Concept | Where to Find It |
|---------|-----------------|
| Structs & impl blocks | `game.rs` — `Game` struct |
| Modules & visibility | `main.rs` — `mod` declarations |
| Error handling | `input.rs` — `match` with `parse()` |
| Crates & dependencies | `Cargo.toml` — `rand` dependency |
| Loops & control flow | `game.rs` — `loop` and `match` |
| Enums | `std::cmp::Ordering` |

---

Good Luck & Good Playing :-)

**Obot Obo** — Developer

