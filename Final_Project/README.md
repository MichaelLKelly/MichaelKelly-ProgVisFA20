IN PROGRESS



Final Project
======================
An Alternate SCOTUS Portrait 
------------------------
This project builds on and dynamically presents research undertaken in a concurrent Data Analysis course, which explored the effects of a theoretical 18-year term limit imposed on the U.S. Supreme Court in 1971. That project consisted of hand-generated tables that were color-coded as ‘Actual’ and ‘Alternate’ heatmaps to show the ideology of the Court over the 50 years from then until the sitting Court. Select cases (one for each decade) were then examined to explore how an Alternate Court’s composition might have changed the Actual ruling. This project took the story told by that research and its accompanying report and translated it into an interactive bit of storytelling, utilizing d3, html, css and javascript.

------------------------
The screenshots below document the structure and interactive features of the project, and a working GitHub Page showing full interaction is [here] (https://michaellkelly.github.io/MichaelKelly-ProgVisFA20/SCOTUS/).

1. Introduction
Even the opening illustration utilizes d3, to create an homage to Justice Ruth Bader Ginsburg’s trademark collars as a half-doughnut chart, featuring nine arcs.


2. Case Structure
Each case study contains an Actual and Alternate heatmap, showing the decade broken up by month, with its nine Justices in an ideologically colored row from left to right. At the center is a combination pie / doughnut chart, with the pie showing the majority / dissent vote and the doughnut showing the individual Justices linked to that vote.

(The case study shown for this example is Citizens United v. FEC, which showcases all changes that may result from interactivity within a particular case study.) To view all cases, one can visit the GitHub page.


3. Ideological Mouseover
Hovering over the doughnut chart reveals the same ideological color-coding as the heatmaps, applied to the individual Justices.


4. Actual / Alternate Toggle
While in the default Actual state, a line highlights the month in the Actual heatmap that the Actual case took place, while the pie / doughnut combination reflects that Actual data in detail. (All as seen above.)

When the Alternate radio button is selected, the highlight line switches to the Alternate heatmap on the right and the decision data switches to reflect that.

Likewise, the mouseover now reflects the ideological scores of the Alternate Justices.

5. In Conclusion
As the visualization has evolved into a kind of scrollytelling, it ends with a brief conclusion, reflecting on the takeaways from the examination of case studies.


![Wk8_Screenshot_1_MKelly.png](/WK8-Projects/Wk8_Screenshot_1_MKelly.png "MKelly_Beatles_Screenshot1")
