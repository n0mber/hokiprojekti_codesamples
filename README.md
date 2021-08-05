# HAMK assignment Spring2021, C# and Object Oriented programming. Working title: hokiprojekti
Authors: Noora Turunen, Hanna S., Riku S., Heidi M.

Goal: Generate Hockey Tournament programm/schedule for NHL console game
Minival vaiable product:
  - ask for the gamers' name
  - choose amount of the round played
  - generate 1vs1 game schedule
    - everyone plays at least once against every other during one round
    - everyone has home and visitor games
  - Schedule is saved as a txt. and json. file format (computer/user specific)
  - User can browse old schedule (computer/user specific) 

Noora's role in project and sample codes:
  Creating and programming schedule generation algorithm and print out (commented out in samples and replaced with code for json) 
    See Generointi_1v1.cs and RoundRobin.cs files of the project
  Circling Scrum master: setting goals for the sprints and adding tasks to project management tool
 
Learning curve:
  Using Visual Studio 2019 and utilizing its collaborative mode
  Agile project work
  Utilizing object oriented programming in real life collaborative project
  Version control with Git and with many contributers
  
This project and my code samples demostrate aptly my problem solving skills and matemathical mind. 
I started creating the algorithm with RoundRobin but, as it fell short to meet the standards for generation, 
I developed it futher to also work for tournaments where there aren't even number of players and optimized it to give everyone the maximum number of home/visitor games that possible (e.g. in a game of 4 players (everyone has 3 games) instead of 1-1-1-3 home games, it would generate 2-1-2-1). And to secure impartiality, when generating the schedule,
the code creates random list from the name of the gamer input.
