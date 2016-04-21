---
title: "Setting up Parse on Heroku"
slug: parse-setup
---

In this tutorial you will setup your own Parse server. In the next tutorial, you will setup the dashboard to interact with your parse server.

1. What is Parse? What is Heroku?
2. Setting up the Server
3. Setting up the dashboard
4. Completion

# What is Parse?

## Background
Parse (was) a mobile Backend as a Service company/product that was purchased by Facebook. The idea was, let individual mobile developers build apps, without having to worry about servers.

The role of the Backend in an internet application revolves around data persistence. In reality, its much more complicated than that, usually because of different application requiring specialized business logic. But for many developers Parse is (and was) enough to ship an amazing app without worrying about servers, and what was on them.

This year, Parse announced that it was going to shut down its platform, but would be open-sourcing the software and tools needed to run your own. Through community efforts, and some effort by members of this team, you can now run your own Parse with two, one-click setups!

The bad news? Parse had a generous free plan that is now gone, and has now shifted the burden of worrying about servers back to the developer.

The good news? You don't have to write your own backend for an infinite number of projects, ideas, hacks, and applications because the now open source parse-server will power them all!

## What it does
Parse lets you store your structured data, handle files such as images, and even manages your users logins and social network connections!

# What is Heroku?

## Background
Heroku is a PaaS (Platform as a Service), that allows you to run code without thinking about the rest of the infrastructure needed to scale an app. It has plenty of caveots, but the most important thing to know, is that if it can run on heroku, it can run anywhere. Targeting Heroku involves utilizing best practices for deploying code in the cloud. The downsides of using Heroku or something similar are usually less choice of technology, high cost to performance ratio, and having the inability to introspect a single server (something that usually comes with having thousands of servers).

Heroku and Parse, while having different offerings, had to compete for the hearts and minds (and wallets) of developers, but now, you get both!

## What it does
Heroku lets you take a repository of code, push your updates/changes, and within minutes they are on the internet!



# Setting up
