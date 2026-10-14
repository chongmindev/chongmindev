# hey, I'm Chong

CS at Stanford ('29). I like building things that turn messy data into something
you can actually use, plus physical AI and sustainability. Off the keyboard:
competitive speedcubing (R U R' U'), lifting, and hunting for good food.

### Building right now

**[omnibowl](https://github.com/chongmindev/omnibowl)**: give it a textbook PDF and it
writes pyramidal quizbowl tossups, hardest clue first. No LLMs: spaCy, keyness
scores and a coreference model pick answers and clues, and every clue points back to
the sentence it came from. Play solo, or in protobowl-style multiplayer rooms (FastAPI WebSockets).
[Try the single-player page](https://github.com/chongmindev/omnibowl/blob/master/play/index.html).

**[local groundwater context engine](https://github.com/chongmindev/local-groundwater-context-engine)**:
public well measurements in, local trend signals out. Each California well gets
Improving / Stable / Declining by comparing before vs. after SGMA (2014) with a
significance test, then gets mapped.

**Cube Recon**: recovering a speedcube's starting scramble from video of the solve.
Computer vision reads the stickers, a CTC-trained sequence model transcribes the moves,
and Bayesian state tracking plus a Z3 solver carry it all back to the first frame.
When a clip can't pin every piece down, it reports a distribution over legal states
instead of one guess.

**Thumbs Up Coffee**: a little family of coffee projects
- [coffee map](https://chongmindev.github.io/thumbsup-coffee-map/): one pin per Instagram cafe review, fed from a Google Sheet
- [cafe diagnostic](https://thumbsupcoffee.vercel.app): a free one-minute online checkup for independent Korean cafes (Next.js, deterministic scoring, public data)
- Explore: an iOS app (Expo) for ranking specialty cafes by head-to-head comparison instead of star ratings (prototype)

### Usually reach for
Python, TypeScript, SQL, spaCy, FastAPI, React Native / Expo, Supabase, Spark / Airflow

### Find me
[chongmindev.github.io](https://chongmindev.github.io) / [LinkedIn](https://www.linkedin.com/in/chongmin07) / cmin29@stanford.edu
