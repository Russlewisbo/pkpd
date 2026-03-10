# Images Directory

This folder is designated for images used in the PK-PD Quarto documents.

## Required Images

The following images are noted as needed in the documents:

### chapter-webpage.qmd

1. **Figure 19.2** - Simulated serum concentration-time profile
   - Shows oral vs IV administration comparison
   - Key parameters labeled (Cmax, Tmax, AUC)

2. **Figure 19.3** - Common antibiotic PK-PD relationships
   - Diagram showing Cmax/MIC, AUC0-24/MIC, T>MIC, and Cmin
   - Concentration-time curve with MIC threshold line

3. **Figure 19.4** - Time-kill curves
   - Shows concentration-dependent killing patterns
   - Example: P. aeruginosa with tobramycin, ciprofloxacin, and ticarcillin

4. **Figure 19.5** - Infusion comparison
   - Simulated serum concentration-time profiles
   - Compares 1-hour, 4-hour, and continuous infusion

5. **Figure 19.6** - Loading dose importance
   - Comparison of continuous infusion with and without loading dose
   - Shows delayed achievement of threshold without loading

6. **Figure 19.7** - Therapeutic window concept
   - Hypothetical exposure vs. desired/undesired effect curves
   - Shows therapeutic index and safety margins

### chapter-slides.qmd

1. **logo.png** - Optional logo for slide footer (can be removed from YAML if not available)

2. **pkpd-triangle.png** - Three-way relationship diagram
   - Drug → Pathogen, Drug → Host, Drug → Microbiome

3. **Concentration-time curve** - Basic PK profile showing:
   - AUC, Cmax, Cmin, T>MIC

## Conceptual Images Needed

The following images would enhance the educational content:

### Mechanism Diagrams

1. **PK-PD indices visualization**
   - Clear illustration of Cmax/MIC, AUC/MIC, and T>MIC
   - Color-coded for different antibiotic classes

2. **ADME process diagram**
   - Visual flowchart of absorption, distribution, metabolism, elimination

3. **Hollow fiber model schematic**
   - Cross-section showing fiber structure
   - Drug and bacteria flow patterns

### Comparison Graphics

1. **Time-dependent vs concentration-dependent killing**
   - Side-by-side comparison of killing patterns
   - Representative agents for each category

2. **Traditional vs extended-interval aminoglycoside dosing**
   - Concentration-time profiles for both approaches
   - Highlighting Cmax/MIC differences

3. **Intermittent vs extended vs continuous β-lactam infusion**
   - Three panels showing different infusion strategies
   - T>MIC highlighted for each

### Clinical Application Graphics

1. **TDM decision flowchart**
   - When to monitor, what targets to use
   - Drug-specific considerations

2. **Vancomycin AUC-based dosing diagram**
   - Evolution from trough to AUC monitoring
   - Two-sample vs Bayesian approaches

## Image Sources

For educational materials, consider sourcing images from:

- Wikimedia Commons (Creative Commons licensed)
- Open access journal figures (with proper attribution)
- Original illustrations created for teaching purposes
- Textbook publisher image libraries (with permission)

## Note on Copyright

Do NOT include copyrighted medical images without proper licensing. When using Creative Commons images, ensure proper attribution is included in the figure captions.

## Suggested Tools for Creating Original Figures

- BioRender (academic license available)
- R/ggplot2 for data visualizations
- Mermaid diagrams (embedded in Quarto)
- draw.io for flowcharts
