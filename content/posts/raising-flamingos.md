---
title: "Raising Flamingo(s)"
date: 2021-11-02
draft: false
author: Bastian Ike
image: /images/74_image-90b_web.jpg
---

5 years ago we set started the adoption of the Go programming language at AOE. 3 years ago we open sourced Flamingo, our web framework, created to enable us to build fast and scalable applications.
Now, looking back, it was quite a ride raising a flock of small Flamingo's to form a stable basis for our daily work.

<!--more-->

But first, why even open source work we have spent hundreds and hundreds of hours on, for free? At AOE, we do not believe in gatekeeping, sharing our code enables us to join an open dialogue with everyone interested in building, growing and learning on a mutual code base.

![Working on Flamingo](/images/csm_csm_AOEpeople2_e68879a572_1e2ebecc16.jpg)

What is our learning in all these years? First of all, things change. Back in the days, we set for server side rendering using a custom PUG implementation in Go, to make sure we can always deliver the fastest and most optimized page, no matter what Browser people run. Nowadays, after many iterations, our default setup uses generated GraphQL code on the Serverside, where Flamingo is the edge to all connected services and microservices, while the Frontend is a standalone React application, requesting precisely the required data necessary to render what we want to show. Remix now allows us to bring back the serverside rendering in a way that we can even support browsers with JavaScript disabled.

![Flamingo sliding down](/images/74_image-90b_web.jpg)

This evolution was nothing we could predict, but we are greatful for all the learnings, all the contributions from the outside and the chance to let our Flamingo grow wings. Now we set out to fly even higher, focusing on making Flamingo accessable and lowering all entry barriers so you can start right away, with a free choice of your tech stack, be it gRPC, GraphQL, Rest, and include and connect any framework you've learned to love in the past.

After all, this is about Open Source, and we love Open Source.
