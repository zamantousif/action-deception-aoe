## Action Deception in Two Player Games

### Research project on Formal Methods in Robotics done at Worcester Polytechnic Institute (WPI), USA during Fall 2019 - Spring 2020

#### Description
In this study, we extend a typical relic retrieval scenario from the popular game of Age of
Empires II (AoE) to demonstrate the application of action deception. In this
scenario, a team of three units of player 1 (P1)—a villager, a knight and an
archer—is tasked to retrieve a relic from the enemy’s (P2) territory, which is
being protected by three P2 watch towers. The challenge presented by the
scenario is that neither the villager can retrieve the relic by himself (as he
would be killed by the watch towers) nor can the armed units destroy the watch
towers by themselves.
In this situation, we compute an action deceptive strategy
for P1, which ensures almost-surely (with probability one) that P1 will be able
to retrieve the relic. The key advantages of this approach are that it allows
efficient use of game resources—P1 can retrieve the relic using 3 units, whereas
the traditional AI would end up sending an army of 15 units to take down
towers—as well as it relieves the traditional PlayerManager from the complex
task planning for individual units. This provides a better and more “intelligent”
game AI design.

#### Source Code
The source code constructs the transition system and proceeds to build the game graph for the example presented in the case study. Results show that the use of deceptive winning strategy yields atleast as many winning states for player P1 as there are in a game with perfect information played with sure winning strategy. 

#### References
The source code borrows the data structures and algorithms implemented for the work published in [Synthesis of Deceptive Strategies in Reachability Games with Action
Misperception](https://www.ijcai.org/Proceedings/2020/0031.pdf) and adapts the game graph construction to suit the example highlighted in the case study.

#### Acknowledgements
I am deeply thankful to Abhishek N. Kulkarni and Dr. Jie Fu for their continued support and guidance throughout this work.
