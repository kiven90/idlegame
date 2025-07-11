# idlegame

This repo contains a simple web page where you can gather gold by clicking a button.
After reaching 5 gold the pickaxe button becomes visible. The first pickaxe can
be purchased for 10 gold and each additional pickaxe costs double the previous
one while increasing the click multiplier from x2 to x3, x4 and so on. The
button now shows the number of the next pickaxe you are buying so the text reads
`Buy Pickaxe #1 (Cost 10 Gold)`, `Buy Pickaxe #2 (Cost 20 Gold)` and so on.
Each time you search for gold the button enters a short half-second recharge period
before it can be clicked again. A small progress bar shows when the button is
ready.
Upon reaching 25 gold you can hire a worker who automatically generates
one gold every second. The current gold per second rate is shown next to
the gold counter.

When you accumulate 100 gold a celebratory "YOU WON" message appears to
let you know you've finished the game.

## Playing locally

Open `index.html` in your web browser or start a small web server in this
directory with `python -m http.server` and browse to `http://localhost:8000`.
