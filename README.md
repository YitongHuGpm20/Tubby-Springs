# Tubby Springs

### A very unbusy business.

A cozy animal resort management game about building a happy little retreat—and keeping it pleasantly unbusy.

Welcome capybaras, Shiba Inus, raccoons, and penguins to a countryside getaway filled with warm baths, tasty snacks, comfy cabins, and blooming gardens. Start small, find your rhythm, and grow a place worth slowing down for.

![Tubby Springs promotional cover: four animal guests relaxing at a paper-collage hot spring resort](releases/tubby-springs-cover-v1.png)

**Browser game · Playable demo · Single player**

[Download the browser build](releases/tubby-springs-0.3.0-itch-web.zip) · [Credits & asset sources](CREDITS.md)

The downloadable ZIP is a web-hosting package. To run the game locally, see the [developer guide](docs/development.md#run).

## Your little retreat

Build hot springs, snack shacks, cozy cabins, and wild gardens across nine meadows. Your guests explore on their own, choosing activities according to their needs, preferences, distance, crowds, and cleanliness.

Your job is to make their holiday work: balance service capacity, prices, upkeep, and visitor happiness, then turn happy reviews into the next improvement. Gardens grow over time, rain gives them a boost, and rotating guest clubs bring fresh demand to the resort.

- **Four charming animal guests.** Meet a professional relaxation consultant, a chair-claiming Shiba, a suspiciously well-equipped raccoon, and a penguin with opinions about water temperature.
- **A business at your pace.** Set prices, upgrade facilities, hire caretakers, and research permanent improvements. Pause whenever you like or speed things up.
- **Room to make it yours.** Expand outward from the central meadow and specialise districts around your favourite services.
- **Always a little to do.** Follow eight career chapters, complete continually refreshed commissions, and collect 29 achievements.
- **A handmade holiday.** Pastel paper landscapes, cutout animal animations, and tucked-away interface panels keep the retreat in focus.

## How to play

Choose a facility from the bottom menu, then click clear ground to build. Select an existing facility to clean or upgrade it. Guests discover available services automatically.

| Control | Action |
| --- | --- |
| Drag | Move around the resort |
| Scroll or + / − | Zoom in and out |
| Fit | View the whole map |
| Escape | Cancel construction or close details |
| Pause / 1× / 2× / 4× | Set the pace |

Open **Getting started** for the introduction and **To-do** for ongoing commissions. The **Cashbook** tracks your business; the **Guestbook** records visitor stories and reviews.

Progress saves automatically in your browser. Return using the same browser and site to continue; clearing site data removes the local save.

## About the project

**Created by Yitong Hu · Game design, systems design, visual direction, and development with AI-assisted workflows.**

Tubby Springs explores how a relaxed atmosphere can coexist with meaningful management decisions. The player shapes the environment while autonomous visitors bring it to life. Capacity, travel distance, cleanliness, and pricing connect the layout of a cute little resort to its economic performance.

The progression combines short, repeatable commissions with longer chapter goals, research, and district specialisation. Caretaker automation gives players another way to manage maintenance as the park grows. The interface gives the world most of the screen, with detailed management tools available when needed.

The current demo contains four animal species and four base facility types. Later progression develops those foundations through upgrades, research, and themed districts. Long-term pacing has been checked through an accelerated 20-hour simulation; player testing is still needed to assess the experience and actual playtime.

**Built with:** Phaser, TypeScript, and Vite. The simulation is separated from rendering and interface code, with tests covering the economy, progression, and save continuity.

For a closer look: [progression design](docs/progression-design.md) · [simulation balance report](docs/career-balance-report.json) · [developer guide](docs/development.md).

## Credits

- **Game design and development:** Yitong Hu, with coding assistance from OpenAI Codex.
- **Character designs and animation:** Generated with DreamLayer. All four animal references, twelve animation sheets, and derived portraits are documented in the asset register.
- **Scenery, facilities, icons, and interface:** Project-specific SVG, Phaser graphics, and CSS created with Codex assistance.
- **Promotional cover:** Generated with OpenAI ImageGen using the existing game characters and a gameplay screenshot as references.
- **Visual inspiration:** [Vincent Wei’s Collage / Cutout Animation reference](https://vincentwei1021.github.io/mg-styles-15/).
- **Fonts:** Fraunces by The Fraunces Project Authors and Patrick Hand by Patrick Wagesreiter, both under SIL OFL 1.1.
- **Sound:** Interface chimes synthesised with the Web Audio API.

See [CREDITS.md](CREDITS.md) for individual asset sources, generation records, and font licenses.
