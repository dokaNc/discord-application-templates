# Discord application templates

Free, copy-and-paste templates for Discord servers: **staff and mod application questions**, **FiveM / GTA RP whitelist
application questions**, a **ban appeal template** and **server rules**. Use them in any form tool, application bot or rules
channel. No credit needed.

Every template comes as Markdown (to read and copy) and JSON (to import into your own tools), in up to 8 languages.

## Templates

| Template | What's inside | Languages |
|---|---|---|
| [Staff & mod application questions](templates/en/staff-application-questions.md) | 58 questions in 7 themes (applicant, experience, motivation, scenarios, rules, availability, helpers) + a 5-question version | [en](templates/en/staff-application-questions.md) · [fr](templates/fr/staff-application-questions.md) · [es](templates/es/staff-application-questions.md) · [pt-BR](templates/pt/staff-application-questions.md) · [de](templates/de/staff-application-questions.md) · [tr](templates/tr/staff-application-questions.md) · [pl](templates/pl/staff-application-questions.md) · [ru](templates/ru/staff-application-questions.md) |
| [FiveM whitelist application questions](templates/en/fivem-whitelist-application-questions.md) | 53 questions for GTA RP servers: OOC basics, RP experience, character and backstory, RP rules (RDM, VDM, NLR…), scenarios + a 5-question version | [en](templates/en/fivem-whitelist-application-questions.md) · [fr](templates/fr/fivem-whitelist-application-questions.md) · [es](templates/es/fivem-whitelist-application-questions.md) · [pt-BR](templates/pt/fivem-whitelist-application-questions.md) · [de](templates/de/fivem-whitelist-application-questions.md) · [tr](templates/tr/fivem-whitelist-application-questions.md) · [pl](templates/pl/fivem-whitelist-application-questions.md) · [ru](templates/ru/fivem-whitelist-application-questions.md) |
| [Ban appeal template](templates/en/ban-appeal-template.md) | 5 core questions + 15 more to pick from | [en](templates/en/ban-appeal-template.md) |
| [Discord server rules](templates/en/discord-server-rules.md) | short (10) and full (20) rules, voice chat rules, moderator rules for staff, roleplay / FiveM rules | [en](templates/en/discord-server-rules.md) |

Each file links to the full guide on toscio.com, with tips, red flags and examples of good answers.

## Tips for Discord forms

- **Keep it short.** 5 to 15 questions is enough. Good applicants give up on 30-question forms.
- **Ask scenario questions.** “Two members are arguing in public chat: what do you do?” tells you more than “Why do you want to be staff?”.
- **Mind Discord's limits.** A native Discord form (modal) shows 5 questions at a time, and a question title is limited to
  45 characters. Put the detail in the description line under the question.
- **Use a checkbox for the rules.** A required “I have read the server rules” checkbox keeps your text questions for real answers.

## JSON format

```json
{
  "title": "Discord Staff & Mod Application Questions: 58 to Copy & Paste",
  "language": "en",
  "source": "https://toscio.com/guides/discord-staff-application-questions/",
  "sections": [
    { "title": "About the applicant", "items": ["How old are you?", "What is your time zone?"] }
  ]
}
```

`items` are questions in application templates and rules in the rules template, in display order.

## Use them with a Discord bot

These templates are maintained by the team behind [Toscio](https://toscio.com/?utm_source=github&utm_medium=templates), a
Discord application bot: members apply in a native Discord form, staff accept or decline from a private channel, and the role
is given automatically. Toscio has ready-made templates for the same uses (FiveM whitelist, staff recruitment, ban appeals and
more), but the files here work with any tool: Google Forms, another bot, or a plain message.

## Contributing

Spotted a question that never works, or one that is missing? Open an issue or a pull request. Keep questions short, neutral
and free of personal data (no real names, addresses or phone numbers).

## License

[CC0 1.0](LICENSE): public domain. Copy, edit and use these templates anywhere, commercial or not, without asking.
