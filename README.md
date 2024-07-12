# The full collection of project materials
All materials for the "Multiscale Dynamics of Multimodal Communication" project in June, 2024 are uploaded here.
The final report of the project: [Final Report](Final%20Report%20-%20Multimodal%20Communication%20Modeling.pdf)

**Contributors**: Kira Miller, Lorenz Hornung and Yunchong Huang.

**Last Update**: July 5, 2024 (still under construction)

## Participatory Dominance - Yunchong Huang

- The original transcripts are in "[linguistic data processing](Yunchong%20Huang%20-%20Participatory%20Dominance/linguistic%20data%20processing)" folder;
- My codes grasp "interruptions" and "unsuccessful overlaps" and output them into _interruptions.csv files and _uns_overlap.csv files. They are stored in "[interruption](Yunchong%20Huang%20-%20Participatory%20Dominance/interruptions)" and "[uns-overlaps](Yunchong%20Huang%20-%20Participatory%20Dominance/uns_overlaps)" folders respectively;
- With the same codes two columns of "int" and "uns_ov" are added to original transcript csv files, those judged by codes to be "int" or "uns_ov" are of value 1. Files after this processing are output to the "[phase_1](Yunchong%20Huang%20-%20Participatory%20Dominance/phase_1)" folder;
-  Manual labeling for uns_overlaps.csv files and rule out some false ones, those not ruled out are of "passive" label, ruled out ones are with "ruled out" label. They are stored in the "[uns-overlaps](Yunchong%20Huang%20-%20Participatory%20Dominance/uns_overlaps)" folder for further processing;
-  Based on manual labeled uns_overlaps files I further adjusted "uns_ov" values of ruled out ones in phase_1 files to 0 output processed files to the "[phase_2](Yunchong%20Huang%20-%20Participatory%20Dominance/phase_2)" folder, these are final files for visualization;
-  Visualization graphs are stored in "[visualization](Yunchong%20Huang%20-%20Participatory%20Dominance/visualization)" folder;
-  The modelling codes used are stored in this [notebook](Yunchong%20Huang%20-%20Participatory%20Dominance/participatory%20dom%20(final).ipynb).

## Quantitative Dominance - Kira Miller

- The original transcripts with corrected timestamps based on the videos can be found in "[Transcripts with Corrected Data](Kira%20Miller%20-%20Quantitative%20Dominance/Transcripts%20with%20Corrected%20Data)" folder;
- The heatmaps for each group can be found in "[Heatmaps](Kira%20Miller%20-%20Quantitative%20Dominance/Heatmaps)" folder;
- The spreadsheet that was used to compile results can be found [here](Kira%20Miller%20-%20Quantitative%20Dominance/Turn%20Taking%20Results%20-%20Success%20Results.csv);
- The codes used for all quantitative data extraction can be found [here](Kira%20Miller%20-%20Quantitative%20Dominance/Turn_Number_and_Percentage.ipynb).
