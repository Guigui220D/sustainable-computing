# Principles for sustainable computing

## Intro

This is a document where I describe what I think should be done to make it more sustainable, i.e. consume less resources and power.

## Backwards compatibility

### In new software

When developping a new piece of software, developpers should try making it compatible with the most existing hardware as possible, both in architecture and in required specs. That means not using the latest most overpowered pc for trying your program, for instance having beta testers use lower specs. 

Making a new great piece of software that everybody wants but developping it with only newer hardware in mind will make people want to buy a new pc. This is especially true in the game industry. Or it could backlash on how many people will use it.

### In existing software

Softwares that still exist should be updated and upgraded considering the capabilities of the device they were initially made for, not the newer devices that could use it.

A lot of products end up being obsolete because the software they work with/ship with is being updated by developpers who care about newer products with much more power, becoming unbearable for a weaker device.

## Thin software layer

Using thinner software layers, i.e. being closer to the metal, lower level, avoids having a bunch of useless data and processing in between your program and the machine that often isnt even felt by the user.

Admittedly, this is much harder in some types of programming, such as web or smartphone apps, and although it does make development harder and or more time consuming, this is less true than it used to be. Newer low level langages and techs manage to bring a lot of power and control with easy development. See Zig, Rust, WebAssembly, D.

## Modular and editable software

Making a software open-source allows having great developpers appropriate it and make it better, make it work on things it wasn't planned for, maintain it in case the original maintainer doesn't want to anymore, etc.

It's a way of making a program cross-platform too. Although it can take effort if the program wasn't written with an other platform in mind, it will still be a gazillon times easier than if it was just provided compiled.

[Suckless](https://suckless.org/) provides software that is provided as a compilable source code with a "menu" of modules you can either decide to compile or not, depending on if you need it. For a terminal for instance, it can allow you to have the best terminal every with all the options or the most sober one that would run on any toaster out there. Suckless is sadly not that popular but i.m.o. it's a great concept that should be taken for inspiration.

This way, programs never get outdated for any type of computer and never bloat your computer with things you don't want or need.

## The cult of quality

This is especially true in the video games industry: game trailers and ads have trained a lot of players to think that life-like graphics and sound are essential to play a game, where in fact, graphics are often the most superficial thing of a game and become a thing you don't even think about once you're immersed.

This is because hardware companies want game studios to use the latest of their hardware the best, in order to sell the hardware, and it has become a loop because a non beautiful game will be disappointing to most users.

A lot of great games, even those that were outstanding at the time of their release, are left behind as if they aren't worth anything anymore, even though some games clearly show graphics arent the important part.