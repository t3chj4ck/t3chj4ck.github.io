---
title: 'The Tyranny of “More”'
date: 2026-08-20
draft: false
---

## experience 
Theres one thing that's been bothering me for a long time:  
i've been using archlinux + hyprland for almost a year,  
and i still dont feel like i truly *know* linux...  
**I've spent almost hundred hours with AI, to configure everthing agaign and again and again**.  
while others already get their job done one hundred times.  

at first i was using archlinux, 40% was for study linux, and 60% was to make me look like a "hacker".  
well, who doesn't wanna say "i use arch btw"? its every kid's dream.  
and in the commiunity, some **Ideology** will really drown your mind,  
in the end, to become a "larper" seems to be unavoidble.  

its the same thing when i am doomscrolling on tiktok,  
i lost my focus while getting infomation flooded,  
especailly bad for people who have ADHD issues,  

## Knowing what you want
“Reason is, and ought only to be the slave of the passions, and can never pretend to any other office than to serve and obey them.”  
human needs desire to live on, like any Mammals would want to eat, to sleep.  
but it'll become a problem when it is impossible to be filled.  

a girl wants to be "the prettiest"  
but pretty was just an idea, theres no way to compare who or what is prettier  

chinese people are always aguring about "what type of kungfu is the strongest?"    
the agruing can last more than decades ,because theres simply no anwser to it    
technique was just tool after all,      
its like comparing c to rust, or python, or anyother language   
or japanese vs english.  
you know if you know.  


The ultimate question is: what do you actually want to do?  
like the acually acual  
If your goal is just ricing, exploring, and having fun—go for it. No judgment.  
But if you fall into the trap of thinking:  
"I configure my WM perfectly, so I know everything"  
then you are chasing a ghost. That's the larper culture.  
Sharpening the axe does not delay the woodcutting.  
but theres no way you will be really "ready" for work  
you can always add more keybind, more script for your tools  
in my oppion, such an idea was kind of terrible,  
as a guy lack of Self-control ability, I cannot put myself in such enviroment 

for me, what i want is just a simple, understandble tilling window manager  
some simple keybinds, a bar with infomation that all i need, and maxium screen space usage  



## Why SUCKLESS?

To be honest, I'm not a fan of "Minimalism" as a dogma.  
Like I said, treating minimalism as an ultimate goal has no end.      
But I do like keeping things as simple as possible, so I can actually focus on what I'm about to do.   

At first, I tried `dwm`.  

On X11, everything was straightforward. Everything could run with a simple `.xinitrc`.  
Xorg did almost all the heavy lifting, so the WM program only needed to focus on how to manage windows.  
It even came with a cool default status bar.  
And all of this was done in about **2000 lines** of `dwm`'s source code.  

In `dwm`, you configure everything in C code. Writing shell scripts for every single keybind and every module on the status bar was incredibly interesting.  

I learned a lot of new things: how signals work, how to output hardware information, and a bunch of Bash and C knowledge.  
It made me feel like I was *actually* learning the core of Linux, not just tweaking a window manager.  

---

## Why WAYLAND? Freedom vs. Reality

as known, X11 is not safe.   
Mainly because of how it handles keyboard listening, and it's no longer actively maintained.   
Who knows what kind of security holes are hiding in there?   

This brings us to the harsh reality of modern computing.   
The tech world is growing fast under capitalism, and it's hard to live without products from big companies.  
For me, the biggest one is **Steam**.    

As I see it, any non-opensource (proprietary) software should run in an environment with **zero-trust**.   
Look at mobile platforms: Android and iOS do this sandboxing well, but the price is your **freedom**.  
If you want some freedom on your Android phone, it's getting difficult.   
Not to mention the iPhone, where it's impossible to break any limits.   

On Windows, security relies 100% on Windows Defender, more like a **Disclaimer**.  
“I told you this is not safe! but you ran it, jokes on you!”  


Luckily, on Linux, you can get more freedom than a smartphone and more fundamental safety than Windows at the same time!   
You just need **Flatpak** and **Wayland**.

Wayland fixes the X11 security flaws at the protocol level.   
Flatpak provides the sandbox to run Steam in a zero-trust environment, keeping your core system safe.  

So, the journey naturally leads me to `dwl` (the Wayland port of `dwm`).   
hopefully it'll end here




