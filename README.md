
## ###################################################################################
##  Discord - Revolutionizing Daily Communication through Artificial Intelligence   ##
## Case Study by Brandon Welsh                                                      ##
## 10/28/2023                                                                       ##
## ###################################################################################

## Overview and Origin
Discord is a casual social messaging platform popular with, and specifically directed towards, gamers and students. Discord Inc was formally ‘incorporated’ on May 13th, 2015. In reality, this is the date that the creators recognize as when random people really started using it (Pierce, 2020). The online communication service has celebrated this date as their "birthday" every year ever since.

Co-founded by Stan Vishnevskiy and Jason Citron, the idea for the creation of Discord dates back to the early 2010s. Jason was a game developer at the time, and had released a mobile game called Fates Forever. The game did not attract much commercial success, but Jason noted that the game's communication feature was widely considered to be better than the game itself. In terms of online gaming communication services, the current market leaders at the time were Skype and TeamSpeak. Both were regarded as being complex, not very user friendly, unreliable, slow, and CPU resource hogs. However, these services represented a legal monopoly in gaming communication, as they were more or less the only option people had for over a decade. With that in mind, Jason Citron and his childhood friend Stan Vishnevskiy set out to create an online gaming communication service using Jason's baseline he created for Fates Forever. The project launched in May 2015 and quickly grew to become one of the most recognizable and widely used communication services in the world, targeted at the gaming demographic (Pierce, 2020).

In the past year or so, Discord has attempted to break into the growing Artificial Intelligence field by experimenting with a true AI chatbot they have named "Clyde" Clyde runs on OpenAI's GPT 3.5 framework, but discord has been modifying the model to encourage it to produce friendly, human-like responses that are playful and quippy. They are also encouraging the model to learn from its conversations with users and alter its behavior to match (Buffy, 2023). The resulting chatbot, Clyde, is a stark contrast to OpenAI's default, cold, calculated ChatGPT, which must be specifically instructed by a user to change the style of responses to queries. Clyde will be explored further on in this case study.

Discord is a free online communication platform, and they do not run ads. It is funded primarily from user's subscriptions to Discord Nitro, a paid monthly premium service which, according to their website, unlocks in-app features such as animated profile pictures, animated emojis, the ability to use custom emojis anywhere, HD video streaming, and larger file upload limits. I personally think Discord Nitro is a waste of money, but apparently that sentiment is not widely shared because they are doing just fine without my subscription:
    According to Sacra, a private markets research database, Discord’s revenue in 2022 was a staggering $455 million. They received approximately $1 billion in funding in 2022 and the company as a whole was valued at over $15.2 billion. Discord also enjoyed a whopping 44% y/y revenue growth rate from 2021 (Sacra, 2022).

## Business Activities (including Discord's entry to the AI field)
Discord’s original aim was to provide a casual online communication service that was more user friendly than the current market leaders, Skype and Teamspeak. Discord advertises itself as a casual communication service for friends and gamers rather than business professionals or working adults. It is used primarily by gamers who create their own communities, or “servers” to host chat rooms and conversations, usually on a specific topic. According to their official website and confirmed by Statista, Discord is used by 150 million monthly active users across 19 million active chat servers. Discord's greatest strength comes from offering an intuitive, user-friendly UI experience not shared by other services at the time of their release. TeamSpeak offered (and continues to offer) a higher quality voice call experience, but discord came in with many more features such as screen sharing, live streaming, and video chat.

Recent developments in artificial intelligence has led Discord to become interested in creating an AI chatbot that sounds more friendly and human than ones which already exist. The ultimate goal is to have a chatbot which sounds like an ordinary member of a given server or community, and is always there to chat when someone needs them to, but feels more personable, relevant, and likable than a soulless chatbot. This has led to the development of Clyde. 
Running on GPT 3.5, Clyde is set apart from other AI chatbots by being fully integrated with discord's features. Clyde is able to send not just witty, human-like messages, but relevant emojis and humorous gifs of its own choosing. Clyde is also able to read user profiles and make comments on people's bios, their status, even their custom usernames. Additionally, Clyde is able to read and analyze the messages in a channel or server, and tune its responses so that they are relevant and interesting (Buffy, 2023).

Anecdotally speaking, I have been granted beta access to Clyde in several of my discord servers. I have noticed that the AI’s behavior differs depending on the theme of a server. For instance, Clyde A in my college friend group is exposed to technical language, chemical engineering discussions, and frequently answers programming queries. As such, Clyde A’s normal manner of speech is very analytical and it will frequently reference advanced topics from earlier discussions even when given a simpler prompt. Meanwhile, Clyde B is on a server full of my gaming friends. We all play an obscure, irrelevant space game called Elite Dangerous, and the server is dedicated as comms, coordination, and opsec for an in-game squadron. Shortly after Clyde B was added to that server, somebody asked what it's favorite video game was. Without missing a beat, Clyde B responded with “Elite Dangerous”, despite the fact that it was not directly involved in any past conversations about the game. Elite is far too obscure for this to have happened by chance. Most notably, however, Clyde B began to pick up Elite Dangerous lingo. Remarkably, it started referring to server members, completely unprompted, as “CMDR” (commander), and saluting people with the “o7” emoji, both of which are culturally unique to the Elite Dangerous gaming community. It appears that Clyde is designed to read all of the content in a given server and uses it as training data alongside the actual OpenAI data it was trained on, which it still has access to in order to fill gaps in its knowledge and attempt to understand jokes, references, and cultural norms.

    Besides utilizing OpenAI’s GPT 3.5 for the development of Clyde, there are numerous technologies, including AI/ML innovations, at work under the hood to make Discord function the way it does. Luckily, discord is staffed almost entirely by geeks, so their engineering blog is hugely detailed. Some of the technology they utilize daily to develop discord include:

        - Elixir: much of Discord's chat infrastructure is written using Elixir, which allows for huge scalability as discord grows to hundreds of millions of users (Vishnevskiy, 2017).
        - ExUnit/Mock: a testing library within Elixir. ExUnit comes with Mock, a feature which is hugely useful for testing new code before pushing it to live servers (Nowack, 2021).
        - ScyllaDB: powers the NoSQL database clusters used by Discord to handle hundreds of terabytes of user data in real time (Oakley, 2022).
        - Machine Learning: Discord utilizes both supervised and unsupervised machine learning to create predictive data models. As stated in their engineering blog, "These models leverage state-of-the-art technology to balance performance and interpretability, providing insights, guiding strategy, and powering downstream analytics and modeling. Feature engineering often gets complicated due to the nonlinear (and long-tail) behaviors of our users! Recent ML projects include constructing a suite of calibrated models to understand the long-term value of subscribers as well as forecasting Discord’s growth for years to come" (Cossio, 2022).
        - Google BigQuery: allows Discord to clean and transform raw data from their 30+ petabyte data warehouse. This data helps them to better understand their communities, identify harmful servers, make informed strategy decisions, and even train and maintain their machine learning models as mentioned above (Meas, 2021).

## Landscape
Discord is in the field of Daily Life, specifically serving as a casual online communication platform. Discord's two main competitors are Skype and TeamSpeak.

Skype - Launched in 2003, Skype’s main draw was live video calls, somewhat of a novelty at the time, but one which could be achieved by anyone with a webcam, a microphone, and Skype on their computer. However, Skype has since been all but buried by many other programs and technologies, especially Discord and smartphones.

TeamSpeak - Launched in 2002, TeamSpeak was largely focused on pure voice communication. Boasting excellent quality due to high audio bitrate (and higher than even Discord offers today), TeamSpeak became the preferred gaming communication service by the mid-2000s, but falling out of favor in the mid-2010s as Discord rose to the forefront. However, TeamSpeak is still widely used in official Esports tournaments (TeamSpeak official site).

Online communication has become increasingly important in the wake of the Covid-19 pandemic, with many companies and schools moving to online work or instruction. This has forced many online communication platforms to become more intuitive and user-friendly. This trend is likely to continue as interconnectivity, communication, and online data sharing is becoming as important as electricity. And as technology continues to improve, the cost of connectivity is far lower today than it was even just 10 years ago. A very recent innovation is the advent of AI-powered chatbots. It remains to be seen just how advanced these chatbots will become, but the addition of Clyde (and the lengthy beta testing period it has been in) is an indication that Discord is attempting to get in on the ground floor.

## Results
Discord has been somewhat of a trendsetter for online gaming communication platforms. One of the most widely-used services for gaming communication before discord's arrival was TeamSpeak, a service launched in 2002 and receiving very little facelift updates for over a decade following. When discord launched with their user-friendly UI, easily accessible server layout, and individual chat channels, TeamSpeak and Skype scrambled to keep up. The former (TeamSpeak) changed the look of their flagship software to more closely resemble discord's UI. These changes are featured prominently on their website in an almost exasperating attempt to attract new users as well as the ones they lost to Discord. The latter (Skype), having previously been purchased by Microsoft, was already in decline as many other social media platforms adopted video conferencing, and smartphones with front-facing cameras took over the casual side of video conferencing (Bright, 2011).

Companies in this field measure success simply by the number of users they have. Skype is in the lead with 300 million monthly active users (Campbell, 2023). It is followed by Discord, which, according to their website, has 150 million monthly active users. Finally, bringing up the rear is TeamSpeak. This information is not public and can only be estimated by using live data from the Teamspeak 3 Statistics site, which shows approximately 300,000 users at peak in the past 24 hours, with most of the traffic coming from Germany, Poland, and Russia.

Another, perhaps less scientifically sound measure for success of these companies is to simply ask a gamer what service they prefer. And as luck would have it, the author of this report is an avid gamer. From my experience, I can safely say that Discord is the market leader when it comes to gaming communication. TeamSpeak used to be extremely popular but has since dropped almost completely off the radar due to the sheer number of extra features that Discord has to offer. In fact, I was surprised to find they even still exist while doing research for this report, and was even more surprised to find that they have attempted to mimic Discord’s look (apparently to little success). Skype meanwhile is almost never used for gaming anymore, and it surprises me that their monthly active users still appear to be so high. I presume this is due to their acquisition by Microsoft and inclusion as pre-installed software on all Windows machines, as well as their shifted focus towards professional online communication, especially in the wake of the Covid-19 pandemic. 

## Recommendations
Following the research performed in this case study, I have come to the conclusion that Discord should attempt to expand further into the AI chatbot market. They have an excellent baseline with Clyde, but it runs on the relatively outdated GPT 3.5. In much the same way that Discord became a trendsetter for online gaming communication, following this route would allow Discord to tap into a currently unexplored market: that of personal AI chat companions. At the very least, Discord should sample GPT 4.0, a model with far higher parameter count than GPT 3.5, and see what Clyde is able to do with it (Guinness, 2023).

Judging by the scale of their engineering blog and the number of talented programmers working for them, Discord could probably afford to create and train their own AI models, and do away with the third-party OpenAI models for Clyde. They certainly have the sheer capital required to fund this project, with revenue approaching half a billion dollars last year as stated earlier in this case study. And this investment could even turn a profit for Discord! They could also allow users to pay to access these premium, advanced chatbots, while letting the old ones remain free to use. This closely matches the premium subscription model they already offer for their platform, and thus would be very easy to implement.

Generative Pre-trained Transformers such as chatGPT are excellent at creating chatbots like the one Discord should be pursuing. These are Large Language Models, which means they are trained on data sets of vast quantities of human-generated content (Guinness, 2023). And as previously mentioned, Discord has 30+ petabytes of user data just sitting around in their data warehouses. If they decided to make their own GPT model, they certainly would have no issue collecting human-generated text to train their models. 

It is important to note that this case study is by no means all-encompassing. If I had more time, I would have done a deeper dive into how people are currently using Clyde or similar chatbots. For future research, I would suggest a case study to include a survey of Discord users who have access to Clyde, and try to get their opinions on how they use it in daily life and how it could be improved. It is also important to research and understand the ethical implications of using private user conversations to train chatbots. I would have also liked to get more detailed information on monthly active users for Discord, Skype, and TeamSpeak, and shown it over a long period of time, but unfortunately, this data is very difficult to find.

## Citations

(Discord Official Site)
https://discord.com/company

(TeamSpeak official site)
https://teamspeak.com/en/more/company/

(Skype official site)
https://www.skype.com/en/about/

(Bright, 2011)
https://www.wired.com/2011/05/microsoft-buys-skype-2/

(Pierce, 2020)
https://www.protocol.com/discord

(Buffy, 2023)
https://support.discord.com/hc/en-us/articles/13066317497239-Clyde-Discord-s-AI-Chatbot

(Oakley, 2022)
https://discord.com/blog/how-discord-supercharges-network-disks-for-extreme-low-latency

(Cossio, 2022)
https://discord.com/blog/how-data-science-informs-strategy-innovation-at-discord

(Meas, 2021)
https://discord.com/blog/how-discord-creates-insights-from-trillions-of-data-points

(Nowack, 2021)
https://discord.com/blog/why-and-how-discord-uses-patch-to-test-elixir

(Vishnevskiy, 2017)
https://discord.com/blog/how-discord-scaled-elixir-to-5-000-000-concurrent-users

(Guinness, 2023)
https://zapier.com/blog/how-does-chatgpt-work/

(Statista)
https://www.statista.com/topics/9816/discord/#topicOverview

(Campbell, 2023)
https://thesmallbusinessblog.net/skype-users/

(Teamspeak 3 Statistics)
https://www.tsviewer.com/index.php?page=teamspeak_statistics&newlanguage=en

(Sacra, 2022)
https://sacra.com/c/discord/
