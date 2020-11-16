# Aaptaha respects a server's privacy!

*Though not needed, Aaptaha is [required by Discord](https://discord.com/developers/docs/legal#a-implement-good-privacy-practices) to list a privacy policy. By using Aaptaha, you agree to the privacy policy exclusively listed on https://github.com/aaptaha/privacy-policy.*

**No personally identifiable information (PII) is collected by Aaptaha deliberately.** You are not required to provide any PII to Aaptaha for the purposes of using Aaptaha on Discord.

---

Aaptaha creates a small database per server to work smoothly. The data isn't used for anything else other than ensuring the functionality of the bot. **It is neither sold to nor used for marketing by any third party.**

The use of a persistent database is to:
- Store the server configuration set by the admin of the server.
- Store the amount of money a member (numeric user ID) of a server has.
- Store anyboard/deletboard configuration (if you set it up).
- Store shop (if you create it).
- Store the welcome/leave message configurations (if you set it up).
- Store roles of member(s) when you mute them (to give back on unmute, and then deleted).

If you want, you can delete the server database entirely in one go (which will also delete users' economy stats). For that, check out `delete_db` command's help. This may cause some commands to not work. You can recreate it after deletion using the `recreate_db` command.

A cache to store cooldown/ratelimits, states, member lists, etc. is also needed for smooth working and to prevent spam. Aaptaha is built using [discord.py library](https://github.com/Rapptz/discord.py/), so check out the library's documentation for in-depth technical information on bot's default cache. Aside from the useful library-generated cache, Aaptaha may have extra cache for requisite functionalities. For example, to store the provided ID of a server you will export emojis to using the `copy_emojis` command.

---

Aaptaha also logs its __**own**__ working, which includes:
- Messages Aaptaha sends (*NO logging of any other messages by anyone else*).
- Internal application database access.
- Application errors and failures (debug level logs).

These are required, since bot may unexpectedly fail/crash, and to fix it the developer needs to ascertain the causes for it. That's when the logs help, since the reasons can be potentially logged.

---

Aaptaha is obliged to respond to legal requests and warrants under the jurisdiction of Republic Of India.

This privacy policy can change in future at any time, without any prior notice, for any reason. Any changes or modifications will be effective immediately upon posting the updated privacy policy. You should check this privacy policy regularly to stay up-to-date. You will be considered to be aware of, be subjected to, and be in acceptance to any change in the privacy policy by your continued use of Aaptaha after the moment such revised privacy policy is posted.
