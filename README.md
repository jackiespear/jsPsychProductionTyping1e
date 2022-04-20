# jsPsych Production Effect by Typing 1b
A jsPsych recognition experiment examining the production effect by typing.

## Purpose

This experiment is a part of my PhD thesis. Data collected will be compared to performance of an instance-based model of human memory, MINERVA 2.

Participants were asked to study a list of words, some of which they will produce by typing, and some of which they will read silently. The study list consisted of two types of words: words that have regular pronunciations and words that have irregular pronuncialtions (with regards to spelling to sound consistency). Words were selected on the basis of norms provided by Chee et al., (2020). At test, participants will be presented with all of the words they previously studied, along with the same amount of new words that they did not study. Their job will be to indicate that yes, they did previously study a word, or no, they did not. Experiment 1d has 40 study words, and 40 lures at test.

Technical details: When words are produced by typing, the typing is recorded, but not mirrored to the screen. The instruction to "read" or "type" remains on the screen for 3 seconds, and participants cannot advance the trial prematurely by pressing the "enter" key. Moreover, in experiment 1d. participants see the instruction to "read" or "type" at the same time as they are presented with the study word. Some modifications had to be made to the jsPsych survey-html-form plugin to accomplish this. All study stimuli are presented for 2 seconds each.

A practice phase has been added to help with typing compliance.

<p align="center">References</p>

Chee, Q. W., Chow, K. J., Yap, M. J., & Goh, W. D. (2020). Consistency norms for 37,677 english words. Behavior Research Methods, 52(6), 2535-2555
