---
title: Who We Are
date: 2018-09-15T07:42:34.000+00:00
slug: getting-started

---
We are Bravo Criteria a self-organizing consultancy that pulls together a group of diverse people passionate about saving time from being wasted in organizations. 

## The document and demo first approach

We've heard this before?

Consultant: What is that you do? Client: What do you want us to do? Consultant: Well that depends what you do? Client:.... Everybody else (sighing): we could be here some time.

### So how about we change the script?

It really shouldn't be that complicated, you have a think about the sort of problems you are facing, and we demonstrate the kinds of things that are possible.

### Facing the future

We can start by writing a press-release of how you would like things to end up, using these simple rules:

1. It must be stated at a future point in time where success has been achieved and realized.  Press releases at “launch” are good, but a better one is sometime after launch, where true success can be discussed.
2. Discuss why it was important, often time to customers (or other key stakeholders).  Discuss the accomplishments first in terms of why it is important to customers.  How did the customer experience improve?  Why do customer care?  Then discuss other reasons why it was important and key goals.
3. Set an ambitious and clear goal:  Articulate a clear measurable results including financial, operating, market share
4. Outline the principles used that led to success.  This is the trickiest, and more important.  Outline the hard things accomplished, the important decisions, the design principles that led to success.  Discuss the issues that had to be addressed to have success

This is part of what we mean by a documentation first approach

### This isn't what is usually understood by document first, is it?

It isn't that's true, and we are keen on the traditional document first approach, this is from [github](https://gist.github.com/zsup/9434452 "ddd.md"), with our little additions.

The philosophy behind Documentation-Driven Development is simple: **from the perspective of a user, if a feature is not documented, then it doesn't exist, and if a feature is documented incorrectly, then it's broken.**

* Document the feature _first_. Figure out how you're going to describe the feature to users; if it's not documented, it doesn't exist. _This is where a demo can really come into its own, it's just the most efficient way to get the user to see what they are going to get, with the demo done and approved - the write-up and screenshotting are straightforward._
* Whenever possible, documentation should be reviewed by users before any development begins.
* Once documentation has been written, _recorded,_ development should commence, and test-driven development is preferred.
* Unit tests should be written that test the features as described by the documentation. If the functionality ever comes out of alignment with the documentation, tests should fail.
* When a feature is being modified, it should be modified documentation-first.
* When documentation is modified, so should be the tests.
* Documentation and software should both be versioned, and versions should match, so someone working with old versions of software should be able to find the proper documentation.

So, the preferred order of operations for new features:

* Do Demo and record
* Get feedback on documentation
* Test-driven development (where tests align with documentation)
* Deliver feature
* Publish documentation
* Increment versions