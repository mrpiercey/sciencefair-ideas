# Science Fair Idea Lab

500 science fair project ideas for 4th and 5th graders, in 11 topics (including Taste & Brand Tests: blind taste tests and brand-vs-brand product tests). Students pick the topics they like, browse the projects, and open one to see its base materials, time, and safety notes. Each project also has 10 open-ended question ideas hidden behind a tap-to-open box (data/questions-*.js); students can pick one as their guiding question. The site never lists hypotheses, variables, or results.

- `index.html`: the app
- `data/*.js`: the projects. Each one has a title (`t`), a description (`d`), a level (`lv`: 1 easy, 2 medium, 3 challenge), `time`, materials (`mat`), and a safety note (`safe`).

Hosting: GitHub Pages now. Firebase Hosting later (`firebase.json` is ready: `firebase init hosting`, keep the existing config, then `firebase deploy`).
