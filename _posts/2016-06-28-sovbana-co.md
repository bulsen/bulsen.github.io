---
layout: post
title: sovbana.co
tags: [ml]
---

turkish is a very rich language if you want to curse. there are thousands of thousands cursing styles and too many bad words.

by the time we were adding the chatting interface to duvartv. we came across a problem in our project; how do we can censor the turkish bad words?

first i tried to write them down, but there was a vastly amount of bad words that i didn't know. then asked my friends for help on this job. eventually we all blocked somehow.

at last! i wrote a little cursing platform and published online under [`sovbana.co`](http://sovbana.co). it is so simple; when you send your cursing to our server it taunts you back with another person's cursing. this is data collection part, because there is no lex for turkish bad words.

also sovbana finds if there is a bad word in the sentence you given. sovbana detects the badwords by learning sentences, abstracting bad words and predicting the cursing templates. these allow us to detect obfuscated badwords too. so that was prediction phase.

at the end of the day sovbana still is another flask project powered by mongo. also querries still be sanitized, no nosqli!(__i_hope__)

if you want to curse in turkish, go [`sovbana.co`](http://sovbana.co)