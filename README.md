OVERVIEW 

CHIKV-HotspotScanner is a reproducible Python-based bioinformatics workflow designed to systematically scan complete Chikungunya virus (CHIKV) genomes and identify GU-rich RNA sequence regions that may possess innate immune stimulatory potential, particularly through TLR7/8 recognition.

The pipeline quantifies GU density, detects immunologically relevant GU-motifs, computes a combined GU-based scoring metric, and provides comparative hotspot visualization across multiple genomes.

SCIENTIFIC BACKGROUND 

Chikungunya virus (CHIKV) is a positive-sense, single-stranded RNA alphavirus (~11.8 kb) that causes large outbreaks characterized by high fever, rash, and severe chronic arthritis, often lasting months to years. Despite extensive research on structural and non-structural proteins, the immunostimulatory behavior of viral RNA fragments remains under-explored.

Host immune sensing of ssRNA viruses is largely mediated by endosomal Toll-Like Receptors 7 and 8 (TLR7/8), which preferentially detect:

-short (18–40 nt) single-stranded RNA fragments

-uridine-rich (U-rich) and GU-rich motifs

-motif patterns such as UGU, GUGU, GUUGU, UGUUU, etc.

-Activation of TLR7/8 leads to:

-MyD88–NF-κB-mediated cytokine expression

-Type-I interferon release

-Antiviral inflammatory signaling

Not all viral RNA regions contribute equally to immune stimulation; therefore, genome-wide GU-rich motif mapping is a biologically relevant exploratory analysis.

PROJECT OBJECTIVE

To computationally identify, compare, and characterize GU-rich RNA hotspots across multiple CHIKV genomes that may represent candidate immunogenic RNA fragments with potential applications in:

-innate immune signaling studies

-RNA therapeutics

-RNA-based vaccine adjuvant design

-immunomodulatory oligonucleotide development

-comparative alphavirus immunobiology

