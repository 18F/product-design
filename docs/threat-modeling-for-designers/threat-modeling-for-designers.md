# Threat Modeling for Designers

This is a living, work-in-progress documentation to shape how _Threat Modeling_ (borrowing from security field) might look like for designers. 

Note: Based on the feedback from few 18F designers, "threat modeling" as a concept may be not be palatable for designers who are not familiar with security, so we are exploring other names for it, e.g. "risk assessment" to create a bridge for designers into the world of security. With this mind, we would frame this resource as a way to help designers strategize how to build safer platforms.

We welcome collaboration on this documentation.

## Why

As a resource, _threat modeling for designers_ will help designers:

1. Understand the threats users face in design, and how designers can identify and prevent harm to their users
2. Make security more manageable
3. Collaborate with partner(s) and colleagues to develop an understanding of our/their assets, adversaries, and capabilities

## How

### Questions we have about the resource itself

- High-level, "How might..." questions to ask ourselves
  - When might threat modeling for designers be useful?
  - When might threat modeling for designers not be useful, and/or in turn, actively harm?
  - How might threat modeling change over time? And how would we maintain/care for it?

- Additional questions
  - [Add yours here]

### Identify and research real world cases and examples

- Discover how they are addressed, resolved or not, etc.
- Identify both external and internal (18F/TTS) cases/examples

## When

In practice, this resource would be part of pre-mortem.

## Resources

**Note:** When researching resources, be aware of authors' backgrounds and biases — Security and threat modeling are heavily authored by a certain demographic, and instead make an effort to find authors from various backgrounds, especially those who are likely to experience vulnerable situations.

- **External resources**
  - **Articles**
    - [Be the Villain](https://24ways.org/2018/be-the-villain/) by Eric Bailey on the fact that technology isn't neutral, inverting the Inclusive Design Principles, asking questions like, "What is the evil version of this feature?", etc
    - [An introduction to approachable threat modeling](https://increment.com/security/approachable-threat-modeling/) — Explores how pairing our existing knowledge and experience with a few simple questions can help us build better systems and keep them safe.
    - [Threat Modeling is So Fetch](https://medium.com/@securityblanket/threat-modeling-is-so-fetch-1c96b7123444) — Examples of threat models inspired by a film classic, Mean Girls
  - **Websites**
    - [Dark Patterns](https://www.darkpatterns.org/) - Its purpose is to spread awareness of dark patterns, which are tricks used in websites and apps that make you do things that you didn't mean to. Also has a [reading list](https://www.darkpatterns.org/reading-list)
    - [Evil by Design](https://evilbydesign.info/) - Evil design implementations grouped under the seven deadly sins, with tips on how to use each pattern, and examples from real life and the Web. 
  - **Talks**
    - [Design Strategies for Building Safer Platforms](https://www.infoq.com/presentations/strategies-safer-platforms/) by Kat Fukui, Product Designer at GitHub
      - Fukui explores 1) user safety, 2) consent-driven design, 3) encouraging inclusive behavior while discouraging destructive behavior, 4) design a paper trail for support team to investigate abuse reports
    - [Shining Light on Dark Patterns](https://drunkenux.com/podcast/dux41/) by Ron Bronson with follow resources on the site
  - **Tweets** 
    - [Tweet thread](https://twitter.com/cattsmall/status/1176653824460775424) by Catt Small on building trust and responsibility into the process 

- **Internal resources**
  - **Websites**
    - [18F Methods: Decide - Design hypothesis / Harm prompt](https://methods.18f.gov/decide/design-hypothesis/) 
    - "... consider the following harm prompt to help the team think about and guard against potential unintended consequences of your work. — '**_But, this could be harmful for [this user] if [this outcome happens]_**.'"
  - **Docs and spreadsheets**
    - 🔒 [Doc: Exercises to identify harm in design](https://docs.google.com/document/d/14WP93iljyATBJOBVtpQGcYDoz_oLVmARW_j4-3qPvMM/) by Christine Bath (with additions by Nick Ng)
    - 🔒 [Risk tracker template](https://docs.google.com/spreadsheets/d/1vdCD4fUdauwdm_Ru17qxPm09820lXHfRcKBroNTUs84/edit#gid=0): Keep track of risks that your project is likely to face or - in the spirit of being ethical technologists - may itself create
