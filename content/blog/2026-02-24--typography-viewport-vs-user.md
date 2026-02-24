---
title: the more your typography responds to the viewport, the less it will respond to user preferences
description: Miriam Suzanne on responsive typography that respects user preferences and interactions
date: 2026-01-26
tags: ["quote", "ai"]
---
>One action (zooming) changes the size of a pixel, while the other (resizing) changes the size of the browser itself – but both change the number of pixels across the width of the browser. As the window gets smaller, or the pixel gets larger – there are fewer pixels in the viewport.
> 
> That disconnect makes responsive typography unreliable. If your text is set to resize based only on a viewport or container, then the user zoom will have no effect! Similarly, neither 1vw nor 100vw accounts for the user default font-size.
>
> —[Stephan Schwab](https://web.dev/articles/baseline-in-action-fluid-type?hl=en)

This [whole video from Oddbird](https://www.youtube.com/watch?v=B-r6wembUxI) was worth watching to see Miriam work through the reasoning. In addition to giving me much to think about in terms of writing good css for website visitors to have good experiences, I'm left wondering if it is possible for AI to have this sort of wondering. Can an LLM ask "hmm, I wonder how this approach to font sizing actually impacts with user preferences and zoom?"