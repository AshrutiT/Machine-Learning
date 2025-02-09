# MEDIQA-Sum 2023 Training/Validation Data


## Data

https://github.com/ImageCLEF/2023_ImageCLEFmed_Mediqa/tree/main/dataset 

## Description

### Tasks A:

The training set consists of 1,201 pairs of conversations and associated section headers and contents. 
The validation set consists of 100 pairs of conversations and their summaries. 


The full list of normalized section headers: 

1. fam/sochx [FAMILY HISTORY/SOCIAL HISTORY]
2. genhx [HISTORY of PRESENT ILLNESS]
3. pastmedicalhx [PAST MEDICAL HISTORY]
4. cc [CHIEF COMPLAINT]
5. pastsurgical [PAST SURGICAL HISTORY]
6. allergy
7. ros [REVIEW OF SYSTEMS]
8. medications
9. assessment
10. exam
11. diagnosis
12. disposition
13. plan
14. edcourse [EMERGENCY DEPARTMENT COURSE]
15. immunizations
16. imaging
17. gynhx [GYNECOLOGIC HISTORY]
18. procedures
19. other_history
20. labs



Depending on the encounter, objective_exam and objective_results may not be relevant.
We encourage review the sample data as well as the evaluation script to understand the best demarkation headers for your generated note. 
