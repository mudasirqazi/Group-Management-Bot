# Group Management Bot

## Purpose
Subscription-based Telegram bot for premium group access management with payment processing and multi-language support.

## Operational Flow
```
Start Command → Language Selection → Main Menu → Subscription/Payment → Group Access
```

1. User starts bot and selects language (English/French)
2. User chooses subscription plan and processes payment
3. Bot generates temporary group invite link
4. Automatic subscription tracking and user removal on expiration
5. Payment renewal process for continued access

## Project Structure
```
Group_management_bot/
├── Database/                    # SQLAlchemy models and operations
├── Handlers/CallBacks/          # Bot command and callback handlers
├── Keyboards/                   # Inline keyboard layouts
├── Languages/                   # Multi-language support
├── Messages/                    # Localized message templates
├── MiddleWares/                 # Router configuration
├── SupportUtils/                # Bot initialization and utilities
├── main.py                      # Application entry point
└── Groupmangment.db            # SQLite database
```

## Programming Language
**Python 3.x**

## Tools and Technologies
- **aiogram 3.x** - Telegram Bot API framework
- **SQLAlchemy** - Database ORM
- **SQLite** - Database
- **python-dotenv** - Environment configuration
- **asyncio** - Asynchronous programming
