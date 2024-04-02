# Harmony
Turns harm into harmony

## Disclaimer 
This project is completely a Work In Progress. 
It is not guaranteed that it will get to v1.0.0. 
With that being said, everyone is free to make PRs, clone, fork or open issues. 
Donations are well accepted! ([PayPal](https://www.paypal.me/MrcSantos))

------------

### Goal
This tool aims to be an enterprise level automatic penetration testing suite.
The configuration would be of the activity scope, a list of checks to do.
Harmony will be able to do osint, enumerate, bruteforce sniff for clear text passwords, scan for vulnerabilities, exploit vulnerabilities, try to exploit windows misconfigurations, try for privilege escalation and complete active dorectory enumeration and exploitation.

---------

### Technical note
I am aware that the project is ambitious however Harmony should firstly be a wrapper that launches other tools and makes decisions based on the parsed output of the launched tools.
The scripting language I choose is Google zx because it is easier to understand for those who know what JS promises are; moreover, it is more confortable in invoking other tools and as such in makes development faster (for me).
I know this approach implies that the software needs a lot of heavy dependencies; the goal is to lower the dependency number and to adopt a real programming language.
It should use a database to store host informations (like Faraday) in order to give the maximum level of details as possible to the analysts.

Last but not least, do not consider the Develop branch to be even usable, there may be commits with incomplete changes, broken syntax or runtime errors.
This branch is used for me in order to keep the commits merge free for now that I am alone in development.

Peace! ❤️
