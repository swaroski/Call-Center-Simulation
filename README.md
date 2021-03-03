# Call-Center-Simulation

Scenario:
A call center runs around the clock. It has a number of agents online with
different skills/competences.
Calls by clients with different questions arrive at an expected rate of
callrate per minute (expo. distribution). An agent only deals with clients with
questions in his competence areas. The number of agents online and their skills
remain
constant --
when an agent goes offline, he is replaced by one withe thesame skills.
The expected service time tService[i] per question
follows an exponential distribution.
Clients are impatient and renege if they don't get service within time
tImpatience.

* Determine the waiting times of clients.
* Determine the percentage renegers
* Determine the percentage load on agents.
