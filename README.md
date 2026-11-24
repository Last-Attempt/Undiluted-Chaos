# Undiluted-Chaos

Most games have a design, a goal, a direction, most games have at least a _genre_.

**This is not most games**.

This is **Undiluted Chaos**.

## What it is

This is a game created collectively, _intentionally_ with no direction at all.

People will be encouraged to add arbitrary stuff to it with no rhyme or reason.

The aim is to be **chaotic but not unpredictable**, **varied but not frustrating**.

## Rules?

Funnily enough, to keep the Chaos running we need a few Rules.

- No destructive operations, hacking users either playing or watching, mining, etc. (this should be common sense but oh well).
- No hidden telemetry, sending data elsewhere, or any other sort of interaction with external sites or entities (same).
- **Everything is public, nothing is secret**. Related to the above, things like heatmaps, stats, and similar stuff are actually allowed, but they will be public for everyone to see.
- This is a **web game**. No executables will be produced.
- Management reserves the right to **change the rules** at any time.
- Code contributions to the project are under the **[MS-PL license](LICENSE)**.
  - Only use code for which you have the full rights (again should be common sense, but...)

### No logins

- Logins will be based on **clients' IP addresses**, in a similar fashion to what [Game1001](https://api.game1001.lastattempt.games/) does.
- D will be the Champion, the individual entity.
- C, B, and A will respectively be Chiefdom, Tribe, and Khanate. They are broad associations of related/allied entities, but what this actually means in this game will be left to see.
- If someone else tries to connect from the same IP you're using (so same Champion), they'll have to spectate until you log out.
  - IPv6 is not currently supported, but we're open to suggestions.

### One world, no mini-games

- This is **one world**. While it's chaotic and doesn't even have a set genre, **everything must be connected**.
  - No sharding or region locking.
- This means **no "isolated" mini-games** that have no or almost none connection with the rest.
- They can still be **radically different things**, you can mix and match some sections to be 2D platformers while others to be spreadsheet strategy, as long as they are **meaningfully** connected to each other.
- No jumpscares, porn, gore, stuff like that. Keep everything SFW and Safe in general.
- No religious, political, or controversial messages unless specifically approved by the Project Owner.

### Tools and moderation

- **No custom text input** is allowed. Yes, players will manage to be inappropriate in creative ways anyway, but we don't want to make this super easy by allowing them to write anything.
  - If discussions are to be had, those can happen in third-party chat servers or whatever.
- Wherever possible, Maintainers will only have to make sure the rules here are respected, but will have no other say in what Contributors will add other than this.
- The exception is where there are **conflicts between Contributors** wishing to give different directions to the same thing. In that case **Maintainers will intervene** and pick a direction, and **everyone will have to respect that**.
- AI use is explicitly allowed for coding, as long as you have enough experience to **review it and understand what's being written**. In other words, AI is allowed **if and only if** you make it code things that **you would be able to code yourself** if you had time and patience to.
  - Conversely, if you have no programming experience at all, please refrain from sending PRs. Feel free to enjoy the game or contribute in other meaningful ways, but **unrevised AI code is not welcome**. Of course if you find a real programmer willing to review your code for you, that's fine.
- Supporting optional peripherials (joypads etc.) is allowed as long as it's not mandatory.
- The game must work properly on normal computers running **any OS**.
  - If it also runs on mobile it's a very nice added bonus, but it's acceptable if some sections are less enjoyable there.
- Write all first-party client and server code in **TypeScript**. It must pass strict type checking. JavaScript libraries are welcome as dependencies.
- **Indentation with tabs is mandatory**. No exceptions.
- EOL is `LF` (`\n`). No exceptions.
