# Tracking Termites in a Crowded Environment

Participants are tasked with developing an algorithm to effectively track termites in a "traffic jam" scenario, where each termite must be uniquely identified and tracked throughout a video. The participants will be given three training and one validation video of termites moving in a confined space; your code should assign a unique ID to each termite and accurately record its $x$ and $y$ coordinates at every frame. The performance of your code will be evaluated on similar videos to ensure that it is robust and generalizable. We will make the training and validation videos public to all participants; however, the judging videos will be kept private. 

* participants are given **one month** to complete their submissions from the competition’s start date: November 20, 2024
* the winning participant (or the team) will receive a cash prize of **1000 USD**
  
<p align="center">
  <img src="https://github.com/AtanuChatterjee/termites/blob/main/image.png" width="450"/>
</p>
<p align="center"><em>Termites in a crowded channel</em></p>

## Training Videos

The Dropbox link provided [here](https://www.dropbox.com/scl/fo/5av213chivoadlzky7yzu/AK3eSUc__VNk_Bzv3-XRWEQ?rlkey=p0m258ja85r29iudv4tz8hc01&st=jj5gbvgp&dl=0) contains three training datasets for participants to annotate termites and train their tracking model. While the videos have been made publicly accessible, we kindly ask participants to refrain from sharing them outside the Georgia Tech community.

## Validation Videos

The Dropbox link provided [here](https://www.dropbox.com/scl/fo/5av213chivoadlzky7yzu/AK3eSUc__VNk_Bzv3-XRWEQ?rlkey=p0m258ja85r29iudv4tz8hc01&st=jj5gbvgp&dl=0) also includes one validation dataset for participants to use in testing their model. 

## Submission

Participants are expected a create a Github project with: 
* complete well-documented source code with clear explanations
* the tracked video where individual termites are distinctly segmented, with unique IDs clearly visible for each termite
* a structured dataset (e.g., CSV file) where each row represents a single frame, with columns for termite ID, $x$ and $y$ coordinates of each termite's center of mass and frame number

Once your repository is ready, send an email with the link to your GitHub repository to [Atanu Chatterjee](mailto:achatterjee96@gatech.edu) and [Saad Bhamla](mailto:saadb@gatech.edu) with the subject line "termite tracking challenge submission".

## Judging Videos

For the final evaluation, judges will use a private set of videos that are similar to the training and validation datasets. The judging dataset will remain undisclosed to participants, allowing us to objectively assess each submission’s performance in a realistic blind-testing environment.

For any questions and queries participants may reach out to [Atanu Chatterjee](mailto:achatterjee96@gatech.edu) 
