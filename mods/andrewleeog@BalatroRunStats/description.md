# Run Stats

Track the current Balatro run with summaries, charts, card usage, and probability hit rates.

## Features

- **Summary:** run records and totals, purchases, Standard/Arcana/Celestial/Spectral/Buffoon pack counts, and average/median hand scores.
- **Trends:** scoring versus blind targets, hands needed to win, money earned and spent, cash reserves by shop, poker-hand usage, and consumables by ante. Switch to Analysis for score consistency and spending categories.
- **Prob:** recorded hits and rolls alongside current listed probabilities, including stacked Oops! All Sixes effects.
- **Cards:** rank/suit charts for played, discarded, drawn, and draw-to-play use rates.
- Shared ante filtering shows played antes, skips gaps, and supports endless runs beyond ante 8.
- Run Stats is available from the pause menu and win/game-over screens. Back returns to the result screen after reviewing a completed run.

Stats persist with the run save. New metrics start recording when installed; missing historical data is not reconstructed. The mod does not keep a separate archive after leaving a result screen or starting another run.

## Requirements

- [Lovely](https://github.com/ethangreen-dev/lovely-injector)
- [Steamodded](https://github.com/Steamodded/smods) is optional. Without it, the mod loads through Lovely and tracks Balatro's built-in chance effects. When installed, Steamodded's probability API is used for vanilla and supported modded effects.
- Talisman is not required.

## Installation and usage

Install into `Mods/BalatroRunStats` and restart Balatro. For manual installation, extract the release ZIP into the Mods directory, keeping its `BalatroRunStats` folder. Open **Run Stats** from the pause menu or result screen.

Released by **andrewleeog** under the [MIT license](https://github.com/andrewleeog/BalatroRunStats/blob/main/LICENSE), which permits redistribution and mod-manager distribution.
