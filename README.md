# GPU Hotel

A browser game about inference economics. You run a hotel with 100 GPUs: models are room types, loading a model is prepping a room, and every request is a guest checking in. Keep enough rooms warm that guests don't walk out, but not so many that you pay for empty rooms.

Open `classic.html` in a browser. No build step, no dependencies beyond Google Fonts.

- Seven in-game days, each with an event modeled on something that happened in the inference market (a model launch-day flood, a GPU crunch, a delisted model, a big customer leaving for its own cluster).
- Languages: English, Español, Français, Türkçe, 中文 (picker in the top-right corner).
- The "Where the numbers come from" table at the bottom lists the public sources behind cold-start times, batching curves, GPU prices and failure rates. Prices, traffic and event strength are tuned for play and are not real quotes.
