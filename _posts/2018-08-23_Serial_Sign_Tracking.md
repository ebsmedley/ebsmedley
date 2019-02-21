---
layout: post
title:  "Serial Sign Tracking"
date:   2019-02-13
excerpt: "Summary of experiments exploring serial lever presentations in Pavlovian conditioning"
project: true
tag:
- post
- projects
comments: false
---


I became interested in serial presentations of cues while taking a learning theory course in the winter of 2018. I was curious about the sign-tracking conditioned response and how multiple lever cues in sequence would elicit behavior. Considering what is understood about dopamine signaling and a back propogation of signal to predictive cues (see Schultz et al., 1997), and that animals with 'increased dopaminergic tone' in nucleus accumbens tend to display more interactions with predicitive lever cues (see Flagel et al., 2010), I wanted to know if sign-tracking animals display a preference towards more distal cues (those furthest in time from the reward) in sequence over learning. Perhaps, the dopamine signal providing information about predictive value of reward, is traveling back toward the first lever in sequence - and our sign-tracking animals may just show us through their behavior that this first lever acquires more incentive value. 

To test this, I engineered a series of experiments looking at whether cues in sequence acquire value similarly to solitary cues, and probed the relationship between serial cues through extinction procedures. *(I've skipped over some details and just focused on the major findings. For each experiment I've shown an experimental schematic where the parts I will cover are highlighted in blue. For more details see <a href="http://www.smith-lab.org/wp-content/uploads/2012/04/Learn.-Mem.-2018-Smedley-78-89.pdf"><b>Smedley & Smith 2018a</b></a>  [Experiments 1-3] and see <a href="https://www.sciencedirect.com/science/article/pii/S0376635718301359"><b>Smedley & Smith 2018b</b></a>  [Experiment 4]).* 

Experiment 1
---------------

**Does the presence of a distal cue alter responding to a proximal cue?**

Figure 1
{% capture images %}
    https://raw.githubusercontent.com/ebsmedley/ebsmedley.github.io/master/_posts/Serial_Sign_Tracking_files/figure_markdown-strict/experiment_1.png
{% endcapture %}
{% include gallery images=images caption="" cols=1 %}

*Figure 1 shows the behavior schedule of our two groups in this experiment (the Serial group [top] and the Proximal-only group [bottom]). Both groups recieved a magazine training day (exposure to the operant box where they got to experience the reward pellet). Both groups had 12 days of training. The Serial group had 25 trials per day of a 10 second lever (CS distal), a different 10 second lever (CS proximal), then a delivery of two grain pellets. The Proximal-only group had a 10 second lever (CS proximal), then a delivery of two grain pellets. All groups had one day of extinction (same training paradigm they had reveived previously, but now without reward delivery), then a reacquisition session (same training paradigm they had received previously, but now with reward again). All groups had a devaluation period where the food reward was paired with a nausea inducing drug (LiCl). Once the food was successfully rejected, a followup extinction, reacquistion, tests followed. Finally, I double checked that the food was still rejected in a consumption test.*

Figure 2
{% capture images %}
    https://raw.githubusercontent.com/ebsmedley/ebsmedley.github.io/master/_posts/Serial_Sign_Tracking_files/figure_markdown-strict/experiment_1_graphs.png
{% endcapture %}
{% include gallery images=images caption="" cols=1 %}

*Figure 2 (left) shows the presses per minute (rate of pressing on the lever) on the proximal lever in the Serial group (white) and the Proximal-only group (grey) over the 12 training sessions. Figure 2 (right) shows just the Serial group's presses per minute responses to the proximal (white) and distal lever (black). Error bars represent +/-SEM.*

Results:
A linear mixed model 

Takeaways:
The presence of a distal lever in the serial group does not alter responding to the proximal lever (Figure 2, left). Within the serial group, animals pressed more to the distal, rather than the proximal, lever over time (Figure 2, right). 


    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

{% capture images %}
    https://raw.githubusercontent.com/ebsmedley/ebsmedley.github.io/master/_posts/Code_Snippets_files/figure-markdown_strict/pressure-1.png
{% endcapture %}
{% include gallery images=images caption="" cols=1 %}



Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.


