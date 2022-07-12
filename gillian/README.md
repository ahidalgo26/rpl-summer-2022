# Gillian Camacho
**Project name:** Pyhamilton Protocol Implementation on Hudson

**Advisor:** Arvind Ramanathan

**Email:** gcamacho@anl.gov

## Project Description
In a recent paper entitled "Flexible open-source automation for robotic engineering" (Chroy et al. 2021), a new software package named Pyhamilton was presented which allows the user to program the actions of Hamilton STAR and STARlet liquid handling robots using standard Python. The capabilities of Pyhamilton were demonstrated by preforming several biological experiments including the use of a feedback loop to maintain culture turbidostats and a high-throughput perturbation analysis of metabolites.For this project, we will reproduce one of the biological experiments presented in this paper using the Python interface that has been developed for the Hudson SOLO liquid handler and Hudson SoftLinx integration system. We aim to prove that our completely open-source Python API is capable of executing the same biological experiments as Pyhamilton with similar results. Students on this project will also contribute to the growing library of biological protocols written for our Hudson robotic experimentation platform.

Link to paper: https://pubmed.ncbi.nlm.nih.gov/33764680/

## Diary

### 6/24
* I attended a group recap meeting 
* I presented for journal club and finished the slides for that
* I learned how to add to github and make a pull request
* I downloaded git

### 6/27
* I met with Halona and Arleen to work on the PyHamilton Protocol
* I read and annotated the Chemputer/XDL paper
* I read more of *Machine Learning: A Concise Introduction*

### 6/28
* I met with Halona and Arleen to continue our work from 6/27 and assemble the code we wrote in the right chronological order
* I met with Casey to rework our approach for the coding of preparing the dilution plate
* I read more of *Machine Learning: A Concise Introduction*
* I started the new code for the preparation of the dilution plate and made calculations for the volumes we would use of each treatment and M9 media 

### 6/29
* I wrote code for preparing the dilution plate from stock cells
* I rethought the dilution amounts we would need because our initial idea may be wrong
* I attended a student connects meeting and panel discussion about possible career paths for my internship program

### 6/30
* I updated my dilution plate code to match the new concentration ideas using 20X stock nitrogen, 10X stock carbon, and 10X stock phosphorus with the different corresponding transfer volumes
* I attended a meeting outlining DNA assembly and how it was implemented in the past on the OT-2
* I ran my dilution ideas by Jeff in Bio and he approved it in theory
* I met with Halona and Arleen to edit the rest of our code for the changes we made to the dilution plate setup and cell stock transfer volumes

### 7/01
* I met with Halona and Arleen to create our slides for the recap meeting and touch base on how we felt about the code we made so that we could make any necessary corrections before we tested it (we still need to change the transfer volumes from the dilution plate to assay plate from 33 uL to 40uL)
* I attended this week's group recap meeting and presented about the progress myproject has made
* I attended journal club and took notes on this week's presentation about machine learning and MRIs 

### 7/05
* I found my first 8 papers on DNA assembly and DNA transformation for Priyanka
* I started to write out the procedures of interest from each of the papers I found

### 7/06
* I attended a seminar on delivering effective oral and poster presentations
* I met with Casey, Halona, and Arleen to talk about the progress we have made in our protocol for the Hudson and we scheduled a time to check our hso files and debug the code
* I attended a talk about bacterial protein nanowires
* I met for an update with HR to talk about starting my deliverables and to ask any questions I had
* We all went to 446 to check our code with Abe's help and we decided what we would need to address for correction

### 7/07
* I read the paper that will be presented on in journal club this week
* I attended a github tutorial from Alex Brace
* I calculated how to change the volumes in our protocol to work with the size of pipettes we have available and started rewriting the code in those sections
* I met with Arleen to finish the changes we had to make, and we will keep thinking of ways to make what we wrote shorthand because we were not able to think of any solutions

### 7/08
* I checked the code I wrote on 7/08 for errors and documentation problems
* I met with Halona and Arleen to make our presentation for the recap meeting at 11:00
* I attended the group recap meeting and journal club presentatinos

### 7/11
* I wrote protocol for a paper I found for Priyanka
* I met with Arleen and Halona to decide when we would need to refill tip boxes in our pyhamilton protocol and also recheck the math for the dilutions I made
* We all went to the bio building 446 to test our code in the lab, which involved making sure the code had no errors, making sure the hso files had less than 72 steps each, and seeing how the robot carried out what we called for. It was successful overall, we just have to make a change to use one full plate of M9 and one full plate of stock treatments instead of letting them split a plate. While we were there we also defined the deep well plates correctly and defined the position of the stock plate and the size of tips we were using