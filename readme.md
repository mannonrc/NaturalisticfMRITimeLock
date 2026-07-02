## Naturalistic fMRI Timelock

This experiment is intentioned to timelock a task-based functional magnetic resonance imaging (fMRI) scan with the beginning of a film using open-source software, PsychoPy.

In a blood-oxygen level dependent (BOLD) fMRI scan, analysis of brain activity can provide insight into which brain circuits are responsible for comprehension of speech and behavior. This experiment is "naturalistic" because it utilizes a stimulus that emulates a "natural" situation, such as conversations between colleagues at work. By displaying a naturalistic stimulus, analysis of brain activity is more translatable and applicable to real-life environments that a subject might experience.

Written into this program is also variable start functionalitym which allows the researcher to manually enter the stimulus start for any timepoint before the scan begins. This feature was included to allow flexibility in the procedure, such as in the case a participant needs to leave the scanner. This functionality is also helpful if a researcher wants to show only a specific part of the stimulus. To exit the program, researchers can use the "escape" or "space" keys.

The machine used in these experiments is a 3T Siemens Prisma MRI scanner that is triggered by the number "5". Dummy scans are not saved in data and are therefore not accounted for in the program. Due to copyright laws, stimulus films are not included in this repository. Note that the .psyexp file is the same experiment as the .py file but represented in the proprietary PsychoPy experiment format. This file type can be managed through the PsychoPy editor and all updates will be automatically saved to a corresponding python source (.py) file. 
