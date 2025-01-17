# Empirical Accuracy
Demystifying Statistical Analysis of Shooting

The purpose of this text is to establish repeatable testing concepts for precision shooting.

## BLOT (Bottom Line On Top)

Most mid-tier rifles with mid-tier optics running mid-tier ammunition will outperform most shooters. More than a handful of "budget" rifle brands will do the same. There is no incantation you can say over a bag rest or magical rune to carve into the turret ring to make precision shooting "easy." Outshooting a store-bought rifle is hard, and nothing is changing that. Anyone telling you differently is selling something.  

## What is "Precision Shooting"?

For this guide, "Precision Shooting" will be defined as the intentional discharge of a firearm with a high degree of accuracy. Two major shooting disciplines include:

*   **Hunting:** In this context, precision shooting enables the hunter to evaluate their system to determine if they can ethically harvest game.
*   **Competition:** Precision shooting in competitive settings typically involves organized events where participants aim (pun intended) to achieve the highest possible scores by shooting targets from various distances and positions. Most competitions also include a time element.
  
Both disciplines require proficiencies such as calculating the effects of distance, understanding environmental (weather) conditions, and executing proper shooting techniques.

Other disciplines include military and law enforcement. These are outside the scope of this guide. The focus will primarily be on competition shooting and applying those concepts, where applicable, to improve hunting proficiencies.

## Budget

Shooting is expensive, and it seems to be getting more expensive every year. Following this guide will not be cheap. One of the many goals is to prevent the waste of time and materials. It will feel more expensive upfront (because it will be).  The first step in collecting data is pulling the trigger.  Every piece of data collected early will make testing/troubleshooting less expensive in the future.

## Skip the Filler...

This guide assumes that the reader knows the basics of firearms and ammunition. The temptation to fill the first 70 pages with definitions of trigger shoes and black powder burn rates will be resisted. That is what the index is for.

## The Old Ways

My first scoped rifle was sighted in using three-shot groups. I was instructed by my father to fire three shots before adjusting the scope. I did as instructed, and with a little less than half a box of .30-06 Core-Lokt remaining, he and I were both satisfied that the rifle was "sighted in." For most of my life afterward, I evaluated rifles and ammo based on three-shot samples. Why wouldn't I? Countless game have been harvested with rifles sighted in based on three-shot samples. It is simple, cheap, and, more importantly, it works!

## Then the Internet...

It doesn't take long to realize that there are as many different ways of evaluating rifles and ammo as there were fathers and sons at the range... and they all seem to work just fine. Forums are filled with hundreds, if not thousands, of accounts of inherited processes that "just worked." But something felt off. How can so many different processes have the same results? I hesitantly realized that the old ways might actually be based on belief and faith. It was devastating to also realize that an overwhelming majority of internet content was selling snake oil to reinforce those beliefs and faith. This industry is one step away from selling magic crystals to help align your rifle's chi and copper socks to stop distortions in your humor's harmonics. The internet is full of people either trying to sell you nonsense or trying to justify having bought into the nonsense. Some truly believe their product is working, and some are just lying. A video of a 1/4 MOA three-shot group on the internet is as useful as a video of a hole-in-one at a driving range. That golfer might have only taken a handful of swings that day. It doesn't mean that club can now be sold as a hole-in-one club.

## The Proof is in the LLN

According to the Merriam-Webster dictionary, the Law of Large Numbers is "a theorem in mathematical statistics: the probability that the absolute value of the difference between the mean of a population sample and the mean of the population from which it is drawn is greater than an arbitrarily small amount approaches zero as the size of the sample approaches infinity."

If you read the above and it makes perfect sense, congratulations; you do not need this guide. If you read that and thought, "WTF does this have to do with a rifle?" then you might be the target audience.

A more jargon-free definition is provided by Wikipedia. To quote Wikipedia, "The law of large numbers is a mathematical law that states that the average of the results obtained from a large number of independent random samples converges to the true value, if it exists."

If someone flips a coin three times and it lands heads-up three times, you instinctively know there is not enough information to prove that the coin will always land heads up. No one would pay a premium for that coin. We all instinctively know that that coin isn't any better at landing heads-up than any other coin. Landing a coin heads up three times doesn't make it a "heads-up coin" any more than printing a sub-MOA three-shot group makes a rifle a sub-MOA rifle. How many coin tosses does your instinct tell you to take before you start to believe the coin is different from the average? Ten tosses? Fifty tosses? A thousand tosses? For whatever reason, humans seem to be better at detecting bad sample rates in simple systems but then easily accept bad sample rates in complex systems. The good news is that many rational people figured out the need to remove human bias from the process. When a slight human bias is the difference between winning a war or not, or launching a successful product or not, these entities have successfully resorted to the LLN. One random taste test for a new product is less useful than 50 taste tests. One participant in a drug trial is less useful than 5,000 participants.

## Data is King... A Better System

Use every piece of data. Every shot not recorded is wasted data.

### Make a Baseline

In its most general sense, a baseline is a starting point or a reference point against which future measurements, observations, or comparisons are made. It represents the initial state or condition before a change, intervention, or experiment is introduced.

Shoot in an environment with the fewest variables. Do your best to eliminate variables you can and to control the variables you can't. A good scenario is something like bags on a bench in an indoor range. Better would be a shooting fixture. I don't have access to a shooting fixture, and I don't have access to a bench. I do have access to an indoor range. I'm not physically able to shoot prone for more than a few minutes. The baseline used in this guide was collected from an indoor range, with a forend bag and a shoulder support rear, with me sitting on a bar stool.  

Log the x and y distance of every shot from the point of aim. I design targets in Paint and print them with my office printer. I use a triangle to create an infinitely small point of aim, and I have my elevation and windage adjusted so I'm putting holes away from the point of aim. I wait until I get home to use a cheap pair of calipers to measure the distance from the point of aim. I record everything in millimeters so everything is in whole numbers. I also find it easier to convert to MRADs with whole numbers. I log everything into a spreadsheet.  A sharpy, paper-plates and a ruler will work just a well.  I use a office printer becuse I have one.  Its not a requirment.  

### How Much Data is Enough

Check for normality with the Shapiro-Wilk test. The Shapiro-Wilk test is a way to check if a set of data is likely to have come from a normal distribution (the bell curve). It gives you a score (W) and a p-value. The formula to calculate W is (Σ aᵢ * xᵢ)² / Σ (xᵢ - x̄)². If the p-value is low (usually below 0.05), it suggests your data is probably not normally distributed. Shapiro-Wilk is commonly used in statistics to ensure data meets certain assumptions before using other tests. Expect to collect around 20 impacts. Thirty is better. Fifty is about the maximum you will ever need. In my experience, I don't often see a p > 0.05 until around 20 shots. It's so common that I just assume I will be starting at 20, and I make my targets accordingly. Don't skip the "flyers." There is a process to account for outliers.

### Extreme Spread: Group Size is Least Useful

Don't base your system entirely on group size (extreme spread). Extreme spread tells you how bad the two worst shots were. Small group sizes limit the chance of a higher extreme spread. Ignoring "fliers" is introducing personal bias to the system. Combine all this, and it's a recipe for self deceit.  Each piece of data added (increasing sample size) makes your data as a whole more accurate. You are paying for the ammo; the least you can do is log every shot. Record the distance from the point of aim (x and y) and muzzle velocity (if you have a chronograph).  Dont get too hung up on the chronograph.  Muzzle verlocity is a nice to have, not a got to have.  Its basically irrelavant until you are pushing out beyond 500 yards.  Until you are shoting ELD the muzzle velocity is basically an indicatory of consistency.

But!  Extrem spread and small shot groups can be very usefull  in determining the health of your system.  If you bought a $7k sub 1/2 MOA rifle and your first 3 shots have an extreme spread of 6 inches that is a indicator that your system is suffereing catastrific failure.  Insecure optics, faulty ammo, defective barrel... etc.  You obviously dont need to print 20 shoots if you spot a problem at three.

### 

### Mean Radius is More Useful

For this guide, the mean radius is the average distance of all impacts from the geometric center of the combined impacts. This metric provides a more comprehensive measure of precision (or lack thereof) than simply measuring the distance between the two farthest shots (extreme spread). Extreme spread measures the two worst shots. We care less about the two worst shots. We care more about how often you should be expecting the good shots.

Compared to the "old ways," calculating the


























# Empirical Accuracy
Demystifying statistical analysys of shooting.

The purpose of this guide is to evaluate repeatable concepts in the world of precision shooting.

## What is "Precision Shooting"?
For this guide, "Precision Shooting" will be defined as the designed intent to discharge a firearm with a high degree of accuracy. Two major shooting disciplines include:

Hunting: In this context, Precision Shooting enables the hunter evaluate their system to determin if they can ethically harvest game.

Competition: Precision Shooting in competitive settings typically as organized events where participants aim (pun intended) to achieve the highest possible scores by shooting targets from various distances and positions.

Both disciplines require proficiencies such as calculating the effects of distance, understanding environmental (weather) conditions, and executing proper shooting techniques.

Other disciplines include Military and Law Enforcement. These are outside the scope of this guide. The focus will be primarily on competition shoots and applying those concepts, where applicable, to improve hunting proficiencies.

## Budget
Shooting is expensive, and it seems to be getting more expenzive every year.  Following this guide will not be cheap.  The hope is to prevent waste of time and materials.  It will feel more expensive up front (becuse it will be).  Every peice of data collect early will make testing/troubleshooting less expensivve in the future.   

## Skip the filler...
This guide is going to assume that the reader knows the basics of firearms and ammunition. The temptation to fill the first 70 pages with definitions of trigger shoes and black powder burn rates will be resisted. That is what the index is for.

## BLOT (Bottom Line On Top)
You don't need to do anything extraordinary to acquire competition-quality hardware.

Most mid-tier rifles with most mid-tier optics running most mid-tier ammunition will outperform most shooters. More than a handful of "budget" rifle brands will do the same. There is no incantation you can say over a bag rest or magical rune to carve into the turret ring to make precision shooting "easy". Outshooting a store-bought rifle is hard, and nothing is changing that. Anyone telling you different is selling something.

## The old ways
My first scoped rifle was sighted in using 3-shot groups. I was instructed by my father to fire three shots before adjusting the scope. I did as instructed, and with a little less than half a box of 30-06 Core-Lokt remaining, he and I were both satisfied that the rifle was "sighted in". For most of my life afterward, I evaluated rifles and ammo based on three-shot samples. Why wouldn't I? There have been countless game harvested with rifles sighted in based on three-shot samples. It is simple, cheap, and, more importantly, it works!  

### Then the internet...
It doesn't take long to realize that there are as many different ways of evaluating rifles and ammo as there were fathers and sons at the range... And they all seem to work just fine.  Forum filled with hundreds if not thousands of accounts of inherated process that "just worked".  But something felt off. How can so many different processes have the results? I hesitantly realized that the old ways might actually be based on belief and faith.  It was devastating to also realize that an overwhelming majority of internet content was selling snake oil to reinforce those beliefs and faith.  This industry is one step away from selling magic crystals to help alligh your rifles chi and copper socks to stop distortions in your humor's harmonics.  The internet is full of people either trying to sell you nonsense or people trying to justify having bought into the nonsense.  Some truely belive their producting is working and some are just lying.  A video of a three shot group on the internet is as usefull as a video of a hole-in-one in a golf tournament.  That golfer might have only taken a handfull of swings that day.  It doesnt mean that club can now be sold as a hole-in-one club          

## The proof is in the LLN
According to the Merriam-Webster dictionary, the Law of Large Numbers is "a theorem in mathematical statistics: the probability that the absolute value of the difference between the mean of a population sample and the mean of the population from which it is drawn is greater than an arbitrarily small amount approaches zero as the size of the sample approaches infinity."

If you read the above and it makes perfect sense, congratulations; you do not need this guide. If you read that and thought, "WTF does this have to do with a rifle?" then you might be the target audience.

A more jargon-free definition is provided by Wikipedia. To quote Wikipedia, "The law of large numbers is a mathematical law that states that the average of the results obtained from a large number of independent random samples converges to the true value, if it exists."

If someone flips a coin 3 times and it lands heads-up three times, you instinctively know there is not enough info to prove to you that the coin will always land heads up. No one would pay a premium for that coin. We all instinctively know that that coin isn't any better at landing heads-up than any other coin. Landing a coin heads up 3 times doesn't make it a heads-up coin any more than printing a sub-MOA 3-shot group makes a rifle a sub-MOA rifle. How many coin tosses does your instinct tell you to take before you start to believe the coin is different from the average? Ten tosses? Fifty tosses? A thousand tosses? For whatever reason, humans seem to be better at detecting bad sample rates in simple systems but then easily accept bad sample rates in complex systems. The good news is a lot of really rational people figured out the need to remove the human bias from the process. When a slight human bias is the difference between winning a war or not, or launching a successful product or not, these entities have successfully resorted to LLN.  One random taste test for a new product is less usefull that 50 taste tests.  I partecepent in a drug trial is less usefull than 5000 partecipents.  

## Data is king... a better system
Use every peice of data.  Every shot not recorded is wasted data.

### Make a baseline
In its most general sense, a baseline is a starting point or a reference point against which future measurements, observations, or comparisons are made. It represents the initial state or condition before a change, intervention, or experiment is introduced.

Shoot in an enviroment with the least abount of variables.  Do your best to eleminate variables you can and to control the variables you cant.  Best case is somthing like bags, on a bench, in an indoor range.  Better would be a shooting fixture.  I dont have access to a shooting fixture, and I dont have access to a bench.  I do have access to an indoor range.  Im not physically able to shoot prone for more than a few minutes.  The baseline used in this guide was collect from an indoor range, with a forend bag and a shoulder support rear, with me sitting on a bar stool.       

Log the x and y distance of every shot from the point of aim.  I design targets in paint and print them with my office printer.  I use a triangle to create an infintly small point of aim and I have my elevation and windgage adjusted so im putting holes away from the point of aim.  I wait until i get home to use a cheap pair of calipers to mesure the distance from point of aim.    I record everything in millimeters just so everything is in whole numbers.  I also find it easier to convert to mrads with whole numbers.  I log everything into a spreadsheet.

### How much data is enough
Check for normality with Shapiro-Wilk test.  The Shapiro-Wilk is a way to check if a set of data is likely to have come from a normal distribution (the bell curve). It gives you a score (W) and a p-value. The formula to calculate W is (Σ aᵢ * xᵢ)² / Σ (xᵢ - x̄)².  If the p-value is low (usually below 0.05), it suggests your data is probably not normally distributed. Shapiro-Wilk is commonly used in statistics to make sure data meets certain assumptions before using other tests.  Expect to collect around 20 impacts.  30 is better.  50 is about the max you will ever need.  In my experiance I dont often see a p>0.05 until around 20 shots.  Its so commmon that I just assume I will be starting at 20 and I make my targets accordingly.  Dont skip the "flyers".  There is a process to account for a outliers.    

### Extreme Spread: Group size is least useful.
Dont base your system enterly off group size (extreme spread).  Each piece of data added (increasing sample size) makes your data as a whole more accurate. You are paying for the ammo; the least you can do is log every shot. Record the distance from Point of Aim (x and y) and muzzle velocity (if you have a chronograph).  Extreme Spread tells you how bad the two worst shots were.  Small group sizes limits the chance of a higher extreme spread.  Ignoring "fliers" is intruducing personal bias to the system.  Combine all this and its a receipe for deceit.



### Mean Radius is more useful.
For this guide, the mean radius is the average distance of all impacts from the geometric center of the combined impacts. This metric provides a more comprehensive measure of precision (of lack of) than simply measuring the distance between the two farthest shots (extreme spread). Extreme spread measures the two worst shots.  We care less about the 2 worst shots.  We care more about how often you should be expecting the good shots.

Compared to the "old ways," calculating the mean radius is much more difficult. The basic concept is determining the center of the group, measuring each printed shot from the center, then finding the mean of each shot printed. The formula to calculate the MR is as follows: √((x₂ - x₁)² + (y₂ - y₁)²) where (x₁, y₁) are the coordinates of the group center and (x₂, y₂) are the coordinates of the shot hole.

Don't let the equations turn you off from the process. Your phone has more compute power than the entire solar system had in the 1950s; technology will make this process simple.

Beyond the hardware... PPPP
Position
Picture
Pull
Practice

First you gotta’ hit it.
In competitive shooting, placing a shot is good enough. Holes in the paper determine the score; the score determines the success. In hunting, the shooter needs to be mindful that success has an ethical element. This guide will tend to focus on the optimization of hit placement above all other considerations. This means a target-focused competition rifle is, IMHO, mostly unfit for harvesting game. In competition, safety is paramount, and hit placement is next. In hunting, safety is paramount, and ethics is next.

TODO: Add examples of ladder targets and an Excel spreadsheet with formulas. ARA unlimited class target.

Circular Error Probable (CEP): A measure of dispersion

Extreme Spread (ES): A measure of dispersion

Horizontal and Vertical Variances: Measures of dispersion

Mean Radius (MR): A measure of dispersion
