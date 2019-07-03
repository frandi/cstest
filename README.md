# Coding Standard

This document provides general guidelines (coding standard) for developers to maintain the quality of code in an application. It should be applicable to the most technology stacks which are used in Polyrific projects. A note will be included if special treatments are needed for certain cases.

## Why would you use this document?

* Code is the product of collective work. (Although you are working alone for now, there’s a high possibility that it will be read by other people in the future, for any purposes.)
* New member needs to onboard fast in adapting with certain convention
* Jumping between projects shouldn’t be a pain experience. (Although no two projects are exactly similar, at least some conventions need to be consistence between them)
* Some conventions have proven to be the best practices in industry through out years of experience. (Although they shouldn’t be used blindly, they can be used as baseline for future improvements)

## Basic Principle

* Principle of Least Astonishment (POLA) - choose a solution that everyone can understand and keeps them on the right track
* Keep It Simple Stupid (KISS) - the simplest solution is more than sufficient
* You Ain’t Gonna Need It (YAGNI) - create a solution for the problem at hand, not for the ones you think may happen later
* Don’t Repeat Yourself (DRY) - if possible, avoid duplication within a component, source control repository, or a bounded context
* The Rule of Three - a heuristic rule to decide when similar pieces of code should be refactored to avoid duplication (this is to bridge between YAGNI and DRY principles):
    * If you need something once, go build it
    * If you need something twice, go build it again, but pay attention
    * If you still need it for the third time, it’s time to refactor it to avoid duplication

