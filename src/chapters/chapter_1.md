# Chapter One: What Is Puppet? Is This DevOps? Will I Be Agile?


> What is Puppet?

This is a question that over the past 2 years I've heard (and asked) many times. It's different to different people. 

For the folks at [Puppet Labs](https://puppetlabs.com/), it's their dayjob to make puppet *awesome*.

For the people at [RackSpace](http://rackspace.com/), it's an important part of managing their infrastructure which runs thousands of websites.

For the operations team at [GitHub](https://github.com), it has been a very important part of [their lifestyle](https://speakerdeck.com/jnewland/chatops).


But for most people, Puppet is a way of doing something we call 

<h2>Infrastructure As Code.</h2>

We'll dig into this more shortly.

## Why Do We Care?

The answer is...

<h1>We Don't.</h1><h4>Yet.</h4>


## What Is this "Infrastructure As Code" Thing You Mentioned?

"Infrastructure As Code" is a very interesting concept

The end goal of infrastructure as code is to perform all the infrastructure tasks programmatically. In other words, the key takeaway is "automation."

Now, this is not Agile. This is Not DevOps. Agile may be a *part* of infrastructure as code, but it is not essential. I'm a firm believer that the only way to manage a software project is to do a variation of agile, so therefore, I would argue that agile can be a very useful part of infrastructure as code. But again, this comes down to automating as much as you can. Try to automate yourself out of a job. 

## The Difference Between Puppet And DevOps.

Now, this is one that people will spend hours debating. But the long and short of it is:

> **DevOps Is A Methodology, Puppet Is A Toolbox.**


Again, this is one that people will spend hours debating, but this is the rational behind it:

> DevOps (a portmanteau of development and operations) is a software development method that stresses communication, collaboration and integration between software developers and information technology (IT) professionals.[1] DevOps is a response to the interdependence of software development and IT operations. It aims to help an organization rapidly produce software products and services.


Ok, so the sum of this is that it's a software development method that is big on communication, integration and collaboration between the operations (IT) and the developers (code monkeys).


> Companies with very frequent releases may require a DevOps awareness or orientation. Flickr developed DevOps capability to support a business requirement of ten deployments per day this daily deployment cycle would be much higher at organizations producing multi-focus or multi-function applications. This is referred to as continuous deployment or continuous delivery and is frequently associated with the lean startup methodology.

<sub>[Thanks Wikipedia](https://en.wikipedia.org/wiki/DevOps)</sub>

The sum of this is that if you're releasing more than once a day, you're practicing part of DevOps. It's frequently viewed as something that startups are big on, release early, fail often, get feedback, etc. In fact, it's been summed up in a lovely meme:



![](images/ship_it_squirrel.png)



Basically, you have this squirrel that is just saying "SHIPIT!". This is important. Shipping your product is important. 

Now, note that you can practice DevOps without using Puppet. It's just much easier when you automate yourself out of a job, and into a job of automating 2 other people out of a job. Allowing them to go forth, learn to automate someone else out of a job, and the vicious cycle continues. But isn't that what we've been doing for thousands of years?

## A Few Notes.

The demos in this book will be using a 12.04 LTS Ubuntu Server virtual machine. We will be using Vagrant, a powerful tool for managing VMs, which in turn uses VirtualBox to run the VMs. We will discuss how to set these up in the next chapter. 


## Additional Reading.


[A guest post on ReadWrite by a founder of Puppet Labs](http://readwrite.com/2011/08/23/devops-what-it-is-why-it-exist). From 2011, but a good read nonetheless.

[What is DevOps?](http://theagileadmin.com/what-is-devops/) A good read on The Agile Admin, a site about being a Agile systems administrator.