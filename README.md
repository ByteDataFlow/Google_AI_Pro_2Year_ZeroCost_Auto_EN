========================================================================  
  Google AI Pro (5 TB) Zero Cost 2 Years (US$0.00 -> 24 Months) Automation Console  
========================================================================  

> **Disclaimer:** I did not develop this project; it is provided as an open-source resource for the community to analyze and learn from.

---

### [1. Environment & System Requirements]
1. **Operating System:** Windows 10 / 11 (or macOS / Linux via terminal)
2. **Browser:** Google Chrome installed (default path)
3. **Python:** Python 3.10 or higher installed (make sure "Add Python to PATH" is checked)
4. **Network:** US proxy enabled locally, or configure proxy settings in the web console's left panel

---

### [2. Quick Start]
1. **First-time setup:** Double-click `1_首次运行_安装依赖并启动.bat` (or run `pip install -r requirements.txt && python app.py`)
2. **Subsequent runs:** Double-click `2_启动控制台.bat` (or run `python app.py`)
3. The browser will automatically open the web console: [http://127.0.0.1:8765](http://127.0.0.1:8765)

---

### [3. Payment Card Configuration & Account Execution]

#### 1. Fill in Payment Card (Required):
- In the left panel under **Global Configuration & Inline Tax-Free Card Binding**, enter your Visa or Mastercard:
  - **Card Number** (16 digits)
  - **Expiration Date** (MM / YY, e.g., `08 / 29`)
  - **Security Code** (3-digit CVC)
  - **Cardholder Name** (English)
  - **Tax-Free Zip Code:** Default is set to `97201` (Oregon, US tax-free state; no changes needed)
- Click **💾 Save Configuration**.
- *Note:* The script features built-in strict $0 charge verification protection; it only clicks subscribe when the checkout modal confirms **US$0.00**.

#### 2. Batch Import Google Accounts:
- In the right panel under **Batch Import Area**, paste your accounts (one per line). Supported formats:
  - `email----password----recovery_email`
  - `email----password----recovery_email----2fa_secret`
  - `email----password----2fa_secret`
- Click **➕ Import Account List**.

#### 3. Start Automated Execution:
- Click **▶ Run** on an individual account or **▶ Run All (Batch)** at the top.
- The automation engine will perform:
  - **Step 1:** Automatically sign in to Google with recovery email / 2FA verification.
  - **Step 2:** Inline tax-free card binding + Tier 1 12-month free package (US$0.00).
  - **Step 3:** Stack Tier 2 6-month free package (US$0.00 -> 18 months).
  - **Step 4:** Stack Tier 3 6-month free package (US$0.00 -> 24 months cap).
  - **Step 5:** Automatically go to Google Play to cancel auto-renewal, lock in 2-year perks, and capture verification screenshots.

---

### Links & Community
- **Store:** https://faka.cdkey.si
- **Blog:** https://blog.caowo.de
- **Telegram Group:** @Hello_Florence
