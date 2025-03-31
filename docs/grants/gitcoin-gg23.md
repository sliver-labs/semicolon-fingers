> A storytelling platform addressing the global loneliness epidemic

Ever seen Harry Potter? There is a scene where Albus Dumbledore uses his wand to remove a memory from his mind to empty into the Pensieve. Semicolon Fingers hopes to enable exactly that, but with all the benefits of web3, ie, it incentivises you to outpour your stories [read: empty your mugs] onto the network. The stories are represented as the balls of coloured yarn, as they usually are, by having them displayed in the form of interactive, clickable links. As the reader clicks, parts of the story are revealed. Think of it as pulling the threads of the yarn ball, and as the reader pulls more, the writer earns\* more; because web3.

In this spirit, Semicolon Fingers is a storytelling platform tackling the global loneliness epidemic through an emotionally intelligent, token-incentivized web3 experience. By blending interactive text, sentiment analysis, and open-source infrastructure, it offers a new kind of human connection — one that is meaningful, measurable, and mental-health-forward.

See the application in action — [![youtube-demo-gg23-thumbnail](https://img.youtube.com/vi/7HWkueO_RF4/0.jpg)](https://youtu.be/7HWkueO_RF4?si=yQt1qHiockcr1JXB)

### Why it Matters

Loneliness is more than a feeling — it’s a public health crisis. Semicolon Fingers is built on the belief that stories, when shared and heard, are an antidote. By enabling readers to pull the thread of someone else’s story, we not only create empathy, but track and reward it. This is social impact, measurable and encoded.

## How it works

Semicolon Fingers has two entrypoints — the writing side (empty-your-mug) and the reading side (pull-my-thread); On the writing side, a user selects a colour (base emotion), a prompt (nuanced emotion), and writes their story. They then deploy their story on the network as a NFT contract (which is sponsored). On the reader side, a user is presented with a random story, coloured by its emotion, which they can unfurl to read, or stumble upon another story. This stumbling informs the rate at which new tokens are dripped to the writers of the stories being read.

### Colours

Semicolon Fingers follows the colour representation of HSL, ie, hue, saturation, and lightness. Hue is the degree of the colour on the colour wheel (from 0 to 359), saturation is defined as the intensity of the colour (from 0% to 100%), ie, how much grey is included, and lightness describes how much light, ie, white, the colour has (again, from 0% to 100%). In our context, each story is associated with an emotion or a mood, which translates to the hue of the story (ie, an angry story is red, so 0 deg., sad story is blue, so 240 deg.). The translation for saturation is straightforward, with the intensity of the story being represented as a percentage. Finally, lightness within Semicolon Fingers is twofold, on the writer side, it represents how _light_ the writer feels after emptying their mug, while on the reader side, it represents how _heavy_ a reader feels on reading the story. The expectation is that these two values would be inverses of each other, but that hypothesis remains to be validated through user interaction.

### Telescopic Text

A transformation that each story goes through is that of being converted to [_telescopic text_](https://telescopictext.org/). Telescopic text is a form of display where a piece of text is expanded by user interaction. At first, a user is presented with a few words, some of which can be clicked. Once such a word is clicked, more words are revealed, and the process follows. This is a novel way to utilize the capabilities of interactive systems like the web browser and create (or track) engagement for every piece of text. Semicolon Fingers uses the inherent properties of this feature to i. create a signal for writers as to how much their story is being read, if at all; and ii. consider each expansion to be a _mining event_, where new tokens are dripped to the writer, as their story is expanded, and read.

### Stumbling

Inspired by [StumbleUpon](https://en.wikipedia.org/wiki/StumbleUpon), Semicolon Fingers' reader face (ie, pull-my-thread) only presents a random story (condensed in telescopic text as described above) and a big shuffle button. Readers now have the choice to either expand the story (unfurl the yarn, if you will) or stumble onto another story. As each story also has associated hue, saturation, and lightness values, these help in letting the reader perform a [_random walk_](https://en.wikipedia.org/wiki/Random_walk) based on their interaction with the site, creating a sort of emotional trail of the reader across the network, akin to wandering through a museum of unspoken feelings. The more a reader stumbles before settling on a story, the more tokens are earned by the writer, a reward for standing out in a sea of voices.

### DeSci

A (slightly) future mechanism of the project revolves around Decentralized Science. This will manifest across three key areas,
1. **Sentiment Analysis** Above, we mentioned that each story is associated with a mood and an intensity. For the alpha version, a writer selects the mood of the story and then writes, while the intensity is kept constant at 50%. As a reader reads a story, they are prompted to enter in their perceived mood and intensity of the story they are reading. Over time, these data points (one from the writer, and many from the readers) will be used to perform sentiment analysis using Support Vector Machines, preferably onchain.
2. **Global Emotion Heatmap** Provided there are many stories on the network, from across the world, a fascinating thing to look at would be what kinds of emotions (ie, colours) are emerging from various geographies. For instance, an area affected by war would likely have a lot of blue and red stories, or an area with a high satisfaction of living might have more yellow (ie, happy) emerging. This is an indirect way to ascertain the prevalent emotion of a place, as opposed to dry surveys.
3. **Mental Health** Finally, and perhaps most importantly, Semicolon Fingers aims to make a dent in the mental health crises in the world. The hypothesis here is that a bunch of mental health conditions manifest due to humans not having a space to let their emotions out, and as a result bottling up their feelings. With a novel approach to tackling this loneliness, Semicolon Fingers aims to have positive downstream effects on mental health itself!

Additionally, all data is stored on-chain and is open by design, enabling researchers, DAOs, and mental health initiatives to access and build upon this emotional dataset.

**a note about loneliness**

So far, loneliness is mentioned multiple times, but it may not be clear as to exactly how Semicolon Fingers addresses this. The idea here is that the tokens mined by the readers for the writers provides a strong signal that there is indeed someone out there who has heard, related to, and engaged with a story; after all, money (or tokens), in its purest form, is a signal. With the premise of each story being that they are deeply personal stories, Semicolon Fingers aims to bring about opportunities for [_fleeting intimacy_](https://feeld.co/ask-feeld/how-to/power-of-fleeting-intimacy). Humans are social creatures and the lack of (meaningful) social interaction is ailing our society. Semicolon Fingers aims to rectify that. Finally, as an aside, if we look back at how the internet gained momentum, a large part of it was through random individuals finding community on the network, and Semicolon Fingers is providing a new opportunity for the same. With the wonders of web3, this time around, maybe the connected individuals get something more than just connection and communion.

## Project Timeline

**2018** Discovery of telescopic text; initial ideas start forming.

**2021** Project begins conceptualizing, with token mechanics and dataflow approaches.

**2022** A small prototype created at ETHGlobal's NFT Hack to gauge interest.

**2025 Q1** Work on MVP begins in earnest, with the idea presented multiple times.

***2025 Q2*** Beta release.

## Resources 

Up to date information can be found on the [community github repository](https://github.com/sliver-labs/semicolon-fingers). Since the project has been in ideation for a long time, and iterated upon several times, the repositories and other related material for the project is very spread out. As such, most current information will be available in the repository linked above, and will contain links to other repositories, along with docs, and community discussions.

For a demo of the project, you can check out [this video on youtube](https://youtu.be/7HWkueO_RF4?si=o0Ubhe-a63M-SaCa) (same as above).

### Architecture

**Base** The project effectively lives on Base. This choice is made deliberately owing to their deep integration with Coinbase. As one of the goals of Semicolon Fingers is to bring about effective change in the mental health crisis in the world, the hope is that any earnings of a writer may go into therapeutic costs.

**Zora** There are two main types of NFTs for the users of Semicolon Fingers that would benefit tremendously by Zora's CoinSDK.

**rollup** The core mechanics of the project is bundled on a rollup, which can be considered as an app chain.

## How will funds be used

Finally, any funding received as a result of this grant will go towards the following (in order),
- Developer support, ensuring a full-time focus on the project
- Deployment of beta version on mainnet 
- Security audits of the contracts and rollup infra
- Sponsoring user transactions until the project becomes self-sustaining