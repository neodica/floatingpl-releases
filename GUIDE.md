# FloatingPL — User Guide

**FloatingPL** is an always-on-top floating widget for MetaTrader 5 that shows the
running profit/loss (floating P/L) of all your positions at once, prices, equity,
and can manage positions automatically.

> **Activation / buy a code:** ndr_dc@yahoo.com
> **Support:** neo_dica@yahoo.co.id

---

## 1. Activation (once per PC)

1. Run **FloatingPL.exe**.
2. On the activation screen, enter the **license key** you received → click **Activate**.
3. Once activated, the widget opens. You won't need to activate again on the same PC.

**Important:**
- **1 key = 1 PC.** A key already used on one PC cannot be used on another.
- On **one PC**, a single key can run **multiple widgets** (for several MT5 accounts) at once.
- No key yet? The app gives a **1-day free trial** automatically on first run.

---

## 2. Connecting to MetaTrader 5

1. Make sure **MetaTrader 5 is open and logged in** to your account.
2. Enable **AutoTrading** in MT5 (toolbar button, or press **Ctrl+E**) — required so the automatic features can place orders.
3. If asked, choose the **terminal64.exe** file of the MT5 folder you want to monitor.

If the widget shows "⚠ MT5 not connected", open/log in to MT5 and wait a few seconds.

---

## 3. Reading the Display

- **Big number** = floating P/L (total running profit/loss). Green = profit, red = loss.
- **Price line** = main symbol + current price (e.g. XAUUSD).
- **Rotating line** (changes every ~4s): Equity ↔ Margin, and positions ↔ Balance.
- **Info line** (rotating): RSI/Trend/Session + candle countdown → today's P/L → connection status.
- **1h** = P/L of the last hour. **Today** = P/L, number of trades, and win % for today.

---

## 4. Buttons & Menu

- **Move the widget:** hold left-click and drag.
- **AUTO** (title): master switch for all automatic features (all ON/OFF at once).
- **Algo ON/OFF:** MT5 AutoTrading status (Ctrl+E).
- **+ / − :** enlarge / shrink / collapse the panel.
- **× :** close the widget.
- **Right-click** opens the menu: change pair, SL+ now, **Check update**, **About / Version**, etc.

---

## 5. Automatic Features

| Feature | What it does |
|---|---|
| **Auto Entry** | Opens a recovery entry when floating is negative (max 1 active, with a cooldown). |
| **Auto Correction** | Counter-trend scalping (max 3), exits via Auto SL+. |
| **Auto SL+** | Trailing: locks in profit on positions already in the green. |
| **Auto CutLoss** | Closes all positions once the loss reaches the set percentage. |
| **Break-even Rescue** | When you already have 2+ losing positions and price reverses, it automatically closes everything at break-even (0) — no Stop Loss needed. |

All features only run while **MT5 AutoTrading is ON**.

---

## 6. Changing the Pair

Right-click → choose a pair (e.g. XAUUSD, EURUSD, BTCUSD) → confirm.
Lot size adjusts automatically to the selected pair.

---

## 7. Multiple Accounts / Several MT5 on One PC

- One PC can run **several widgets** (one per MT5 terminal) using the same key.
- **Do not start several widgets at the same time** — leave a **~10 second gap** between them, so each widget can connect to its own MT5 (starting together can make one fail to connect).
- A **staggered launcher** (.vbs file) is recommended to do this automatically.

---

## 8. Updating the App

Right-click → **Check update**. If a new version exists, the app downloads it and restarts itself.
Updates never happen automatically without your approval.

---

## 9. License Security

- Keep your key safe; **1 key is for 1 PC only**.
- Do not share your key — a key already active on another PC will be rejected.

---

## 10. Contact

- **Activation / buy a code:** ndr_dc@yahoo.com
- **Support (issues/questions):** neo_dica@yahoo.co.id
