# Empirical Accuracy: A Statistical Approach to Precision Shooting Analysis

**This guide provides a systematic, data-driven methodology for evaluating precision shooting performance.** It is intended for individuals with the ability to consistently operate a rifle system and who seek to objectively assess modifications—such as comparing reloaded versus factory ammunition or transitioning to a precision chassis—through repeatable, evidence-based techniques.

## BLUF:  Bottom Line Up Front

**Shooter proficiency is the primary determinant of performance; equipment enhancements yield progressively smaller benefits.**  Mid-teir modern rifles often exhibit exemplery performance, and surpassing their capabilities requires significant investment and effort.  No device or technique can simplify precision shooting.  Anyone tell you differently is trying to sell you somthing.

## Historical Context: Transitioning from Anecdotal to Statistical Evaluation

My first experience with a scoped rifle was sighting in using three-shot groups. Under my father’s direction, I fired three rounds, adjusted the scope, and repeated until it was deemed satisfactory.  Leaving with still over half of the single box of .30-06 Core-Lokt that was brought.  Pretty sure that box lasted at least 2 more seasons.  This approach proved effective for my purposes.  I was indocternated.  For years, I relied on three/five-shot groups to assess rifle systems becuase, well, it is simplicit, cost-effective, and adequat.

Then came the internet and with it as many forum posts and methods as there were fathers and sons needing to sight in a rifle.  Each endorsed by its proponents.  But somthing wasnt adding up.  How can so many differnt methods claiming to be the best still end up with the same results.  If every method was best how could any be the best.  With so many methods in compatition to be the "right" method a new peridimn paradigm formed...  the MOA became above reproach.  If the method was the religion then the MOA become the martyr.  People were less interested in figuring out the best way to evalute a rifle system and more instered in getting a three shot group with a small MOA.  Its unclear if the MOA was pushed by the snake oil salesmen or if they just adopted it.  Traditional practices may confirm operational reliability but cannot substantiate sub-MOA performance. Moreover, much online content promotes unproven solutions, undermining objective analysis. A video demonstrating a 0.25 MOA three-shot group holds little evidentiary weight, akin to an isolated success in a controlled setting.

**Indicators of Unreliable Information:**

- **Limited sample sizes:** Assertions based on three-shot groups labeled as "sub-MOA."
- **Selective reporting:** Exclusion of outliers to artificially improve results.
- **Insufficient detail:** Absence of testing conditions, such as range or environmental factors.
- **Overstated simplicity:** Claims that inexpensive tools can significantly enhance precision without evidence.

## Statistical Foundation: The Law of Large Numbers

The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true population mean. **In precision shooting, larger shot counts provide a more accurate depiction of a rifle system’s performance.** Consider a coin flipped three times, all resulting in heads: this outcome does not confirm a bias toward heads. Similarly, a three-shot group does not definitively establish sub-MOA capability. Intuitively, one might require 50 or 100 flips to assess a coin’s true nature, yet small shooting samples are often accepted without scrutiny. This discrepancy arises because simple systems are more easily evaluated, while complex systems like rifles obscure judgment. Statistical methods, such as those employed in performance analysis or ammunition testing, leverage the LLN to eliminate subjectivity. Increased shot counts enhance reliability over anecdotal assessments.

## Data-Driven Evaluation: A Superior Methodology

All shots contribute valuable information. Discarding data, such as outliers, compromises accuracy and wastes resources. The objective is to compile a comprehensive database of shot impacts for statistical analysis. The tools outlined below, supported by a free resource at [LE Production Service](http://www.leproductionservice.com), facilitate this process.

## Terminology

| Term                | Definition                                                                                                        | Example in Shooting                                                                                                  |
| :------------------ | :------------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------- |
| Mean                | Arithmetic average of data points.                                                                                  | Average distance of shots from the point of aim (e.g., 0.8 inches).                                                  |
| Standard Deviation  | Measure of variability in data points.                                                                              | Consistency of shot placement (e.g., SD of 0.3 inches indicates tight grouping).                                     |
| Extreme Spread (ES) | Distance between the two most distant shots.                                                                        | Total group size (e.g., 1.2 inches for 5 shots).                                                                     |
| Mean Radius (MR)    | Average distance of each shot from the group’s center.                                                              | Comprehensive precision metric (e.g., MR of 0.5 inches for 10 shots).                                                |
| Sample Size         | Number of shots recorded.                                                                                           | Shots taken during testing (e.g., 20 shots).                                                                         |
| MOA                 | Minute of Angle, an angular unit of measure.                                                                        | Approximately 1 inch at 100 yards.                                                                                  |
| MRAD               | Milliradian, an angular unit of measure.                                                                            | Approximately 0.36 inches at 100 yards for 0.1 MRAD.                                                                 |

## Comparing Extreme Spread and Mean Radius

Extreme Spread (ES) measures the distance between the two furthest shots, emphasizing the least favorable outcomes. Relying solely on small groups or excluding outliers introduces bias, which may benefit promotional efforts but undermines objective testing. Every recorded shot enhances the dataset’s integrity.

ES remains useful for diagnosing significant malfunctions. For instance, a $7,000 rifle advertised as sub-0.5 MOA yielding a 6-inch ES after three shots suggests issues such as unsecured optics or defective ammunition, requiring no further testing to identify a problem.

Mean Radius (MR) offers a more thorough assessment by averaging the distance of each shot from the group’s center, rather than focusing on extremes. For example, a 3-shot group with a 0.98-inch ES compared to a 10-shot group with the same ES intuitively differs in quality; MR quantifies this distinction. However, small samples (e.g., 3 or 10 shots) limit the applicability of the Law of Large Numbers. A minimum of 20 shots is recommended for dependable results.

MR calculation involves determining the group center, measuring each shot’s distance using the formula √((x₂ - x₁)² + (y₂ - y₁)²), and computing the average. Modern technology simplifies this process. A free tool for marking shots and performing calculations is available at [LE Production Service](http://www.leproductionservice.com).

## Establishing a Baseline

### Cost Considerations

Precision shooting entails significant expense, and this methodology increases initial costs. A 20-shot baseline may require $20 to $50 in ammunition, depending on caliber. However, this investment reduces long-term inefficiencies by minimizing reliance on untested modifications.

### Data Collection Protocol

A baseline represents the rifle system’s performance prior to alterations. Conduct testing in a controlled environment, such as an indoor range with a bench rest, to minimize variables. Personally, I utilize a rest on an ammunition shelf at an indoor facility, acknowledging its limitations. Control measurable factors (e.g., wind, shooter position) and document uncontrollable variables (e.g., humidity, barrel temperature).

Record each shot’s horizontal (X) and vertical (Y) distance from the point of aim in millimeters (e.g., 5 mm left, 3 mm up). Positioning impacts above and to the right of the point of aim eliminates negative values, and millimeter measurements provide precision equivalent to 24ths of an inch. Targets are designed in a basic graphics program with a triangular bullseye, offering a precise point for measurement compared to circular designs. Shots are fired, targets preserved, and measurements taken later using calipers (or a ruler and marker). Limit shots per target to maintain clarity.

### Sample Size Guidance

A minimum of 20 shots is advised. Statistical reliability emerges around 20 shots, stabilizes by 30, and remains consistent beyond 50. Advanced tests, such as the Shapiro-Wilk method, assess data normality and are available on the referenced website, though optional. Based on experience, 20 shots suffice for practical purposes; targets are designed accordingly. All shots, including outliers, should be recorded, with separate methods to address anomalies.

## Sample Data Table

| Shot # | X (mm) | Y (mm) |
| :----- | :----- | :----- |
| 1      | 5      | 3      |
| 2      | 2      | 7      |
| 3      | 8      | 1      |
| ...    | ...    | ...    |
| 20     | 4      | 6      |

**Note:** X denotes horizontal distance from the point of aim; Y denotes vertical distance.

## Shooter Fundamentals: Position, Picture, Pull, Practice

**Shooter technique significantly influences data quality.** Inconsistent methods (e.g., unstable positioning or abrupt trigger activation) introduce variability, obscuring the rifle system’s true performance. Focus on these principles:

- **Position:** Maintain a stable, repeatable stance.
- **Picture:** Ensure a clear, consistent sight alignment.
- **Pull:** Execute a smooth, controlled trigger press.
- **Practice:** Engage in regular, deliberate training to enhance proficiency.

---

### Summary of Methodology
- **Objective:** Assess rifle system modifications with precision.
- **Approach:** Record 20+ shots, compute Mean Radius, eliminate subjectivity.
- **Resource:** [LE Production Service](http://www.leproductionservice.com).
- **Guidance:** Proficiency outweighs equipment. Prioritize fundamental skills.

Adopt this methodology to achieve reliable, reproducible results in precision shooting analysis.



Empirical Accuracy
Demystifying Statistical Analysis of Shooting

The purpose of this text is to establish repeatable testing concepts for precision shooting. The target audience is anyone that has the skills to repeatedly shoot a rifle system with precision but are interested in exploring how to test if a change in the system is actually an improvement. Such as testing reloaded ammo vs factory ammo. Testing an upgrade from a factory stock to a custom precision chassis. Even testing minor changes like a different lot number of your favorite reloading component.

BLUF (Bottom Line Up Front)
Most mid-tier rifle systems with mid-tier optics running mid-tier ammunition will outperform most shooters. More than a handful of "budget" rifle systems will do the same. There is no incantation you can say over a bag rest or magical rune to carve into the turret ring to make precision shooting "easy." Outshooting a store-bought rifle system is expensive and hard, and nothing is changing that. Anyone telling you differently is selling something.

Skip the Filler...
This guide assumes that the reader knows the basics of firearms and ammunition. The temptation to fill the first 70 pages with definitions of trigger shoes and black powder burn rates will be resisted. That is what the index is for.

The Old Ways
My first scoped rifle system was sighted in using three-shot groups. I was instructed by my father to fire three shots before adjusting the scope. I did as instructed, and with a little more than half a box of .30-06 Core-Lokt remaining, he and I were both satisfied that the rifle system was "sighted in." For most of my life afterward, I evaluated rifle systems and ammo based on three-shot samples. Why wouldn't I? Countless game have been harvested with rifle systems sighted in based on three-shot samples. It is simple, cheap, and, more importantly, it was good enough!

Then the Internet...
It doesn't take long to realize that there are as many different ways of evaluating rifle systems and ammo as there were fathers and sons at the range... and they all seem to work just fine. The change came when good enough wasn't good enough... only MOA was good enough. Forums are filled with thousands, if not millions, of accounts of inherited processes that took a good enough rifle system to a SUB MOA rifle system. But something felt off. How can so many different processes have the same exacting results? I hesitantly realized that the old ways might be good enough to prove a rifle system "good enough" but can in no way prove a rifle system SUB MOA. It was devastating to also realize that an overwhelming majority of internet content was selling snake oil to reinforce using the old ways to prove a SUB MOA rifle system. This industry is one step away from selling magic crystals to help align your rifle system's chi and copper socks to stop distortions in your barrel harmonics. The internet is full of people either trying to sell you nonsense or trying to justify having bought into the nonsense. Some truly believe their product is working, and some are just lying. They even have video proof. A video of a 1/4 MOA three-shot group on the internet is as useful as a video of a hole-in-one at a driving range.

The Proof is in the LLN
According to the Merriam-Webster dictionary, the Law of Large Numbers is "the probability that the absolute value of the difference between the mean of a population sample and the mean of the population from which it is drawn is greater than an arbitrarily small amount approaches zero as the size of the sample approaches infinity."

If you read the above and it makes perfect sense, congratulations; you do not need this guide. If you read that and thought, "WTF does this have to do with a rifle system?" then you might be the target audience.

A more jargon-free definition is provided by Wikipedia. To quote Wikipedia, "The law of large numbers is a mathematical law that states that the average of the results obtained from a large number of independent random samples converges to the true value, if it exists."

LLN converges on the truth if it exists.

If someone flips a coin three times and it lands heads-up three times, you instinctively know there is not enough information to prove that the coin will always land heads up. Is three flips enough to converge on the truth? No one would pay a premium for that coin as a heads only coin. We all instinctively know the coin isn't any better at landing heads-up than any other coin. Landing a coin heads up three times doesn't make it a "heads-up coin" any more than printing a sub-MOA three-shot group makes a rifle system a sub-MOA rifle system. How many coin tosses does your instinct tell you to take before you start to believe you are converging on the truth of the coin might be different from the average? Ten tosses? Fifty tosses? A thousand tosses? For whatever reason, humans seem to be better at detecting bad sample rates in simple systems but then easily accept bad sample rates in complex systems. The good news is that many rational minded people figured out processes to remove human bias from the process. When a slight human bias is the difference between choosing the best player in a draft or not, or launching a successful advertising campaign or not, these people have successfully resorted to the LLN. One random taste test for a new product is likely to have converged on the truth than 50 taste tests. One participant in a drug trial is less useful than 5,000 participants.

Data is King... A Better System
Use every piece of data. Every shot not recorded is wasted data. The end goal is to have a working database of impacts for statistical analysis.

Let's define some terms
Mean
Mean is just a fancy word for the average of a set of data points. In this document, mean will usually indicate a distance but mean could also indicate an average of muzzle velocity etc. The mean of the x-coordinates and the mean of the y-coordinates give you the Mean Point of Impact for a shot group.

Standard Deviation
Standard Deviation is a measure of how spread out the data points are. A smaller Standard Deviation means the data points are more tightly clustered. A small Standard Deviation is an indicator of consistency.

Extreme Spread (ES)
Extreme Spread (ES) indicates the difference between the highest and lowest values in a dataset. In this context, it would indicate the distance between the centers of the two most distant impacts in the group of shots on the target. Aka group size.

Mean Radius
For this guide, the Mean Radius is the average distance of all impacts from the geometric center of the combined impacts. Opposed to Extreme Spread, the Mean Radius calculation takes into account every impact. This matters when evaluating small changes in a system.

Sample Size
Sample Size refers to the number of observations or individual data points included in a study or experiment. Essentially, it's how many items you're measuring or counting within your selected group.

Normal Distribution
Consider a Normal Distribution as a distribution of data points that form a graph that appears as a "bell curve". Showing that data points near the mean are more frequent than data far from the mean.

MOA (Minute of Angle)
MOA is an angular measurement. One MOA subtends approximately 1.047 inches at 100 yards. For practical purposes it is usually rounded to 1 inch at 100 yards.

MRAD (Milliradian)
MRAD is also an angular measurement. One MRAD subtends approximately 3.6 inches at 100 yards, or 0.1 MRAD subtends approximately .36 inches at 100 yards.

Extreme Spread is Least Useful
Don't base your system entirely on group size. Extreme Spread only tells you how bad the two worst shots were. This leads people to bias their data by self limiting to small group sizes to lower their chance of a larger extreme spread. This is perfect if you are selling a gadget but not very useful if you are trying to actually test how useful that gadget is. Ignoring "fliers" is also a way to introducing personal bias to the system. Its way easier on the ego to ignore the "flyer" in a group than to have to come to the realization that the system is not sub-moa. Combine all this, and it's a perfect recipe for self deceit. Each piece of data added (increasing sample size) makes your data as a whole more useful. You are paying for the ammo; the least you can do is log every shot.

But! Extreme spread and small shot groups have a use. Extreme Spread is very useful in determining the health of your system. If you bought a $7k sub 1/2 MOA rifle and your first 3 shots have an extreme spread of 6 inches that is a indicator that your system is suffering catastrophic failure. Insecure optics, faulty ammo, defective barrel... etc. You obviously don't need to print 20 shoots if you spot a problem at three.

Mean Radius is More Useful
Mean Radius provides a more comprehensive measure of precision (or lack thereof) than simply measuring the distance between the two farthest shots (extreme spread). We care less about the two worst shots. If for example you only record the ES/Group size. You fire 3 times and record the ES as .98 inch. You switch ammo and decide to fire 10 rounds also recording a ES of .98 inches. Most people will instantly understand that a 3 shot 1 inch group is not as good as a 10 shot 1 inch group. But exactly how much better is it... or is it actually any better at all? Using Mean Radius you can actualize the difference in precision between those 2 groups. Any groups. The caveat is that 3 shots or even 10 shots is not enough data for the equations to really kick in. Its called the law of large numbers not the law of 3 numbers.

Compared to the "old ways," calculating the mean radius is much more difficult. The basic concept is determining the center of the group, measuring each printed shot from the center, then finding the mean of each shot printed. The formula to calculate the MR is as follows: √((x₂ - x₁)² + (y₂ - y₁)²) where (x₁, y₁) are the coordinates of the group center and (x₂, y₂) are the coordinates of the shot hole.

Don't let the equations turn you off from the process. Your phone has more compute power than the entire solar system had in the 1950s; technology will make this process simple.

Below is a link to a very simple webpage that can mark shots on a target and perform calculations. Free to use! http://www.leproductionservice.com

Make a Baseline
Budget
Shooting is expensive, and it seems to be getting more expensive every year. Following this guide will not be cheap. One of the many goals is to prevent the waste of time and materials. It will feel more expensive upfront (because it will be). The first step in collecting data is pulling the trigger. Every piece of data collected early will make testing/troubleshooting less expensive in the future.

Collect Data
In its most general sense, a baseline is a starting point or a reference point against which future measurements, observations, or comparisons are made. It represents the initial state or condition before a change, intervention, or experiment is introduced.

Shoot in an environment with the fewest variables. Do your best to eliminate variables you can and to control the variables you can't. A good scenario is something like bags on a bench at an indoor range. Better would be a shooting fixture. I don't have access to a shooting fixture, and I don't have access to a bench. I do have access to an indoor range. I'm not physically able to shoot prone for more than a few minutes, so i use a bag on the range ammo self. Not perfect but nothing ever is. The data is this guid was was collected in this way. Don't let good enough get in the way of perfection.

Log the x and y distance of every shot from the point of aim. Log the distance left or right of your POI as x and the distance up or down from your POI as y. It is easier if your points of impacts are always above and to the right of your point of aim. This prevents you from having to deal with negatives in your data set. Additionally recording the impacts in millimeters is perfectly accurate and will illuminate fractions(recording in mm is equivalent to recording in 24ths of an inch). Following the recommendations will produce a database of positive integers. Of course you are free to adapt any method you wish but for this text all the data will be positive metric integers. I also find it easier to convert to MRADS. IMHO it is very easy to convert to MOA with metric units.

I draw targets in the equivalent of MS Paint and print them with my office printer. For the "bullseye", I use a triangle. The tip of the triangle is an infinitely small point of aim. It's much easier to measure the distance from the tip of an angle then, say, the center of a circle. Because I actually save the targets for later reference I limit the damage to a minimum number of shots per bullseye. It's of no use to turn a target into confetti and then try to pull data from it. Also I don't worry about collecting the specifics until I get home. At home I can take my time using a cheap pair of vernier calipers to measure and record the distance from the point of aim. A sharpy, paper-plates and a ruler will work just a well. Calipers and printers are not a requirement. The end goal is to lay down shots with a minimum of variables in a way individual shots can be easily recorded for later use.

How Much Data is Enough
Assume 20 shots. These equations seem to come into high levels of reliability for precision shooting at about 20 shoots as data points, really gets locked it at 30, seems to never really change after about 50. There are "tests" that are used to determine how well your data set will work. This is called checking for normality. This is a entire new level of complication that I don't expect the average user to bother with, but is included as an option of the website. The check for normality is with the Shapiro-Wilk test. The Shapiro-Wilk test is a way to check if a set of data is likely to have come from a normal distribution (the bell curve). It gives you a score (W) and a p-value. The formula to calculate W is (Σ aᵢ * xᵢ)² / Σ (xᵢ - x̄)². If the p-value is low (usually below 0.05), it suggests your data is probably not normally distributed. Shapiro-Wilk is commonly used in statistics to ensure data meets certain assumptions before using other tests. Again, in my experience, I don't often see a p > 0.05 until around 20 shots. It's so common that I just assume I will be starting at 20, and I make my targets accordingly. Don't skip the "flyers." There is a process to account for outliers.

Beyond the hardware... PPPP
Position Picture Pull Practice

TODO: Ladder Targets: Explain what ladder targets are and how they are used in load development. Website with Formulas: Ensure the website is reliable and the formulas are clearly presented. ARA Unlimited Class Target: Explain what this is, why it's relevant, how to find one. Circular Error Probable (CEP): Provide a clear definition and explain how it relates to other measures of dispersion. Horizontal and Vertical Variances: Define these terms and explain how they can be used to analyze shot patterns. Add a section on equipment: Briefly discuss the types of equipment used in precision shooting (rifles, optics, ammunition, rests, etc.) and how they can affect accuracy. Add a section on environmental factors: Explain how wind, temperature, humidity, and other environmental factors can affect shot placement and how to account for them. Add a section on shooting techniques: Discuss the fundamentals of good shooting technique (e.g., stance, grip, trigger control, breathing) and how they contribute to accuracy. Consider adding a glossary of terms.




