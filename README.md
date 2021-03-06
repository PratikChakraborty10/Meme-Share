# Meme-Share Application

## _API Used:_


- [Reddit Meme API](https://meme-api.herokuapp.com/gimme/1) - Meme Share API

Endpoint: [/gimme/{count}](https://meme-api.herokuapp.com/gimme/1)
- MAX COUNT: 50

Example: https://meme-api.herokuapp.com/gimme/1

> Respone

```
{
count: 1,
memes: [
{
postLink: "https://redd.it/nhfeum",
subreddit: "dankmemes",
title: "Title",
url: "https://i.redd.it/wws44tgs8d071.jpg",
nsfw: false,
spoiler: false,
author: "mc-fortress-fans",
ups: 387,
preview: [
"https://preview.redd.it/wws44tgs8d071.jpg?width=108&crop=smart&auto=webp&s=5151b492b5951a000edf4525e2c7b68d842bce86",
"https://preview.redd.it/wws44tgs8d071.jpg?width=216&crop=smart&auto=webp&s=f0f751b890aea1bb7e3ccf58e5770d561ffa40b2",
"https://preview.redd.it/wws44tgs8d071.jpg?width=320&crop=smart&auto=webp&s=9f27467dea6f623149370ce7a3b61b86834ccae9",
"https://preview.redd.it/wws44tgs8d071.jpg?width=640&crop=smart&auto=webp&s=a8d4399aa5051e0dadf70a4b7252fd1497e74dce",
"https://preview.redd.it/wws44tgs8d071.jpg?width=960&crop=smart&auto=webp&s=1153ef1e0ee31b352cddfe8a55d643e0db9f688b",
"https://preview.redd.it/wws44tgs8d071.jpg?width=1080&crop=smart&auto=webp&s=3fb4375bb1ff3a968e355f90ec5a3ebbfd2ee7c3",
],
}
],
}
```

## Specify Subreddit

By default the API grabs a random meme from 'memes', 'dankmemes', 'me_irl' subreddits. To provide your own custom subreddit use the following endpoint.

Endpoint: [/gimme/{subreddit}](https://meme-api.herokuapp.com/gimme/wholesomememes)

Example: https://meme-api.herokuapp.com/gimme/wholesomememes

> Response

```
{
postLink: "https://redd.it/nf49r8",
subreddit: "wholesomememes",
title: "I have been chosen!",
url: "https://i.redd.it/3e72jsu60uz61.jpg",
nsfw: false,
spoiler: false,
author: "Kirishima_San",
ups: 71423,
preview: [
"https://preview.redd.it/3e72jsu60uz61.jpg?width=108&crop=smart&auto=webp&s=e4b2ee8e784dc855a22f144287b0df80ca7a1768",
"https://preview.redd.it/3e72jsu60uz61.jpg?width=216&crop=smart&auto=webp&s=dbd5df743c5a72d5a6924924c44296cb78a07140",
"https://preview.redd.it/3e72jsu60uz61.jpg?width=320&crop=smart&auto=webp&s=73533ee248636f0a7d48db933e0698bd36c48dbc",
"https://preview.redd.it/3e72jsu60uz61.jpg?width=640&crop=smart&auto=webp&s=3504ef7a2969cf6568eabd342fd79dcf7003280d",
],
}
```
