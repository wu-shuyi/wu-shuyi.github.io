---
layout: page
permalink: /learning resources
categories: journal
tags: [documentation,sample]
image: lionrock.JPG
---

Here I would share some of my learning notes and open materials. <br>

---
<font size="4.5"> Open materials </font> <br>
<font size="4.5"> 1. Neuroscience </font> <br>
<font size="4"> (1) Harvard - Fundamentals of Neuroscience P3: The Brain (Prof. David Cox) </font> 
[video](https://www.bilibili.com/video/av41830186/?p=1) <br>

<font size="4"> (2) MIT - Human Mind and Brain, Spring 2018 (Prof. Nancy Kanwisher) </font> 
[home video](https://nancysbraintalks.mit.edu/course/9-11-the-human-brain), [B站 video](https://www.bilibili.com/video/av24615914/?p=1) <br>

<font size="4"> (3) MIT 9.40 - Introduction to Neural Computation, Spring 2018 </font> 
[home link](https://ocw.mit.edu/courses/9-40-introduction-to-neural-computation-spring-2018/) <br>

<font size="4"> (4) Neuromatch computational neuroscience course </font> 
[home link](https://compneuro.neuromatch.io/tutorials/intro.html) <br>
<br>

<font size="4.5"> 2. Deep learning </font> <br>
<font size="4"> (1) Neuromatch deep learning course </font> 
[home link](https://deeplearning.neuromatch.io/tutorials/intro.html) <br>

<font size="4"> (2) 机器学习深度学习-台湾大学-普通话版 (Prof.李宏毅) </font> 
[B站 video](https://www.bilibili.com/video/BV1JE411g7XF)<br>

<font size="4"> (3) Calculus -MIT (Prof Gilbert Strang) </font> 
[B站 video](https://www.bilibili.com/video/BV18z411b731) <br>
 
<font size="4"> (4) The essence of calculus (from 3blue1brown) </font> 
[video](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)  <br>

<font size="4"> (5) Linear Algebra -MIT (Prof Gilbert Strang)</font> 
[B站 video](https://www.bilibili.com/video/BV1at411d79w) <br>

<font size="4"> (6) Essence of linear algebra (from 3blue1brown) </font> 
[video](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)  <br>
<br>

<font size="4.5"> 3. Others </font> <br>
<font size="4"> (1) Introduction to Probability - MIT (Prof. John Tsitsiklis) </font> 
[home link](https://ocw.mit.edu/courses/res-6-012-introduction-to-probability-spring-2018/), [B站 video](https://www.bilibili.com/video/BV1LE411B7ir) <br>

<font size="4"> (2) Psychological Statistics - Beijing Normal University </font> 
[video](https://www.youtube.com/playlist?list=PLNybgro6DM2H7mmTV7eBBH-0nW7rtrypo) <br>

<font size="4"> (3) functional MRI principles - by Martin Lindquist and Tor Wager </font> 
[video](https://www.youtube.com/@principlesoffmri6920) <br>

<font size="4"> (4) fMRI analysis - by Jeanette Mumford </font> 
[video](https://www.youtube.com/@mumfordbrainstats/playlists) <br>

<br>
<font size="4.5"> Notes </font> <br>
<font size="4.5">  1. fMRI </font> <br>
<font size="4"> (1) View and open DICOM data </font>  <br>
Both [BeeDicomViewer](https://beedicom.com/) and [Mango](http://mangoviewer.com/usingmango.html) work good for viewing MRI raw data. 
For further analysis, you could use [mricroGL](https://www.nitrc.org/projects/mricrogl/) or [dcm2nii](https://www.nitrc.org/projects/dcm2nii/) to get data in the nii format.

<font size="4"> (2) data analysis </font>  <br>
<font size="4"> a) preprocess  </font>
When you happen to have data in the BIDS format, a preprocessing pipeline,[fMRIPrep](https://fmriprep.org/en/stable/), will work very well. Feel free to link my [notes](https://www.evernote.com/shard/s721/sh/c0f52dc3-a373-afc1-d57c-da19eb7e8ae2/hn3E1th6vOlWhKrLNENrQtWp6H85a-ejgoelDlEN6Zj4vieru_2fIXZrrg) for your reference. 
If you feel more comfortable with matlab, then [dpabi](http://rfmri.org/DPABI) would be a good choice.

<font size="4"> b) contrast analysis(GLM) </font>
I used to run GLM with [SPM](https://www.fil.ion.ucl.ac.uk/spm/course/slides23-oct/), but switch to [nilearn](https://nilearn.github.io/stable/index.html) for my current project. My notes will come out soon:) <br>

<font size="4">(3) results plot </font> <br>
There are plenty of toolbox that could plot imaging results. Here I would like to share some amazing toolbox that I am familiar with.
I first know [nilearn](https://nilearn.github.io/stable/plotting/index.html) from Dr.Li Jixing at CityU HK and this package can plot ROI, surface map, stats activations, and whatever you want. But if you would plot some clusters with different highlighted colors, [paraview](https://docs.paraview.org/en/latest/) would definitely be a better choice. Feel free to check my [note](https://www.notion.so/ParaView-for-plotting-cluster-activation-4c6d74afee8640649330c83957a6ffec?pvs=4) for your reference.

Again,if you feel more comfortable with matlab, you can find [mricorGL](https://www.nitrc.org/projects/mricrogl) and [BrainNet Viewer](https://www.nitrc.org/projects/bnv/) very useful. My notes about microGL will come out soon:)


<font size="4.5">  2. Meta-review </font> <br>
First of all, you may not want to miss the youtube channel of [Dr. Gilad Feldman](https://www.youtube.com/@GiladFeldmanScience/playlists). In his channel, you can find all video recordings of his previous workshops about behavioural meta-analysis review and of course the pre-registered report template:). 

As for fMRI coordinate-based meta-analysis, you can follow my previous project on [uncertainty processing](https://www.sciencedirect.com/science/article/pii/S1053811921003864). In this study, we employed ALE algorithm and functional connectivity analysis (incl. MACM and RSFC) to identify both task-based joint activations and synchronized spontaneous neural signals in the absence of an actual task. Here you can find my [notes](https://www.evernote.com/shard/s721/sh/a709bb6c-d8aa-d3a8-7f11-ba7194ff1cca/rcclWe5Cvk7UT_XObTR9rSagqOFU93kXmz_XlZPR_DyIP9Mf_GikTtdRPQ) about MACM analysis based on BrainMap dataset.

Besides practical tops, it is always good to learn the goals of meta science and rules of open science before starting a meta-review study.
To publish a high-impact meta research, the contribution should be clear. Interested in how to indicate a clear contribution, you are highly recommended to watch the [talk](https://github.com/wu-shuyi/meta-analysis_behavioural) offered by Dr.Rong Su from IOWA. This can also help you have a sense of how to come up with a research gap. <br>


<br>
<font size="4.5">  3. EEG </font> <br>
<font size="4"> (1) preprocessing analysis </font> <br>
In general, the preprocessing analysis would include the following steps:
a) filter pass
b) bad channels removal and interpolate
c) ICA components weight computation and bad components rejection
d) Eye blinks artifact removal
e) reference 
f) downsampling (optional)

I used to use EEGLAB and ERP to run those analyses, and my next goal is to get familiar with mne-python. 


<font size="4"> (2) ERP analysis </font> <br>
<font size="4"> (3) EEG spectrum analysis </font> <br>


<br>
<font size="4.5">  4. Eye-tracking </font> <br>
I had been involved in a project using eye-tracking a few years ago. Need some time to sort out my notes that written on the hard paper. 
<font size="4"> (1) eye-movement recording (Eyelink-SR1000) </font> <br>
<font size="4"> (2) data-analysis </font> <br>
<br>
<br>

<font size="4.5"> 5. DTI analysis </font> <br>
I will sort out my notes from a tutorial offered by a current doctoral student from Institute of Psychology CAS.


 