# tutor-progress-tracker
An electronic sheet to track the progress of your tutoring/part-time gig

# How to use it
Input columns are written in **bold**, setup input columns are written in <ins> *underlined bold* </ins> and optional inputs are written in ***italic bold***. All other columns are computed using values in previous columns.

## Setup
You need to specify the **VALUE OF PRIZE** as the total amount of money you can earn from the tutoring, and the **INITIAL TO DO** as the total amount of time you can spend doing tutoring gigs. 

## Steady state use
Each time you perform a gig, you can write in one line the **DATE**, the **START** time and the **END** time of the gig times are read in 24h format, hh:mm, date can be in any format you want. The sheet will calculate how much money you are eligible to earn by looking at the total amount of minutes spent working on tutoring gigs.

If you decide to collect some of your hard earned money, you can update the **REQUESTED** single-row column with the amount of minutes you requested to collect to your manager. The sheet will distinguish the money you have actually collected from the amount you have earned, but you still have to collect.

If at some point your manager gives you additional working hours that you can use to perform gigs and you want to keep track of them in the same sheet, you must update the <ins> *BONUS* </ins> single-row colunn with the corresponding amount of additional minutes.

## Example

![Screenshot_20231101_123716](https://github.com/Torkin1/tutor-progress-tracker/assets/32265040/250ed62f-51d0-4063-964c-dd399d2f2217)
