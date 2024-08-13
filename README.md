<h1>Image Enhancements in Three-dimensional Computed Tomography Baggage Screening</h1>

This repository includes descriptions of our work and data from our project on image enhancement technology in three dimensional computed tomography baggage screening. You can see an example of the experimental procedure here: https://app.gorilla.sc/openmaterials/867312

The data files included here map on to the tasks in the Gorilla Open Materials respository and outlined in our manuscript 'An Evaluation of Image Enhancements in Three-dimensional Computed Tomography Baggage Screening' as follows: 

questionnaire-xbvt - Information and consent form, questionnaire-pgup - Debrief form

task-jd1t - Browser compatibility check, no significant data recorded

task-8w8s - Fullscreen check, no significant data recorded

task-kpb7 - Experiment 1 and 2 familiarisation phase, no significant data recorded

task-ltzh - Experiment 1 and 2 item categorisation phase

    Key variables:
    'randomiser-s8gy' - The experiment and trial order the participant was assigned values with 'slice' indicate Experiment 1 and values with 'mask' indicate Experiment 2	
    'Response' - Participant response, a category of item
    'Correct' - A binary value indicating whether or not the response was correct
    'ANSWER' - The correct answer, a category of item
    'Button1Text', 'Button2Text', 'Button3Text', 'Button4Text' - The four possible answers presented on screen, all categories of item

task-enkl - Experiment 1 and 2 item recognition phase

	Key variables:
	'randomiser-s8gy' - The experiment and trial order the participant was assigned values with 'slice' indicate Experiment 1 and values with 'mask' indicate Experiment 2		'Response' - Participant response, a binary response whether they were previously trained on this category of item or not
	'Correct' - A binary value indicating whether or not the response was correct
	'ANSWER' - The correct answer, whether they were previously trained on this category of item or not
	'CorrCategoryText' - The category of item shown

task-6v2p - Experiment 1 and 2 segmentation phase

	Key variables:
	'randomiser-s8gy' - The experiment and trial order the participant was assigned values with 'slice' indicate Experiment 1 and values with 'mask' indicate Experiment 2		'Response' - Participant response, a binary response whether a bag was safe or dangerous
	'Correct' - A binary value indicating whether or not the response was correct
	'ANSWER' - The correct answer, whether the bag was safe or dangerous
	'Item1', 'Item2', 'Item3'- The three item categories present in the bag

task-h1pz - Enforced ten minute break, no significant data recorded

task-9fig - Experiment 1 test phase (trial order 1), task-rrk4 - Experiment 1 test phase (trial order 2), task-3nvc - Experiment 2 test phase (trial order 1), task-cu39 - Experiment 2 test phase (trial order 2)
 
  	Key variables:
	'randomiser-s8gy' - The experiment and trial order the participant was assigned values with 'slice' indicate Experiment 1 and values with 'mask' indicate Experiment 2		
 	'Response' - Participant response, a numerical response indicating both whether the participant believed the bag to be safe or dangerous and their confidence in their response (0 = certainly dangerous, 100 = certainly safe)
	'Correct' - A binary value indicating whether or not the response was correct
	'ANSWER' - The correct answer, whether the bag was safe or dangerous
	'type' - Whether the bag contained only unique items that had not previously been viewed or whether it contained some repeated items
