[ATAI 2018-19] - [HOMEWORK 4] - [Team JBROMAS]
==================================================
ALLIED - David Max, Oier Eguiazabal, Manuel Ruiz
AXIS - Mikel Berganza, Isabel Losantos, Egoitz Herrera
==================================================

[FILE CHANGES - ALLIED] For task 1 the only change we have done to beat the default AXIS team is to avoid friendly fire. For task 3 the changes we have done to beat the other AXIS teams are also to avoid friendly fire, and make all ALLIED agents to follow the flag carrier forming a line.

[FILE CHANGES - AXIS] The things we changed are the next plans: Perform aim action, update targets. In perform aim action plan, first, we look for the aimed agents. If the aimed agent is an allied or a flag agent, we will go to their position, always following them.
On the update targets plan, if the agent is thinking about what to do, the agent will go to patroll again.
Perform look action, this plan is only implemented on the normal axis agents. If the flag is taken, we change the priority of the task attack, so its the first the agent will do. If its not taken, the agent will go to patroll the flag.
We tried changing the get_agent_to_aim plan, so we could stop shooting if we saw an axis agent, however, for some reason, after copying our allied's code, the axis agents would stop and do nothing. 
So we decided to not use it.

[GITHUB LINK] https://github.com/damax1995/FINAL_PROJECT_ATAI

[CHECK THE MANUAL] http://gti-ia.dsic.upv.es/sma/tools/jgomas/archivos/documentation/Jason%20JGOMAS%20-%20Manual%20-%20english.pdf