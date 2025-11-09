# ZygnalBot-Auction-System
The ZygnalBot Auction System is a Discord bot extension designed to manage and automate auction listings, particularly for trading cards like Sorare. It creates a seamless and organized auction environment within designated Discord channels.
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# ZygnalBot Auction System

The ZygnalBot Auction System is a Discord bot extension designed to manage and automate auction listings, particularly for trading cards like Sorare. It creates a seamless and organized auction environment within designated Discord channels.

## Features

- **Automated Auction Threads:** When a new auction post is made in a monitored channel, the bot automatically creates a public thread for it.
- **Time-based Deletion:** Each auction post and its replies are set with an automatic 10-day deletion timer, ensuring the channels stay clean and up-to-date.
- **Persistent Cleanup:** The system continues to monitor and delete expired auctions and replies even if the bot is restarted.
- **Flexible Configuration:** Administrators can easily add or remove auction channels and configure system settings such as whether to delete entire threads or just the main auction post.
- **User-Friendly Interface:** The bot offers a simple control panel with buttons for managing all settings, eliminating the need for complex commands.
- **Organized Replies:** Replies to an auction post are stored within a dedicated thread, keeping the main channel clutter-free.

## Commands

- `/zauction`  
  Opens the main control panel for the Auction System. Provides a user-friendly interface with buttons to manage all features.

- `!zauction`  
  (Prefix command) Also opens the control panel, offering the same functionality as the slash command.

## How It Works

1. An administrator uses the `/zauction` command to open the control panel.
2. They click "Add Channel" and provide the ID or mention of a channel where auctions will be posted.
3. Any new message posted in this channel will be recognized as an auction.
4. The bot then creates a new public thread for that message.
5. A confirmation message and a "Place Your Bids Here!" anchor message are automatically sent to the thread.
6. All replies within the thread are automatically given a 10-day timer for deletion.
7. The main auction post and its associated thread are also automatically deleted after 10 days.


**Made By TheHolyOneZ**
