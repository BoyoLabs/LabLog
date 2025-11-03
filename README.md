# DevBlog
Dev log? Dev blog? Whatever. This is where I post a blog of sorts.

---

__*11/3/25*__

## Need Instructive Losses

I have been thinking about my chess data CDL framework (found here: https://github.com/BoyoLabs/ChessData ) and I have realized that in bullet, there aren't very many instructive losses -- or rather that there is plenty to learn from analyzing your wins because theres still so much that you did wrong in bullet, but losses are just immediate punishments of those problems. You learn less because its the same problems as in wins, but with literally less data. That doesn't make them unimportant for a CDL framework however. As those datapoints will be useful for the LLM to notice how quickly they get punished. My focus for that CDL is to try to incorperate more losses. Not because there is more data (in fact theres less) but because I want to teach the LLM that these losses can be quickly punished. I need to find some good ones though to add so it can really tell whats going on.

---

__*11/2/25*__

## dev blog idea / catching up to now

Lately, I have been incredibly busy. Studying chess and working with our chickens, yard work and house work. Living in the country is a ton of work. However, I have had some time to test out both Lexl (an LLM enhancement tool, found here: https://github.com/BoyoLabs/Lexl ) as well as my first pet project in the foray into meta programming with prompt and context engineering in the form of what I like to call Contextual Data Logic (CDE) frameworks -- chessData (found here: 
https://github.com/BoyoLabs/ChessData )

I have completely given up on the IDE for CDE, promptForge. Its a neat idea, but really, CDE is just a modified markdown language and other IDEs far better work just fine. My goal isn't to build an IDE after all.

However, I have been working on a tool that gets AI to generate the CDE code! It isn't perfect, and it's not supposed to be. It only generates a starting point so I (or the user) doesn't need to make everything themselves. I still need to add the data set (if one is required) and I can always add specific functions and conditionals.

I am particularly interested in this method of programming because I went to school for philosophy and have a love for formal logic on top of other educational background (AI prompt engineering cert from vanderbilt, and IT Support Professional Certificate from google) and my professional background (teaching computer science k-12 and now working an internal IT role for a company.) I have always had an interest in programming -- particularly web development with an emphasis on javascript and later taught python as the preferred educational language. It seems this meta-programming with CDE has sort of merged all my skills together. This is why I think I enjoy it so much.

So, without much further catching up, why am I making a dev blog? Well, I want to! Do I really need a further reason? However, if you must know, I really enjoy being involved. And I am not always working directly on my projects. This is a good way for me to blow off steam and not be working on my projects while remaining involved. I wont promise how often I will post a dev blog, but as my work continues -- some of it in the background with no commits -- I can remind myself of what I have been doing and remind myself that I am making progress, even if it doesn't look like it.

On a final note for todays entry, I am considering uploading all of my tech projects here. By this, I mean that even 3d print projects may find their way here. I would like to use github as a sort of social media for my tech world and work. I have never actually gone through with that sort of thing on here before. So, it might be fun, who knows.

Okay, anyways, thats enough shouting into the void for one session.

distro: MX Linux

Okay bye.
