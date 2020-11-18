---
layout: post
title: A guide to Cryptography for beginners
date: 2020-08-09 00:00:00 +0300
description: A collection of resources that can help you set your foot into the magical realm of cryptography # Add post description (optional)
img: Crypto.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Cryptography, Beginner] # add tag
---


Being the 'science of keeping secrets', cryptography teases the inherent winsome intrigue in all of us. Yet, beyond the cursory abstraction of fancy terms, lies the challenge of ensuring robustness that can withstand cleaver attacks from hackers or data-leakages due to negligence. Although some of this robustness can be derived from the strong mathematical roots of the subject, a single flaw in perceiving the problem or its implementation can break security. 
Having explored this fascinating field for a few years now, I present my guide to building a good foundation in Cryptography.

The most common route for beginners to start with any field is introductory courses that can give you an overview of the domain. The following are the courses that I followed: 
1. [Introduction to Cryptography and Data Security](http://www.infocobuild.com/education/audio-video-courses/computer-science/IntroductionToCryptography-Ruhr/lecture-01.html) (Prof Christof Paar, Ruhr University) - 
  * Difficulty level: Easy 
  * Strengths: Provides a good outline of topics like Elliptical Curves and Elliptical Curve Cryptography missing from many courses. 
2. [Cryptogaphy - I](https://www.coursera.org/learn/crypto) (Prof Dan Boneh, Stanford University) -
  * Difficulty level: Medium 
  * Strengths: Includes coding exercises and quizzes. In-depth coverage of essential topics along with mathematical proofs.

Courses mentioned above try to introduce students to the necessary math involved in a few devoted lectures. For those interested in taking a deeper dive into the mathematics of the realm, relevant courses are: 
- [Abstract Algebra](http://wayback.archive-it.org/3671/20150528171650/https://www.extension.harvard.edu/open-learning-initiative/abstract-algebra) by Professor Benedict Gross - One of the best courses on the domain with in-depth analysis of algebraic structures and related concepts like homomorphism, which can help develop a strong foundation for areas like lattice cryptography. 
- [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/) by Professor Gilbert Strang - A easy to grasp guide to linear algebra which can help develop a sharp intuition for the area. 

For a hands-on experience with each topic covered in the above courses, one can solve the eight sets of [Cryptopals challenges](https://cryptopals.com/). These challenges underscore vulnerabilities in real-world systems and acquaint you to the required robustness we talked about in the beginning. They cover modern crypto attacks involving elementary mathematics, thus can act as an excellent resource for people who lack a strong mathematical background. 

Introductory coursework in cryptography tends to focus on symmetric crypto and primitives like hash-functions and trapdoors; thus, it leaves the vast territory of public-key cryptography and riveting subdomains like multi-party computation, homomorphic encryption etc. unexplored. 
It's safe to assume that the above resources, by their very definition, are a great way to learn some basic concepts in crypto but are not a definitive representation of the field as a whole. 

To delve deeper into a single domain, say privacy-preserving machine learning or cryptocurrencies, reading academic research papers can go a long way. To this end, the online schools held by various universities can provide a comprehensive take on different sub-domains in crypto via talks on selected pioneer works. This approach highlights the exciting applications and on-going research in a broad array of disciplines coming from renowned researchers in the field, which can help you find a subject that interests you. Some of the topics covered in this winter school series are:
- [Secure Multi-party computation](http://cyber.biu.ac.il/event/the-5th-biu-winter-school/) - A subfield in crypto that aims to create methods for parties to jointly compute a function over their inputs while keeping those inputs private.
- [Blockchains and Cryptocurrencies](https://iias.huji.ac.il/event/3rd-winter-school-computer-science-and-engineering-blockchains-and-cryptocurrencies) - Blockchain is a distributed ledger technology that allows data to be stored globally on numerous servers – while letting anyone on the network see everyone else's entries in near real-time.; in simpler words, it refers to digital information, i.e. the "block", stored in a public database, i.e. the "chain".

I hope this guide proves of some help. 
Spending time with these resources, you'll develop a sense of what works for you and helps your understanding. Crypto offers a broad spectrum of exciting topics to choose from, and with patience and hard-work, I'm sure you'll thrive in the area.
