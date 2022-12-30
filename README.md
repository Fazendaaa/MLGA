# MSMGA (Make Social Media Great Again)

Make Social Media Great Again -- a browser extension that blocks known profiles that post too much non-relevant content.

- [MSMGA (Make Social Media Great Again)](#msmga-make-social-media-great-again)
  - [Introduction](#introduction)
    - [Tribes](#tribes)
    - [Users](#users)
    - [Ratio](#ratio)
    - [Quid quo pro](#quid-quo-pro)
  - [Data](#data)
  - [Tech](#tech)
    - [Browsers](#browsers)
    - [API](#api)
  - [Contributing](#contributing)
  - [TODO](#todo)
  - [Appendix](#appendix)
  - [References](#references)

## Introduction

At first, intended to be used only on LinkedIn, you can read more about it [here]() -- portuguese post --; MSMGA intends to be a non relevant content filter from known offenders in social media, profiles like:

- Clickbait promoted content
- Copycats profiles
- Pyramid schemes
- etc

It's a community driven approach, whereas a user flag a content tagging accordingly and the aggressor is banned from the whole community feed.

Social medias company have shown us over and over again that they cannot -- or won't -- moderate properly all flamming publications. This aggravates even further because this direct and indirectly generates engagement to them, this also generates revenue. A good and proper community doesn't generate money and fame to social media companies.

### Tribes

Tribes are how communities are organized. You can be part of many tribes so you can help them flagging content and also helping be helped by them. I.E.: you can be part of a left wing tribe, where any right wing content is filtered from it and vice-versa.

### Users

Our users won't need also to be part of any tribes if the chose so, they can only share their filters to others to consume or not share at all.

### Ratio

We won't lock any service or tool to any user, a user cannot be banned from our system. But this doesn't mean that they cannot be banned from a tribe; as shown here, a tribe is a collective of users and if one user is toxic to a tribe, he can be banned from it and MSMGA will give full autonomy to it's tribes; going even further give tribes incentives to monetize their top users' work.

### Quid quo pro

We even tho a tribe has its chieftain -- the user who created it -- that doesn't mean he has the whole authority, no user is more or less than any other user. So if someone decides to challenge the tribe chieftain status, all tribe's members must decide to change or not.

## Data

All data will be exportable so anyone can change from MSMGA to another platform anytime or even host their own MSMGA instance in any cloud provider or host on their own home-lab. Not only to enforce GDPR or anything like that, we don't need anything to deanonymise our users.

## Tech

All the code provided here is for all projects, a monorepo approach for now.

### Browsers

MSMGA acts in the browser as a extension. You won't need to create a profile or anything like that, when the browser extension is installed any user related data will be cryptographically stored in the browser itself, our servers won't have access to it.

### API

An API will be able so users can create any new application, an idea is to create a DNS hole list based on that API so any user could plug it in [PiHole]().

## Contributing

Right now the thing we need most is contributions in the following order:

1. Translations
2. Divulgation
3. Code
4. Anything else that you may be able to help us with

We won't integrate or try to be any monetization platform even tho we allow monetization _per se_. Our users can choose to monetize their work in any platform that they like and share the link to it in their rank status.

## TODO

- Create ports to non-chromium based browsers
- Create user ranking
- Create a search engine

## Appendix

This project has its own twin brother: [Ironglass](), a project that indents also in a community driven approach, to help make a rank about any companies infractions. The idea is to be a propaganda vaccine, protecting the user from big brother's influence and his eyes.

## References
