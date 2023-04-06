----
marp: true
theme: uncover
----
<style>
    :root {
        --color-background: #FFE4E2;
        --color-foreground: #EF6269;
    }
</style>

<!-- ### :steam_locomotive: Welcome :steam_locomotive: -->
# **Ruby on Rails** 
![w:300](https://raw.githubusercontent.com/rubyaustralia/roro/master/rorosyd-logo.png)
## **_Oceania_**
11th April 2023

<!-- 
Welcome to RoRo Syd.
Thank you all for coming, I'm David and I'll be your host for this evening. -->

---

# **Tonight** 
### *Talks*
### *Events / Tips / Jobs*
### *Pub/~~Gelato~~*

<!-- ^
Again tonight we have a great lineup of speakers, we'll cover some upcoming events, tips, tricks and jobs opportunities.<br />
Then it's off to the pub ~~or gelato~~ to continue the conversation. -->

---

# **Housekeeping**
 **Bathrooms**
 **Emergency Exits**
 **Hot food**
 **Glass bottles**

<!-- ^
- Location of bathrooms
- Location of exits in an emergency
- Feel free to take any leftover food home with you
- Once you've finished your food and drinks, please be sure to put your plates and bottles in the bins provided.
- Please recycle all bottles in the tubs -->

---

# **Code Of Conduct**
### *ruby.org.au/code-of-conduct*
### *ruby.org.au/committee-members*
conduct@ruby.org.au

<!-- ^
If this is your first RORO, or if you were previously unaware, Ruby Australia events are run under a code of conduct.<br />
This is the link where you can find it and have a read, but in summary we want this meetup to provide a friendly and welcoming environment for everyone who attends, and harassment of any kind is not tolerated.<br />
If you have any issues you want to raise about anything that has happened at a RORO, you can talk to any of the organisers who are Me, Dan and Yasmin, or you can go straight to a Ruby Australia committee member if you don't think you can reach out to a RORO organiser.<br /> -->

---

# **Thanks** **_to our_**
# **Sponsors**

<!-- ^
RORO has many sponsors, without which these meetups would not be possible.
With the new year we've had a change up sponsors. -->
---

# **Drink & Venue Sponsor**
![w:600 h:400](https://mablestaging.wpenginepowered.com/wp-content/uploads/2020/10/mable-logo-white.svg)

<!-- Mable are on a mission to improve access to affordable, flexible, quality support and care for Australians everywhere -->

---

# **Community Sponsor**
![w:300 h:300](https://www.dropbox.com/s/cxq6w0jx76jyc3x/ruby-au-logo.png?dl=1)

<!-- The bill for our meetup gets sent to Ruby Australia, who organises the sponsorship for all Ruby-related meet-ups around Australia.<br /> Their sponsors are our community sponsors, so we would like to thank... --> -->

---

# **Community Sponsor**
![inline](https://www.dropbox.com/s/hzw69l2uen1k2rn/assembly-four-logo.png?dl=1)

<!-- Assembly Four is a collective of sex workers and technologists founded in Naarm/Melbourne. They build technology-oriented solutions as well as actively engage in policy development that not only helps sex workers survive, but thrive. -->

---

# **Community Sponsor**
![inline](https://www.dropbox.com/s/wu8oicdlxs3kwuq/culture-amp-logo-2.png?dl=1)

<!-- ^ -->
<!-- Culture Amp’s mission is to create a better world of work. They are the global leader for employee experience and their platform helps the world’s most innovative organisations put their culture first. -->

---

# **Community Sponsor**
![inline](https://bpsoftware.net/wp-content/uploads/2019/09/HotDoc-Logo.png)

<!-- HotDoc is Australia’s largest patient engagement platform with over 8 million app downloads in Australia. Our mission is to enable the best health care experience for everyone in Australia by working directly with medical professionals. -->

---

# **Community Sponsor**
![inline](https://www.dropbox.com/s/b6t5p5l0phosti0/buildkite-logo.png?dl=1)

<!-- Buildkite is a platform for running fast, secure, and scalable continuous integration pipelines on your own infrastructure. -->

---

# How's the food?

![w:400](https://c.tenor.com/X3ILIJoDKX0AAAAC/twitch-chewing.gif)

<!-- Show of hands if this is better than pizza
Show of hands who's had something to eat (trying to figure out if we've order too much or too little) -->

---
# Intermission 🍿

<!-- ^
We're just going to take a quick break while we get the first speaker set, grab a drink, some more food and I'll see you back in 5ish minutes -->

---

![bg left](https://res.cloudinary.com/leesheppard/image/upload/c_scale,h_250,w_250/v1679958092/photos/lee_sheppard_profile.jpg)

## **Biohacking the developer**
*Programming on the right side of the brain, hacking our minds to increase performance and be more productive*
**_Lee Sheppard_**

<!-- ^ -->
<!-- Lee will be teaching us about programming on the right side of the brain, hacking our minds to increase performance and be more productive. -->

---

![bg left](https://lh3.googleusercontent.com/vM6gSWCFZRAtuDpR3N9ASVXpFQl2ra354LnwZV1lLu8mARskM87lVpLN9zMS7EdMtKHalUxIfwC9Ga91JIpRyqeZYaZNsvLzHUknFuFOnUg-HoRuvNqPeRJkhj4rSuDqd7AlaLoAYjFUx9mPnpMy2t9xSOpgjVab-3xCe-5K0bqR2SpXTaXOFR1SZYDxyrYpGPyxP3i9bwUFcgcZW281rMVLgRBVGUEe7TsetqR20YVJy_L8vWCLVCe0kldeySxA87lqjMbMmREC61Db3nvtEHTOMVNybYhBmAFxikQsPeprz_dmyCr79sFUJ60c8KawocDALizRpkA-psLjmmudFX6NZsdg9zqaQZ-yFm-iOtbzCu33yMx4jZRM__fFG6mWZxcDuoq4dUcVNvJgHI6E-ADq7OP-rJzN05rs4DFXn4t_0ZFgc27MHXs5d1Z9cOSyIGmKTw6pQGqbE6PYZmtsrNcgRHNyBKakOTLGyBwA6v1jABRPpuE1cyUGX8sOsoLUUctgjDlYdYWitDIp4AF5XYVAK5o2HDZMp8DN347dgVKM9YUJxmCksBMbKBubOOUZYb9bshIbnnQ95GQ0ntzWyY-pI4pvFWeztX4wtYMOThXVk4FP-LJM6ZA0lUoVIYErWNQxjlenKdSG1gn0MnlOQ2C6fbD3ddhLtbYo4KSIH3PhbMc7BzKYcEWe2PJ0ATdlzT9-heVGuHtrvtCvUil1-umQ7g640Nrp72E_zeIHf39zDkIVuVyUrOHvEOyhwkBWO6DZQIDrfYBZ70PUlrVAttXlcYA2Ts2OzzMvcHusDxwvVjjO-FUFSBwGpbj12yr-VvcNrVC0Xd0BYwBXEuZF49lGKdVLZ6CaKPwBV87u4EGD8k49cwlY2U0PSZDYxj8VEDFB6MKjZMscZzs7HqNyWYlvuKu9g2Rr_A5ZkefnQenIKRxeB5BFvEk5eHwPL8qM69Qo_kJpNOZ-rMryRTqz6Q=w889-h966-s-no?authuser=0)

## **Railway Oriented Programming**
*Patterns of functional programming paradigm*
**_Arpan Lepcha_**

<!-- ^
Arpan will be Introducing functional programming paradigm in ruby using Railway Oriented Programming and Monads. Examples through the usage of Deterministic Gem. -->

---

![bg left](https://lh3.googleusercontent.com/9nAnYAxRZD996KAOGaEM7MfJ8zcvUtO6eG2pith9Rv2zt26ZnpwtlIE98MLls_63AHOArsL7Iv8LntX9X9tui7ENhXPLJAs-xaEKTiAo-3yCuQzI_ZVPUjVjIOQkgg3wuivEfZmwwgZyr9_6ChKRqrVlJa9rJgAiAT0H4NO0LC1M6RC_uo3rSBe87BC3g3hTlQDILmheHES7rahtsjqikJRw4Dt_C81E4opNWgXCQ7kqMNOQK48mtQTTKpMHFlIM5AwSwpj1RomNG6qHJTK4M9cJqU4leEY_Hw-Whg7gcJBCSIYtZRiH5abiFYPMrZV3dAjHShPIrmWbL4C5iD2ss4MHkwYPs2f4OadBWIriwksIhJyL2rjrp5cPL0qMwVvkRbz_ojRy2E1H6XOzKei07rhwPam_oLvSLV3_72M3pyjDe_zTy9xDVsoTkQhqOKoEfW3WOvvkuhLa-ANeFS9Y4tMPHQKex7a9E949NXBFJ07Mh4Piwr9q_D637qvE2NANj3HqOAfv6em1cDnAVD3ZgPY2BQGLQl6lUFHa4Tv2h7X-cwYV_TCoRz4eku64oTwhGPW1fvsiac0608JPEq6mb6lQ8eL2-B1QsgQLa6KB6JawjbsxJrarW9tf2878IVoyZSsmycd0Nf3yXAPQ0SXK1-7XqDqPmWTTUMADKcoaCgeJJWWoh6WflUdUM8hHzqT9dRBwxzM1nWEP9kaGTfjgLOM8kWg1JAw8rstLuro8-NIv5FPyzp4pL3j-RGJpVERgLnbhraPxHiljDjilgKzOsi_WEnBOwOli0kjz57Mq6nQ3QPwoEr5zi4k2zmKs0nuKPYz99durYI5GoyccYpMEa-LzVHmGrs6ptR41iTfescx8HudCA-xHL_GiPKYR_iS9VP3TpJOdqNYj9uI3vpYT6P-DLEEgNAPKuUWyAP7tQ3WWr0UdnVcqp49MchgDTI1pEDH3YU2_hGMFxwitGRqZGw=w262-h301-no?authuser=0)

## **Our Exorcism Challenge:**
### *Luhn*
**_Paul Fioravanti_**

<!-- ^
Paul will be covering the exercism challenge
 -->
---

![w:300 h:300](https://www.dropbox.com/s/6lcxixt3dtsiw3g/Twitter_logo_bird_transparent_png.png?dl=1)


# **_`@rorosyd`_**


<!-- ^
If you're Twitter-inclined please let tonight's speakers know how much you appreciate the work they put in by tweeting about it. Giving feedback definitely makes the speakers feel their efforts have made an impact beyond building their own presentation portfolio. Don't forget to mention rorosyd to tie the night altogether. -->

---

# *Next Meetup's* Exercism
<!-- # </br> -->
### **_Luhn Algorithm_**
<!-- # </br> -->
##  *`exercism.io`*

<!-- ^
The exercism challenge for next month is the Luhn Algorithm. -->

---


### The Luhn Algorithm
Given a number
`4539 3195 0343 6467` - Valid

`8273 1232 7352 0569` - Invalid

<!-- ^
The Luhn algorithm is a simple checksum formula used to validate if a given number is valid or not.
Most will be familiar with this but probably didn't know your name, it's how a credit card form can tell you if you've typed an incorrect credit card number without submitting anything to a payment provider -->

---

# **Thank you!**
<!-- 
Thanks so much to all the speakers tonight, and if anyone is interested in giving a talk at a future RORO... -->

---

# *We are always looking for*
# **SPEAKERS!**

<!-- ^
We are looking for speakers!
- We'd like to encourage anyone that's been sitting on the fence about speaking to look at submitting an issue for February's meetup
- There is nothing to lose and everything to gain from sharing ideas with your fellow rubyist.
- Any talk you present here is great fodder for your resume and portfolio, and just by virtue of presenting, everyone will think you're an expert, which will surely lead to at least an endorsement on LinkedIn<br />
- So if you've got something to say, or to show and tell, that you think the Ruby community would love to hear about... -->

---


# **Where do I sign up?**

- :globe_with_meridians: *`github.com/rubyaustralia/roro/issues`*
- *:email: `rorosydmeetup@gmail.com`*


![w:250](https://www.dropbox.com/s/p5wqhng4andc4ne/qr-code-2020-02.png?dl=1)

<!-- ^
- Open up an issue at the RORO Github repo and tell us about the talk you want to submit, or feel free to message any of the organisers.<br />
- The repo has presentation requests added, so check them out if you're looking for an idea to do a talk about.
- Remember, It is *good* to throw yourself out of your comfort zone and try
something different, and who knows, you might even end up liking it and wanting
to do more.<br />
- Also, if you need any help creating or critiquing your presentation or want someone to do a dry run, then please feel free to approach any of the RORO organisers and we're happy to help you in any way we can to make you look awesome up on stage. -->

---

# **JOBS**
# *Offering work?*

<!-- Offering: say your name, your company name, a sentence on what you do. And a sentence on who you're looking for - juniors, mids, seniors etc -->

---

# *We are always looking for*
# **VENUES!**

<!-- ^
While Mable have been very generous we don't want to overstay our welcome so if you're interested in hosting the ROROSyd meetup in the future I would love to hear from you. -->



<!-- # **NEWS**


# Rails 7.1 introduces async queries

- `ActiveRecord::Relation#load_async`:

Schedules a query in a background thread pool, allowing us to do stuff like Post.where(published: true).load_async.

^
- This new feature builds on an earlier feature from rails 7.  -->


<!-- 
# Rails 7.1 simplifies environment checks
- a new `local?` method was added

^
Environment checks simplified! 

---

# **Tips and Tricks**
# __*Stuff that makes your life*__
# _easier/better/faster_ -->

<!-- [Anything speakers want to add...?] -->

---

# **Slack/Forum**
 *- `ruby.org.au/slack` #rorosyd*
 *- `forum.ruby.org.au`*


---


# *Next Meetup*
# 8 May 2023
# **_\(2nd Tues of the month\)_**
# *at* Mable

<!-- ROROSyd will be back next month on the 14th of April. -->

---

# **And Now...**
# *Pub* :beer:
# ~~*Gelato* :ice_cream:~~

<!-- Please make sure to clean up after yourself and put your plates in the rubbish bins and empty bottles in the recycling bins. Thanks for coming along and we hope to see you next month! -->