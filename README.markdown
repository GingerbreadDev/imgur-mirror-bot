# imgur-mirror-bot
http://www.reddit.com/user/imgur-mirror-bot

## Changelog
* *Feb 24th/25th* - The bot now attempts to mirror images to both Minus.com and Imgur.com
* *Feb 24th* - Tweaked upload page links to prevent RES from transforming them into direct links.

## What?
imgur-mirror-bot is a simple little bot that scans new reddit
submissions for image links, and provides a mirror to those
images as a comment in the original post.

## Why?
1. **Redundancy** - Traffic gained from getting featured on
reddit is often enough to bring a website to its knees. imgur-mirror-bot
makes sure you never miss out on that picture of the cute cat with
a tortilla on its head.

2. **Choice** - A lot of redditors do their redditing from their jobs or schools - 
these will often block common image hosts, websites like facebook or
tumblr (from which images are commonly linked), etc. imgur-mirror-bot
provides an alternative to these users.

## Isn't this against the rules?
No, imgur-mirror-bot uses the Reddit open API, and abides by its rules - all operations
have a delay between 3 and 6 seconds - I'd hate to be responsible for more downtime.

You can learn more about the reddit API [here](https://github.com/reddit/reddit/wiki/API)

The bot only runs on major subreddits with frequent image submissions, or where requested
by moderators & users.

## FAQ

**Q.** - Your "Upload Page" and "Direct Link" links both point to the same thing.  

**A.** - If you have RES (Reddit Enhancement Suite) enabled with the inline image viewer, it
will intelligently transform imgur.com page links to direct image links. 
*Update: worked around this issue by appending upload page links with a hash portion*

-----

**Q.** - I posted an image link, but the bot didn't mirror it!  
  
**A.** - imgur-mirror-bot will only mirror images if some conditions are met: The image is not already on imgur.com,
the link has a positive score above a certain value, and has at least one other comment.

These conditions are subject to change as the bot is refined.

## Tell me more
You're free to contact me by messaging the bot: [Compose a Message](http://reddit.com/message/compose?to=imgur-mirror-bot)