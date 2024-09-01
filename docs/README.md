# Apple Support AI Bot

## Introduction

The Apple Support AI Bot is a sophisticated Discord bot designed to provide high-quality, automated support for Apple products and services within Discord servers. It serves as an efficient first line of support for Apple-related queries in Discord communities, potentially reducing the workload on human moderators while providing quick and accurate assistance to users.

## Features

- AI-powered responses to Apple-related questions
- Support for multiple languages
- Configurable question limits per user
- Integration with up to two forum channels per server
- Role-based access control for administrative commands
- Suggestion system for user feedback
- Ban/unban system for user management
- Customizable maximum question limit

## Setup

1. Invite the bot to your Discord server using the provided invite link.
2. Ensure the bot has the necessary permissions (Managing Channels, Viewing Channels, Send Messages, Read Message History, etc.).
3. Create the required roles in your server: Senior Mod, Manager, Admin, Server Owner.
4. Use the `/configure_forum` command to set up the support forum(s).

## Required Roles

The bot uses a role-based permission system. The following roles are recognized:

- Senior Mod
- Manager
- Admin
- Server Owner

Users with these roles will have access to administrative commands.

## Configuration

### Setting Up Forums

Use the `/configure_forum` command to set up one or two forum channels for the bot to operate in:

```
/configure_forum forum1:<ForumChannel> [forum2:<ForumChannel>]
```

### Setting the General Channel

Set a general channel for bot announcements (Server Owner only):

```
/setgeneralchannel channel:<TextChannel>
```

### Setting Maximum Questions

Set the maximum number of questions a user can ask in 24 hours (0-6, default is 5):

```
/setmaxquestions max_questions:<int>
```

## Usage

Users can ask Apple-related questions in the configured forum channels. The bot will respond with AI-generated answers based on its trained knowledge of Apple products and services.

### User Commands

- `/about`: Get information about the bot
- `/ping`: Check if the bot is online
- `/suggestion`: Submit a suggestion or feedback (limit 2 per day)

### Administrative Commands

- `/apple_support`: Manually ask a question (Senior Mods and above)
- `/ban`: Ban a user from using the bot
- `/unban`: Unban a user
- `/viewbans`: View currently banned users
- `/setlanguage`: Set a user's preferred language
- `/getconfigforum`: View configured forums
- `/remove_forum`: Remove a configured forum
- `/setmaxquestions`: Set the maximum questions per user
- `/viewsuggestions`: View user suggestions (Bot Owner only)
- `/reset_all_limits:`: Reset all user question limits to 0 (Senior Mods and above only)

## Language Support

The bot supports multiple languages. Use the `/setlanguage` command to set a user's preferred language:

```
/setlanguage user:<User> language:<LanguageCode>
```

Replace `<LanguageCode>` with the appropriate ISO language code (e.g., 'fr' for French, 'es' for Spanish).

## Limitations

- The bot has a configurable limit on the number of questions a user can ask within 24 hours.
- Some commands are restricted to users with specific roles.
- The bot can only be configured for a maximum of two forum channels per server.

## Support

If you encounter any issues or have questions about the bot, please contact the bot owner or use the `/suggestion` command to provide feedback.

## Contributing

We welcome suggestions for improvements! Use the `/suggestion` command in Discord to submit your ideas.


## Creator

Made by Sam (techcodes27) for [The Apple Den](https://discord.gg/appleden)


## License

GNU GENERAL PUBLIC LICENSE

---

Thank you for using the Apple Support AI Bot! We hope it enhances your Discord community's support experience.
