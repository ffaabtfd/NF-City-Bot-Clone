Here's a `README.md` file with all the essential details about your bot script and some emojis to make it more engaging:

---

# 📲 NF-City-Bot-Clone 🤖

Welcome to **NF-City-Bot-Clone**! This Telegram bot provides premium accounts through a referral and point-based system. Users can earn points through referrals and exchange them for premium accounts, such as *Chorki* and *Hoichoi*, right on Telegram!

### 🌐 Repo Link
[GitHub Repository](https://github.com/abirxdhackz/NF-City-Bot-Clone)

---

## ⚙️ Features

- **User Registration**: New users are welcomed and can register with optional referral.
- **Referral System**: Users earn points by inviting others to join the bot.
- **Points and Balance Check**: Users can check their balance at any time.
- **Order System**: Users can redeem points for premium accounts like *Chorki* and *Hoichoi*.
- **Account Provisioning**: Users receive account credentials upon successful redemption.
- **Admin Reply Notifications**: Users are notified if an admin replies to their order.
- **Channel Membership Verification**: Ensures users join required channels.
- **User Review Submission**: Users can submit reviews of their experience.

---

## 🔐 Requirements

- Python 3.6+
- Libraries: `pyTelegramBotAPI`, `logging`, `random`, `string`, `time`

## 🛠 Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/abirxdhackz/NF-City-Bot-Clone.git
    cd NF-City-Bot-Clone
    ```
   
2. **Install Dependencies**:
    ```bash
    pip install pyTelegramBotAPI
    ```

3. **Configure Bot Token**:
    Update `BOT_TOKEN` with your bot token in the script:
    ```python
    BOT_TOKEN = 'YOUR_BOT_TOKEN_HERE'
    ```

4. **Run the Bot**:
    ```bash
    python bot_script.py
    ```

---

## 📚 Bot Commands & Options

- **/start** - Register and check channel membership.
- **💰 Balance** - View user’s current point balance.
- **👥 Referral** - Get referral link to earn points.
- **💲 Withdraw** - Redeem points for premium account access.
- **📂 PROOFS** - Access proof of successful transactions.
- **📞 Support** - Contact support for issues.
- **👥 Submit Review** - Submit a review with screenshots.

---

## 🔄 How It Works

1. **Referral System**: Share your referral link and earn points when others join via your link.
2. **Point Redemption**: Choose a service (like *Chorki Crack*) and confirm. Points will be deducted based on service cost.
3. **Account Delivery**: The bot sends account details upon successful redemption.
4. **Review System**: Share your experience, and optionally upload a screenshot for others to see.

---

## 🤖 Code Summary

- **User Data Management**: Track user balances, referrals, and activity.
- **Order Tracking**: Log order ID, service, and user details.
- **Account Provisioning**: Send random account credentials for selected services.
- **Channel Check**: Ensure users join required channels before accessing premium services.

---

## 🛡️ License
This project is for educational purposes only and intended to demonstrate Telegram bot capabilities.

---

Enjoy using the **NF-City-Bot-Clone**!