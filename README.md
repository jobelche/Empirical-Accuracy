# Empirical Accuracy
Demystifying Statistical Analysis of Shooting

The purpose of this text is to establish repeatable testing concepts for precision shooting.

## BLUF (Bottom Line Up Front)

Most mid-tier rifles with mid-tier optics running mid-tier ammunition will outperform most shooters. More than a handful of "budget" rifle brands will do the same. There is no incantation you can say over a bag rest or magical rune to carve into the turret ring to make precision shooting "easy." Outshooting a store-bought rifle is expensive and hard, and nothing is changing that. Anyone telling you differently is selling something.  

## What is "Precision Shooting"?

For this guide, "Precision Shooting" will be defined as the intentional discharge of a firearm with a high degree of consistency. Two major shooting disciplines include:

*   **Hunting:** In this context, precision shooting enables the hunter to evaluate their system to determine if they can ethically harvest game.
*   **Competition:** Precision shooting in competitive settings typically involves organized events where participants aim (pun intended) to achieve the highest possible scores by shooting targets from various distances and positions. Most competitions also include a time element.
  
Both disciplines require proficiencies such as calculating the effects of distance, understanding environmental (weather) conditions, and executing proper shooting techniques.

Other disciplines include military and law enforcement. These are outside the scope of this guide. The focus will primarily be on competition shooting and applying those concepts, where applicable, to improve hunting proficiencies.

## Budget

Shooting is expensive, and it seems to be getting more expensive every year. Following this guide will not be cheap. One of the many goals is to prevent the waste of time and materials. It will feel more expensive upfront (because it will be).  The first step in collecting data is pulling the trigger.  Every piece of data collected early will make testing/troubleshooting less expensive in the future.  

## Skip the Filler...

This guide assumes that the reader knows the basics of firearms and ammunition. The temptation to fill the first 70 pages with definitions of trigger shoes and black powder burn rates will be resisted. That is what the index is for.

## The Old Ways

My first scoped rifle was sighted in using three-shot groups. I was instructed by my father to fire three shots before adjusting the scope. I did as instructed, and with a little less than half a box of .30-06 Core-Lokt remaining, he and I were both satisfied that the rifle was "sighted in." For most of my life afterward, I evaluated rifles and ammo based on three-shot samples. Why wouldn't I? Countless game have been harvested with rifles sighted in based on three-shot samples. It is simple, cheap, and, more importantly, it was good enough!  

## Then the Internet...

It doesn't take long to realize that there are as many different ways of evaluating rifles and ammo as there were fathers and sons at the range... and they all seem to work just fine.  The change came when good enough wasnt good enough... only MOA was good enough.  Forums are filled with thousands, if not millions, of accounts of inherited processes that took a good enough riles to a SUB MOA rifle.  But something felt off. How can so many different processes have the same exacting results? I hesitantly realized that the old ways might be good enough to prove a rile "good enough" but can in no way prove a rifle SUB MOA.  It was devastating to also realize that an overwhelming majority of internet content was selling snake oil to reinforce using the old ways to prove a SUB MOA rifle. This industry is one step away from selling magic crystals to help align your rifle's chi and copper socks to stop distortions in your humor's harmonics. The internet is full of people either trying to sell you nonsense or trying to justify having bought into the nonsense. Some truly believe their product is working, and some are just lying.  The even have video proof.  A video of a 1/4 MOA three-shot group on the internet is as useful as a video of a hole-in-one at a driving range.

## The Proof is in the LLN

According to the Merriam-Webster dictionary, the Law of Large Numbers is "the probability that the absolute value of the difference between the mean of a population sample and the mean of the population from which it is drawn is greater than an arbitrarily small amount approaches zero as the size of the sample approaches infinity."

If you read the above and it makes perfect sense, congratulations; you do not need this guide. If you read that and thought, "WTF does this have to do with a rifle?" then you might be the target audience.

A more jargon-free definition is provided by Wikipedia. To quote Wikipedia, "The law of large numbers is a mathematical law that states that the average of the results obtained from a large number of independent random samples converges to the true value, if it exists."

If someone flips a coin three times and it lands heads-up three times, you instinctively know there is not enough information to prove that the coin will always land heads up. No one would pay a premium for that coin. We all instinctively know the coin isn't any better at landing heads-up than any other coin. Landing a coin heads up three times doesn't make it a "heads-up coin" any more than printing a sub-MOA three-shot group makes a rifle a sub-MOA rifle. How many coin tosses does your instinct tell you to take before you start to believe the coin is different from the average? Ten tosses? Fifty tosses? A thousand tosses? For whatever reason, humans seem to be better at detecting bad sample rates in simple systems but then easily accept bad sample rates in complex systems. The good news is that many rational minded people figured out processes to remove human bias from the process. When a slight human bias is the difference between choosing the right player in a draft or not, or launching a successful add compain or not, these people have successfully resorted to the LLN. One random taste test for a new product is less useful than 50 taste tests. One participant in a drug trial is less useful than 5,000 participants.

## Data is King... A Better System

Use every piece of data. Every shot not recorded is wasted data.  The end goal is to have a working database of shots for stastical analysys.

##  Lets define some terms

### Mean
Mean is just a fance word for the average of a set of numbers.  In this document mean will usually indicate a distance but mean coupld also indacte an avarge musszle volicity etc.  The mean of the x-coordinates and the mean of the y-coordinates give you the Mean Point of Impact for a shot group.  

### Standard Deviation
A measure of how spread out the numbers are.  A smaller standard deviation means the data points are more tightly clustered.  A small SD is an indicator of consistancy.      

### Extreme Spread
Extreme spread (ES) indicates the difference between the highest and lowest values in a dataset.  In this context it would indicate the distance between the centers of the two most distant holes in the group of shots on the targe.  Aka group size.

### Mean Radius 
For this guide, the mean radius is the average distance of all impacts from the geometric center of the combined impacts.  Opposed to Extreme Spread the Mean Radious calculation takes into account every point of impact.  This matters when evaulating small changes in a system.

### Normal Distribution
Consider a normal distribution as a distribution of date points that form a graph that appears as a "bell curve".  Showing that data points near the mean are more frequent than data far from the mean.  

## Group Size is Least Useful
Don't base your system entirely on group size. Extreme Spread only tells you how bad the two worst shots were.  This leads people to bias thier data by self limiting to small group sizes and lower their chance of a larger extreme spread.  This is perfect if you are selling a gadget but not very usefull if you are trying to actually test how usefull that gadget is.  Ignoring "fliers" is also a way to introducing personal bias to the system.  Its way easier on the ego to ignore the "flyer" in a group than to have to come to the realization that the system is not sub-moa.  Combine all this, and it's a perfect recipe for self deceit.  Each piece of data added (increasing sample size) makes your data as a whole more usefull. You are paying for the ammo; the least you can do is log every shot.   

But!  Extrem spread and small shot groups have a use.  ES is very usefull in determining the health of your system.  If you bought a $7k sub 1/2 MOA rifle and your first 3 shots have an extreme spread of 6 inches that is a indicator that your system is suffereing catastrific failure.  Insecure optics, faulty ammo, defective barrel... etc.  You obviously dont need to print 20 shoots if you spot a problem at three.

## Mean Radius is More Useful

Mean Radious provides a more comprehensive measure of precision (or lack thereof) than simply measuring the distance between the two farthest shots (extreme spread). We care less about the two worst shots.   If for example you only record the ES/Group size.  You fire 3 times and record the ES as .98 inch.  You switch ammo and decide to fire 10 rounds also recording a ES of .98 inches.  Most people will instenctly understand that a 3 shot 1 inch group is not as good as a 10 shot 1 inch group.  But exactly how much better is it... or is it actually any better at all?  Using Mean Radious you can calculate the difference in percision between those 2 groups.  Any groups.  The caveot is that 3 shots or even 10 shots is not enough data for the equations to really kick in.  Its called the law of large numbers not the law of 3 numbers. 

Compared to the "old ways," calculating the mean radius is much more difficult. The basic concept is determining the center of the group, measuring each printed shot from the center, then finding the mean of each shot printed. The formula to calculate the MR is as follows: √((x₂ - x₁)² + (y₂ - y₁)²) where (x₁, y₁) are the coordinates of the group center and (x₂, y₂) are the coordinates of the shot hole.

Don't let the equations turn you off from the process. Your phone has more compute power than the entire solar system had in the 1950s; technology will make this process simple.

Below is a link to a very simple webpage that can mark shots on a target and perform calculations.  Free to use!
http://www.leproductionservice.com

### Make a Baseline

In its most general sense, a baseline is a starting point or a reference point against which future measurements, observations, or comparisons are made. It represents the initial state or condition before a change, intervention, or experiment is introduced.

Shoot in an environment with the fewest variables. Do your best to eliminate variables you can and to control the variables you can't. A good scenario is something like bags on a bench at an indoor range. Better would be a shooting fixture. I don't have access to a shooting fixture, and I don't have access to a bench. I do have access to an indoor range. I'm not physically able to shoot prone for more than a few minutes, so i use a bag on the range ammpo self.  Not perfect but nothing ever is.  The data is this guid was was collected in this way.  Dont let good enough get in the way of perfiction.  

Log the x and y distance of every shot from the point of aim.  Log the distance left or right of your POI as x and the distance up or down from your POI as y.  It is easier if your points of impacts are always above and to the right of your point of aim.  This prevents you from having to deal with negatives in your data set.  Additionally recording the impacts in millimeters is perfectly accurate and will illimante fractions(recording in mm is equilicant to recording in 24ths of an inch).  Following the recomdations will produce a database of positive integers.  Of course you are free to adapt any method you wish but for this text all the data wil lbe positive integers in mm.  I also find it easier to convert to MRADS.  IMHO it is very easy to convert to MOA with metric units.            

I draw targets in the equilivant of MSPaint and print them with my office printer. For the "bullseye", I use a triangle.  The tip of the triangle is an infinitely small point of aim.  Its much easir to measue the distance from the tip of an angle then, say, the center of a circle.  Becuse I actually save the targets for later reference I limit the damage to a minimul number of shots per bullseye.  Its of no use to turn a target into confette and then try to pull data from it.  Also I dont worry about collecting the specifics until I get home.  At home I can take my time using a cheap pair of vaneer calipers to measure and record the distance from the point of aim.  A sharpy, paper-plates and a ruler will work just a well.  Calipers and printers are not a requirment.  The end goal is to lay down shots with a minimum of variables in a way individual shots can be easly recorded for later use.  

### How Much Data is Enough

Assume 20 shots.  These equations seem to come into high levels of realability for shooting percision at about 20 shoots as data points, really get locked it at 30, seem to never really change after about 50.  There are "tests" that are used to determin how well your data set will work.  This is called checking for normality.  This is a new level of complications that I dont expect a normal user to bother with but is included as an option of the website.  The check for normality is with the Shapiro-Wilk test. The Shapiro-Wilk test is a way to check if a set of data is likely to have come from a normal distribution (the bell curve). It gives you a score (W) and a p-value. The formula to calculate W is (Σ aᵢ * xᵢ)² / Σ (xᵢ - x̄)². If the p-value is low (usually below 0.05), it suggests your data is probably not normally distributed. Shapiro-Wilk is commonly used in statistics to ensure data meets certain assumptions before using other tests. Expect to collect around 20 impacts. Thirty is better. Fifty is about the maximum you will ever need. In my experience, I don't often see a p > 0.05 until around 20 shots. It's so common that I just assume I will be starting at 20, and I make my targets accordingly. Don't skip the "flyers." There is a process to account for outliers.  Record the distance from the point of aim (x and y) and muzzle velocity (if you have a chronograph).  Dont get too hung up on the chronograph.  Muzzle verlocity is a nice to have, not a got to have.  Its basically irrelavant until you are pushing out beyond 500 yards.  Until you are shoting ELD the muzzle velocity is basically an indicatory of consistency.


### Work flow.





Beyond the hardware... PPPP
Position
Picture
Pull
Practice




TODO: Add examples of ladder targets and an Excel spreadsheet with formulas. ARA unlimited class target.

Circular Error Probable (CEP): A measure of dispersion

Extreme Spread (ES): A measure of dispersion

Horizontal and Vertical Variances: Measures of dispersion

Mean Radius (MR): A measure of dispersion
