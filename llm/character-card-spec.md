# character chars spec

> 2025-05-26

While exploring openrouter.ai, looking at some random app that seemingly uses
about 4B tokens per day (chub.ai)

1 words, about 0.75 tokens. To 3B words passing through a single app, or about
35K tokens per second; may correspond to up to 2K concurrent users, on average.

Character chat app, uses

* [https://github.com/malfoyslastname/character-card-spec-v2](https://github.com/malfoyslastname/character-card-spec-v2)
* spec: [https://github.com/malfoyslastname/character-card-spec-v2/blob/main/spec_v2.md](https://github.com/malfoyslastname/character-card-spec-v2/blob/main/spec_v2.md)


cf. SillyTavern;

> SillyTavern is built around the concept of "character cards". A character
> card is a collection of prompts that set the behavior of the LLM and is
> required to have persistent conversations in SillyTavern. They function
> similarly to ChatGPT's GPTs or Poe's bots. The content of a character card
> can be anything: an abstract scenario, an assistant tailored for a specific
> task, a famous personality or a fictional character.

> To have a quick conversation without selecting a character card or to just
> test the LLM connection, simply type your prompt input into the input bar on
> the Welcome Screen after opening SillyTavern. This will create an empty
> "Assistant" character card that you can customize later.

> To get a general idea on how to define character cards, see the default
> character (Seraphina) or download selected community-made cards from the
> "Download Extensions & Assets" menu.

note: oss openrouter.ai, https://llmgateway.io/


