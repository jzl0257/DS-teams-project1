# DS-teams-project1
# Quick navigation
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Repo Structure](#repo-structure)  
[Logistics](#project-logistics)  
[Resources](#resources)  
[Contact](#contact-info)  

# Goal

The motivating goal of this work is to identify the location(s) of ancient stone tool manufacturing sites given 50 soil samples from the Maya site of Nacimiento and 30-50 stoneknapping microdebitage exemplar samples. To achieve this result, this project will focus on generating a model or algorithm to characterize the composition of soil samples by identifying particles which are likely microdebitage. The model may then be used to calculate the percentage composition of the entire soil sample which is microdebitage, enabling the ability to identify which households likely hosted stoneknapping work. A secondary objective is to establish a workflow for the management of data, although this will proceed in parallel with the modeling and characterization efforts.


# Background  

Analyzing lithic microdebitage (<4mm debris produced in the creation of stone tools) can reveal ancient stone manufacturing sites to provide insight into past cultural activity. In this work, we build models to identify microdebitage particles from soil samples collected from a Mayan village. These models are then used to characterize the soil composition to reveal ancient stoneknapping sites in Nacimiento, Guatemala.

# Data

Data is provided by the DSI under a Data Access agreement.

## Data security

Because the data is only given to us under a data access agreement, it CANNOT be shared outside of the project and access to the repository must be limited to those who have signed the agreement.

## Counts

Currently, there are 50 soil samples from the Mayan village of interest. The goal is to identify the composition of these soil samples, and the contained particles will be characterized by the PartAn 3D particle analyzer. The particle analyzer measures 40 variables for every particle, and there are approximately ~500,000 particles in every sample. The training data contains 30-50 collected and labelled microdebitage samples collected from modern stoneknappers, and represents the stages of specific work.

# Models

In modeling, we will attempt to classify lithic microdebitage from standard soil smaples.

# Timeline

Start of Project: Jan 30th, 2022

Project Deadline: Feb 28th, 2022

# Repo Structure

The repo is structured as follows: All *0- (e.g., 10-, 20-, 30-) files contain finalized work for the purpose described (e.g., "process-data"). Subfiles related to the task (e.g., 11-, 12-) should be created in order to explore and document relevant or interesting subtasks.

All files which appear in the repo should be able to run, and not contain error or blank cell lines, even if they are relatively midway in development of the proposed task. All notebooks relating to the analysis should have a numerical prefix (e.g., 31-) followed by the exploration (e.g. 31-text-labeling). Any utility notebooks should not be numbered, but be named according to their purpose. All notebooks should have lowercase and hyphenated titles (e.g., 10-process-data not 10-Process-Data). All notebooks should adhere to literate programming practices (i.e., markdown writing to describe problems, assumptions, conclusions) and provide adequate although not superfluous code comments.

# Project logistics

**Sprint planning**:  Sprint planning is done in a weekly meeting held on Fridays.
**Demo**:  Not applicable to this sample project.

**Data location**:  Data is currently on the repo as it is a private repo to only us.

**Slack channel**:  Our Slack Channel is #sp22_teams_team9 in the Data Science MS Slack
**Zoom link**:  https://vanderbilt.zoom.us/j/95537652368?pwd=S1J1TXVRK3FrL3J5QXhmTGFKY3JxUT09

# Resources

DSI Cool Things video explaining this project: https://www.youtube.com/watch?v=_Yq5ixf95Ao&t=509s&ab_channel=VanderbiltDataScience


# Contact Info

Preston Abraham, Team Lead

preston.d.abraham@vanderbilt.edu


Shihan Lyu,Team Member

shihan.lyu@Vanderbilt.Edu


Alvin (Yiwen) Chen, Team Member

yiwen.chen@vanderbilt.edu


Jonathan Srinivasan, Team Member                       

jonathan.devaraj.srinivasan@vanderbilt.edu            
