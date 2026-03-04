# polymarket
WhaleSight is an open-source browser extension designed to bring real-time on-chain analytics directly to your Polymarket interface. Track smart money, monitor high-volume bets ($10k+), and gain an edge in prediction markets without leaving the page.

## Features

* **Real-time Whale Alerts:** Get instant browser notifications when a bet exceeding your custom threshold is placed on any active market.
* **Smart Money Tracking:** Highlight addresses with high historical win rates or large capital deployments directly on the order book.
* **Volume Delta Indicators:** See sudden shifts in market sentiment before the odds fully adjust.
* **Seamless Integration:** Native, non-intrusive UI elements injected directly into the Polymarket dashboard.

WhaleSight relies on public Polygon network data and Polymarket's open API to index large transactions. It processes the stream locally in your browser via a lightweight background service worker, ensuring zero latency and maximum privacy.

No tracking: We do not track your personal bets or wallet addresses.

No wallet connection required: The extension reads public data; it never asks for your private keys or seed phrases.

⚠️ Disclaimer
Not Financial Advice. WhaleSight is an analytical tool built for educational and informational purposes only. Prediction markets are highly volatile. Always do your own research (DYOR) before placing any trades. The maintainers of this project are not responsible for any financial losses.
