#############
Data to accompany:
“Relaxation of putative plant defenses in a tropical agroecosystem”
Lauren N Carley and Susan G Letcher
#############

correspondence:
lauren.n.carley@gmail.com

#############

“2011-Bioassays.csv” 

Contains data on palatability bioassays for leaf extracts from three species collected upstream and downstream of rice growing at one site (BAG) in 2011. 
Columns include:

Species: Plant species used to make leaf extracts
Colony_Num: Pheidole gouldi colony number (assigned to independent colonies surrounding Palo Verde Biological Station)
AntNum_5min_Control: Number of ants feeding at control extract 5 minutes after discovery
AntNum_5min_Upstream: Number of ants feeding at upstream leaf extract 5 minutes after discovery
AntNum_5min_Downstream: Number of ants feeding at downstream leaf extract 5 minutes after discovery
Upstream/Control: (AntNum_5min_Upstream)/(AntNum_5min_Control)
Downstram/Control: (AntNum_5min_Downstream)/(AntNum_5min_Control)
Difference: (Downstream/Control)-(Upstream/Control)

#############

“2013-Vachellia-EFN-thorns-ants.csv”

Contains field data on plant traits measured on acacia (V. collinsii) trees upstream and downsream of agricutlure at two sites in 2013. 
Columns include:

Block: Sub-site sampling position
Sample_no: Tree number, unique within blocks
Site: Agricultural site (BAG or FAL)
Position: Upstream vs. downstream, relative to agriculture
Date: Data collection date
DBH_cm: Diameter at breast height of the focal tree
AntRes_1min: Number of ants responding to a controlled stimulus over 60s
NumSpines_distal60cm: Total number of swollen thorns in the distal 15cm of each of 4 branches at breast height
DiamLargestSpine_mm: The basal diameter of the largest swollen thorn among the most distal 60cm of the sampled branches
Leaf1_Rachis_cm: Rachis length of collected leaf #1
Leaf1_NumEFN: Number of EFN present on collected leaf #1
Leaf1_LengthEFN_mm: The total length of the EFN glandular field, in mm, of collected leaf #1
Leaf2_Rachis_cm: Rachis length of collected leaf #2
Leaf2_NumEFN: Number of EFN present on collected leaf #2
Leaf2_LengthEFN_mm: The total length of the EFN glandular field, in mm, of collected leaf #3
Leaf3_Rachis_cm: Rachis length of collected leaf #3
Leaf3_NumEFN: Number of EFN present on collected leaf #2
Leaf3_LengthEFN_mm: The total length of the EFN glandular field, in mm, of collected leaf #3
Mean_Rachis_cm: The mean rachis length across all collected leaves from an individual tree
Mean_LengthEFN_mm: The mean EFN glandular field length across all collected leaves from an individual tree
log_AntRes: ln(AntRes_1min)
DBH_rel_to_median: “Above” = DBH > 2 cm. “Below” = DBH <= 2cm.

#############

“2013-Vachellia-herbivory.csv”

Contains data collected from scanned V. collinsii leaf images collected upstream and downstream of agriculture at two study sites in 2013.
Columns include:

Block: Sub-site sampling position
Sample_Num:
Site: Tree number, unique within blocks
Date: Date that leaf samples were collected from the field
Position: Upstream vs. downstream, relative to agriculture
DBH (cm): Diameter at breast height of the focal tree
Mean_Rachis_cm: The mean rachis length across all collected leaves from an individual tree
Num_Leaflets: Total number of leaflets present in the focal area (left hand lobe of one leaf per tree)
Total_Dam_Leaflets: Total number of leaflets in the focal area showing herbivore damage
Total_Undamaged_Leaflets: Total number of intact leaflets in the focal area
Proportion_Damaged_Leaflets: Total_Dam_Leaflets/Num_Leaflets

#############

"2013-AcephateExposure.csv"

Contains data collected from water samples assayed for acetylcoholinesterase-inhibiting insecticides using the Abraxis OP/C test kit in 2013.
Columns include:

Sample No.: Sample number
Sample Location: Study site location (BAG or FAL), or control type 
Position: Upstream or downstream relative to agriculture for field samples; "n/a" for controls
A405 (Sample): Spectropotometric absorbance at 405 nm following incubation period, according to manufacturer's protocols
A405 (Negative Control): The average spectrophotometric absorbance at 405 nm of two negative controls following incubation, according to manufacturer's protocols
% Inhibition of Color: (1-(A405 (Sample)/A405 (Negative Control)))*100

#############
 
