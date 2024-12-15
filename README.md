# Persulfidation--A-proteomic-Analysis
This is a proteomic analysis of the project "Regulation of energy metabolism by H2S in experimental models of cerebral ischemia". Use the **‘SCRIPT.pdf’** file for a quick and static view of the content. It contains lists of proteins that were found to be persulfurated.  On the other hand, refer the **‘SCRIPT.Rmd’** file if you want to run the code in R and obtain dynamic and comprehensive outputs. Request from the CVS files.

# **How to Run the Analysis**

1. Open `SCRIPT.Rmd`.
2. Ask for the remaining files stored in /-Persulfidation--A-proteomic-Analysis/Proteins. Please contact us at our lab: AL-305, Fisiología Celular UNAM.  
3. Run the R Markdown file to generate GO plots and other outputs.  
4. Outputs (GO plots) will be saved in the **`GO Plots/`** directory.  

# **Protein Data Files**

These are the oners to be asked. 

- `b.csv`: Baseline protein data.  
- `C1.csv`, `C2.csv`, `C3.csv`: Protein data for Condition C (e.g., Control).  
- `O1.csv`, `O2.csv`, `O3.csv`: Protein data for Condition O (e.g., Oxygen Deprivation).  
- `S1.csv`, `S2.csv`, `S3.csv`: Protein data for Condition S (e.g., Stress or other experimental treatments).  

# **Generated Plots**

The Gene Ontology (GO) analysis results are visualized as plots and stored in the **`GO Plots/`** folder:  

- **GO_Control_NaHS_Plot.png**: Control vs NaHS condition
- **GO_Control_OGD_Plot.png**: Control vs OGD condition
- **GO_Control_OGD_NaHS_Plot.png**: Control vs OGD + NaHS
- **GO_NaHS_Plot.png**: NaHS-specific GO enrichment
- **GO_OGD_NaHS_Plot.png**: OGD + NaHS condition
- **GO_OGD_Plot.png**: OGD-specific GO analysis

# **Folder Structured**

Persulfidation--A-proteomic-Analysis/
│
├── GO Plots/                    # Directory containing Gene Ontology result plots
│   ├── GO_Control_NaHS_Plot.png           # GO Plot: Control vs NaHS
│   ├── GO_Control_OGD_NaHS_Plot.png       # GO Plot: Control vs OGD + NaHS
│   ├── GO_Control_OGD_Plot.png            # GO Plot: Control vs OGD
│   ├── GO_Control_Plot.png                # GO Plot: General Control comparison
│   ├── GO_NaHS_Plot.png                   # GO Plot: NaHS-specific analysis
│   ├── GO_OGD_NaHS_Plot.png               # GO Plot: OGD + NaHS condition
│   └── GO_OGD_Plot.png                    # GO Plot: OGD-specific analysis
│
├── LICENSE                      # Licensing information
├── README.md                    # Project description and documentation
├── SCRIPT.pdf                   # PDF version of the analysis script
├── SCRIPT.Rmd                   # R Markdown script for the analysis
└── Proteins/  # Those are stored in our lab data base, and will be needed for running **‘SCRIPT.Rmd’** 
    ├── b.csv                    # Cuantitative analysis
    ├── C1.csv                   # Condition C1
    ├── C2.csv                   # Condition C2
    ├── C3.csv                   # Condition C3
    ├── O1.csv                   # Condition O1
    ├── O2.csv                   # Condition O2
    ├── O3.csv                   # Condition O3
    ├── S1.csv                   # Condition S1
    ├── S2.csv                   # Condition S2
    └── S3.csv                   # Condition S3