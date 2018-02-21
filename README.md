**ChatCleaner** clears/resets a player's chat when joining the server and on command.

## Permissions
- `chatcleaner.use` -- allows player to clean their own chat

## Command
- **cleanchat** -- Clears/resets the chat of all previous messages.

## Configuration
You can configure the settings in the ChatCleaner.json file under the oxide/config directory.
```json
{
  "Clean chat on connect (true/false)": true,
  "Show chat cleaned message (true/false)": true,
  "Show welcome message (true/false)": true
}
```

## Localization
The default messages are in the ChatCleaner.json under the oxide/lang directory. To add support for another language, create a new language folder (ex. de for German) if not already created, copy the default language file to the new folder, and then customize the messages.
```json
{
  "ChatCleaned": "Chat has been cleaned",
  "CommandClean": "cleanchat",
  "NotAllowed": "You are not allowed to use the '{0}' command",
  "Welcome": "Welcome to {0}, {1}!"
}
```
