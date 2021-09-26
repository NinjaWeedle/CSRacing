 _____   ___   ____
|       /     |    |
|       \__   |____|
|          \  |    \
|_____  ___/  |     \ACING - The ultimate drag race.

CALCULATOR STREET RACING V1.0

A drag racing game written by Oxiti8 in pure TI-BASIC for the TI-84 Plus.

The ultimate drag racing game for the 84+ has arrived! Collect, Race and Upgrade 30 different cars, or create your own car from the ground up and share it with the world. 
Compete in 5 different event types- Climb the rankings in officially sanctioned Ladder races, assert your racing prowess over CSR's best racers in the challenging Crew Battle mode, 
demonstrate true mastery of your car in Car Specific races, just make some quick cash in Regulation races, or, once you've completed all the other modes, experience the freedom of Custom Spec races. 
The game's shell compatible, too. Can you conquer the drag strip?

Github: https://github.com/NinjaWeedle/CSRacing - If there's a new version of CSRacing, you'll find it here first.
Cemetech topic: https://www.cemetech.net/forum/viewtopic.php?t=17903 - Check out this forum topic for the latest updates on CSRacing!
_________________________________________________________
Table of contents:

I. GETTING STARTED
 1: How to install Calculator Street Racing on your TI-84+
 2: How to play
 3: Game modes
 4: CSR Garage

II. CSRACING IN DEPTH
 5: Tips & Tricks
 6: The 3 Crews
 7: Car List
 8: Guide to creating a car

III. EXTRA INFORMATION
 9: Developer's Notes & Technicalities
 10: A short guide to CSRacing jargon
 11: Credits and License
_________________________________________________________

< I. GETTING STARTED >


1. HOW TO INSTALL:

Send CSRACING.8xp and CSRGARAG.8xp to RAM. (Or send CSRACING.8xp to archive if using a shell like MirageOS or Doors CS7)


2. HOW TO PLAY:

Navigating the main menu is simple - press one of the top five buttons (Y=, WINDOW, ZOOM, TRACE, or GRAPH) to select an option.
 - Press GRAPH to select "RACE" and access the event list.
 - Press TRACE to select the "TUNE" option and enter the upgrade shop. The upgrade shop allows you purchase performance parts to make your car faster.
 - Press WINDOW or ZOOM to select the "CSR GARAGE" option and open CSR Garage. (Refer to section 4 for more details on CSR Garage)
 - Press Y= to select the "QUIT" option and quit the game.

Racing controls: 

Press 2ND to start your engine and begin the countdown to launch. To rev quickly, repeatedly press 2ND. To rev slowly, press ALPHA (Or any key that isn't 2ND or ON). 
 - Pay attention to the text at the bottom of the screen- it'll tell you if your RPM is above, below, or at the number needed for the fastest launch.

Once the race begins, your car will begin accelerating automatically. Press the up arrow key to shift up, and the down arrow key to shift down.
 - Every car drives differently. The best time to shift, the number of gears, best launch RPM, and many other stats differ from car to car, and certain cars may not need to shift at all for shorter races.


3. GAME MODES

Upon selecting the "RACE" option in the main menu, you will be presented the event list that shows the different kinds of races you can enter.
Each mode has its own rules:
 
- Regulation: Any car with any upgrades can enter. After selecting this option, you'll be asked to enter a difficulty level, and after that, the track length.
The difficulty level is the MPH the opponent will travel at: Entering a difficulty of 10 will have the opponent drive at a constant 10 MPH, a difficulty of 35 equates to 35 MPH, and so on and so forth.
The higher the difficulty level, the better the rewards!
After entering the difficulty, you'll be asked to specify the length of the road. A length of 1 is the standard length, 2 is double length, 3 is triple length, 4 is quadruple length, and 5 is quintuple length. The track length does not affect the Cr. earned for winning, but does slightly increase the payment for losing.

- Ladder: Race your way through 25 increasingly challenging races! The Grand Prize is 5000 Cr. Beware though: If you lose a race, you'll be knocked down a spot on the ladder.

- Crew Battle: Take on the best drivers CSRacing has to offer. There are three crews to beat, with each crew having 3 members. Crews will only race you if you use a car from their respective tier, so you'll need to save up your Cr. to buy cars- but the rewards are worth it. (For more info, see section 6)

- Car Specific: A true test of car mastery. There is 1 race for each of the 30 cars- you need the car with the same CIN (Car Identifier Number) as the race number to be allowed entry- race #1 requires car #1 (Sivic Si), race #2 requires car #2 (Oxiti Increceba), and so on and so forth for all 30 races. You'll need to own all 30 cars the game in order to complete this mode. (Refer to section 7 to see cars listed by their CIN.)
   -- Beating a race in Car Specific mode will drop the price of creating a custom car by 3000 Credits per race, and beating all 30 races drops the price of car creation to 10000 Cr. Why? The guys over at R&D say seeing all these cars race helps lower development costs.
   -- After beating all 30 Car Specific races, opening up Car Specific mode again will bring you to Custom Spec mode. Press enter, and a difficulty selection screen not unlike that of regulation races- except instead of choosing the length, you can now set the launch speed (LAUNCH SPD?) and acceleration level (ACCEL. LV?) exclusive to the more advanced AI that appear in Crew Battles and Car Specific races. The launch speed is the MPH the opponent car starts at, and the acceleration level is the amount of MPH the opponent car gains per frame. Any car can enter these races!


4. CSR GARAGE

Upon starting CSR Garage, you have three options to choose from:

 - Change Car: Self explanatory. Selecting this option lets you swap to another car you own. 

 - Car Dealer: Buy cars here. 4 cars are available for purchase each day, with a total of 28 cars available for purchase. 
   -- If you're looking to buy a specific car, check the Car List (section 7) to find out which day of the week it is available for purchase.
   -- Once you purchase a car, you can get in it from the Change Car menu.

 - Create Car: Once you progress past a certain point in the game, you can come here to create a new car from scratch. 
   -- The initial cost of creating a car is 100000 Cr. per car- You can lower development costs substantially by winning Car Specific races as previously mentioned in section 3.
   -- Cars you create will dissappear once you switch to another car- If you want to save your creations, back up the list named "CAR" and String Variable Str1 to your computer. Once you've backed them up, you can also share your custom cars with your friends by sending them these variables.
   -- To load or restore a custom car, just send the files that contain the custom car data (namely CAR.8xl and Str1.8xs) to your calculator. They will appear in game when you next launch CSRACING. 
   -- Refer to section 8 for more details on car creation.


< II. CSRACING IN DEPTH >


5. TIPS & TRICKS

 - Good launches will earn you an extra 5 Cr, and Perfect launches will net you 10 extra Cr.
 - The key to the best shifts is to shift up the same frame the max speed in the current gear is reached- nailing the timing will let you constantly accelerate.
 - Upgrades scale in cost based on the tier of the car you're upgrading- Tier 1 cars are the cheapest cars to upgrade, and Tier 3 cars are the most expensive to upgrade due to their exotic nature.
 - Upgrades offer a noticeable performance boost, but buying faster cars is eventually necessary to stay competitive.
 - Regulation races are a great way to earn Cr. - Just make sure to keep the difficulty at a level your car can handle.
 - There are 10 Tier 1 cars, 14 Tier 2 cars, and 6 Tier 3 cars making for a total of 30 cars- can you collect them all?


6. THE THREE CREWS

In the Crew Battle mode, you'll have to race the three unique crew members of each crew in order to progress to the next tier. 
The third and final member of each crew is the crew leader- You'll have to beat Leaders three times to get them to concede.

- Tier 1 - The Flames
This crew is the first you'll face. They control the west side of town. Their cars may not be the fastest, but their knowledge of their rides makes them a force to be reckoned with.
  Tier 1 first opponent: Ito - Drives a Beetle. Ito bought his car while it was brand new and has carefully maintained and tuned it ever since. 
  Tier 1 second opponent: Steve O - Drives an Impala SS. He was the one who gave this crew its name. He loves doing burnouts, but as a result has spent hundreds of dollars on tires…
  Tier 1 leader: Winnace - Drives a Javelin-AMS. Winnace spent months restoring his Javelin before forming The Flames- His dedication has seemingly paid off, as no challenger has managed to defeat him in a race since. He's grown somewhat complacent as a result…


- Tier 2 - The Tuners
The leader of this crew, Kenido, runs CSR Garage alongside his older brother Mayeo in the east side of town. Some of the modifications they put on their cars aren't exactly street legal.
This crew loves to modify their cars. To show off the speed of their cars, the members of this crew race on a road double the length that The Flames do. You'll need to learn to time multiple gear changes right in order to win.
  Tier 2 first opponent: Ker - Drives a CRX SIR. Ker works as a detective. He joined The Tuners as part of an undercover operation to bust the local street racing scene (unbeknownst to Kenido). After realizing that this street racing could be a great tourist attraction for the financially struggling city, Ker managed to get a fairly long section of road legally sanctioned off for drag racing on the weekends. His job keeps him busy a lot, but his skill as a driver has kept him in the crew.
  Tier 2 second opponent: Mayeo - Drives a Supra. Mayeo and Kenido worked on this Supra for months.
  Tier 2 leader: Kenido - Drives a GTR R34. Kenido focuses on constantly improving the performance of his GTR- sometimes to the point of forgetting to do routine maintenance! He's also a bit immature.

- Tier 3 - Team Oxiti
This final crew appears to be short a member. What isn't short is the quadruple length, dedicated drag strip this crew races on- Speeds in excess of 100 MPH are inevitable!
  Tier 3 first opponent: Goomzo - Drives a 458 Italy. A true veteran of the scene, Goomzo's skill is no joke. Apparently, he's a distant cousin of Winnace.
  Tier 3 leader: Muncher - Drives a Mcl F1. Muncher doesn't have a lot of experience as crew leader, but his reasonable nature has kept him well respected by his 
  Original Tier 3 leader: Supposedly, the founder of Team Oxiti left to start a car company under the same name.


7. CAR LIST (by car identifier number):

1*: Sivic Si Coupe (2010) - The starter car. - Tier 1
2*: Oxiti Increceba - Beat the crew battle mode to unlock! - Tier 3
3: Beetle (2004) - Available Economy Car Mondays - Tier 1
4: Golf GIT (2005) - Available FWD Fridays - Tier 1
5: 458 Italy (2011) - Available Supercar Saturdays - Tier 3
6: 'Vette ZR1 (2009) - Available Supercar Saturdays - Tier 3
7: Dino 256 GT (1969)- Available Sunday Drive Sundays (Classic cars) - Tier 1
8: CRX SIR (1991) - Available FWD Fridays - Tier 2
9: McL F1 (1993) - Available Supercar Saturdays - Tier 3 (RECCOMMENDED)
10: Impala SS (1964) - Available Sunday Drive Sundays - Tier 1
11: Viper (2013) - Available Supercar Saturdays - Tier 3 (RECCOMMENDED)
12: Javelin-AMS (1971) - Available Sunday Drive Sundays - Tier 1 (RECCOMMENDED)
13: RX-7 Type RS (1998) - Available Tuner Thursdays - Tier 2 (RECCOMMENDED)
14: RS 6 (2003) - Available AWD Wednesdays - Tier 2 (RECCOMMENDED)
15: GT500 (2010) - Available Tier TWOsdays - Tier 2
16: DMC-12 (1981) - Available Economy Car Mondays - Tier 1
17: GTR R33 (1997) - Available Tuner Thursdays - Tier 2 (RECCOMMENDED)
18: Muira P400 (1967)- Available Sunday Drive Sundays - Tier 2
19: NSXR (1992) - Available Tuner Thursdays - Tier 2 (RECCOMMENDED)
20: CLK55 AMS (2003) - Available Tier TWOsdays - Tier 2 (RECCOMMENDED)
21: Coopa S (2003) - Available Economy Car Mondays - Tier 1 (RECCOMMENDED)
22: 350Z (2003) - Available Tier TWOsdays - Tier 2
23: WRX STI (2012) - Available AWD Wednesdays - Tier 2
24: Supra (1998) - Available Tuner Thursdays - Tier 2 (RECCOMMENDED)
25: Sentra SER (2007) - Available Economy car Mondays - Tier 1 (RECCOMMENDED)
26: Focus RS (2009) - Available FWD Fridays - Tier 2 (RECCOMMENDED)
27: EVO X (2012) - Available AWD Wednesdays - Tier 2
28: Neon SRT4 (2005) - Available FWD Fridays - Tier 1
29: GT-R R34 (2002) - Available Tier TWOsdays - Tier 2 (RECCOMMENDED)
30: Reventon (2008) - Available AWD Wednesdays - Tier 3 - The most expensive car in the game. You'll need 1,000,000 Cr. to purchase this!

*Cars with "*" next to their number cannot be purchased at the Car Dealer.


8. GUIDE TO CREATING A CUSTOM CAR:

This section explains each step involved in custom car creation. Refer to this when making a custom car.

1(NAME): Enter the name of the car.
2(MAX RPM): Max RPM(x1000) A.K.A redline - This is the max RPM the car can rev to. I recommend a number between 2 and 10 here, but any positive number should work.
3(BEST RPM): Best launch RPM - This is the number of RPM needed for a perfect launch. Use a whole number that's below the max RPM.
4(TOP SPEED): Actual Top speed - This is the Top speed of the car in Miles Per Hour- Keep this number positive and non-zero, or things will break.
5(GEARS): Number of Gears - The number of gears in the transmission. Enter a number between 1 and 6- anything higher than 6 or lower than 1 will be set to 6.
6(G1): Max MPH allowed in gear 1 - The top speed allowed in gear 1.
7(G2): Max MPH allowed in gear 2 - The top speed allowed in gear 2. If there is no 2nd gear, you should enter 0 for the smallest filesize but any number will do.
8(G3): Max MPH allowed in gear 3 - The top speed allowed in gear 3. If there is no 3rd gear, you should enter 0 for the smallest filesize but any number will do.
9(G4): Max MPH allowed in gear 4 - The top speed allowed in gear 4. If there is no 4th gear, you should enter 0 for the smallest filesize but any number will do.
10(G5): Max MPH allowed in gear 5 - The top speed allowed in gear 5. If there is no 5th gear, you should enter 0 for the smallest filesize but any number will do.
11(G6): Max MPH allowed in gear 6 - The top speed allowed in gear 6. If there is no 6th gear, you should enter 0 for the smallest filesize but any number will do.
12(ACCEL. LVL): Acceleration level (maximum increase in pixels moved per cycle) - how many MPH this car gains per frame. 0.1-1.4 is typical of Tier 1 cars, 1.6-2.4 is typical of Tier 2 cars, and 2.9-3.3 is typical of Tier 3 cars. Try to keep this number below 8 though or things WILL BREAK
13(RPM LOSS): Amount of rpm (x1000) lost per cycle while revving - This one's tricky but very important. I recommend a value of 0.1 for slow revving cars, 0.2 for most cars, and 0.25 for fast revving cars. REALLY fast revving cars should use 0.5. anything higher will have unexpected results.
14(SPD. LOSS): Reduction in speed gained in per gear (1.1 - ([THIS VALUE]* Current Gear) * Acceleration level) - This simulates a steady loss in acceleration as the car gets into higher gears. Setting this too high will result in the car going backwards in higher gears. A safe value is 0.1, but the Acceleration level and number of gears plays into this as well. A higher acceleration level means this stat can be higher- For example, cars with an acceleration level of 2 should keep this value at 0.18 or lower to not go backwards in 6th gear.
15(COLOR): Car color (AFFECTS CE ONLY) Same as the color values on the CE- 10=Blue, 11=Red, 12=Black, 13=Magenta, 14=Green, 15=Orange, 16=Brown, 17=Navy, 18=LtBlue, 19=Yellow, 20=White, 21=LtGray, 22=MedGray, 23=Gray, and 24=DarkGray. If you enter an invalid number, the color will be set to Black. Names won't work so don't try them.
(The car tier for custom cars is automatically set to tier 4.)

And your car is complete! You'll probably want to backup your creation to a PC for later use, so make sure to back up List CAR and Str1 before switching to another car.

If you want to cancel car creation at any point during the process, press ON and you will not be charged.


< III. EXTRA INFORMATION >


9. DEVELOPER'S NOTES & TECHNICALITIES:

 - This game was developed on a TI-84 Plus with a non-mathprint OS installed. Users with OS version 2.53MP or higher should enable CLASSIC mode for the best speed & compatibility.
 - While CSR Garage can only be accessed on a TI-84 Plus, the base game, CSRACING.8xp, should work on a TI-83 Plus as it does not use TI-OS time. Please note that TI-83 Plus users will only be able to use the Sivic Si as a result.
 - The cars in this game have the same gear ratios and top speeds of their real-world counterparts (The names are a bit different here due to copyright, but I'm sure you can figure out what cars they represent via the Developer's Documentation in the extras folder.)
 - Cars with electronically limited top speeds in the real world (i.e. 155 MPH) have their limiters removed here.
 - Races take a couple seconds to start due to how slow the Shade( command is at drawing.
 - If you get ERR: UNDEFINED after the title screen, it's likely because you deleted Str1. To fix this, launch CSRGARAG.8xp and switch to any car.
 - If List CAR is missing for whatever reason when launching CSRACING, the game will load the Sivic Si. Please note that this will reset that car's upgrade level to stock. If you lose List CAR and don't want your Sivic Si's upgrades reset, launch CSRGARAG instead of CSRACING and switch to any car.
 - A contrast level of highest 5 is recommended for this game. Please note that the contrast level may need to be higher or lower depending on your screen.
 - Almost all car data was pulled from FM4 and/or FH1. The three exceptions to this are as follows: The RX-7 Type RS, whose data was collected from GT2, the Sivic Si (misc. sources), and the Oxiti Increceba (created for CSRacing).
 - The file size for CSRACING.8xp and CSRGARAG.8xp are the exact same: 7258 bytes.


10. A SHORT GUIDE TO CSRACING JARGON

 - CSRacing = Calculator Street Racing
 - Cr. = Credits, the currency of CSRacing
 - CIN = Car Identifier Number. The Car Identifier number refers to the general order that cars were added to the game in.
 - Oxiti = A fictional car brand. 
 - Tune = refers to the act of tuning a car, in this case for performance.
 - Home = the homescreen of the game.


11. CREDITS, LICENSE AND CONTACT INFORMATION

Game created by Oxiti8 in 2021.

Special thanks to Mr. Womp Womp and fghsgh on Cemetech for help with optimization.

THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THIS SOFTWARE OR THE USE OR OTHER DEALINGS IN THIS
SOFTWARE.

Redistribution of this software is welcome, but this document MUST be accompany it.

Email: weedleninja88@gmail.com
Ticalc.org author profile: https://ticalc.org/archives/files/authors/117/11708.html