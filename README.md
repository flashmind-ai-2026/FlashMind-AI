FlashMind AI 🧠⚡
Experimental Cross‑DEX Arbitrage Scanner — Real‑Time Opportunities, Open‑Source

FlashMind AI is a research‑focused engine that scans decentralised exchanges for price discrepancies and prints potential arbitrage opportunities directly to your terminal. No registration, no API keys, no hidden costs. Just download, launch, and let the scanner do the heavy lifting.

🚀 How to start
macOS
Download the latest DMG from the Releases page.
Open the DMG file and drag the FlashMind AI.app to your Desktop.
On your Desktop, Control‑click (or right‑click) the app icon → Open.
If you see a warning about an unidentified developer, click "Open" again.
(First time only) If macOS asks to install Rosetta, click Install, wait for completion, then re‑open the app with Control‑click → Open.
The terminal will launch. Simply press Enter to confirm — FlashMind AI will immediately start scanning and printing arbitrage opportunities.
To stop, press Enter again in the terminal window.
⚠️ Do NOT run the app directly from the DMG! Always copy it to your Desktop or Applications folder first.

Windows
Download the FlashMind_AI_Windows.zip from the Releases page.
Extract the ZIP to any folder (e.g., your Desktop).
Double‑click FlashMind_AI.exe to launch.
If Windows Defender SmartScreen shows a warning, click "More info" → "Run anyway".
Once the terminal window opens, press Enter to start scanning.
To exit, press Enter again in the terminal.
📊 Core Capabilities
Multi‑DEX scanning – monitors Uniswap v4, PancakeSwap, Orca, Raydium, Meteora, SushiSwap, and more.
Real‑time output – prints price deltas, possible triangular / 2‑hop arb paths, and estimated profit.
Lightweight – pure local execution; no external API keys required.
Research‑grade pathfinder – Bellman‑Ford algorithm for up to 3‑hop detection.
Open‑source – full Python and C++ source available; build and run anywhere.
📦 System Requirements
macOS: 11 (Big Sur) or later, Apple Silicon (M1/M2) or Intel with Rosetta 2.
Windows: 10/11 64‑bit (Visual C++ Redistributable 2015‑2022 recommended).
Linux: build from source (instructions in repo).
Approx. 10 MB of disk space.
⚠️ Known Issues (v1.0)
Windows blank console: Install VC++ Redist 2015‑2022; use PowerShell if CMD shows nothing.
macOS empty terminal after Gatekeeper bypass: Press Enter a few times; if stuck, run sudo xattr -cr /path/to/FlashMind AI.app in Terminal.
False positives: Some arb opportunities may fail due to slippage or low liquidity — this is a prototype.
M1/M2 occasional freeze: Restart and press Enter again.
Unsigned binaries: Expect security warnings; building from source avoids them.
⚖️ Disclaimer
This software is for educational and research purposes only. It does not constitute financial advice. Trading cryptocurrencies involves substantial risk. The authors are not responsible for any financial loss or decisions made while using this tool.

Keep it safe. Keep it curious.
