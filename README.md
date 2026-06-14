# JES — AI Portfolio Assistant

**[Talk to JES live →](https://jesbot.netlify.app)**

---

## What is this?

JES is an AI-powered portfolio chatbot built as a direct ode to ELIZA — the 1966 rule-based chatbot by Joseph Weizenbaum that first sparked my fascination with human-computer interaction at age 13.

I was captivated by the illusion of intelligence before I understood what intelligence was. That curiosity never left. So when I decided to build a portfolio assistant, I asked myself: what better way to show how much I love AI than to turn myself into one?

Unlike ELIZA, which simulated understanding without having any — JES actually knows what she is talking about. Same aesthetic. Very different brain underneath.

---

## The Inspiration — ELIZA (1966)

The aesthetic is a deliberate tribute to the world ELIZA came from: 1960s and 70s CRT terminals.

![ELIZA screenshot 1](Eliza_inspo1.jpg)
![ELIZA screenshot 2](Eliza_inspo2.png)
![ELIZA screenshot 3](Eliza_inspo3.png)

---

## The Design Process — Figma

Before building, I designed the UI in Figma — mapping out the terminal layout, colour palette, and typography.

![JES Figma design](JesBot_figma.png)

- Background: `#0A1A0A` forest green
- JES responses: `#FF69B4` magenta
- User input: `#FFFFFF` white
- Font: VT323 (Google Fonts)
- Dashed pink dividers, scanline overlay, blinking cursor, typewriter effect

---

## The Final Product

![JES working](JesBot_working.png)

**[Try it live at jesbot.netlify.app →](https://jesbot.netlify.app)**

---

## Why "JES"?

My initials are JS. Say them fast enough and you get Jes. It started as a nickname my school best friend and I came up with when creating alter egos for each other. But Jes became more than a nickname — she is my alter ego. Bolder, more confident, more get-it-done. When it came to building an AI that would represent me to the world, who better to be than Jes?

---

## How it works

- Frontend: vanilla HTML, CSS, JavaScript — single file, no frameworks
- AI: Claude Sonnet 4.6 via Anthropic API
- Hosting: Netlify
- System prompt trains JES on my background, experience, projects, and personality

---

## To run locally

1. Clone this repo
2. Add your Anthropic API key to the `ANTHROPIC_API_KEY` variable in `index.html`
3. Open `index.html` in a browser

---

## Built by

**Janhavi Shrivastava**
MSc Human-Computer Interaction, Newcastle University
[jesbot.netlify.app](https://jesbot.netlify.app) · [shrivastavajanhavi1@gmail.com](mailto:shrivastavajanhavi1@gmail.com)
