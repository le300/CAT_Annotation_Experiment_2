# CAT_Annotation_Experiment_2

This repository contains the data, code for the statistical analyses, and other supplemental materials for the paper "Measuring inter-subjective agreement on units and attributions in comics with annotation experiments".

## File List


* [Examples_Background_Information_Amount.pdf](Examples_Background_Information_Amount.pdf) - This pdf provides a simple annotation scheme with instructions on how to approach annotating a comics page, as well as examples annotated panels. This pdf is downloadable from the Comics Annotation Tool (CAT) so that an annotator can refer to it at any time.

* [Participant_Information_Sheet.pdf](Participant_Information_Sheet.pdf) - This pdf is an information sheet about the study described in the associated paper. This information sheet shows that the study was approved by Queen Mary University of London, and was given to every annotator before their participation in the study.

* [Consent_Form.pdf](Consent_Form.pdf) - This pdf is the consent form given to each annotator to confirm that they choose to participant in the study and can withdraw consent at any time. These statements were given to each annotator to initial and sign out within the Comics Annotation Tool (CAT).

* [Annotations_Prolific](Annotations_Prolific) - This folder contains all the collected annotations for each study.
  
  * [Background_Detail_Binary_Story1](Annotations_Prolific/Background_Detail_Binary_Story1) - Holds all the annotations collected when testing agreement for Story 1 using a binary scale. The [Processed_Data](Annotations_Prolific/Background_Detail_Binary_Story1/Processed_Data) subfolder contains each individual participant's annotations in JSON files. 
  * [Background_Detail_Binary_Story2](Annotations_Prolific/Background_Detail_Binary_Story2) - Holds all the annotations collected when testing agreement for Story 2 using a binary scale. The [Processed_Data](Annotations_Prolific/Background_Detail_Binary_Story2/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Background_Detail_LikertScale_Story1](Annotations_Prolific/Background_Detail_LikertScale_Story1) - Holds all the annotations collected when testing agreement for Story 1 using an ordinal scale. The [Processed_Data](Annotations_Prolific/Background_Detail_LikertScale_Story1/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Background_Detail_LikertScale_Story2](Annotations_Prolific/Background_Detail_LikertScale_Story2) - Holds all the annotations collected when testing agreement for Story 2 using an ordinal scale. The [Processed_Data](Annotations_Prolific/Background_Detail_LikertScale_Story2/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Background_Detail_RealValue_Story1](Annotations_Prolific/Background_Detail_RealValue_Story1) - Holds all the annotations collected when testing agreement for Story 1 using a continuous scale. The [Processed_Data](Annotations_Prolific/Background_Detail_RealValue_Story1/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Background_Detail_RealValue_Story2](Annotations_Prolific/Background_Detail_RealValue_Story2) - Holds all the annotations collected when testing agreement for Story 2 using a continuous scale. The [Processed_Data](Annotations_Prolific/Background_Detail_RealValue_Story2/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
 
* [Inter-Annotator_agreement_analysis_code](Inter-Annotator_agreement_analysis_code) - This folder contains the code to calculate annotator agreement for each study, and all results including heatmaps visualizing annotator agreement and reliability. The analyses are done using python within jupyter notebook files. Annotation data can be read in from the JSON files in the [Annotations_Prolific](Annotations_Prolific) folder. 

  * [Background_Detail_Binary_Story1.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_Binary_Story1.ipynb) - Contains agreement results for Story 1 using a binary measure.
  * [Background_Detail_Binary_Story2.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_Binary_Story2.ipynb) - Contains agreement results for Story 2 using a binary measure.
  * [Background_Detail_LikertScale_Story1_checked.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_LikertScale_Story1_checked.ipynb) - Contains agreement results for Story 1 using an ordinal scale.
  * [Background_Detail_LikertScale_Story2_checked.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_LikertScale_Story2_checked.ipynb) - Contains agreement results for Story 2 using an ordinal scale.
  * [Background_Detail_RealValued_Story1_checked.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_RealValued_Story1_checked.ipynb) - Contains agreement results for Story 1 using a continuous scale.
  * [Background_Detail_RealValued_Story2_checked.ipynb](Inter-Annotator_agreement_analysis_code/Background_Detail_RealValued_Story2_checked.ipynb) - Contains agreement results for Story 2 using a continuous scale.
  * [Background_Location_Information_Amount_Comparisons_checked.ipynb](Inter-Annotator_agreement_analysis_code/Background_Location_Information_Amount_Comparisons_checked.ipynb) - Contains analyses between the distributions of agreement scores between annotator pairs, inlcuding significance tests and visualizations of mean agreement scores per-panel. 

* [ComicPages](ComicPages) - This folder contains pdfs of all the comic pages that were annotated in the annotation experiments described in the paper. 

  * [Story1](ComicPages/Story1) - This folder contains all five pages of "The Cadmus Seed!" as pdfs. [Story1_Info.md](ComicPages/Story1/Story1_Info.md) provides the authorship and publication information. 
  * [Story2](ComicPages/Story2) - This folder contains all five pages of "The Fourth Dimension is a Many Splattered Thing!" as pdfs. [Story2_Info.md](ComicPages/Story2/Story2_Info.md) provides the authorship and publication information.
  * [Story3](ComicPages/Story3) - This folder contains all five pages of "My Robot Plants" as pdfs. [Story3_Info.md](ComicPages/Story3/Story3_Info.md) provides the authorship and publication information.
  * [Story4](ComicPages/Story4) - This folder contains all five pages of "The Man Who Never Lived" as pdfs. [Story4_Info.md](ComicPages/Story4/Story4_Info.md) provides the authorship and publication information.

* [VLFI_Questionnaire.pdf](VLFI_Questionnaire.pdf) - This pdf provides the questions of the Visual Language Fluency Index (VLFI). These questions were given to each annotator to fill out within the Comics Annotation Tool (CAT).  

* [Annotator_competence_and_reliability.pdf](Annotator_competence_and_reliability.pdf) - This pdf goes into detail about agreement between annotator pairs and assesses the reliability of individual annotators. Heatmaps per study condition and all the Visual Language Fluency Index (VLFI) scores are provided. 




