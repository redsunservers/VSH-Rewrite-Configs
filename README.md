# VSH-Rewrite-Configs

This is a public repository for [redsun.tf](https://redsun.tf/) VSH Rewrite configs. Currently have class/weapon balances and dome sizes for each maps.
VSH-Rewrite main code is still private, meaning you can only use this to see current balance infromation in use on the Red Sun servers, and discuss/update balances. You are free to fork this repository and send in pull requests for changes you feel would improve balance.

## How does this work?

VSH-Rewrite reads this config to balance several weapons or general class slot by adding attributes, minicrit/crit, etc.
Most of the time it uses weapon index to grab balances. If not found, it uses general class/slot instead if there is one.

## Contributing

Everyone is free to create issues and pull requests here, whenever if it balance ideas, requests, or bugs related to config/repo itself.
Bugs related to main code still go to [LoadoutBugTracker](https://github.com/redsunservers/LoadoutBugTracker).

When creating issue or pull request for weapon balances, you ideally want to have most of the following:
- Put some thoughts into it, don't submit idea that appeared in your head for only like 2 seconds
- List all weapon reskins index using `prefab`
- Try limit yourself to only use `attrib`, `minicrit`/`crit` and existing `tags` to keep it easy without touching main code.
- Request to add/modify new/existing tags is still allowed, but requires updating main code and can depend on how complex it takes to implement it.
- Adding new convars should really only be needed if it general stuff, while not limited to specific weapons or slot

## Useful links
- [VSH-Rewrite megathread discussion in redsun.tf forum](https://forum.redsun.tf/threads/2864/)
- [List of all TF2 weapon indexs in tf2b.com](https://tf2b.com/itemlist.php)
- [List of all TF2 attributes in tf2b.com](https://tf2b.com/attriblist.php)
