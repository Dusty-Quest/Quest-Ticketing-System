# Quest-Ticketing-System
 That ticket system built for you!

# Config.json Explaination!
Here's an explanation of each of the properties in the config.json file:

prefix: This is the prefix for your bot's commands. For example, if your prefix is set to !, then your bot's commands would be triggered by messages that start with !.

token: This is the Discord bot token that you'll get from the Discord Developer Portal when you create your bot application. It's important to keep this token secret, so make sure you don't share it with anyone else.

ticketCategory: This is the ID of the category that your tickets will be created under. You can find this ID by right-clicking on the category in Discord and selecting "Copy ID".

ticketChannel: This is the ID of the channel that your tickets will be sent to. You can find this ID by right-clicking on the channel in Discord and selecting "Copy ID".

staffRole: This is the ID of the role that is required to manage tickets. Only users with this role will be able to use the commands to manage tickets.

allowedRoles: This is an array of role IDs that are allowed to create tickets. If a user does not have one of these roles, they will not be able to create a ticket.

color: This is the color that will be used for the embeds that are sent when a ticket is created or updated. It should be a valid hex color code.

ticketSystemName: This is the name of your ticket system that will appear in the embeds.

ticketMessage: This is the message that will appear in the embed when a ticket is created.

ticketPromptMessage: This is the message that will appear in the embed when a user creates a ticket but does not provide a name for it.

renameCommandName: This is the name of the command that is used to rename a ticket.

renameCommandDescription: This is the description of the command that is used to rename a ticket.

renameCommandUsage: This is the usage of the command that is used to rename a ticket.

addCommandName: This is the name of the command that is used to add a user to a ticket.

addCommandDescription: This is the description of the command that is used to add a user to a ticket.


addCommandUsage: This is the usage of the command that is used to add a user to a ticket.

closeCommandName: This is the name of the command that is used to close a ticket.

closeCommandDescription: This is the description of the command that is used to close a ticket.

closeCommandUsage: This is the usage of the command that is used to close a ticket.

alertCommandName: This is the name of the command that is used to alert staff members about a ticket.

alertCommandDescription: This is the description of the command that is used to alert staff members about a ticket.

alertCommandUsage: This is the usage of the command that is used to alert staff members about a ticket.

closeRequestCommandName: This is the name of the command that is used to request that a ticket be closed.

closeRequestCommandDescription: This is the description of the command that is used to request that a ticket be closed.

closeRequestCommandUsage: This is the usage of the command that is used to request that a ticket be closed.

I hope that helps! Let me know if you have any other questions.
