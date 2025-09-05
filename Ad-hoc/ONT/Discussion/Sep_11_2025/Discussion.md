# Dataset
## 20% Reads
1. SD386613
   * Total Size of Passed BAM(aligned): 63 GB
```
/DCEG/CGF/Sequencing/ONT/Prom24/RawData/AS_chrX_ONT_training_07012025/SD386613/20250701_1804_1C_PBE55027_8e8920e8/bam_pass
```
2. SD407538
   * Total Size of Passed BAM(aligned): 19.63 GB
```
/DCEG/CGF/Sequencing/ONT/Prom24/RawData/AS_chrX_ONT_training_07012025/SD407538/20250701_1804_1F_PBE54594_26fb9d5f/bam_pass
```
## Whole Flowcell
1. SD386613
   * Reload 5 times
   * Total Size of Passed BAM(aligned): 148.68 GB
```
/DCEG/CGF/Sequencing/ONT/Prom24/PostRun_Analysis/20250701_1804_1C_PBE55027_8e8920e8/pass
```
2. SD407538
   * Total Size of Passed BAM(aligned): 77.50 GB
```
/DCEG/CGF/Sequencing/ONT/Prom24/PostRun_Analysis/20250701_1804_1F_PBE54594_26fb9d5f/pass
```
# Discussions
1. The coverage issue between "20% Reads" and "Whole Flowcell"
2. The reads number in chrX VS reads number in the whoe BAM
3. The consistancy between the results from self-count and toulling QC

## The coverage issue between "20% Reads" and "Whole Flowcell"
### Output From humane-variant pipeline
We use 4 types of results for quick evaluation, including 
   * bed_summary.tsv
   * flagstat.tsv
   * mosdepth.summary.txt
   * reads_per_hour.png (draw it based on "sequencing_summary.txt" from my code)

1. SD386613
```
(1) "20% Reads" 
    a) General reslts: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results

(2) Whole Flowcell
    a) General reslts: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results
    b) Plot of reads_per_hour: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results/Whole_Flowcell_huname_variant_pipeline_SD386613_reads_per_hour.png
```
   
2. SD407538
```
(1) "20% Reads" 
    a) General reslts: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results

(2) Whole Flowcell
    a) General reslts: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results
    b) Plot of reads_per_hour: https://github.com/Bio-Developer-lxwg/ProjectRecord/tree/main/Ad-hoc/ONT/Discussion/Sep_11_2025/Results/Whole_Flowcell_huname_variant_pipeline_SD407538_reads_per_hour.png
```
 
