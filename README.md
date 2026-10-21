# Born To Banger: Digital Experiences

Interactive tools for events, celebrations and creative moments. This repo is the source of **[gm.borntobanger.in](https://gm.borntobanger.in)**, part of [Born To Banger](https://www.borntobanger.in).

Built by [Suraj Dev](https://www.surajdev.com).

<!-- Add one screenshot per tool here -->

## The tools

**AI Caricature Studio** turns a guest photo into a personalised caricature in seconds. Live at [/ai-caricature-studio](https://gm.borntobanger.in/ai-caricature-studio).

**Color My Art** lets you pick a design, colour it your way and end up with your own artwork. Live at [/color-my-art](https://gm.borntobanger.in/color-my-art).

**Room** is a shared digital space for watching, listening and experiencing together. Live at [/room](https://gm.borntobanger.in/room).

More tools are on the way for events: AI experiences, games, creative tools, artist experiences, interactive installations and digital gifting.

## Repo structure

```
gm.btb/
├── index.html                 landing page
├── ai-caricature-studio.html
├── color-my-art.html
├── room.html
└── CNAME                      custom domain for GitHub Pages
```

Each tool is a single HTML file. There's no build step and no framework. Push to `main` and GitHub Pages publishes it.

To preview locally:

```bash
git clone https://github.com/thesurajdev/gm.btb.git
cd gm.btb
python3 -m http.server 8000
# open http://localhost:8000
```

## Using these at your event

Born To Banger runs these experiences at weddings, parties and brand events. To bring one to yours, get in touch through [borntobanger.in](https://www.borntobanger.in).

## Privacy

Guests may upload photos to some tools. Don't use real guest photos with a tool until you know where the image is processed and stored. If you fork this repo, never commit API keys or tokens. Keep them on a server, not in the HTML.

## License

No license file yet. All rights reserved by default until one is added.
