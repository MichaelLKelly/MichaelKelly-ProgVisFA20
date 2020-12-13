Final Project
======================
An Alternate SCOTUS Portrait 
------------------------
This project builds on and dynamically presents research undertaken in a concurrent Data Analysis course, which explored the effects of a theoretical 18-year term limit imposed on the U.S. Supreme Court in 1971. That project consisted of hand-generated tables that were color-coded as ‘Actual’ and ‘Alternate’ heatmaps to show the ideology of the Court over the 50 years from then until the sitting Court. Select cases (one for each decade) were then examined to explore how an Alternate Court’s composition might have changed or affected the ruling. This project took the story told by that research and its accompanying report and translated it into an interactive bit of storytelling, utilizing d3, html, css and javascript. All code and CSV files are included here, along with a PDF of the accompanying Data Analysis project's research report for further context.

------------------------
The screenshots below document the structure and interactive features of the project, but one can also view a [working GitHub Page](https://michaellkelly.github.io/MichaelKelly-ProgVisFA20/SCOTUS/).


<h2>1. Introduction</h2>
Even the opening illustration utilizes d3, to create an homage to Justice Ruth Bader Ginsburg’s trademark collars as a half-doughnut chart, featuring nine arcs.
![SCOTUS_Final_Intro.png](/Final_Project/SCOTUS_Final_Intro.png "SCOTUS Introduction")

<h2>2. Structure</h2>
Each case study contains an Actual and Alternate heatmap, showing the decade broken up by month, with its nine Justices in an ideologically colored row from left to right. At the center is a combination pie / doughnut chart, with the pie showing the majority / dissent vote and the doughnut showing the individual Justices linked to that vote.
![SCOTUS_Final_Structure.png](/Final_Project/SCOTUS_Final_Structure.png "SCOTUS Structure")

<h2>3. A Case Study in Detail</h2>
The case study shown for the next few screenshots is example is Citizens United v. FEC, which showcases all changes that may result from interactivity within a particular case study.) To view all cases, one can visit the [GitHub Page](https://michaellkelly.github.io/MichaelKelly-ProgVisFA20/SCOTUS/).
![SCOTUS_Final_CUvFEC_actu.png](/Final_Project/SCOTUS_Final_CUvFEC_actu.png "SCOTUS Case Study: Actual")

<h2>4. Ideological Mouseover</h2>
Hovering over the doughnut chart reveals the same ideological color-coding as the heatmaps, applied to the individual Justices.
![SCOTUS_Final_CUvFEC_actu_mo.png](/Final_Project/SCOTUS_Final_CUvFEC_actu_mo.png "SCOTUS Case Study: Actual with Mouseover")

<h2>5. Actual / Alternate Toggle</h2>
While in the default Actual state, a line highlights the month in the Actual heatmap that the Actual case took place, while the pie / doughnut combination reflects that Actual data in detail. (All as seen above.) When the Alternate radio button is selected, the highlight line switches to the Alternate heatmap on the right and the decision data switches to reflect that.

![SCOTUS_Final_CUvFEC_alt.png](/Final_Project/SCOTUS_Final_CUvFEC_alt.png "SCOTUS Case Study: Alternate")

Likewise, the mouseover now reflects the ideological scores of the Alternate Justices.
![SCOTUS_Final_CUvFEC_alt_mo.png](/Final_Project/SCOTUS_Final_CUvFEC_alt_mo.png "SCOTUS Case Study: Alternate with Mouseover")

<h2>6. In Conclusion</h2>
As the visualization has evolved into a kind of scrollytelling, it ends with a brief conclusion, reflecting on the takeaways from the examination of case studies.
![SCOTUS_Final_Conclusion.png](/Final_Project/SCOTUS_Final_Conclusion.png "SCOTUS Conclusion")

