# PathPlanningBar-AI2Assignment1
In Japan, a few coffee shops are using robots as waiters and baristas. However, as the number of customers increases, the shops realise that they need to efficiently and effectively plan the way in which robots perform their tasks, to properly run the shop.
In this paper, we analysed the efficiency of our PDDL planning model, which has the task of managing the movements and actions of a waiter robot and a barista robot running a coffee shop. The model is performed with ENHSP Planning System (version: ENHSP-20), using different engines, due to the limits of ENHSP. The environment is defined and the robots have limits and specific rules to comply with in order to perform and satisfy customers’ needs.

![shop layout](https://github.com/ClousTom/PathPlanningBar-AI1Assignment1/assets/117213899/364cfac6-d267-45e7-ae88-af1fa4164a9d)

![gerarchia](https://github.com/ClousTom/PathPlanningBar-AI1Assignment1/assets/117213899/bb9e4638-78fe-491c-8a87-00a34ba93a0b)

*Language*: PDDL+

*Planning engine*: [ENHSP](https://sites.google.com/view/enhsp/) (version 20)

### Execution

*Remember to install ENHSP20 before running!*

To execute planning run the script:
```bash
java -jar ENHSP/enhsp.jar -o <domain> -f <problem> -planner <configuration>

# " opt-blind " configuration for the first 3 problems and " sat-hmrph " for the last problem
```

### Dependencies

The only dependency needed is Java (15 possibly, otherwise also 17 and 18 should work):
```bash
sudo apt install openjdk-17-jdk
```

*Note*: if you choose to install Java 15, you'll have to install it manually.
