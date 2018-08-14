# Agent-Based Epidemic Models

I wanted to make a model of how a infectious disease, such as the flu, spreads through a population. Using NetLogo, I made several *agent-based* models, meaning there can be many agents with different properties doing different things. In these models, each agent is a different person. The people are programmed to move around and come in contact with other people.

## SIR Model

Each person starts out as either infected with the contagious disease or healthy but susceptible to the disease. I made two sliders that can change the number of people who start out in each state. A susceptible person that comes in contact with an infected person has a certain probability of becoming infected. This probability, a number out of one hundred, can be changed with a slider. After being in the infected state for a certain amount of time, a person becomes removed, which means he/she is immune to further infection. The number of people in each state over time is graphed. Time in the program is measured in ticks.

## SIRS Model

Almost everything in this model is the same as my SIR model. However, when a person becomes removed, after a while, they become susceptible again. I also made another parameter — some of the infected people can be sick without showing any symptoms. I also made a slider that can change the probability, out of one hundred, of a person being infected without symptoms. I did this because in the real world symptoms sometimes don’t always show. Again, the number of people in each state is graphed. However, in the susceptible and infected graphs, the number of people who look susceptible or infected and the number of people actually susceptible or infected are both graphed.

## SEIR Model

This model is also similar to the SIR model. However, when a person gets infected, the person will still be healthy for a certain amount of time, meaning the person will not show any symptoms of being sick and will not be able to infect anyone else. This period of time is the E, “exposed,” part of SEIR. In the real world, sometimes after viruses enter a body, they remain latent for a period of time. The SEIR model reflects this phenomenon.

## SEIRP Model

The SEIRP model shows a double epidemic phenomenom. 

## Small-World Network

The next thing I wanted to do was to make a program with a network of agents. In the real world people don’t wander aimlessly like the agents were doing in the previous models. Most people have a “network” of people—family, friends, co-workers—that they spend most of their time with, not random strangers. And since my simulations are supposed to model the real world, I wanted to make the agents of my programs have networks. In NetLogo, the agents can create links with other agents.
