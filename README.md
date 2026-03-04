# polymarket
WhaleSight is an open-source browser extension designed to bring real-time on-chain analytics directly to your Polymarket interface. Track smart money, monitor high-volume bets ($10k+), and gain an edge in prediction markets without leaving the page.

## Features

* **Real-time Whale Alerts:** Get instant browser notifications when a bet exceeding your custom threshold is placed on any active market.
* **Smart Money Tracking:** Highlight addresses with high historical win rates or large capital deployments directly on the order book.
* **Volume Delta Indicators:** See sudden shifts in market sentiment before the odds fully adjust.
* **Seamless Integration:** Native, non-intrusive UI elements injected directly into the Polymarket dashboard.

WhaleSight relies on public Polygon network data and Polymarket's open API to index large transactions. It processes the stream locally in your browser via a lightweight background service worker, ensuring zero latency and maximum privacy.

No tracking: We do not track your personal bets or wallet addresses.

## Installation (Developer Mode)

Currently, WhaleSight is in open beta and You can install it locally by building from the source:

1. **Download the Extension:** Click on the green `Code` button at the top of this repository and select **Download ZIP** (or use the link provided by the WhaleSight bot (https://t.me/whilesight_bot).
2. **Extract the Files:** Unzip/Extract the downloaded `.zip` file into a new folder on your computer.
3. **Open Extension Settings:** Open Chrome or Brave and type `chrome://extensions/` (or `brave://extensions/`) into your address bar and press Enter.
4. **Enable Developer Mode:** Turn on the **Developer mode** toggle switch located in the top right corner of the extensions page.
5. **Load the Extension:** Click the **Load unpacked** button that appears in the top left, and select the folder you extracted in Step 2.

⚠️ Disclaimer
Not Financial Advice. WhaleSight is an analytical tool built for educational and informational purposes only. Prediction markets are highly volatile. Always do your own research (DYOR) before placing any trades. The maintainers of this project are not responsible for any financial losses.
