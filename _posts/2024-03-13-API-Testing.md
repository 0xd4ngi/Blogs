---
layout: post
---

## API Testing

API testing requires new skills, tools and new approaches


## Bussiness Logic Flaws

Manipulating the legitimate data, workflows and functionality of an API

1. Misusing HTML Elements and other client side code 
2. Authorization Bypass </br>
Broken object level authentication(BOLA) is #1 OWASP API Security
* lateral movement : accessing data of another account at the same privilage level
* Privilage Escalation : Accessing data that the current privilage level isn't supposed to have acces to </br>
(Strong authorization and authentication protocols - such as oAuth or OpenID - should be implemented to prevent authorization bypass and protect your systems against this attack vector.)
3. Failing to handle unconventional User Input(Fuzzing random input)
4. Domain-Specific Flaws : API management tools analystics and reporting capabilities to identify and analyze usage patters