---
project: tdd-adventure
tag: tdd-adventure
priority: 2
published: true
---

Recently, I've been volunteering as a mentor/guide at the [nodeschool](http://nodeschool.io) workshops that are held in Rosslyn as part of the [node.dc](http://www.meetup.com/node-dc/) meetup.

Nodeschool is a great environment for people of all skill and experience levels to get together and learn more about node. At any given meetup, we might have participants who have been programming for decades, to current college or high school students, to recent bootcamp graduates. The idea behind nodeschool is to provide a series of community-developed, open source tutorials delivered via command line interface. I personally love this format, as it encourages people to work in an environment similar to the environment in which they might actually be working, as opposed to within a web-based ui or other tool that keeps the user from getting comfortable running the code on their individual machine.

One thing that I noticed, however, is that many people just starting out with programming (or even, in some cases, people who are recent graduates of bootcamps or other formal programs) tend to be a little skittish on the command line. The normal workflow for a nodeschool workshop is that you receive a description of a problem to solve, code up a solution, and then attempt to verify your solution using a simple command line instruction. For whatever reason, workshop students tend to spend a lot of time looking at their code without running the verify command - depriving themselves of the useful feedback provided when the nodeschool runs tests against their solution.

I decided that, as an experiment, it would be fun to create a workshop that tries to acquaint students with some of the key concepts of test-driven development. The hopeful outcome would be that students get into a better flow of writing code, running it against tests, and using the test feedback to ensure that they are headed in the right direction, encouraging behavior that creates a tighter learning feedback loop. 