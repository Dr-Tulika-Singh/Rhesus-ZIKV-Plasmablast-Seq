# Rhesus-ZIKV-Plasmablast-Seq
Public repository of plasmablast B cell receptor variable region sequences associated with the following publication: Prior dengue virus serotype 3 infection modulates subsequent plasmablast responses to Zika virus infection in rhesus macaques (Singh et al., 2024, ASM mBio). 

*Please cite this paper if you use data in this repository.*

*All authors:* Tulika Singh1,5, Itzayana G. Miller6, Sravani Venkatayogi1, Helen Webster1, Holly J. Heimsath1, Josh A. Eudailey1,6, Dawn M. Dudley2, Amit Kumar1, Riley J. Mangan1, Amelia Thein6, Matthew T. Aliota4, Christina M. Newman2, Mariel S. Mohns2, Meghan E. Breitbach2, Madison Berry1, Thomas C. Friedrich3, Kevin Wiehe1, David H. O’Connor2, and Sallie R. Permar1,6*

1Human Vaccine Institute, School of Medicine, Duke University

2Department of Pathology and Laboratory Medicine, University of Wisconsin-Madison 

3Department of Pathobiological Sciences, University of Wisconsin-Madison 

4Department of Veterinary and Biomedical Sciences, University of Minnesota, Twin Cities

5Division of Infectious Disease and Vaccinology, School of Public Health, University of California, Berkeley

6Department of Pediatrics, Weill Cornell Medicine

*Corresponding author: sallie.permar@med.cornell.edu (S.R.P)

*Abstract:* Immunodominant and highly conserved flavivirus envelope proteins can trigger cross-reactive IgG antibodies against related flaviviruses, which shapes subsequent protection or disease severity. This study examined how prior dengue serotype 3 (DENV-3) infection impacts subsequent Zika virus (ZIKV) plasmablast responses in rhesus macaques (n=4). We found that prior DENV-3 infection was not associated with diminished ZIKV-neutralizing antibodies or magnitude of plasmablast activation. Rather, characterization of 363 plasmablasts and their derivative 177 monoclonal antibody supernatants from acute ZIKV infection, revealed that prior DENV-3 infection was associated with a differential isotype distribution towards IgG, lower somatic hypermutation, and lesser B cell receptor variable gene diversity as compared to repeat ZIKV challenge. We did not find long-lasting DENV-3 cross-reactive IgG after a ZIKV infection, but did find persistent ZIKV-binding cross-reactive IgG after a DENV-3 infection, suggesting non-reciprocal cross-reactive immunity. Infection with ZIKV after DENV-3 boosted pre-existing DENV-3-neutralizing antibodies by 2-3-fold, demonstrating immune imprinting. These findings suggest that the order of DENV and ZIKV infections impact the quality of early B cell immunity which has implications for optimal immunization strategies.

DEFINITION OF VARIABLES IN REPOSITORY
Each row represents heavy (VH) and light (VL) chain variable region data from a single plasmablast. VH contains the VDJ sequence. VL contains the VJ sequence. NA or No D indicates missing information or annotation due to low quality genomic sequence.

rhesus_ID = the animal identifier and day of plasmablast sampling post challenge (D), separated by an underscore (_). This defines the analytic groups of the study: Primary ZIKV (12016_D7 and 11046_D10), secondary ZIKV-ZIKV (12016_D74 and 11046_D73), secondary DENV3-ZIKV (11029_D6 and 13036_D9)
IgH_ID = heavy chain ID
H_CLEAN_VDJ_SEQ = VH nucleotide sequence obtained
H_VGENE = VH V gene annotation based on the VH sequence obtained
H_DGENE = VH D gene annotation based on the VH sequence obtained
H_JGENE = VH J gene annotation based on the VH sequence obtained
H_MUT_FREQ = somatic hypermutation frequency in the VH (must multiply by 100 to achieve a percentage)
H_CDR3_LEN_AA = length of the complementarity determining region 3 in the VH (units are number of amino acids)
H_CONST = short sequence of VH constant region used for isotype inference
ISOTYPE = constant region isotype of the VH 
LC = kappa or lambda constant region of the VL
IgL_ID = light chain ID
L_CLEAN_VJ_SEQ = VL nucleotide sequence obtained
L_VGENE = VL V gene annotation based on the VL sequence obtained
L_JGENE = VL J gene annotation based on the VL sequence obtained
L_MUT_FREQ = somatic hypermutation frequency in the VL (must multiply by 100 to achieve a percentage)
L_CDR3_LEN_AA = length of the complementarity determining region 3 in the VL (units are number of amino acids)

