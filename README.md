### Melih Gürlek

AI engineer. Istanbul.

I build language models that aren't allowed to lie, and I read other people's code for the bugs they didn't see. The second one is faster.

Day job: RAG agents on Azure at **Ensight Data & AI**.

**Security**

- containerd sits under Docker and most of Kubernetes. One malformed digest crashes it. **[CVE-2026-95839](https://github.com/containerd/containerd/security/advisories/GHSA-vwhp-8p66-mq4f)**, credited.
- The NSA has a bug report from me in **Ghidra**. They accepted it. Details when they publish.

**Upstream**

- [perses/shared#255](https://github.com/perses/shared/pull/255): their panel links menu didn't open inside the overflow menu. Now it does. Merged.

**Things I've built**

| | |
|---|---|
| **AlignCV** | Tailors a resume to any job posting and cannot invent a single line. It also reads the job boards every morning so I don't have to. *Private. Ask.* |
| [**lexiconweaver-core**](https://github.com/melihgurlek/lexiconweaver-core) | Machine translators rename the same character three times in ten chapters. This one doesn't. |
| [**InsiderProject**](https://github.com/melihgurlek/InsiderProject) | A Go transaction engine with a concurrent task queue on PostgreSQL, Redis, and p95 latency dashboards, because I wanted to know. |
| [**GoodreadsScore**](https://github.com/melihgurlek/GoodreadsScore) | Goodreads ratings on Amazon and Kitapyurdu. I shouldn't need a second tab. |
| [**frostpeak-mail**](https://github.com/melihgurlek/frostpeak-mail) | Gmail, but there's a dragon. |
| [**lg-webos-mirroring**](https://github.com/melihgurlek/lg-webos-mirroring) | My TV's Wi-Fi died. I didn't buy a new TV. [Here's why I didn't have to.](https://github.com/melihgurlek/lg-webos-mirroring/blob/main/FINDINGS.md) |
| [**Match-3**](https://github.com/melihgurlek/Match-3-Case-Study) · [**Void Drifter**](https://github.com/melihgurlek/Project-Boost-Platformer-Game) | Two games. [Playable in your browser.](https://aciros.itch.io/) |

**Currently researching**

- **Reinforcement Learning from Human Frustration (RLHF):** reward signals derived from the volume of the keyboard
- **Room-temperature superconductivity:** LK-99 replication, in progress
- **Retrieval-Augmented Guessing (RAG)** for production incident response
- **P vs NP:** I have a truly marvelous proof, which this README is too narrow to contain
- **Self-healing distributed systems** with fault tolerance through `except: pass`
- **Dark matter localization:** current estimates place most of the universe's missing mass in `node_modules`
- **Hyperparameter search**, which has converged on `seed=42` across all experiments to date
- **Collatz conjecture:** verified by hand up to 27, which took longer than expected
- **Heisenbug spectroscopy:** characterizing defects that vanish under observation
- **Sprint estimation** under the spherical-cow approximation
- **O(1) root-cause attribution** with `git blame`, pending the result I keep getting

Python, Go, TypeScript, C#. Whatever you're using, I'll have it by Monday.

If you're hiring: [LinkedIn](https://linkedin.com/in/melihgurlek). If you're a maintainer: check your security advisories.
