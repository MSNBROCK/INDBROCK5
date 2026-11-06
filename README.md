# Northstar Capital & Banking Management System

A multi-client banking, share market, and institutional portfolio management web application built for instant hosting on **GitHub Pages**.

---

## 🌟 Key Features

1. **🔐 Multi-Role Authentication & 14 Client Sandbox:**
   - 14 distinct pre-populated client profiles (`client1` through `client14`, password: `pass123`).
   - 1 Master Super Admin Console (`admin`, password: `admin123`).
   - 1-Click quick sandbox switcher buttons on the login card.

2. **📊 Comprehensive Client Dashboard:**
   - Real-time Total Balance, Active Investments, Pending Withdrawals, and Net Profit/Loss calculations.
   - Interactive Chart.js portfolio yield and performance curve.
   - Live asset allocation breakdown and recent account movements.

3. **📝 Simulated Regulatory KYC & UTR Withdrawal Portal:**
   - Form capturing Bank Name, Account Number, IFSC, PAN, and Masked Aadhaar.
   - Immediate escrow lien assignment and UTR number generation.

4. **📅 30-Day Withdrawal Milestone Progress Tracker:**
   - Visual progress bar tracking Day 1 KYC verification, Day 10 Audit Clearance, Day 20 Escrow Liquidation, to Day 30 Final Bank Settlement.
   - Interactive `-5 Days` and `+5 Days` buttons to simulate progress across the 30-day clearing window in real-time.

5. **📄 Certified Bank Statements:**
   - Institutional header with Account Number and date.
   - Filter by All, Credits Only (+), or Debits Only (-).
   - One-click Print layout (`Ctrl+P` / `Cmd+P` ready) and instant CSV Export.

6. **📈 Reliance Jio IPO Participation Desk:**
   - Real-time Grey Market Premium (GMP) indicator (+₹135 / +41.5%).
   - Dynamic lot size calculator (45 shares/lot at ₹325 cut-off).
   - Direct ASBA UPI mandate simulation with automated portfolio balance blocking.

7. **👨‍💻 Super Admin Command Center:**
   - Real-time aggregate AUM, total invested capital, total processing payouts, and system P&L.
   - Searchable directory of all 14 clients.
   - Admin Override Modal to adjust any client's cash balance, investments, and net profit.
   - One-click approval action to clear pending payout queues.

8. **📱 Responsive UI & Zero Backend Setup:**
   - Dark fintech aesthetic built with Tailwind CSS.
   - Saves all state and transaction data automatically using browser `localStorage`.

---

## 🚀 How to Host on GitHub Pages (Step-by-Step)

1. **Create a GitHub Repository:**
   - Go to [github.com/new](https://github.com/new).
   - Name your repository (e.g., `northstar-bank` or `capital-system`).
   - Set the repository visibility to **Public**.
   - Click **Create repository**.

2. **Upload the Files:**
   - Click **Add file** > **Upload files**.
   - Drag and drop `index.html` and `README.md` into the upload zone.
   - Commit the files to the `main` branch.

3. **Enable GitHub Pages:**
   - In your repository, click the **Settings** tab.
   - On the left sidebar, click **Pages** (under "Code and automation").
   - Under **Build and deployment > Branch**, select `main` from the dropdown and leave the folder as `/(root)`.
   - Click **Save**.

4. **Access Your Live Website:**
   - In 1 to 2 minutes, refresh the Pages settings tab.
   - Your live link will appear at:  
     `https://<your-github-username>.github.io/<repository-name>/`

---

## 🔑 Demo Account Credentials

| Account Role | Username | Password | Notes |
| :--- | :--- | :--- | :--- |
| **Super Admin** | `admin` | `admin123` | Full access to all 14 clients, balance overrides, payout approvals |
| **Client 1** | `client1` | `pass123` | Aarav Sharma (Active with pending withdrawal & chart) |
| **Client 2** | `client2` | `pass123` | Diya Patel |
| **Client 3** | `client3` | `pass123` | Rohan Verma |
| **Client 4** | `client4` | `pass123` | Ananya Iyer |
| **Client 5** | `client5` | `pass123` | Kabir Mehta |
| **Client 6** | `client6` | `pass123` | Ishaan Gupta |
| **Client 7** | `client7` | `pass123` | Vikram Malhotra |
| **Client 8** | `client8` | `pass123` | Neha Rao |
| **Client 9** | `client9` | `pass123` | Arjun Sen |
| **Client 10** | `client10` | `pass123` | Pooja Reddy |
| **Client 11** | `client11` | `pass123` | Kunal Singhania |
| **Client 12** | `client12` | `pass123` | Meera Chawla |
| **Client 13** | `client13` | `pass123` | Siddharth Roy |
| **Client 14** | `client14` | `pass123` | Zoya Khan |
