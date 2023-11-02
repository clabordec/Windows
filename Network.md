# Types of Network

## Workgroup
- No centralized authentication:
    - If you have 3 computers (computer 1, computers 2 and computer 3) you are user ```Jacob Roberts```, and you want to log into the computers, you will need to log into these computers from time to time
    - Assuming that computer 1 is your primary computer, but you want to log into computer 3, someone will need to go to computer 3 and create a user account for ```Jacob   Roberts```
    - These computers have no relationship to each other than they physically reside on the same network
- No centralized administration
    - If I want to configure the firewall, I have to physically touch each of these computers
    - There is no place you can go and say, I want to configure this setting and I want it to apply to all 3 computers, this will not work due to the environment being workgroup
- Max of 20 computers supported
    - Let's say that you have a shared folder on computer 1, and you want users on computer 2 and 3 to be able to browse to this share and copy a file, since there is just 2 computers, it is acceptable
    - But let's say that there are 25 computers, if you have 25 different computers that try to browse the shared folder at the same time, they're going to get an error message that says "The maximum number of connections has been exceeded"
- Low security

<br>

## Domain
- Centralized authentication
- Centralized administration
- Unlimited number of computers
- High security

<br>

