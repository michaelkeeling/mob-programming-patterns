# Mob Programming Patterns

Mob programming is an approach to creating software in which the whole team
works together on the same thing at the same time. At the heart of every
effective mob there is a group of people working from a place of mutual
respect to deliver the best software they can, as fast as they are able.
Effective mob programming comes about from effective communication among
teammates.  Naturally, interaction styles will vary greatly from team to team
and situation to situation.  As such, there is no "one way to do mob
programming."  This is where a robust patterns catalog can help.

A pattern is a repeatable solution that emerges in response to a specific
problem in a particular context.  You might think of a patterns catalog as a
collection of tools in a toolbox.  While you might use your trusty hammer
often, selecting the right tool for the job can not only make work easier, but
the final result even better.  They key lays in knowing when to use a particular
pattern and how to use it.

Mob programming is still a relatively young method.  We're all learning how to
practice mob programming better.  While we've found it to be a very powerful
method, it does take some practice to do well.  The goal of this repository
is to capture the patterns we've discovered so far in the hopes that other teams
might find them useful as a jumping off point for getting started with mob
programming.

## Patterns

| Pattern                    | Category      | Gist                                                                                                                                                                                                                              |
|----------------------------|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Facilitator                | Mob role      | Volunteer who helps the group stay focused and to help resolve differences of opinion.  Typically the driver does not take this role.                                                                                             |
| Recorder                   | Mob role      | Volunteers who capture notes such as context or design decisions on behalf of the mob.                                                                                                                                            |
| Researcher                 | Mob role      | Volunteers who seek out information in real-time that is required for the mob to move forward.                                                                                                                                    |
| Navigator                  | Mob role      | Direct the driver in what to do.  Members of the mob not currently driving are assumed to be a navigator.  Navigators can contribute to the mob in many ways.                                                                     |
| Driver                     | Mob role      | The person currently at the keyboard, capturing the thoughts of the navigators as everyone works to solve a particular problem.                                                                                                   |
| Devil’s Advocate           | Mob role      | A navigator who takes a contrarian position to help make the mob’s designs stronger.                                                                                                                                              |
| Punch List                 | Collaboration | A task list used by the mob to track work items and select what to work on next.  Punch lists can be text-based or graphical.                                                                                                     |
| Splinter Group             | Collaboration | One or more members of the mob who break away from the main group to complete a routine task.  Splinter groups can also investigate alternatives for review by the whole mob.                                                     |
| Ridin’ Shotgun             | Collaboration | A navigator who solely dictates the mob’s work to the exclusion of other navigators.                                                                                                                                              |
| Mute your mic              | Collaboration | A navigator chooses to temporarily remain silent as a navigator to give other navigators a chance to contribute.  Used as a way to kick start a slow mob or prevent one person from dominating the mob.                           |
| Fight Club                 | Collaboration | A situation in which two or more participants fight over the direction of the mob with total disregard for the guiding principles of mutual respect and consideration.  Extremely harmful to the mob, considered an anti-pattern. |
| Natural Swap               | Collaboration | A new driver takes the keyboard without prompting by either a member of the mob or timer at a “natural” break in the work, such as after a test passes or a refactoring step is completed.                                        |
| Forced Swap                | Collaboration | A new driver takes the keyboard after being prompted by either a member of the mob or a timer.                                                                                                                                    |
| Distracted non-Participant | Collaboration | Navigators who are present in the mob but otherwise do not participate, perhaps distracted by other work.                                                                                                                         |
| Thinking Out Loud          | Driving       | The driver articulates their current thinking as they are the prevailing expert in the room or see the path forward.                                                                                                              |
| Tell me what to write      | Driving       | A prompt drivers will sometimes use to engage help from navigators, inviting someone from the mob to direct the driver.                                                                                                           |
| Driving on Autopilot       | Driving       | A driver who proceeds without inputs from the rest of the mob.                                                                                                                                                                    |
| Plowing Through            | Driving       | A driver who, with the support of the mob, works on the task at hand with the intent of completing it as quickly and painlessly as possible.  Often combined with the thinking out loud pattern.                                  |




## Additional Resources

[Ars16] Arsenovski, Danijel.  “Swarm: Beyond pair, beyond Scrum,”
Proceedings from Agile2016, August 2016,
https://www.agilealliance.org/resources/experience-reports/swarm-beyond-pair-beyond-scrum/, retrieved May 24, 2019.

[Fre18] Freudenberg, Sal and Wynne, Matt. “The Surprisingly Inclusive Benefits of Mob Programming,”
Proceedings from XP 2018, May 2018,
https://www.agilealliance.org/resources/experience-reports/the-surprisingly-inclusive-benefits-of-mob-programming/, retrieved May 24, 2019.

[Ham18] Hamid,Amr Noaman Abdel. “Experimenting with Mob-Programming,”
Proceedings from Agile2018, August 2018,
https://www.agilealliance.org/resources/experience-reports/experimenting-with-mob-programming/, retrieved May 24, 2019.

[Kee18] Keeling, Michael and Runde, Joe. “Share the Load: Distributing Design Authority with Lightweight Decision Records,” 
Proceedings from Agile2018, August 2018,
https://www.agilealliance.org/resources/experience-reports/distribute-design-authority-with-architecture-decision-records/ retrieved May 24, 2019.

[Kee19] Keeling, Michael and Runde, Joe. “Harvesting Mob Programming Patters: Observing How we Work,”
Agile Alliance Curated Experience Report, July 2019,
https://www.agilealliance.org/resources/experience-reports/harvesting-mob-programming-patterns-observing-how-we-work/ retrieved July 8, 2019

[Ker15] Kerney, Jason. “Mob Programming -- My First Team,”
Proceedings from Agile2015, August 2015,
https://www.agilealliance.org/resources/experience-reports/mob-programming-my-first-team/, retrieved May 24, 2019.

[Luc17] Lucian, Chris. “Growing the Mob”,
Proceedings from Agile2017, August 2017, 
https://www.agilealliance.org/resources/experience-reports/growing-the-mob/ retrieved May 24, 2019.

[Zui14] Zuil, Woody. “Mob Programming -- a Whole Team Approach,”
Proceedings from Agile2014, August 2014,
https://www.agilealliance.org/resources/experience-reports/mob-programming-agile2014/ retrieved May 24, 2019.
