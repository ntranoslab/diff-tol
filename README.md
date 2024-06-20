This repo contains scripts and datasets needed to replicate the figures in "Uncovering differential tolerance to deletions versus substitutions with a deep protein language model." All code in `code/` is organized by figure section. 

The repo is generally self-contained, although a few additional datasets must be downloaded by the user, depending on which figures are to be replicated:

- All UniProt annotated domains, via `Domain [FT]` column at https://www.uniprot.org/uniprotkb?query=Human&facets=reviewed%3Atrue%2Cmodel_organism%3A9606.
- All AlphaFold .pdb files for human proteins, via https://alphafold.ebi.ac.uk/download.
- ESM1b substitution (LLR) effects, via https://huggingface.co/spaces/ntranoslab/esm_variants/blob/main/ALL_hum_isoforms_ESM1b_LLR.zip.
- All protein sequences (canonical and isoforms), via `Sequence` column at https://www.uniprot.org/uniprotkb?query=Human&facets=model_organism%3A9606%2Creviewed%3Atrue.
  
