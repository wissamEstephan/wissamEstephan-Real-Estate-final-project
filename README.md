# Wildlife Explorer

A sleek **web app** for nature lovers that delivers quick animal facts, real-time search, and playful 3-D emoji animations – all with pure **HTML 5**, **CSS 3 / Bootstrap 5**, and vanilla **ES 6 JavaScript**.

---

## Author

**Wissam Antoine Estephan**

---

## Public API Used

| Purpose | API Service | Endpoint |
| ------- | ----------- | -------- |
| Species data, habitat & emoji hint | API Ninjas – Animals | `https://api.api-ninjas.com/v1/animals?name=` |

> **Heads-up :** API Ninjas requires a free key. The first call in `WildlifeAPI.js` expects it in the `X-Api-Key` header.

---

## Project Map

| File / Page       | Role in the app                                                                                               |
| ----------------- | -------------------------------------------------------------------------------------------------------------- |
| **`home.html`**  | have the animation of the logo of the company.                                                                   |
| **`add.html`** | add a house demended by the client through the company website                                                    |
| **`buy.html`**  | show the houses already in sales, also filters the choises of house                                              |
| **`contact.html`** | used by the client when he wants to get more infos                                                            |
| **`house1.html`**  | example of showing the houses below the page                                                                  |

---

## Notable UI / UX Touches

- **3-D Orbit Animation** – CSS-only effect that makes the hero emojis “pop” off the screen.  
- **Adaptive Layout** – Mobile-first breakpoints, off-canvas navigation, and fluid cards.
- **Dynamic Bootstrap Modal** – Displays live animal data fetched from an API, shown only when a user interacts with a card.

---

## Getting Up & Running

1. **Clone** this repository or download the ZIP.  
2. Open `WildlifeAPI.js` and paste your **API Ninjas key** into the `API_KEY` constant.  
3. **Serve** the project from VS Code Live Server.  
4. Browse to `http://localhost:<port>/index.html`
---
