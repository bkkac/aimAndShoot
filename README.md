# Aim and Shoot

![artwork](artwork.png)

You're Nole Ksum (the k is silent), a citizen concern about the uprising of the machine who decide to take matters into your own hands and put an end to all artificial intelligence. You must kill all the evil robots controlled by Neural Networks and stoping them from evolving into more dangerous beings. The entire human race counts on you, don't let them down.

Play it [here](https://victorribeiro.com/aimAndShoot) | Alternative link [here]()

## How To Play

### Controls

**w, a, s, d** - Move the player up, left, down, right.

**mouse** - Aims and shoots (click).

### Objetives

Kill the bots, don't get killed. Also don't touch the borders of the screen, they hurt you. But, fell free to push the bots into them.

### Bars

Above the bots there are two bars. The red one indicates health, if it's empty you die. The green one is the cool down meter, if it's empty you can't shoot.

## About the Experiment

I've always wanted to take the time to make a [Neuroevolution](https://en.wikipedia.org/wiki/Neuroevolution) experiment, so I did.

Each bot is controlled by it's own Neural Network (that I made a while back - [here](https://github.com/victorqribeiro/digitRecognition)). When all the bots die, the genetic algorithm evaluates their fitness score (based on how many shots they fired, how many hits the got, how many friends they shot, how much they hurt themselfs and how much they moved during the round) and cross the ones with the highest scores.

This goes one forever, until the player dies (which will happen eventually, so Nelo can't never save the human race, after all). By the way, the background history is a joke. I don't mean to make fun of anyone. The idea just seems funny and fit the project.