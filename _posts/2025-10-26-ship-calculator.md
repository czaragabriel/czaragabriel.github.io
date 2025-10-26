
---
layout: post
title: "Test Snippet Post"
date: 2025-10-26 12:00:00 +0000
categories: test snippet
---
Here is a test snippet for my ship speed calculator:

```javascript
export class speedCalculator {
  constructor(ship, baseSpeed) {
    this.ship = ship;
    this.baseSpeed = baseSpeed;
  }
  calc() {
    console.log(`${this.ship} speed is ${this.baseSpeed}`);
  }
}

const berserker = new speedCalculator('Berserker', 300);
berserker.calc();

- The `javascript` after the triple backticks enables **syntax highlighting**.

---

## **3️⃣ Save the file in `_posts`**

Example folder structure:

