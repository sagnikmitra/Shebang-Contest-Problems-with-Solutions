# Shebang 2020
A Coding Contest arranged by School of Engineering, Sister Nivedita University
Problems:
#TETRIS! - P1

On a boring quarantine evening, you find yourself in quite an unexceptional situation, where you have got nothing to do, and to your luck (or bad luck) it’s raining cats and dogs outside, consequently you don’t seem to find any reception.

Having nothing to do and no possible way to pass the time, you decide to play ‘Tetris’. Fifteen minutes into the game and lightning strikes! Everything rumbles! And you tumble, into a dizzying blackout. As you slowly come back to your senses, you realize you are not in your room anymore, you are inside the world of Tetris!

Trying to make sense of everything you decide to scan your surrounding, while doing so you find yourself a laptop and a note, the note goes as follows:



The ‘Tetris Grid’ is much like an M x N matrix with row indices starting from 0 to M-1 and column indices from 0 to N-1.
Multiple blocks never fall together, i.e., at any particular instance only one block can fall.
Blocks fall along their respective column in a straight line starting from the 0th Row. This event of a block falling is called a Fall.

Cannons are placed at each Fibonacci Row(row with a fibonacci index number), right outside the matrix at the leftmost corner.
Cannon-balls follow a straight line along the row from when they are shot, until they hit the opposite wall or a falling block.

At any particular instance during a Fall, a block can only be hit if it’s in a Prime Row(row with a prime index number). Nonetheless it can be hit by multiple cannons times during the same fall.



You understand that you must come up with a program that can calculate the maximum number of hits possible in the Tetris System.


Input:
The first of the input file contains T, total number of test cases. Followed by T lines, each line containing 2 integers, M & N, number of rows and columns. 

Output:
The output file must contain a single string of SPACE SEPARATED integers indicating the maximum number of HITS possible, for all the test cases.

Sample Input
2
9 2 
4 8

Sample Output
3 2

-----------------------------------#!--------------------------------------

#MINECRAFT! - P2

Minecraft is a virtual sandbox world allowing people plenty of freedom choosing how they interact with it. Players explore a blocky terrain brimming with various raw materials, which they may use to craft tools, build structures or earthworks. 

This world also accommodates hostile AI-controlled ‘mobs’, inclusive of large spiders, zombies, skeletons and various other creatures. Frequent wars between the players and these mobs are common. 

Even still, there exists a far dangerous region in the Minecraft universe, the Nether, it is a hell-like dimension that can only be accessed by distinct portals, however it contains some of the most precious and unique resources. Apparently a war has broken out in Nether, the players have come to mine the unique resources of this dimension, but the zombies are preventing them from acquiring it.

As the players need to mine miscellaneous resources spread across different islands to build everything in this virtual world, they need a strategy to take down the power of the ‘MOBS’. They have decided to talk with the Zombie King, but when they went there, there was a long Note writing:

Players,

Today, I won’t take a decision for Kill & Glory, rather I will throw you a problem, if you can solve it within time, the shared resources are yours. This is a problem from the Ancient Zombies of Nether. And it goes like -
The nth term of the sequence of Nether Numbers is given by, Zn = n(n+2)/3; so the first ten Nether Numbers are:
1, 2, 5, 8, 11, 16, 21, 26, 33, 40
Converting each letter in a word to a number corresponding to its alphabetical position (A = 1 … Z = 26) and adding these values we form a word value. For example, the word value for SHEBANG is 19 + 8 + 5 + 2 + 1 + 14 + 7 = 56 = Z12. If the word value is a Nether Number then we shall call the word a Nethword.
You need to find out the number of Nethwords in the given note.
									Yours harmfully,
							   		    ZOMBIES
Now, in this situation the Players reached out to us for immediate help, so you need to help them find the number of Nethwords as quickly as possible and save them.

Input:
The input file will contain 50 random words. You need to find the number of Nethwords in the file.

Output:
For the input file, you have to give the output containing the total number of Nethwords in the input file.

Sample:
Input-				Output-
“WHY”,“WILL”,“YOU”,  		3
“ADOPT”,“NETHER”


-----------------------------------#!--------------------------------------
#HALF LIFE!  - P3

Some years after Gordon Freeman and other scientists accidentally opened a portal to a dimension of hostile aliens at the Black Mesa Research Facility, Freeman is awoken from stasis by the mysterious G-Man. The portal attracted the attention of the Combine, a technologically superior multidimensional empire which conquered Earth in seven hours. The Combine has implemented a brutal police state by biologically assimilating humans and other species, and preventing humans from breeding via a "suppression field". 

This portal also helped to enter AI-controlled ‘mobs’, inclusive of large spiders, zombies, skeletons and various other creatures. As these creatures wanted to get hold of our Earth, so they started to kill humans and when the human army fought back at their destruction, a situation of war landed on our earth, a war of life, a war of survival, a war between us and them, a war between Earth and Aliens.

In this war, both the parties agreed upon some rule that they must follow:

Players (the army of earth fighting against these creatures in this war) take the first turn at attacking Aliens (The army of the creatures that entered through the portal as mentioned before). The rule of the war is that the beings who get the resources change every time [N] beings (either Players or Aliens) kill an other being.

You shall be provided with the current number of kills by each party ([K1] and [K2] respectively). Can you determine which beings get the resources next, after [N] kills are conducted?

Input:
The first line of the input set contains the number of test cases [T]. The first line is followed by [T] lines, each containing three space-separated integers [K1], [K2] and [N].

Output:
In the output file, for each test case, print a single line containing the string "PLAYERS" if the Players get the resources or "Aliens” if the creatures get the resources.


#NEED FOR SPEED!  - P4

Tyler "Ty" Morgan, Sean "Mac" McAlister, and Jessica "Jess" Miller are part of a crew in Silver Rock, Fortune Valley along with their friend and mechanic Ravindra "Rav" Chaudhry. After a friendly race between them, Tyler's childhood acquaintance and fixer Lina Navarro arrives, with a job for them: steal a precious Koenigsegg Regera belonging to Marcus "The Gambler" Weir with some high level tech inside. Tyler, posing as a test driver, successfully steals the car and evades the police. However, as he arrives at the drop point, he finds Rav knocked out. 
Lina appears, revealing that she set up Tyler and his crew to take the fall for the stolen car and she drives away, leaving them at the mercy of the oncoming police force. Now for continuing their setup, Tyler need to lead the Police Car away from his way and the biggest challenge, he is going to face is the Grid Racing Ground which is one of the oldest and trademark racing grounds of Silver Valley that is free of obstacles and made like a matrix grid allowing the professional drivers to test acceleration, break, drift and stability of a new proposed model. But due to the free space in the Grid Racing Ground, Tyler’s smooth plan gets a big threat as he can’t skip the Ground in any way. So he needs to figure out the intersection time of his Car & the Police Car. Tyler has an edge in this escape plan from as his beast, the Lamborghini Aventador has a super nitro mode that will help him a lot in this Escape.
Tyler needs your help and he gave these details to us to provide you help him figuring out the precise time (if there is a chance of meet/hit).

The Grid Racing Ground is much like an n x n matrix. 
The Police car approaches from North to South (can be considered along a particular column) at a time with a constant velocity [ V ].
At that particular moment, only one car is approaching according to the given direction.
This event of a Police approaching is called a Catch denoted by [F].
A Catch can start from any point in the Grid.


Tyler’s car is standing at any random given point along the leftmost side of the wall and is ready to run from West to East (Can be considered across the row) to outrun the above mentioned police car.
Tyler’s Car is the only car that will approach east at that moment.
Tyler’s car has zero initial velocity but some acceleration [A]. 
Tyler’s car follows a straight line along the row from where he started, until they reach the opposite side and escape or come across the police car and get caught.

You need to find out after how much second Tyler’s Car will hit/meet the Police Car according to their starting point, approach direction, velocity and acceleration so that Tyler can have a precaution and can escape easily keeping in mind the time of meet. Also, if there is no chance of meet/hit, return -1 and give Tyler a heap of relief.

P.S. Tyler has sent you an advance Thank you letter.
Input:
First line of the input file contains [T], number of test cases. It is followed by [T] numbers of pairs of lines.
The first line of each pair contains [Rb], [Cb] and [V],that denotes the row number, column number and velocity of the Police Car respectively for the corresponding test case.
The second line of each pair contains [Rc], [Cc] and [A], row number, column number and acceleration of MAC’s Car respectively for the corresponding test case.

Output:
The output file contains the required number of seconds for each test case, in separate lines.

Sample:
Input-                          Output-
2
10 6 23                        
5 8 44                          -1
42 54 32 
64 32 56                        0.1989

-----------------------------------#!--------------------------------------


#DEVIL MAY CRY! - P5
After the incident of Fortuna, the former knight now hunter Nero starts to build a branch for Devil May Cry, with his new partner & gunsmith Nico Goldstein, daughter of Agnus. Just then, a hooded man barges in and rips the Devil Bringer off of Nero in his own home, leaving him to die bleeding with Yamato in the hooded man's hands.
Regaining consciousness, Nero climbs to the top of the tree, alongside the mysterious V who is helping him, just to see Dante, Trish and Lady fighting the new demon king, Urizen. The trio gets easily defeated by the immense power of the king, and Nero is forced to escape the scene by Dante with the help of V.
It is later revealed that V was the one who hired Dante and his friends to take down Urizen, however, after they are defeated, V decides to rely on Nero's help  with his newly equipped Devil Breakers as a replacement for his lost arm. During the mission, overhearing information from demons, such as Malphas, in their plan to destroy the Devil Sword Sparda, V and his Familiars seek it out before them. Once acquired, V finds Dante in what seems like a comatose state. But when he was about to break the door, he saw an Encryption System on it without which the door could not be broken. 
The Encryption system shows the hint for decryption that V summarised to us like this and he needs your help to decrypt it:
The System has a letter written on it. And blinks another letter, that I have to place either on the left or on the right. When I place the blinking one, a third letter (Third because, one was previously on the system and one I placed) which I have to place again in the left or right of this string of length two, and when this blinking alphabets ends and I am done with letter placements, the system will check whether the string is alphabetically in the last position of the dictionary (Considering different arrangements as different positions), if it is not I will be killed by a poisonous jelly immediately thrown by the system after a wrong entry) 
For example, for S = DAB, after writing the word D on the whiteboard, the contestant could make one of the following four sets of choices:
put the A before D to form AD, then put the B before AD to form BAD
put the A before D to form AD, then put the B after AD to form ADB
put the A after D to form DA, then put the B before DA to form BDA
put the A after D to form DA, then put the B after DA to form DAB
The word is called the last word when the contestant finishes writing all of the letters from S, under the given rules. The contestant wins the game if their last word is the last of an alphabetically sorted list of all of the possible last words that could have been produced. For the example above, the winning last word is DAB (which happens to be the same as the original word). For a game with S = JAM, the winning last word is MJA.

Think you need to decrypt the system that has shown you the string [W]. What's the winning last word that you should produce?
    
Input:
The first line of the input file provides the number of test cases [T]. The first line is followed by [T] lines, each line containing a sequence [Wi] for each test case.


Output:
For every test case, output in every line contains “Instance #i:  Zi” , where i is the test case number and [Zi] is the optimal sequence generated for the ith test case. So , in total there’s going to be [T] lines of output.

Sample:
Input-                               Output-
2
FERRARI                              RRRFEAI
LAMBORGHINI                          ROMLABGHINI

-----------------------------------#!--------------------------------------
TETRIS -> PRIME X FIBONACCI
MINECRAFT -> 50 RANDOM WORDS
HALF-LIFE -> mineC
NEED FOR SPEED -> Tetris
DEVIL MAY CRY -> NFS
