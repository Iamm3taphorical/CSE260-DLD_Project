# CSE260 — Digital Logic Design  
## Project Ideas

This repository contains project ideas for the CSE260 (Digital Logic Design) course.  
Each project focuses on implementing digital circuits using basic logic gates and displaying outputs on 7-segment displays.

---

## 🥤 Idea 1 — Naive Vending Machine

### Description
A simple vending machine with two available items:

- **Item 1:** 4 Taka (Selection bit = `0`)
- **Item 2:** 5 Taka (Selection bit = `1`)

The machine accepts up to **7 Taka** (binary input) and allows selecting only one item at a time.

Behavior:

- If entered amount **> price** → return balance
- If entered amount **= price** → no change
- If entered amount **< price** → display negative amount (how much more is needed)

All outputs are shown using a **7-segment display**.

### Allowed Gates / Components


AND, OR, NOT, NAND, NOR, XOR, X-NOR, Parallel Adders



### Sample Input–Output

#### Example 1


Input:
Selection = 1
Amount = 110

Output:
01   (Displayed on 7-segment display)

`

#### Example 2


Input:
Selection = 2
Amount = 011

Output:
-1   (Displayed on 7-segment display)




## ➖ Idea 2 — Subtractor

### Description
Two 3-bit numbers are subtracted, and the result is displayed using **two 7-segment displays**.

### Allowed Gates / Components


AND, OR, NOT, NAND, NOR, XOR, X-NOR



### Sample Input–Output

#### Example


Input:
111
010

Output:
05   (Displayed on 7-segment display)




## 📌 How to Use

1. Select a project idea.
2. Design logic using only the allowed gates.
3. Create truth tables and simplify circuits.
4. Simulate using tools such as:
   - Logisim
   - Proteus
   - Multisim
5. Document results and outputs.

---

## 📄 Recommended Documentation

Include the following when submitting:

- Project overview
- Block diagram
- Truth tables
- K-map simplification
- Final circuit diagram
- Simulation screenshots
- Test case results
- Conclusion

---

### 📘 License
For academic and learning purposes only.

Just tell me 👍
