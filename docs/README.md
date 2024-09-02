# Apple Support AI Bot

## Author
Created by @Sam (techcodes27)

GitHub: [https://github.com/TermuxHackz](https://github.com/TermuxHackz)

## Description
The Apple Support AI Bot is a sophisticated Discord bot designed to provide high-quality, automated support for Apple products and services within Discord servers. It serves as an efficient first line of support for Apple-related queries in Discord communities, potentially reducing the workload on human moderators while providing quick and accurate assistance to users.

## Features

### 1. AI-Powered Support
- Responds to Apple-related questions in designated forum channels.
- Uses advanced AI models to generate helpful and accurate responses.
- Supports multiple AI models: Claude, LLaMA, and Gemini.
- Maintains conversation context for follow-up questions.

### 2. Multi-Language Support
- Can translate responses to various languages set for individual users.

### 3. Configurable Forums
- Admins can configure up to two forum channels for Apple support.
- The bot will only respond to questions in these designated forums.

### 4. User Management
- Ban/unban users from using the bot.
- Set language preferences for individual users.

### 5. Question Limits
- Default free limit of 5 questions per user per day.
- Upgradable limit for premium servers (10-20 questions per day).

### 6. Server Upgrades
- Paid upgrades to increase question limits and access premium features.
- Stripe integration for secure payments.

### 7. Model Selection
- Premium servers can choose between different AI models for responses.

### 8. Feedback System
- Users can submit suggestions and feedback to the bot owner.
- Limited to 2 suggestions per user per day per server.

### 9. Admin Commands
- Reset all user question limits.
- Set maximum questions for the server.
- View banned users.

### 10. Monitoring
- Uptime tracking and status checking.

### 11. Human Escalation
- Option to escalate queries to human specialists when needed.

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

## Required Roles and Setup

### Important: Necessary Roles
The bot requires specific roles to be set up in your Discord server for proper functionality:

1. **Administrative Roles**: 
   - Senior Mod
   - Manager
   - Admin
   - Server Owner
   
   These roles are required for using administrative commands and managing the bot's configuration.

2. **Support Roles**:
   - Genius Bar Specialist
   - Genius Bar Master
   
   These roles are crucial for the human escalation feature. When the bot cannot resolve an issue, it will mention these roles to request human assistance.

### Setting Up Roles
1. Create these roles in your Discord server if they don't already exist.
2. Assign the appropriate roles to your moderation team and support staff.
3. Ensure that people with the "Genius Bar Specialist" and "Genius Bar Master" roles are available to assist when the bot escalates issues.

### Role Permissions
- Administrative roles should have permissions to manage channels, roles, and server settings.
- Support roles don't need special permissions, but users with these roles should be knowledgeable about Apple products and services.

## Installation and Setup
1. Invite the bot to your server using the provided [OAuth2 link](https://discord.com/oauth2/authorize?client_id=1279505556347949147).
2. Use `/configure_forum` to set up the support forums.
3. Use `/setgeneralchannel` to set the announcement channel.
4. Create and assign the necessary roles as described above.
5. Optionally, upgrade your server using `/upgrade_limit` for premium features.

## Upgrade System
- Servers can upgrade to increase their question limit and access premium features.
- The upgrade costs $30.00 and provides:
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

## Note
This bot is designed to assist with Apple-related queries but should not be considered an official Apple support channel. For official support, please visit [Apple Support](https://support.apple.com).
