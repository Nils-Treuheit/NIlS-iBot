# NIlS-iBot
A fixed decision environment-based strategy to [compete](https://sites.google.com/site/micrortsaicompetition/introduction?authuser=0) in the MicroRTS Game

Combines standard strategies from [MicroRTS-Game](https://github.com/Farama-Foundation/MicroRTS):
 - MilitaryUnit-Rush
 - MilitaryUnit-Defense
 - Worker-Rush

Also follows the [mayariBot](https://github.com/barvazkrav/mayariBot) mentality of engaging in combat first before executing other tasks. However, I extended the proposed attack-first behavior to a battle power based flee/re-group or attack behavior.

Some deviations from my newly developed strategy combination were put into place to deal with edge cases and prevent any laggy behavior, that could cause timeouts or exceptions.  
