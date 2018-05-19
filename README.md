# VAMPseq
  
This repository houses the files needed to recreate the anaylses required for the VAMP-seq manuscript. The "VAMP-seq_analysis.Rmd" R Markdown file is intended to be run with R Studio. To run this script, place these four files in the same directory:
1) "PTEN_variant_data.tsv"
2) "TPMT_variant_data.tsv"
3) "PTEN_positional_data.tsv"
4) "TPMT_positional_data.tsv"
  
Furthermore, please create a directory titled "Output", which will house image files of the plots included in the manuscript. Notably, once run, this R Markdown will also create a series of ".pml" files in the "Output" directory. These ".pml" files can be loaded into PyMOL to start interactive sessions with the VAMP-seq abundance scores overlaid on the PTEN and TPMT crystal structures.
  
<br />
  
### TPMT/PTEN Protein Variant Abundance Scores Academic License Agreement
  
The University of Washington hereby allows User and Institution to search, download, copy or use TPMT/PTEN Variant Abundance Scores (TPMT/PTEN variant abundance scores) on the following conditions:
  
1. The scores are being made available here for non-profit, non-commercial uses only. If User wishes to use TPMT/PTEN variant abundance scores, derivatives of TPMT/PTEN variant abundance scores, or the data on which they are based, for any commercial or for-profit purpose, please contact the corresponding authors. Low-cost or no-cost licenses will be extended for commercial or for-profit uses, contingent on the engagement of the licensing entity in best practices specified by ClinGen for TPMT/PTEN variant data sharing.
  
2. The University of Washington owns the intellectual property for TPMT/PTEN variant abundance scores. In any reposting of the scores or their derivatives, User agrees to retain the copyright, trademark, or other notices pertaining to TPMT/PTEN variant abundance scores as provided by UW associated with the TPMT/PTEN variant abundance scores. Use of the copyright in any printed excerpts shall include the following notice (or the equivalent thereof): 'TPMT/PTEN variant abundance scores are the copyright of the University of Washington.'
  
3. Any risk associated with using TPMT/PTEN variant abundance scores by User is with User and Institution. TPMT/PTEN variant abundance scores are experimental in nature and is made available as a research courtesy 'AS IS,' without obligation by the University of Washington to provide accompanying services or support. The TPMT/PTEN variant abundance scores are for informational purposes only, and is not intended to be a substitute for professional medical advice, diagnosis, or treatment. UW and the developer expressly disclaim any and all warranties regarding the TPMT/PTEN  abundance scores, whether expressed or implied, including but not limited to warranties pertaining to non-infringement, merchantability or fitness for a particular purpose.
  
<br />
  
<img src="https://abundance.gs.washington.edu/shiny/stability/Fig1_Cartoon.PNG"
     width="50%"
     height="50%"/>
