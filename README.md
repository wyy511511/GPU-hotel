# GPU Hotel

Browser games about inference economics. You run a hotel with 100 GPUs: models are room types, loading a model is prepping a room, and every request is a guest checking in.

Open either file in a browser. No build step and no dependencies beyond Google Fonts. Both are in English, Español, Français, Türkçe and 中文 (picker in the top-right corner).

## `index.html`: Model Marketplace

One API key, every model. On top of running GPUs, you resell other labs' models:

- **Open models** run in your own rooms. You keep the whole price, but you need warm rooms, and every extra model spreads your rooms thinner.
- **Closed models** run in the lab's rooms. They cost you no GPUs, but you keep only the lab's cut (10–25%), and the lab caps how many requests you can send.
- **Customers pick a model, not a hotel.** Every request chooses from the whole market; if that model isn't on your shelf, most customers take the request elsewhere. Coverage is the share of demand you could serve.
- **Labs choose launch partners by developer community.** A bigger community gets you day-zero access to hot closed models; walkouts and rate limits shrink it.
- **Exclusive turbo versions**: co-develop a faster version of an open model with its lab. Nobody can pull it from your shelf.
- **Named customers** grow, complain about reliability, leave, or try to graduate to their own GPUs and compete with you.
- Day 7 ends with a valuation: annualized revenue times a multiple that rewards community, exclusive models and margin, and punishes dependence on one customer.

Events are modeled on the 2025–2026 generative-media market (day-zero launches, a GPU crunch, a lab pulling its model from aggregators, a big customer leaving). Model, lab and customer names are fictional; the "Where the numbers come from" table lists the real-world parallels and sources.

## `classic.html`: Seven-Day Run

The original version: four fixed room types (chat, image, video, agent sandboxes), focused purely on scheduling: cold starts, batching, keep-warm timeouts, surge pricing and emergency rentals.

Prices, traffic and event strength in both games are tuned for play and are not real quotes.
