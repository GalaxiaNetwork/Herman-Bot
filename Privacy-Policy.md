*Effective: April 1, 2022*

*Last updated: August 25, 2024*
### Privacy Policy

By using this bot you agree that you have read and agree to this policy.

This is our "Privacy Policy" which outlines the use of the data and information which you provide to us. The terms "we", "us" and "our" refer to Galaxia Studios and "bot" refers to the Discord bot itself.

This policy may be updated at any time. Changes in this policy will be effective immediately, and we will notify our users before any major policy changes. Please note notification of any change, and the method we use for disclosure is at our sole discretion.

### Privacy Statement

We respect the privacy of your information. We provide this explanation about our information practices as a show of our commitment to protect your privacy. This policy describes the types of information we may collect from you or that you may provide when you use the bot and our practices for collecting, using, maintaining, protecting and disclosing that information.

### What information do we collect?

Certain information we collect is classified as "permanent data", meaning it is stored in a MySQL database permanently and is not erased unless you contact us. This data is necessary for the function of the bot. Once erased, no feature of the bot will be usable and in order to regain functionality, the bot must be removed from the guild and added back to restore __default data__. Please note that data recovery is **impossible** once it is erased from our permanent database.

Listed below are the different types of information we collect and permanently store:

- Your guild ID, which is provided to us upon the bot being added to your server.
- Your guild name, which is provided to us upon the bot being added to your server.
- The user ID of the owner of your guild, which is provided upon the bot being added to your server.
- The username of the owner of your guild, which is provided upon the bot being added to your server.
- Settings for your guild, such as: "welcome" messages, "goodbye" messages, configured channels for specific modules, whether or not a command is enabled for use in your guild, configured autoroles for your guild, whether or not a specific module is enabled in your guild, leveling/chatlevels-related settings, your guild's assigned theme, protected mode status, tips enabled status, a custom description for your guild.
- Your guild's Club Herman status, start/end date, ID of the user who activated the membership, the activation code that was used, billing source, membership activity logs (for customer support), and tier.
- All Club Herman data associated with your user ID (membership status, tier, number of guilds activated, max possible number of guilds activated, total months subscribed, current membership streak, highest membership streak, billing source, membership activity logs (for customer support), start/end date).
- All leveling/chatlevels data associated with your user ID in a specific guild (level, xp earned, xp needed to level up, total xp earned).

Other information we collect is classified as "temporary" or "cached" data, meaning it is stored in a Redis database and then deleted after **30 days**. You may still ask for this data to be erased by contacting us. This data is not necessary for the function of the bot, and certain data is permanently erased upon rebooting certain services, such as the music queue, its playing state, its assigned channel, all audio sync/frame data, etc.

Listed below are the different types of information we collect and delete after 30 days:

- Your guild's music queue
- Your guild's music playing state
- Your guild's assigned music channel
- All other data associated with the music system (sync/frame data, track metadata, track names, track authors, track duration, track queue position)
- All data associated with leveling/chatlevels leaderboards (level data for users in your guild sorted from highest to lowest)

### How do we use this information?

- User IDs and usernames are stored for identification purposes, and are solely used to associate a Discord user entity with a guild they have created, any leveling/chatlevels data associated with the user, or a subscription they have activated.
- Guild IDs and names are used to associate settings configurations and module data with a guild. All general settings/module data and music data is linked to the guild ID.
- We **DO NOT** sell or disclose any information to third parties.

### Where do we store this information?

All data is stored on a dedicated server which is monitored throughout the day. Authentication to the server is handled through SSH keys. Only the bot, the bot owner, and managers have access to this server.

Any direct modification to the database is performed by the bot itself. When data deletion is requested, a bot command is used to do so. All database access and querying activity is logged, and these logs are only available to the bot owner.

- "Permanent" data (seen above) is stored in a secured MySQL database.
- "Temporary/cached" data (seen above) is stored in a secured Redis database.

### Data Deletion/Revelation Policy

- Users can request to view all data associated with their guild ID, user ID, or username(*) by contacting us on our support server: https://dsc.gg/hermandcs/.

(*) *User IDs associated with a guild are treated as guild data. User IDs associated with leveling/chatlevels are not treated as regular guild data so they require a separate process to be deleted (meaning a separate command).*

- Certain data, such as the blacklist state of your guild and your membership history, may be deleted with the discretion of a manager.
- You may request for your data to be deleted by contacting us on our support server: https://dsc.gg/hermandcs/.
