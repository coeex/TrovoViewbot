# TrovoViewbot

## No time nor interest in updating, making cookie monster or this repo. 

If you wish to use the bot fix it yourself, don't ask me stupid questions on how to start it or how to use it. GitHub is a platform for programmers. If you don't know how to program gtfo


## Cookie note

Cookies might be banned, signed out of or just dead. Try them out if you want but I suggest making your own with cookie monster. 
~[https://github.com/IgrutinovicL/Cookie-monster](https://github.com/IgrutinovicL/Cookie-monster)~ 

~New and improved cookie monster will be available soon~ 

## UPDATE

PRIVATE PROXIES FROM 99% OF PROXY PROVIDERS ARE BANNED, DETECTED ON TROVO, TWITCH, YT. 
If you want to use this bot be prepared to drop at least $1k on residential proxies.

Before starting the bot please download all the required libraries. ( pip install -r requirements.txt )


## How to use?
1. Get some cookies with Cookie-monster
2. Before starting the bot place the cookies in the active_cookies directory
3. ~Check current chrome version. ( About chrome )~
4. ~Download selenium version that your chrome supports~
5. ~Place that .exe file you got into the root directory of the script. ( Where bot.py is)~
6. Be sure to have at least one working proxy in proxies.txt file.
7. Start the bot and enter the setup mode.
8. Do not choose more bots than the number of cookies you have.
9. Answer the questions in the setup.
10. After that select start when starting the bot.



What has been detected:

  - Selenium
  - Headless mode
  - Cheap proxies (webshare,proxyscrape etc)
  - Accounts without a real email(gmail,icloud,hotmail...) + no phone number.

New ways to circumvent bot security:
  
  - Undetected chromedriver
  - DO NOT USE HEADLESS MODE ( It does not prevent DNS leaks and other stuff that will easily ban your accounts or not show legit watch time)
  - Residental proxies or virgin scraping proxies
  - Using the SAME proxies for the same account
  - Create accounts with a GMail or an iCloud account
  - Add a phone number to the account
  - Do not follow and watch only one person
  - Add additional ways to enter trovo.live
  - If you see RECaptcha just change the proxy, it is dead.


# How do bots function?

## Proxy

They usually use a proxy to connect to a network. If the programmer has access to residental proxies without a bandwith limit that would be the best choice since that is undetected! Of course I will not share providers here nor will I answer on how to find one.

## Types of bots

In my example I use Selenium to controll the web browser. Remember that programmers are really clever and they can use a wide range of tools like:

- Making a bot with a google extension.
- Making a bot with a custom driver. 
- Making a bot with Selenium
- Making a bot with a python(client) and extension(server)

And of course much more but this is not a tutorial on how to make a viewbot, rather an insight on how they work.

## Navigating to the target website

Okay so now the bot is controlled by a program.

The bot will navigate to the target website. If the programmer is clever they will add variations on how they get to the website. They could do so with a google search, direct link, a referal link and so on...

Why not just visit via link? Because if you want to make the traffic look legit you need to diversify.

After getting to the website they need to log in into an account.

In my case I have chosen to use a cookie inject method:

## How does cookie injection work??

- You log in into the website with an account.
- You then download the cookie.
- After that you tell your bot to load the cookie and viola! You are logged in without typing the password/username everytime.

But is that not detectable more?

On the contrary! The user is expected to log in once and then when they visit the website they will have the cookie. It is suspicious if you log in every time.

## Visiting the channel

To visit the streamer the bot will do it randomly.

It will sometimes:

- Enter via a link
- Enter via a search
- Enter via a follower tab
- Enter via a referral link

## The final steps

Now the bot will visit the streamer and watch their video. Now I have added random events that fire randomly (duh...). 

The bot will do a random thing based on a random timer. 

it can:

- Send mana
- Send a follow
- Send a message
- Go watch another channel then come back
- Click chat settings

And so much more can be made.

## The end

Okay now you understand how bots work and the best way to fight them is:

- Know the proxy providers ip's
- Closely monitor the activities of accounts. (If an account only watches one streamer there is something fishy there...)
- Detect webdrivers
etc... etc...
