[ATAI 2018-19] - [HOMEWORK 4] - [Team JBROMAS]- [AXIS]
==================================================
Mikel Berganza, Isabel Losantos, Egoitz Herrera
==================================================

[FILE CHANGES] The things we changed are the next plans: Perform aim action, update targets. In perform aim action plan, first, we look for the aimed agents. If the aimed agent is an allied or a flag agent, we will go to their position, always following them.
On the update targets plan, if the agent is thinking about what to do, the agent will go to patroll again.
Perform look action, this plan is only implemented on the normal axis agents. If the flag is taken, we change the priority of the task attack, so its the first the agent will do. If its not taken, the agent will go to patroll the flag.
We tried changing the get_agent_to_aim plan, so we could stop shooting if we saw an axis agent, however, for some reason, after copying our allied's code, the axis agents would stop and do nothing. 
So we decided to not use it.

[CHECK THE MANUAL] http://gti-ia.dsic.upv.es/sma/tools/jgomas/archivos/documentation/Jason%20JGOMAS%20-%20Manual%20-%20english.pdf

=======================================================
[ATAI 2018-2019]-[HOMEWORK 4] - [Team JBROMAS]- [ALLIED]
=======================================================
Oier Eguiazabal, David Max, Manuel Ruiz
=======================================================
Task 1:

Changes done for beat the default AXIS team:
	-Avoid friendly fire


Task 3:

Changes done for beat others AXIS team:
	-Avoid friendly fire
	-All ALLIED agents follow the flag carrier forming a line.
	