# PJensen

Software architect at Harvard Management Company. I design systems that make institutional-scale portfolio management transparent and navigable — bridging human judgment with structured data where the stakes are real.

<img src="images/1985.jpg" width="160" align="right" />

I've been writing code for thirty years. BASIC in fourth grade, C by sixth, inline x86 assembly by sixteen — plotting pixels to `0xA000` on an 80386 using shift-add multiplication picked up from a book I found at the Salvation Army. The reference books are still in the garage.

Since then: Acadia University (CS), cross-platform systems across GNU/Linux, Win32, HP-UX, and Solaris, sixteen years of C#/.NET, and a long arc through Python, JavaScript, and whatever the problem demands. I care about the layer underneath — the primitives, the state model, the thing hiding below the abstraction everyone's excited about.

I also paint, sculpt, ski, drum, and grow rare medicinal plants. My grandmother taught me to work with my hands across every medium. Each one reinforces the same principle: precision and creativity aren't opposites — they sharpen each other.

---

### Projects

**[ecs-js](https://github.com/PJensen/ecs-js)** — A tiny, deterministic Entity–Component–System core in pure JavaScript. Zero dependencies. No build step. Fourteen source files.

- Caller-driven ticking — the library has no opinion about time
- Phase-agnostic system scheduling with topological ordering (`before`/`after` declarations)
- Seeded PRNG (mulberry32) + deferred structural mutations = full determinism
- Snapshot/restore for time travel, replays, and branching
- Archetypes, hierarchy management, cross-world entity references
- Query builder with `where`, `project`, `orderBy`, `offset`, `limit`
- Entity-local scripting via handler tables with event routing and error capture
- Storage flexibility: `map` for clarity, `soa` for throughput

Built for simulations, agent-driven systems, and complex interactive state — not just games, though it handles those too.

**[js-hack](https://github.com/PJensen/js-hack)** — A spiritual successor to NetHack, built on ecs-js. Roguelike mechanics as an architectural stress test.

**[DotNetHack](https://github.com/PJensen/DotNetHack)** — The earlier attempt — a .NET roguelike from 2012 that started the thread.

---

### Writing

I publish on [Substack](https://pjensen.substack.com/) — essays on system architecture, AI substrate problems, institutional dynamics, and the practice of looking underneath.

---

<p align="center">
<img src="images/conways_glider.png" width="32" />
</p>
