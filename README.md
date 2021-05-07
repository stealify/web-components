# components
A Collections of Reuseable ECMAScript WebComponents including a Framework SDK to build your own react or angular, vue, lit-html.

this project is inspired by all Major and Legacy Frameworks and aims to clear the Fog around WebComponent Frameworks.
It offers the ionic framework components as reuseable stealify-components as also the stealify-web-and-component-framework-sdk

As i tend to eat my own dog food this will get used to build "Streamline" my newst Product. A Full App Lifecycle Managment Solution.

## Why Ionic?
The Ideas of them in general and the mindset and Project Missions to algin and overlap with my Vision for the Web. While i disagree 
on the Tooling my Philosophie is that it should be possible to archive that with more nativ methods so we disagree on for example
"Stencil" while we agree that the usage of the customElements API and WebComponents in general for ios and android are great.
Also we agree on Cordova as Compatibility Layer between the two platforms.


## Compatibility Basics

You will need to learn some basics before you can unleash the power of such a free component system

- Understand basics of Operating Systems and Queues CPU Cycles and Interrupts.
- The Callback Pattern. And the ECMAScript Engines eventLoop and queues
- Understand how to implement a NodeJS Like EventEmitter
- How to Implement Callback to Promise and Promise to Callback adapters
- How to Implement then Ables also called Promises.
- Understand how to implement a NodeJS & WebStream API Interface.
- Understand how to apply Streaming Algorythems and Implementations backpresure, debounce, throttel
- Understand how to abstract time and use the for Streaming Implementations and or Functional Programming.
- How to use Hire Order Functions to return Functions and how to curry them.

To enable you to learn all that while your still productive you can start with using any framework you like and partial upgrade and switch as
you learn.

## What you gain with that?
Universal Reuseable WebComponents that work in any Framework. And are also easy to Read Understand and Maintain as we use Only ECMAScript and
do not need any Transpiling Every One who Really Understands ECMAScript is able to Read and Understand the Components.

So We Aim to gain Documentation Less WebComponents that are Highly Reuseable while also Maintaining Good useage in SDK's with Typescript&JSDOC Support
without Transpiling via Typescript. We Encurage to use // @ts-check usage or configuring allowJS and using the ES6+ Syntax in .js files as also
for node compatibility creating a package.json with content "type": "module" in the directorys that use our modules to partial migrate
we do not suggest mixing code inside the directorys to keep better maintainable code for tooling later.
