# Stress Pills Prescription

Configurable mechanism for **stress performance web testing**.

## Goals

Offer an easy way to define and execute small performance test over a website.

## Details

* Possibility to define the number of users per second
* Possibility to increment the stress progressive 
* Possibility to define maximum users running
* Allow login and session dependent HTTP stories

Still don't know if is good idea to use already existing **linux stress tools** like:

* http://www.softwareqatest.com/qatweb1.html
* http://www.joedog.org/index/siege-home
* http://www.opensourcetesting.org/performance.php

Or implement the whole HTTP stress mechanism from scratch.

## Challenges

* Define and implement an **HTTP Request script** configuration system (maybe a DSL)
* Launch, monitor and centralize several processes (maybe using an already existing gem)
* Make it very simple, trying to focus to offer just one thing but do it well.
* Offer usable reports.

## Future

Not to be done as part of the RbMU exercise, they are ideas for a possible improvement of this project:

* JavaScript support
* Multiuser web app with web interface.
* Possibility to launch the stress test from different servers, even different countries (integration with EC2?)
