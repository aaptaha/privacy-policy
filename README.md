# Aaptaha respects a server's privacy!

*Throughout this policy, the word "Aaptaha" shall mean, depending on the context, either the bot / service, or its maintainers and developers.*

*Though not needed due to a non-intrusive design, Aaptaha is [required by Discord](https://discord.com/developers/docs/legal#a-implement-good-privacy-practices) to list a privacy policy. By using Aaptaha, you agree to the latest revision of this privacy policy, which can be found exclusively on https://github.com/aaptaha/privacy-policy.*

---

**No personally identifiable information (PII) is collected by Aaptaha deliberately. You are not required / needed to provide any PII to Aaptaha for the purposes of using Aaptaha on Discord.**

You are considered to be entirely responsible for handling and exposing of your PII to anyone, including Aaptaha, and in no cases will Aaptaha be considered responsible for anything related to your PII. You cannot hold Aaptaha responsible for any (including malicious) use of it by any user for any reason.

---

Aaptaha creates a small database per server to work smoothly. The data isn't used for anything else other than ensuring the functionality of the bot. **It is neither sold to nor used for marketing by any third party.**

The use of a persistent database is (but not limited) to:
- Store the server configuration set by the admin of the server.
- Store the amount of money a member (numeric user ID) of a server has.
- Store deletboard configuration (if you set it up).
- Store shop (if you create it).
- Store the welcome/leave message configurations (if you set it up).
- Store roles of member(s) when you mute them (to give back on unmute, and then deleted).
- Store debate messages to send them at the end in a file (and is deleted afterwards).
- Persist command cooldowns between restarts.
- And some other miscellaneous stuff.

If you want, you may delete the server database entirely in one go (which will also delete users' economy stats). For that, check out `delete_db` command's help. This may cause some commands to not work. You can recreate it after deletion using the `recreate_db` command.

A cache to store cooldowns, rate limits, states, member lists, interactions, etc. is also needed for smooth working and to prevent spam. Aaptaha is built using the [Pycord library](https://github.com/Pycord-Development/pycord), so check out the library's documentation for an in-depth technical information on bot's default cache. Aside from the useful library-generated cache, Aaptaha may have extra cache for requisite functionalities. For example (but not limited to), storing the provided ID of a server you will export emojis to using the `copy_emojis` command.

---

Aaptaha also logs its __**own**__ working, which includes:
- Application errors, failures, and all other things (debug level logs).
- Internal application database access (warn level logs).
- Messages Aaptaha sends.
- In case of a crash on usage of a command, the command message user sends.

**Aaptaha does NOT log any other messages by anyone else unless specified/requested\*.**

These are required, since bot may unexpectedly fail / crash, and to fix it the developer needs to ascertain the causes for it. That's when the logs help, since the reasons can be potentially logged.

The logs are often deleted permanently.

\* An example is the debate feature, wherein messages are logged to combine them and send later. It is explicitly made clear in the help command.

---

Aaptaha uses tried-and-tested industry-standard practices to protect and safeguard the access to data. Still, one cannot guarantee that any system be 100% secure, due to inherent technological reasons. You will not hold Aaptaha responsible for any data breaches, and in case if you have any knowledge of data breach you are required to inform/report about the same through appropriate channels.

Aaptaha is obliged to respond to legal requests and warrants (including requests for data sharing) under the laws and jurisdiction of Republic Of India. The Courts at Delhi, India shall have exclusive jurisdiction over any disputes.

This privacy policy can change in future at any time, without any prior notice, for any reason. Any changes or modifications will be effective immediately upon posting the updated privacy policy. You should check the privacy policy page regularly to stay up-to-date. You will be considered to be aware of, be subjected to, and be in acceptance to any change in the privacy policy by your continued use of Aaptaha after the moment such revised privacy policy is posted.

