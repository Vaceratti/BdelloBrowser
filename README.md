# BdelloBrowser

Interactive multi-omics browser for *Bdellovibrio bacteriovorus* HD100 -
genome, transcriptome, proteome, Tn-seq in a single static HTML file,
no backend required.

**Live version:** https://<user>.github.io/<repo>/

## What it does

Per-gene view combining:
- Genome annotation (RefSeq GCF_000196175.1)
- Proteome dynamics across the predatory cycle (Lai et al. 2025)
- Secretome (Tyson et al. 2024)
- RNA-seq: own dataset (PRJNA1156087) + Karunker et al. 2013 (incl. TSS/operons, sRNA)
- Tn-seq fitness (Duncan et al. 2019)
- c-di-GMP binding candidates (Rotem et al. 2015)
- COG functional categories, UniProt/InterPro/AlphaFold/STRING/KEGG links

## Usage

Open `index.html` directly in a browser, or visit the live link above.
Core data works offline; live UniProt/KEGG/STRING lookups need internet.

## Data & citations

Full citations for all integrated datasets are in the tool's own
"About / Methodology" tab. Code is MIT-licensed. The RNA-seq dataset
PRJNA1156087 is unpublished - please contact the author before reuse.
Third-party datasets remain subject to their original publications' terms.

## Status

Research tool, actively developed alongside an ongoing publication.
