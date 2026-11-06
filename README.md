<a href="https://somethingobvious.github.io/glassbox/#route"><img src="https://raw.githubusercontent.com/SomethingObvious/glassbox/live/route.svg" width="100%" alt="Today's top Hacker News headline going through IBM Granite's router, each token lighting 8 of 32 experts in every layer"></a>

# Paul Wu

I currently work at [Backboard.io](https://backboard.io), an AI inference and model quantization company in Ottawa, Ontario, and I do both of those things, mostly on B200s, H100s and RTX 6000 Pros.

Nearly everything here runs on your own computer, and while local projects are currently all the rage, I've been building on my own systems since well before this trend. There's something beautiful about how your data can stay on your machine, continuing working when the internet or the company behind it doesn't, and nobody can change the price or take it away later. There is a great sense of freedom when one realizes that so much of what one uses can be made by themselves, and I hope that you'll share this feeling with me going through my projects. 

## glassbox

Animated pictures of what happens inside LLM inference (Drawn from real runs). Every morning a workflow pushes the top Hacker News headline through a real mixture-of-experts router and redraws the banner at the top of this page, and the [live page](https://somethingobvious.github.io/glassbox/) runs speculative decoding with two real models on your own GPU through WebGPU. [Demo](https://somethingobvious.github.io/glassbox/), [source](https://github.com/SomethingObvious/glassbox).

<a href="https://somethingobvious.github.io/glassbox/#draft"><img src="https://raw.githubusercontent.com/SomethingObvious/glassbox/main/assets/draft.svg" width="100%" alt="Qwen3-0.6B guessing tokens and Qwen3-1.7B checking four at a time, with kept guesses boxed and the first miss in red"></a>

<a href="https://somethingobvious.github.io/glassbox/#waves"><img src="https://raw.githubusercontent.com/SomethingObvious/glassbox/main/assets/waves.svg" width="100%" alt="A matrix multiply's tiles going out to an H100's 132 SMs in waves, with 80 idle in the last one"></a>

## JWSTDetector

It looks for strange things in James Webb images with no labels, by ranking every tile on how far it sits from ordinary sky. The banner is a real run on Webb's First Deep Field, and every tile lights up by its score. [Demo](https://somethingobvious.github.io/JWSTDetector/), [source](https://github.com/SomethingObvious/JWSTDetector).

<a href="https://somethingobvious.github.io/JWSTDetector/"><img src="assets/field.svg" width="100%" alt="The galaxy cluster in Webb's First Deep Field. A scan line lights up each tile by its anomaly score, six numbered boxes lock on, and the camera zooms in on a lensed galaxy at redshift 6.27."></a>

<a href="https://somethingobvious.github.io/JWSTDetector/"><img src="assets/jwst.svg" width="100%" alt="Four highly ranked tiles shown in turn: lensed arcs, the cluster core, a lensed galaxy at redshift 6.27 and a diffraction spike"></a>

## Keepsake

A free video, audio and gallery downloader for Android and Windows, built on yt-dlp and gallery-dl. This is the real interface, running a scripted queue. [Site](https://somethingobvious.github.io/keepsake/), [source](https://github.com/SomethingObvious/keepsake).

<a href="https://github.com/SomethingObvious/keepsake"><img src="assets/keepsake.webp" width="100%" alt="The Keepsake downloads page as a link is added, each running film draws its speed as a line, and finished films drop to the bottom of the queue"></a>

## Netwatch

A small Windows desktop board that tells you when packet loss is bad enough to restart the router. This is the app's own flap animation, playing through a scripted bad hour. [Source](https://github.com/SomethingObvious/netwatch).

<a href="https://github.com/SomethingObvious/netwatch"><img src="assets/netwatch.webp" width="100%" alt="The Netwatch board flipping its split-flap letters from Fine to Watch to Reset to Recovery as bad minutes fill its strip for the last hour"></a>

## Valorant Overseer

A VALORANT match tracker that shows every player's rank, peak and K/D, with no account and no tracking. [Site](https://somethingobvious.github.io/Valorant-Overseer/), [source](https://github.com/SomethingObvious/Valorant-Overseer).

<a href="https://somethingobvious.github.io/Valorant-Overseer/"><img src="assets/overseer.webp" width="100%" alt="The opening of the Overseer website, with the letters of its name slapping down over a red slash and the board landing beside them"></a>

## Also Here

[The Lab](https://github.com/SomethingObvious/the-lab) messages the coding agent on your own computer from an Android phone.

[remote-search-sms](https://github.com/SomethingObvious/remote-search-sms) answers web searches by text, for a phone with no data and a satellite SMS plan.

[Prompt-Baking](https://github.com/SomethingObvious/Prompt-Baking) bakes a system prompt into a LoRA adapter, and it fits on an 8 GB GPU.

[tiktok-activity-data-scraper](https://github.com/SomethingObvious/tiktok-activity-data-scraper) turns your TikTok data export into a report of what you watch most.
