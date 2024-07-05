# The full collection of project materials
All materials for the Multimodal Communication Modelling project in June, 2024 are uploaded here.

**Contributors**: Kira Miller, Lorenz Hornung and Yunchong Huang.

**Last Update**: July 5, 2024 (still under construction)

## Participatory Dominance - Yunchong Huang

- The original transcripts are in "[linguistic data processing](Yunchong%20Huang%20-%20Participatory%20Dominance/linguistic%20data%20processing)" folder;
- My codes grasp "interruptions" and "unsuccessful overlaps" and output them into _interruptions.csv files and _uns_overlap.csv files. They are stored in "interruption" and "uns-overlaps" folders respectively;
- With the same codes two columns of "int" and "uns_ov" are added to original transcript csv files, those judged by codes to be "int" or "uns_ov" are of value 1. Files after this processing are output to the "phase_1" folder;
-  Manual labeling for uns_overlaps.csv files and rule out some false ones, those not ruled out are of "passive" label, ruled out ones are with "ruled out" label. They are stored in the "uns_overlaps" folder for further processing;
-  Based on manual labeled uns_overlaps files I further adjusted "uns_ov" values of ruled out ones in phase_1 files to 0 output processed files to the "phase_2" folder, these are final files for visualization;
-  Visualization graphs are stored in "visualization" folder.
