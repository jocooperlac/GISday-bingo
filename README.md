# Los Angeles County GIS Day Bingo

A game of chance, clicks, and emoji.
Made with [Svelte](https://github.com/sveltejs/svelte).
Click [here](https://jocooperlac.github.io/GISday-bingo/) to play.

# Gameplay

Before playing,
have everyone load the game on their own device.
With the game loaded on everyone's device,
select a host.
The host will click the call button.
The rest of the group will click the play button.

The host is responsible for
generating and calling out the randomly chosen word
as well as verifying each bingo.
On the call page,
click the spin button to generate the next randomly chosen geographic term.
Each randomly chosen geographic term will show up at the bottom of the call page.
This will help with verifying each bingo.

The rest of the group will use the play page.
On the play page is the bingo card.
Each bingo card is generated randomly.
When the host calls out a word,
find that particular geographic term on your card.
If your card contains the given term,
click it.
If it doesn't contain it,
wait for the host to give the next word.
If you accidentally click a square,
you can click it again to deselect it.

When you get a bingo,
let the host know so they can verify it.

# Customize

The emoji are located in [main.js](src/main.js).

# Build

```bash
git clone https://github.com/lettier/GISday-bingo.git
cd emoji-bingo
# Install Node Version Manager.
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
nvm use
npm install
npm run build
```

# Run

```bash
npm run dev &> /dev/null &
python -mwebbrowser http://localhost:55555
```

## Copyright

Based on original code (C) 2020 David Lettier
<br>
[lettier.com](https://www.lettier.com)
