# Machine Learning Engineer Nanodegree
## Capstone Proposal
Jonatan Dellagostin  
February 31st, 2018

## Proposal

Surface electromyography (sEMG) is the temporal and
spatial superposition of faint b
ioelectrical signals generated
by the muscle nerve cells during muscle contraction [
1]. It
is collected and recorded through the skin surface elec-
trodes. Compared to conventional EMG signal acquisition
that requires inserting a needle
electrode into muscle tissue,
the sEMG signal has the advantages of being noninvasive
and providing the convenience of collection. The sEMG
signal from the arm has been used in human-computer
interaction, rehabilitation trai
ning, and artificial prosthesis
[2
–
5]. Because it can indirectly reflect the gestures of the
person, it has extensive application and research value 
NinaPro - Non-Invasive Adaptive Hand Prosthetics
Daily life of hand amputees can be poor compared to what it was before the amputation. The state of the art in hand prosthetics, at the time of writing, does not offer more than 2-3 degrees of freedom and a very coarse control of the force, as there is no haptic feedback. Patients interface with the prothesis via surface electromyography (sEMG), recorded using surface electrodes. Learning how to control the device through many input sEMG channels is a long and difficult process for most patients, that therefore settles for limited and very simplified movements (open/close). This contrasts with recent advances in mechatronics, thanks to which mechanical hands gifted with many degrees-of-freedom and force control are being built. There is a need for prosthetic hands able to naturally reproduce a wide amount of movements and forces, while at the same time requiring a lower effort in learning how to control hand postures. This goes beyond mechatronic dexterity: the real challenge is how to provide patients with a cheap, easy and natural way of controlling the prosthesis. 
The goal of this project is to develop a family of algorithms able to significantly augment the dexterity, and reduce the training time, for sEMG controlled prosthesis. By testing our findings on a very large collection of data, this project will pave the way for a new generation of prosthetic hands. The work will be organized along the following four themes.

Theme 1: Data Acquisition and Analysis. The goal of this theme is to develop a reproducible protocol to acquire large data sets for healthy patients performing certain movements and amputated patients also making complex movements, while analyzing and assessing the data as they become avaliable. The data acquisition includes the acquisition of signal data and the calibration of the sensors to limit the noise in the data. Relevant clinical data will be acquired at the same time such as age, gender, height, weight and for amputated patients also the exact place of the amputation and the time between amputation and tests performed. The data acquisition and analysis will proceed in close connection with the other themes.

Theme 2: Augmented Dexterity: Posture Classification. The objective of this theme is to push the current state of the art in prosthetic hand posture classification from handling a maximum of 12 postures up to 40-50. We will design and implement state of the art machine learning algorithms within the multi kernel learning framework, using the sEMG signals separated instead of concatenated, as it is the mainstream practice today. We will then proceed to extend the algorithm so to exploit the intrinsic hierarchical structure of hand postures. The outcome of this theme will offer patients a much wider dexterity compared to the current state of the art.

Theme 3: Augmented Dexterity: Natural Control. This research theme is about pushing the envelope of sEMG control: extending it to a quasi-perfect prediction of force, by independently modeling and controlling single degrees-of-motion. The overall aim is then to augment the dexterity that an sEMG-controlled prosthesis could potentially achieve mimicking the way a human hand works. Results in this theme will be periodically benchmarked against those achieved in Theme 2.

Theme 4: Adaptive Learning. The goal of this theme is to develop learning algorithms to better interpret the sEMG signals acquired from the patients, with the ultimate goal of boosting the learning process necessary for the patient to effectively use the prosthesis. We will build pre-trained models of various data postures, on the data acquired in theme 1, and we will adapt these general models to the needs of individual users as new data will became available using adaptive online learning methods.



### Domain Background
_(approx. 1-2 paragraphs)_


In this section, provide brief details on the background information of the domain from which the project is proposed. Historical information relevant to the project should be included. It should be clear how or why a problem in the domain can or should be solved. Related academic research should be appropriately cited in this section, including why that research is relevant. Additionally, a discussion of your personal motivation for investigating a particular problem in the domain is encouraged but not required.

### Problem Statement

The problem faced by amputees is the lack of some part of an arm, specially the hand. A robotic hand is a proposed solution in the field of prosthetics.  In the case of a real hand, the movements are triggered by eletrical impulses sent by the brain. They travel through the nerves until reaching the arm muscles inervations, which are then activated and produces the muscular activity responsable for the hand movements. 
The common approach is to provide a functional prosthesis that simulates some of the most important movements of a real hand.


### Datasets and Inputs
_(approx. 2-3 paragraphs)_

https://www.idiap.ch/project/ninapro

In this section, the dataset(s) and/or input(s) being considered for the project should be thoroughly described, such as how they relate to the problem and why they should be used. Information such as how the dataset or input is (was) obtained, and the characteristics of the dataset or input, should be included with relevant references and citations as necessary It should be clear how the dataset(s) or input(s) will be used in the project and whether their use is appropriate given the context of the problem.

### Solution Statement
_(approx. 1 paragraph)_

In this section, clearly describe a solution to the problem. The solution should be applicable to the project domain and appropriate for the dataset(s) or input(s) given. Additionally, describe the solution thoroughly such that it is clear that the solution is quantifiable (the solution can be expressed in mathematical or logical terms) , measurable (the solution can be measured by some metric and clearly observed), and replicable (the solution can be reproduced and occurs more than once).

### Benchmark Model
_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
