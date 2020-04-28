# Threat Modeling for Designers

This is a living, work-in-progress documentation to shape how might _Threat Modeling_ (borrowing from security field) look like for designers. Alternatively, we can relabel "threat modeling" as "risk assessment."

We welcome collobration on this documentation — Suggest and create a PR to add, suggest improvement, etc.

## Why

As a framework, _threat modeling for designers_ will help designers:

1. Understand the threats users face and how designers can counter those threats
2. Make security more manageable
3. Collobrate with partner(s) and colleagues to develop an understanding of our/their assets, adversaries, and capaiblities

## How

*The process of speculating with questions*

- High-level, "How might..." questions to ask ourselves
  - When might threat modeling for designers be useful?
  - When might threat modeling for designers not be useful, and/or in turn, actively harm?
  - How might threat modeling change over time? And how would we maintain/care for it?

- Additional questions
  - [Add yours here]

*Identify and research real world cases and examples*

- Discover how they are addressed, resolved or not, etc.
- Identify both external and internal (18F/TTS) cases/examples

## Resources

Note: When researching resources, be aware of authors' backgrounds and biases — Security and threat modeling are heavily authored by a certain demographic, and instead make an effort to find authors from various backgrounds, especially those who are likely to experience vulnerable situations.

- **External resources**
  - **Articles**
    - [Be the Villain](https://24ways.org/2018/be-the-villain/) by Eric Bailey on the fact that technology isn't neutral, inverting the Inclusive Design Principles, asking questions like, "What is the evil version of this feature?", etc
    - [An introduction to approachable threat modeling](https://increment.com/security/approachable-threat-modeling/) — Explores how pairing our existing knowledge and experience with a few simple questions can help us build better systems and keep them safe.
    - [Threat Modeling is So Fetch](https://medium.com/@securityblanket/threat-modeling-is-so-fetch-1c96b7123444) — Examples of threat models inspired by a film classic, Mean Girls
  - **Websites**
    - [Dark Patterns](https://www.darkpatterns.org/) - Its purpose is to spread awareness of dark patterns, which are tricks used in websites and apps that make you do things that you didn't mean to. Also has a [reading list](https://www.darkpatterns.org/reading-list)
    - [Evil by Design](https://evilbydesign.info/) - Evil design implementations grouped under the seven deadly sins, with tips on how to use each pattern, and examples from real life and the Web. 
      - Speculative question: The seven deadly sins concept is framed on modern westerrn society / Christianity thought. How might this look in another framework, e.g. eastern thoughts of "sin" or "evil"? For example in Chinese thought, "sin" is typically framed as wrongdoing, but more about only _if you're caught_. How do we determine that the intention is wrong? 
  - **Talks**
    - [Design Strategies for Building Safer Platforms](https://www.infoq.com/presentations/strategies-safer-platforms/) by Kat Fukui, Product Designer at GitHub
      - Fukui explores 1) user safety, 2) consent-driven design, 3) encouraging inclusive behavior while discouraging destructive behavior, 4) design a paper trail for support team to investigate abuse reports 
  - **Tweets** 
    - [Tweet thread](https://twitter.com/cattsmall/status/1176653824460775424) by Catt Small on building trust and responsibility into the process 

- **Internal resources**
  - [18F Methods: Decide - Design hypothesis / Harm prompt](https://methods.18f.gov/decide/design-hypothesis/) 
    - > ... consider the following harm prompt to help the team think about and guard against potential unintended consequences of your work. `But, this could be harmful for [this user] if [this outcome happens].`
  - [Doc: Exercises to identify harm in design](https://docs.google.com/document/d/14WP93iljyATBJOBVtpQGcYDoz_oLVmARW_j4-3qPvMM/) :lock: by Christine Bath (with additions by Nick Ng)
