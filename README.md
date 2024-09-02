# Apple Support AI Bot

## Author
Created by @Sam (techcodes27)

GitHub: [https://github.com/TermuxHackz](https://github.com/TermuxHackz)

## Description
The Apple Support AI Bot is a sophisticated Discord bot designed to provide high-quality, automated support for Apple products and services within Discord servers. It serves as an efficient first line of support for Apple-related queries in Discord communities, potentially reducing the workload on human moderators while providing quick and accurate assistance to users.

## Features

### 1. Apple Support Q&A
- Users can ask questions about Apple products and services in designated forum channels.
- The bot uses advanced AI models to generate helpful and accurate responses.
- Daily question limits are enforced to prevent abuse.

### 2. Multi-Language Support
- The bot can translate responses to various languages set for individual users.

### 3. Configurable Forums
- Admins can configure up to two forum channels for Apple support.
- The bot will only respond to questions in these designated forums.

### 4. User Management
- Ban/unban users from using the bot.
- Set language preferences for individual users.

### 5. Question Limits
- Default free limit of 5 questions per user per day.
- Upgradable limit for premium servers.

### 6. Server Upgrades
- Paid upgrades to increase question limits and access premium features.
- Stripe integration for secure payments.

### 7. Multiple AI Models
- Access to various AI models including Claude, LLaMA, and Gemini.
- Model selection available for upgraded servers.

### 8. Feedback System
- Users can submit suggestions and feedback to the bot owner.
- Limited to 2 suggestions per user per day per server.

### 9. Admin Commands
- Reset all user question limits.
- Set maximum questions for the server.
- View banned users.

### 10. Monitoring
- Uptime tracking and status checking.

## Commands

### General Commands
- `/apple_support [question]`: Ask a question about Apple products or services.
- `/about`: Get information about the bot.
- `/ping`: Check if the bot is running.
- `/uptime`: See how long the bot has been online.
- `/check_limit`: Check your remaining questions and server limit.
- `/suggestion [suggestion]`: Send feedback to the bot owner.

### Admin Commands
- `/configure_forum forum1:[ForumChannel] [forum2:[ForumChannel]]`: Set up to two forum channels for Apple support.
- `/remove_forum [forum]`: Remove a configured forum channel.
- `/getconfigforum`: View currently configured forum channels.
- `/setgeneralchannel [channel]`: Set the general channel for bot announcements.
- `/setmaxquestions [max_questions]`: Set the maximum number of questions per user (1-6 for free servers).
- `/reset_all_limits`: Reset all user question limits to 0.
- `/setlanguage [user] [language]`: Set the language for a specific user.
- `/ban [user] [duration]`: Ban a user from using the bot.
- `/unban [user]`: Unban a user.
- `/viewbans`: View all currently banned users.

### Premium Commands (Upgraded Servers Only)
- `/choose_model`: Select the AI model for the bot to use.
- `/upgrade_limit [new_limit]`: Upgrade the server's question limit (10-20).

## Required Roles
- Most admin commands require one of the following roles: Senior Mod, Manager, Admin, or Server Owner.(case sensitive)
- The `/apple_support` command is restricted to users with Senior Mod or higher roles.
- **PLEASE MAKE SURE THE TEAM MANAGING YOUR SERVER HAS THESE ROLES< IF YOU DONT< KINDLY CREATE THEM AND ALSO A GENIUS BAR SPECIALIST ROLE AND GENIUS BAR MASTER ROLE THAT WOULD ASSIT HUMANLY.**

## Upgrade System
- Servers can upgrade to increase their question limit and access premium features.
- The upgrade costs $30.00 (due to maintenance) and provides:
  1. Increased question limit (10-20 questions per user per day).
  2. Ability to change AI models.
  3. Unlimited use of the reset_all_limits command.
- Payment is processed securely through Stripe.

## AI Models
- Default model: Claude 3 Sonnet (FREE)
- Premium models (available after upgrade):
  - Claude 3 Opus
  - LLaMA 3 Sonar Large
  - Google's Gemini

## Installation and Setup
1. Invite the bot to your server using the provided OAuth2 link.
2. Use `/configure_forum` to set up the support forums.
3. Use `/setgeneralchannel` to set the announcement channel.
4. Optionally, upgrade your server using `/upgrade_limit` for premium features.

## Note
This bot is designed to assist with Apple-related queries but should not be considered an official Apple support channel. For official support, please visit [Apple Support](https://support.apple.com).
