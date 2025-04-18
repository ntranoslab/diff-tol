This repo contains scripts and datasets needed to replicate the figures in "Uncovering differential tolerance to deletions versus substitutions with a deep protein language model." All code in `code/` is organized by figure section. 

## Data Directory

The repo is generally self-contained, although a few additional datasets must be downloaded by the user, depending on which figures are to be replicated:

- All AlphaFold .pdb files for human proteins, via https://alphafold.ebi.ac.uk/download.
- ESM1b substitution (LLR) effects, via https://huggingface.co/spaces/ntranoslab/esm_variants/blob/main/ALL_hum_isoforms_ESM1b_LLR.zip.
  
### Supplementary data files
- `data/tsuboyama_ddg_esm_scores.csv.gz` Tsuboyama sites with ESM-predicted deletion and substitution tolerance.
- `data/tsuboyama_ddg_processed.csv.gz` Processed ddG measurements from Tsuboyama et al. https://doi.org/10.1038/s41586-023-06328-6
- `data/tsuboyama_2mkx_i36.csv` Raw, disaggregated stability change measurements at position I36 in domain 2MKX from Tsuboyama et al. 
- `data/pg_predictions_with_esm.csv.gz` Experimental deletion datasets curated from https://proteingym.org/ with VEP scores, including ESM. 
- `data/esm_ins_sub_pllr.csv.gz` Insertion and substitution effects, measured via PLLR, for 1,632 structurall diverse proteins.
- `data/uniprot_domains.tsv.gz` All annotated UniProt domains for human canonical transcripts.
- `data/uniprot_sequences_all.tsv.gz` All sequences for all human proteins in UniProt.
- `data/pdb_data.csv.gz` Contact number, rSASA, binding site data computd from the .pdb file or extracted from UniProt. 

## Code Directory

Find scripts to replicate all main text and supplementary figures. 
