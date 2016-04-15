# open-source-workshop

I'm Trent Oswald, Infrastructure Team Lead at Code for San Francisco

I've worked in open source now for over 4 years in various capacities, including serving as facilitator for Node.js's Website Working Group for about 6 months. I am building with a Code for San Francisco team a Code for America Brigade Content Management Portal, and I currently work at Mashape, who publishes an open source API gateway server called Kong.

## What is open source

Contrary to popular belief, open source does not mean free software.

Open source makes source code available to the general public with relaxed or non-existent copyright restrictions. It is a development model that encourages universal access and redistribution of the project’s source (like code, blueprints, recipes, whatever), allowing for third-party modification and redistribution.

Open source is a rich and thriving community, with shared values that celebrate open exchange of information, open governance, collaborative participation, rapid prototyping, transparency, meritocracy, and community development. It enables self-enhancing diversity of a project’s production.


## when did it start

The ideas of open source existed ling before computing, Henry Ford in the early 1900s pushed for open disclosure of automobile patents, paving the way for computing to follow suit almost a century later.

Officially named “open source” (or OSS) when split from the “free software” foundation in 1997

Developers wanted to separate from the political agenda and moral philosophy of the "free software" movement, and emphasize a commercially-minded mindset. The main developers behind Netscape, now Mozilla Firefox, Debian, and the Linux Kernal made the Open Source Initiative in 98

Made a marked difference between freeware and OSS, also known as Free as in beer (freeware) vs. Free as in speech (OSS)

## Not just Software

- Media Content - Wikimedia Foundation
- Hardware - Raspberry Pi, Arduino
- Beverages - Open Source Cola, Brewtopia
- Firearms - 3D Printed firearms
- Medicine - Tropical Disease Initiative
- Religion - Open Siddur Project, Open Source Yoga Unity

## what makes something open source?

- release of source code. This can be through Github, on your own website, or even pastebin.
- Public and permissive license, li MIT, ISC, GPL or Apache. This allows people to legally use and or iterate on your work
- Clear and approachable documentation. security through obscurity is a real thing and is utilized often in the industry, it's hard to iterate on minified or undocumented code.

## Libraries that are open source and accept new developers

- React, backed by facebook
- Ruby on Rails
- Linux, which is one of the oldest Git-based source codes still in production
- Android, backed by Google
- even the .NET framework from windows, which includes the C# programming language.

## How do I Open Source?

- Start your own Open Source project
- Contribute to other projects

## Start your own

- Release Code
- Public and Permissive License
- Clear Documentation

But I would add three more is you are building your own:

- Testing, because then your contributors know if they break functionality on contribution
- Publishing, so people can easily install / implement your software
- Evangelize - Reddit, Github, HackerNews, so you can increase adoption

The heart of open source is simply, "If it's broken, fix it, and release it."

**A lot of OS philosophy can be summarized in something called the OSS Manifesto**

- Respect
- Collaboration
- Healthy Debates
- A standard set of basic documentation (like README's, Changelogs, and Contributing guides)
- A consistent versioning of releases, so people know what to expect when upgrading

You can find all of these things at github.com/therebelrobot/open-source-workshop

## contribute to others

is arguably quite a bit more daunting than starting something on your own for a very simple reason:

Human interaction. This might scare a lot of you away from contributing your first time, but int's important to remember a few things:

- these maintainers are coders. Just like you. They have ideas and thoughts and feelings and lives with families just like you.
- nobody is born a coder. You don't hop into this world knowing advanced compiler algorithms and how to scale AWS clusters on the fly. All of us, these maintainers included, started somewhere, and if they can get to where they are now, you can there too.
- The open source community is enormous. If you have a bad interaction with one branch of it, odds are that's an isolated incident, and you can find another project or another language that is more welcoming to what you need. You are not bound to any one project.

** there are a couple contributing models available when you are working collaboritively on a project. Branching, or the internal parallelization of the codebase, is very common in company and paid work, when everyone is in the same organization and you trust everyone to play nice. Forking, or the external parallelization of the codebase, is what you do when you don't necessarily trust your contributors to do everything 100% correct, or when there's a possibility of someone pushing problematic code. Most of the work you do in the community of Open source is going to be using the forking model, and creating pull requests for your code.

Before beginning any work in another person's repo, always always read the attached CONTRIBUTING doc. This will often let you know how to file an issue, what to include in bug reports, and how to contribute code to the codebase. A lot of arguments online can be avoided by just reading the documentation.

The easiest way to contribute to a repo is through the issue tracker. If there is no license attached to the codebase, ask for a license. Report any bugs you've seen using the software. Something that helps out a lot is trying to replicate currently logged bugs. This will help determine if the issue is isolated or global. Include info about your environment while doing this, like your operating system, the version of the language you are running, and the versions of the applicable modules you may have loaded. You can also suggest new features you'd like to see in the software, but be aware that the library maintainer may not accept or agree with the suggestion for a variety of reasons.

Some things to remember when interacting on Github issue threads:

- These developers are from all over the world, from every kind of cultural background, and so you are bound to have language / culture / personality clashes. Expect these to happen, and make sure your communication is as clear and respectful as you can make it. And when a conflict occurs, be gracious and seek for common ground.
- Since the core contributors can be anywhere in the world, you could be submitting an issue at 3am their time, and they'd be dead asleep. Also a lot of these libraries are built in the developer's spare time, so response times to your issue's questions can vary dramatically, from a couple of seconds to a couple of weeks.

If you want to get your name on that contribution list, however, you'll need to do a bit more. You'll actually need to contribute content to the project. Some ways that a lot of people overlook when looking for ways to contribute:

- Assist in documentation improvement
- Assist in writing tests
- Try fixing a currently reported bug
- Try adding a currently proposed feature

These are normally things you can contribute without much check in with the core contributors. If you are looking at fixing a bug you found, or adding a feature you would like, this is where you would want to coordinate with the powers that be on the library and make sure that it's actually something they want added, or if someone is already working on it.

If you are wanting to contribute to a project, but don't know which one or where to start, up-for-grabs.net is an excellent resource, and one that we'll be look at today.

With that, let's dive into some code!

## Workshop portion

### Build /publish your own library (addition module)
### to your neighbors newly published library
### either find something you have already built and start getting it ready for release
### or find a project in up-for-grabs.net to jump into
