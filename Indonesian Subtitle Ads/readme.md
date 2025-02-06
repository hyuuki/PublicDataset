# Indonesian Subtitle Ads

## Description
This repository contains a collection of Indonesian subtitles from movies collected from subtitle provider.  We already extracted the subtitles from raw subtitles (.srt, .sub, .ssa) to retain original form (keeping the tags for formatting) and saved to Excel file (.xslx). Since these subtitles are suffered from manually inserted advertisements by the subber, we can later use predictive model trained from this data to detect/identify whether a line is advertisements or normal conversation.

There are three columns inside Excel files:
1. Index or line number
2. Class/Label: It is labeled with 0 if the line is normal conversation and 1 if the line is advertisement. 
3. Text: the line contains conversation or advertisement

## How to Cite:
*will be added later*
2025. Putra Pandu Adikara, Randy Cahya Wihandika, Indriati, Rizal Setya Perdana, M. Ali Fauzi, and Tutut Herawan. AdSubCleaner: A Framework for Detecting and Removing Improper Advertisement in Subtitles with Highly Imbalanced Dataset.

## Original work:
Putra Pandu Adikara, Randy Cahya Wihandika, Indriati. Faculty of Computer Science, Universitas Brawijaya.
