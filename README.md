This repo contains scripts and datasets needed to replicate the figures in "Uncovering differential tolerance to deletions versus substitutions with a deep protein language model." All code in `code/` is organized by figure section. 

## Data Directory

The repo is generally self-contained, although a few additional datasets must be downloaded by the user, depending on which figures are to be replicated:

- All AlphaFold .pdb files for human proteins, via https://alphafold.ebi.ac.uk/download.
- ESM1b substitution (LLR) effects, via https://huggingface.co/spaces/ntranoslab/esm_variants/blob/main/ALL_hum_isoforms_ESM1b_LLR.zip.
  
### Supplementary data files
- `data/all_helix_llr.csv.gz` All substitution effects (LLR) within helices.
- `data/all_w2g_llr.csv.gz` All W -> G substitution effects (LLR).
- `data/esm_ins_sub_pllr.csv.gz` Insertion and substitution effects, measured via PLLR, for 1,632 structurall diverse proteins.
- `data/gnomad_del_sub_merge_AF.csv.gz` Allele frequencies for all sites in gnomAD containing both a single in-frame amino acid deletion and a substitution.
- `data/tsuboyama_ddg.csv` Processed ddG measurements from Tsuboyama et al. https://doi.org/10.1038/s41586-023-06328-6
- `data/tsuboyama_esmfold_plddt.csv` Average ESMFold pLDDT per structure in Tsuboyama et al. containing a D-S+ site, and deletions and substitutions on these sites.
- `data/uniprot_domains.tsv.gz` All annotated UniProt domains for human canonical transcripts.
- `data/uniprot_sequences_all.tsv.gz` All sequences for all human proteins in UniProt.

## Code Directory

Find scripts to replicate all main text figures. 
