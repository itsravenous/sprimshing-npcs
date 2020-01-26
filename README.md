# @sprimshing/npcs

Allows posting as an NPC.

## Usage
1. Create a Google spreadsheet with two columns, Name and Image to hold youre NPCs and their avatars, like this:

|Name   |Image   |
|-------|--------|
|Bilbo  |https://example.com/bilbo.jpg|
|Frodo  |https://example.com/frodo.jpg|
|Arwen  |https://example.com/arwen.jpg|

2. Make sure the spreadsheet's sharing option is set to "Anyone with the link can view", otherwise the script won't be able to access it.
3. Deploy functions/npcs.js via netlify or AWS.
4. Add a slash command to your Slack app pointing to the function's endpoint, e.g. `/npc`
5. Send messages as an NPC with `/npc <npc name> <message>`, e.g. `/npc Frodo I can't go on, Sam`.

