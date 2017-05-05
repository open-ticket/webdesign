---
layout: home
---

# What Is Openticket?
Openticket is an open-source ticketing platform that you can freely download
and run on your own server or machine. You're no longer restricted by a
closed-off platform; you have the freedom to make the platform work for your
organisation.

## How does it work?
Openticket is made up of a collection of microservices. These are small
applications that perform certain tasks and interact with each other. They stack
together like bricks to power Openticket. For instance, there's an application
dedicated just for generating and validating attendee tickets. Also, developers
and organisations can drop in their own services to interact with their
Openticket deployment -- allowing for infinite customisability.

## What technology does it use?
Most of the server-side services will be written in Go. We chose this language
as it has relatively low overhead and has great HTTP libraries built-in. The
webapp will most likely be written using Ruby on Rails and/or React, for
simplicity of setup, and the services will probably use local PostgreSQL
servers, although this can be changed.

<!--
vim: textwidth=80
-->
