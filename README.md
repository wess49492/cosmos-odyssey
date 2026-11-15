# Cosmos Odyssey

**Play it here: https://wess49492.github.io/cosmos-odyssey/** (runs in the browser, no install).

**Pitch (7 slides, PDF): https://wess49492.github.io/cosmos-odyssey/cosmos-odyssey-pitch.pdf**

A browser game for the **NASA Space Apps Challenge 2026**, challenge **Space Mission Design Game**, by **Team Capella Stars** (Recife, Brazil).

Students rarely live a whole space mission, so engineering trade-offs stay abstract. In Cosmos Odyssey you plan, build, launch and bring a spacecraft home with limited resources, following the 7 phases of the NASA project life cycle:

1. **Concept studies:** compare real mission alternatives (OSIRIS-REx, Perseverance, a future resource mission).
2. **Concept development:** choose the objective, the launch site (Kennedy, Vandenberg or Wallops) and the launch date inside the launch window (Mars about every 26 months, asteroid Bennu about every 6 years, the Moon almost every month).
3. **Preliminary design:** build the spacecraft with science points; every part is a trade-off.
4. **Final design and fabrication:** assemble the rocket and tune the parameters.
5. **Assembly, integration and test:** the requirements decide if the test flight passes.
6. **Operations:** launch and fly, solving random crew tasks, each one opening with a short science note.
7. **Closeout and return:** reentry, landing and a final mission report that shows which early choice made the difference, plus the real mission most like your spacecraft (OSIRIS-REx, Stardust, Hayabusa2, Perseverance, InSight, Dawn, Voyager, Psyche or LCROSS) and what it did differently.

English and Portuguese (EN / PT button). Everything runs in a single `index.html` file.

## NASA resources used
- Design and Develop Science Missions (official challenge resource).
- NASA Systems Engineering Handbook and NASA project life cycle (Pre-Phase A to Phase F).
- Concept Maturity Levels (JPL) and NASA's Mission Design Lab: phases 1 to 3 show how mature your concept is (CML 1-2, 3 and 4) and the matching MDL study (Office Hours and Concept Development, Trade Study, Point Design); each spacecraft row is one MDL discipline (power, propulsion, thermal, communications, science payload).
- NASA mission pages: OSIRIS-REx, Mars 2020 Perseverance (and MOXIE), LCROSS, Psyche.
- GMAT, NASA's General Mission Analysis Tool (challenge resource): the launch-window step is a simplified version of its launch-window analysis.
- A Learning Game About Telescopes (challenge resource): the idea of ending by comparing the player's design with real missions.

Numbers in the game are simplified for learning. The crew is named after the Artemis II astronauts (Reid Wiseman, Victor Glover, Christina Koch and Jeremy Hansen) as a tribute; their lines in the game are invented, not quotes, and the game is not endorsed by them, by NASA or by the CSA.

## Use of AI
The game idea and every design decision came from our team. We used AI tools as follows:
- **Code and texts:** most of the code (HTML, CSS, JavaScript), the in-game texts and the English translation were written with the help of an AI coding assistant (Claude, by Anthropic), following our specifications. We reviewed and tested everything.
- **Research:** Google Gemini gave us a first summary of NASA mission-process pages, which we checked against the NASA Systems Engineering Handbook.
- **Crew portraits:** the four crew faces and the full-body crew line-ups shown before launch and after landing are AI-generated caricatures named after the Artemis II astronauts, with the NASA logo covered. Their speech balloons are written for the game.
- **No AI-generated audio or video.** All other visuals are drawn in code or are screenshots of the game.

The same notice is in the `ai-assistance` meta tag at the top of `index.html`.

*Per aspera ad astra.*
