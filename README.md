# COSYPress
#### An open-source multimedia CMS built to democratise media for a new generation.

> 🚨🧑‍💻 **Calling all coders, DevOps, QA testers, UI/UX designers...** whatever your niche, COSY needs **you!** Get in touch on Discord: faizpapaya#1653

## What is COSYPress?

**COSYPress** is our home-grown CMS (content management system) that powers [**COSY MAG**](https://cosy.land), an open-submission magazine on the web featuring perspectives from writers all around the world. It will also power [**COSY FM**](https://cosy.fm) — a music and podcast streaming app designed to connect independent musicians and podcasters to listeners — in an age where it's become impossible to stand out on mainstream platforms like Spotify and SoundCloud

It's early days right now, but **COSYPress** includes some cool features designed just for COSY MAG and COSY FM, like:

* **Supports** written articles, audio articles, podcasts and music as first-class content types.
* **Sophisticated storage and distribution of multimedia content.** COSYPress automatically transcodes audio/video content that users upload into more efficient formats, just like Spotify, Apple Music and the other big guys. This really saves money on those bandwidth bills!
* **Built to be collaborative.** COSYPress lets anybody sign up for an account and start submitting content. It allows a group of editors to then review that content to make sure it fits an editorial standard. It democratises the entire journalistic and editorial process.
* **COSYPress Studio** makes it easy for creators, editors and publishers to manage a publication. Submit, edit and review drafts in an elegant, easy-to-use interface.
* **Robust profile management features** including a deeply customisable profile page for all users.
* **Import content from all over the web.** Want to let writers import drafts from a .docx file, or a Google Doc, or a webpage? Sure thing. COSYPress makes it super easy for writers to upload their drafts, wherever they might have written them.
* **Plug and play**. COSYPress talks to clients using [**GraphQL**](https://graphql.org/), so queries are well-defined, strongly typed and easy to design. Better yet, we have a connector library for JavaScript called [**PressKit**](https://github.com/cosy-land/PressKit) — so you can consume content from COSYPress in your React website with ease.
* **Entirely open source under the MIT license.** You want to start a publication like COSY? Fork away. We're not trying to compete — we're trying to design and develop a platform for *everybody* to use.

## Why a home-grown CMS?
It's a good question. Building a CMS is a lot of work, and when there are so many pre-established open-source solutions available, like WordPress and Ghost... you'd have to be crazy to want to build your own for most projects!

But honestly, it was kind of out of necessity for us. Mid-2020, when we first sat down to build the first version of the COSY website, we wanted a CMS that could not only handle all of the needs we had back then — making it as accessible as possible for writers who might be unfamiliar with technology to submit their drafts — but something that could handle our needs in the future too.

WordPress had all the plugins to build what we needed, but WordPress has a tendency to quickly get slow and janky. And many of the plugins are low-quality, and we didn't want a website bogged down by legacy, inconsistent APIs. Add to that the fact that we knew that we'd eventually want to build mobile apps and more sophisticated projects, and it seemed to us that we'd quickly outgrow WordPress.

In the end, we chose Ghost — a simple but powerful CMS designed _specifically_ for writers and publications like ours. It has a super clean API, and it can run headlessly as part of a React website. It has served us really well, and continues to! But when we look forward to COSY FM, and our long-term plans of completely decentralising our editorial process, it can only take us so far. Already we have had to expend so much time expanding Ghost past its comfort zone, and it would be so much easier and time-efficient to develop new features if we just created our own CMS.

The exciting thing about having our own CMS though, is that there is **no limit to what we can build with it**. Now, we're completely in control, end-to-end. And now that we're open-source, it means we can hand over an unprecedented level of control to the community about how to run this beast.

## Sounds great! How can I use this?

Things are early right now, but they are rapidly moving forward. We're trying to get a new version of **COSY MAG** powered by COSYPress ready by July this year. If you _Watch_ us on GitHub, you'll get updates as soon as there's usable code here.

If you believe in what we're doing and want to help, we're always looking for collaborators, so if you feel like you can help, please get in touch on my Discord (faizpapaya#1653) and we can jump on a DM or a call and hash out the details :)
