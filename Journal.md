# res_hardware_week_1
Week  one of resolution!! TBH IDK how to do ts lol so im kinda just doing all of this here

#### The starting tutorial
To be completely honest idk if they week one is just eh starter tutorial or if the challenge is nesscary🤷🏿‍♂️ but idk lol. But for the first circut where we 

# First 30 minutes (starter circut)
Ok for the start circut i thought this would be easy bc i have some electornics at home (although i've pretty much never gotten past the 3rd project which is why im doing ts now) but like ts took me 30 minutes lol😭😭😭 I'm kinda just do the question and answer format cuz i've never jornaled before....


### 1. Project Goal
The goal of doing the starting project was so i can get familar with the software and also so i can learn how to read schematic's. ALthough i have a starter kit at home i've pretty much been following the bread board design and such at the schematic/ the corret way
### 2. Why did I design it this way?
Cuz of the tutorial lol
### 3. How did I build it?
I built it using falstad, a switch, resistor, capicitor, battery/power, LED
### 4. Problems Encountered
Ok the problem that i encountered was trying to build the parrel circut. it fr took like 15 min of debugging lol. But the main problem was that i didn't folow this flow "Voltage source → switch → resistor → LED → ground" Rather my project looked more like " Voltage source -> switch -> resistor -> LED -> ground with the capcitor connecting to the endpoint of LED". What i did was experiement on wheather or not it was the simulation/current speed causing the problem or like if it was how i wired it. I tried to add wires like this "Left cornor, wire, led, 1 endpoint of the capcitor, wire switch". But then i looked at the GIF inside the tutorial and added the switch ontop. Until i finally looked at the flow of the electricity and relized i needed to flip the way the voltage is going to it goes counter clockwise rather than clockwise. But this made me relize how much teh flow matters
### 5. What happened when I tested it?
So i mainly tested it by changing the amont of storage the capistor can store and the amont of restance in the resitore. The more resistant the slower the partcles moved. The more of basically anything made the LED lasted a lot more longer when the switch was off. Pretty cool. And btw the last analogies about the buck and water was fire. It genuiely made me understand electronics LOL



# Final PROJECT (KINDA)!!!!!

## 1. Project Goal
Build a Circut where LED's Light up but with a couple second delays and each Light gets dimmer over time. Optionally Make them all close at the same time
## 2. Initial Idea/Research
Ok so TBH i lowkenly took an hour doing the first cricut so i think i should keep this circut simple so i don't frustrate myself. I'm try and do the suggest project where like the LED all light up in almost a second delay and perchance MAYBE if i have time try and get it
## 4. Detailed Design
This isecond is for the intial disign/idea

Ok so i think this simple shouldn't be too hard. IM thinking i would loook like this (DC SOURCE -> switch (so the power source can cut off instantly) -> wires & Resistor (smalll amount) -> LED1 -> resitor (meduim) -> LED 2 -> resitor -> LED 3

## 3 hours laterr
so im kinda crashing out cuz i still can't get it to work quite litteraly 3 hours later. I decided to give up cause i still hadn't been able to get a 3rd led to fit in and its litteraly been 3+ hours (i started this at about 6:40) and it got to the point where i had to use AI to ask it questions and such about 2 hours in but like idk i felt like i wasn't learning anything and ts was giving such horrible suggestions. Also its like midnight for most ppl so i can't really ask slack atp. Like it just won't work as in some problems i encountered:

1. Someitmes the LED would be like turned on on both sides so like of course the flow wouldn't work
2. When evr i try to connect 2 LED the other LED would just go completely off
-ALthough i was able to find out the solution for this. I litteraly just needed to connect every single end point to its own wire rahter than just using 1 wire for all of ground and power/rail
3. Whenever i turned off the switch it would litteraly just start flowing the other way which PMO or like one part would suddenly turned on.

Some things i tried: 1. I made all the LED's parrell to eachother rather than just resitors or capsitors parrel to eachother

here are some pictures;

-----OK i can't copy and paste or drag or drop so ima ust add to a file


# FINAL FINAL FINAL PROJECT
ok hopfeuly ts can work but honest i have low hopes. genuiely im so freaking cooked if its taking me this long for day one..... ima just give up if i can't get this done:

## 1. Project Goal
Ok this is going to be very simple (hopefully) i just want a circut that can turn on turn on 2 led's but one with a 1 second delay
Ok so i kinda thought i might be able to wing the last project and did not really look into RC timing cuz i saw all that made and kinda thought i can wing it. Maybe seeing this circut might help me
## 2. initial Idea/Research
OK this is a big one so i kinda searched it up and it ain't really that bad. Its litteraly just R * C = Time. Ima just do a littel test with this image i found from instructables that was really helpful in just getting a visual feeling on how it's supposed to work  here is the article: (genuiely PEAK and so understandble🥹"https://www.build-electronic-circuits.com/rc-delay-element/")
The goal of this test was just to get on light bulb to delay  inside a super simple circut nothing fancy
OMG OMG OMG OMG OMG OMG IT WORKED!!! I'm so freaking glad. And I've only been working on this one for about 30 minutes !!! (atleast according to my timer) NOW we can do into a more detialed deisgn
## 3. Detailed Design
Ok so idk what to put here TBH so ima just describe the flow of the circut LOL
So it goes like " DC (5v) pos -> Regular switch -> 1k ohms of resitance, -> || SPIT || Bottem  => Capcitor (1mF)     Right  => Wire -> Led going back ground  || SPLIT RECONNECT ||  A write connecting all the differnt downward lines to the ground part of the DC
## 4. Testing
1. THe first tests was to recomfirm if i really do need to wire between every new connection connection rather than connnecting mutiple wire to a middle of a wire. SO i did test it out and the circut did NOT work unless i did the wiring between every connect i wanted to make.

## 5. Problems Encountered
1. Ok so the problem that i once again encounters was that my circut after being switched off would still keep on going. And turns out this is kinda the point😭🙏🏾 I'm crine why did it took me this long to figure out. I did some calculations and i though it was only going to take like 1 second but i took like a good 20 with the falst lab probably because of he werid time. Now my simulation speed is on max so it truely takes about a second!!!
2. OK after the second iteration im a litte bit sad bc the 2nd LED isn't as bright so it doens't look as cool so ima try and fix ts. Ok so the thing is i though lowering resitance and increasing the capicitor's would do it but i actually just made it hard to tunr off so an equlibaruim would probably be best. I guess the next bext thing to do would be to do transitors
## 6. Iterations/Improvements
####First version with just one LED (FIRST WORKING CIRCUT):
<img src="./Failed final circit gif.gif)" alt="Working circut with just 1 LED" width="50%"/>

Ok now onto the second iteration. I'm hopefully have mutiple LED so im just try and copy the end of the 1st circut and see how it goes. OK IT WORKED!!! SO LIKE IT TURNS ON TOGETHER KINDA AT DELAYED RATES BUT KINDA JUST TURNS OFF TOGETHER IM TECHNICALLY DONE!!!!
<img src=".v2 RC delay circ.gif)" alt="Working 2nd LED" width="50%"/>


## 7. Reflection




