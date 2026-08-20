# Peek-a-Boo Haunted House 👻

A cozy, touch-friendly hide-and-seek game made for 5–6 year olds on an iPad. Little players tap the friendly monsters, ghosts and creatures hiding in windows, doors, trunks and baskets to earn stars, light up each room, and finally fill the big lamp at the top to light up the **whole house**.

The whole game is **one single HTML5 file** — no installs, no server, no app store. Just open `index.html` in any browser (Safari on iPad works great) and it runs.

---

## 🎮 How to play

1. Tap **TAP TO PLAY!** to start.
2. Friends pop up and hide in windows, doors, trunks, baskets, barrels and more.
3. **Tap the friends** to catch them and earn a star (a sparkly golden friend gives **2 stars**!).
4. Find **all 4 friends** in a room to light that room up — watch the room's dot fill with a little star.
5. Use the big **◀ ▶ arrow buttons** to walk to the next room.
6. Fill the lamp meter at the top to light up the **whole house** — the big celebration happens, then the fun starts again.

Tapping empty space always makes a friendly little sparkle, so there's no frustration — the screen always responds.

## ✨ What makes this version better

- **6 different rooms**, each with its own look and furniture:
  - 🛋️ **Living Room** (fireplace, sofa, rug)
  - 🍳 **Kitchen** (stove, fridge, hanging pans)
  - 🛏️ **Bedroom** (bed, night lamp, teddy)
  - 🧸 **Attic** (boxes, hanging lamp, cobweb)
  - 🕳️ **Basement** (stone shelves, barrels, pipes)
  - 🌻 **Backyard** (trees, bushes, pumpkins, fireflies)
- **More hiding spots per room** — windows, round windows, doors, cupboards, wardrobes, picture frames, trunks, baskets, barrels, dark holes, stone arches and a garden shed.
- **8 character types**, each with its own look and animation:
  - 👻 Ghost, 🧟 Zombie, 👾 Monster, 🦇 Bat, 💀 Skeleton, 🕷️ Spider, 🧙 Witch, 🎃 Pumpkin
- **Better graphics**: richer wall gradients, wallpaper dots, themed floors (wood, tile, carpet, stone, grass), ceiling strips, ambient floating dust, firelight, flickering lamp glow and vignette lighting.
- **Better gameplay mechanics**:
  - Each room now has a **"find all 4 friends" goal** that lights up the room.
  - Room progress is shown as **star-filled dots** at the bottom.
  - Rare **golden friends** give 2 stars.
  - Bigger confetti + fanfare celebrations for milestones and room clears.
- **Preschool-friendly touches**: big touch targets, no reading required (emoji icons instead of text), multi-touch safe, no pinch-zoom or long-press interference.

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The **entire game** — graphics, sounds, gameplay, everything, in one file. |
| `README.md` | This guide. |
| `LICENSE` | License terms. |

## ▶️ Running it

- **iPad / iPhone**: open `index.html` in Safari. No internet needed.
- **Desktop**: just double-click the file in any modern browser.
- For best results, open it full-screen (the game auto-fits any screen size and works in both portrait and landscape).

## 🛠️ Customising (quick tips)

Everything lives in one file, so edits are easy:

- **`ROOMS` array** (near the top of the script): change room colors, emoji, furniture and hiding spots.
- **`starGoal`** variable: how many stars fill the house lamp (default `10`).
- **`roomGoal`** variable: friends needed to light a room (default `4`).
- **`drawCharacter()`** function: the character types. Add your own draw function and register it here.

## 🎵 Sounds

All sounds are generated live in the browser (no audio files). Tapping friends plays a giggle, room changes play a whoosh, and milestones play a little fanfare. A soft looping tune starts when you tap play.

## ✅ Requirements

- Any modern browser with HTML5 canvas + Web Audio support (Chrome, Safari, Firefox, Edge — iPad Safari included).
- No external assets, no network connection needed.

---

Have fun hunting for the spooky friends! 🎃✨
