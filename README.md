# WEEK-8-websecurity
Saul Noda
# Project 8 - Pentesting Live Targets

Time spent: **7** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)



Vulnerability #1: SQL Injection (SQLi)
## Blue
![sqli](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/BLUE.gif)



Vulnerability #2: Session Hijacking/Fixation
I can log in in one browser and get the session id which can be use by pass login process in another browser. the session can be hijacked and steal users information.
![session hijacking fixation](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/BLUE2.gif)





Vulnerability #1: Username Enumeration
## Green
![username enumeration](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/green.gif)

Vulnerability #2: Cross-Site Scripting (XSS)
![cross-site scripting](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/green2.gif)






Vulnerability #1: Insecure Direct Object Reference (IDOR)
## Red
![insecure direct object reference idor](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/red.gif)

Vulnerability #2: cross-site request forgery csrf
![cross-site request forgery csrf](https://github.com/nodasaul/WEEK-8-websecurity/blob/master/gif/red2.gif)


## Notes

Describe any challenges encountered while doing the work



## License
  Copyright 2017 SAUL NODA

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
