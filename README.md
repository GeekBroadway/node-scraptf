# node-scraptf

node-scraptf is an unofficial nodejs wrapper for the [scrap.tf](https://scrap.tf) API used internally.
## Installation

## Disclaimer
This wrapper potentially violates scrap.tf terms of service:

> As a user of ScrapTF, you agree that you will not:
>
> * Circumvent the security of the website and its servers in any way.
> * Try to disrupt our service (including, but not limited to exploiting bugs, bypassing limitations, or server scans/attacks).
> * Allow an error in the bots (such as receiving an extra item) to occur without notifying the staff of ScrapTF.
> * Use any methods to gain advantage over users (including, but not limited to automation, scripts, user-scripts, auto-refreshers, external tools, bug-abusing, or other tampering).
> * Forge or modify evidence for a refund.
> * Perform a charge back in any form after donating PayPal funds to ScrapTF and successfully receiving benefits.
>
> Punishment can include site user account bans or IP bans.

**As such, use this software at your own risk.**


## Development

Current development progress:
- Logs into scrap.tf using existing steam session (generated from node-steam/node-steam-user/
anything that you can get web cookies from)
- Can use the 'AutoScrap' function of scrap.tf