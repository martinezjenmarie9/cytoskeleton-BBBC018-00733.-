# Cytoskeleton and Cell Morphology

## Project Information
**Dataset:** BBBC018

**Chosen phenotype:** Prometaphase

**Image-field ID:** 00733

**Actin filename:** 00733-Actin.DIB

**DNA filename:** 00733-DNA.DIB

**Dataset download:** https://bbbc.broadinstitute.org/BBBC018


## 2. Brief Fiji Steps

* Download and extract the [BBBC018 image dataset](https://bbbc.broadinstitute.org/BBBC018).

* Open 00733-Actin.DIB in Fiji using **File → Open**. If it fails, try **File → Import → Bio-Formats**.
  
* Open the matching `00733-DNA.DIB` file using the same method.
  
* Examine the DNA channel for condensed chromosomes consistent with prometaphase and use actin to identify cell boundaries.
  
* Choose five intact, clearly outlined cells, avoiding border cells and overlapping cells.
  
* Record the required measurements and save both plots.

## Comparison with the phenotype example on dataset webpage (Prometaphase)

### Visual Observation

In my figure, the actin image shows cells with mostly rounded or irregular shapes and visible actin staining around their boundaries. Compared with the prometaphase reference image from the Broad Institute dataset, some cells show changes in shape and actin organization that may be associated with cell division. However, actin staining alone cannot confirm prometaphase, so the DNA channel is also considered to look for condensed chromosomes.

## 3. Plots

### Plot 1: Cell Selection Image
- **Purpose:** Shows the five selected cells in the chosen field.
- **File:** `plot1.png`

### Plot 2: Cell Measurement Plot
- **Purpose:** Presents the measurements of the five selected cells.
- **File:** `plot2.png`

## Questions
* 1. Which specific phenotype did you choose, and what visible features support that choice?

I chose the prometaphase stage of mitosis as my specific phenotype. Prometaphase is characterized by the breakdown of the nuclear envelope and the attachment of spindle microtubules to the chromosomes. The chromosomes begin moving toward the middle of the cell but have not yet fully aligned at the metaphase plate. These features can support the identification of prometaphase in a fluorescence image, although chromosome arrangement and spindle structure should be visible to confirm the stage.
* 2. Were your five cells mostly round or elongated? Refer to your circularity and aspect-ratio results.
     
Based on my Fiji measurements, the five cells were mostly round to slightly elongated. Their circularity values ranged from 0.689 to 0.911, with an average of approximately 0.826. Since a circularity value closer to 1 indicates a more circular shape, most of the cells appeared relatively round. Their aspect ratios ranged from 1.024 to 1.856, with an average of approximately 1.347. Values closer to 1 indicate a rounder shape, while higher values indicate elongation. Overall, the results suggest that the cells were generally round, although some showed slight elongation.
* 3. What role does actin play in maintaining cell shape and in cell movement? (Karp, Chapter 9)
     
Actin is a major component of the cytoskeleton that helps maintain cell shape, provides structural support, and enables cell movement. Actin filaments form a network beneath the plasma membrane that helps the cell maintain its shape. They can also reorganize and work with myosin motor proteins to generate force for movement, changes in cell shape, and cytokinesis, or the division of the cytoplasm. During mitosis, actin also contributes to the formation of the contractile ring that separates the daughter cells.
* 4. Why can a single fixed fluorescence image NOT show how fast a cell moves?
     
A single fixed fluorescence image cannot show how fast a cell moves because it captures the cell at only one point in time. Fixation preserves the cell's structure and stops its movement, so there is no information about changes in position over time. To measure cell movement or speed, live-cell imaging or time-lapse microscopy is needed to track the cell's position at different time points and calculate the distance traveled per unit of time.

## References and Tools Used

**Fiji (free):** https://imagej.net/software/fiji/downloads

**R (free):** https://cran.r-project.org/

**RStudio Desktop (optional):** https://posit.co/download/rstudio-desktop/

**BBBC018 dataset page and phenotype examples:** https://bbbc.broadinstitute.org/BBBC018

**Direct download:** BBBC018
v1
_
_
images.zip (46 MB): https://data.broadinstitute.org/bbbc/BBBC018/BBBC018
v1
_
_
images.zip

> Note: I used image set BBBC018v1 from the Broad Bioimage Benchmark Collection (Ljosa et al., Nature Methods, 2012).The images are licensed CC BY-NC-SA 3.0; retain attribution when sharing image-derived screenshots.
