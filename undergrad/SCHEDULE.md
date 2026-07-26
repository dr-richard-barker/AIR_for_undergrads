---
description: >-
  12-week course schedule mapping astrobotany topics to readings, lab activities,
  and deliverables.
---

# 📅 Weekly Course Schedule

This schedule details the weekly topics, readings, lab exercises, and assignments for the 12-week undergraduate track.

---

## 🗺️ Week-by-Week Calendar

### Week 0: Course Intro, FAIR Data, & Safety
* **Topics & Focus**: Introduction to astrobotany history; the importance of plants in closed-loop life support systems; introduction to the Open Science/FAIR data ethos.
* **Required Readings**:
  * [🌱🚀 Grow Plants in Space](../index.md)
  * [Program Overview — Microgreens in Microgravity](../program-overview.md)
  * [Introduction to AstroBotany & Data Sharing](../air-astrobotany-introduction/README.md)

---

### Week 1: Plant Growth Basics & Scientific Photography
* **Topics & Focus**: Principles of crop selection (microgreens); lighting parameters (PPFD, spectrum); setup and calibration of a scientific photography station.
* **Required Readings**:
  * [Stage I: Scientific Photography](../stage-i-scientific-photography/README.md)
  * [Space Biology Photography Guide](../stage-i-scientific-photography/photography-guide.md)
  * [Stage II: What's Your Favorite Microgreen?](../stage-ii-whats-your-favorite-microgreen/README.md)
  * [Table 2: Microgreen Growth Rates](../stage-ii-whats-your-favorite-microgreen/tables-of-microgreen-growth-rates-and-example-conditions-to-use-a-general-guide.md)
* **Practical Lab Activity**: Assemble the photography station (contrasting background, scale bar, soft box lighting). Photograph a reference object and verify alignment. Select 2 microgreen varieties for the terrestrial growth experiment.
* **Deliverable**: Upload a calibrated reference photograph to your lab journal demonstrating proper scale bar placement and color balance.

---

### Week 2: Terrestrial Microgreen Experiment Setup
* **Topics & Focus**: Germination biology; terrestrial growth media (soil vs. coconut coir vs. hydroponic mats); experimental controls and baseline parameter documentation.
* **Required Readings**:
  * [Stage III: Growth of Microgreens in Terrestrial Environments](../stage-iii-growth-of-microgreens-in-terrestrial-environments/README.md)
  * [Green Area Index with PlantCV](../stage-iii-growth-of-microgreens-in-terrestrial-environments/green-area-index-with-plantcv.md)
* **Practical Lab Activity**: Plant seeds of your selected microgreens. Position trays under lights and capture Day 0 baseline photographs. Run basic PlantCV testing locally or on Colab.
* **Deliverable**: Complete the Day 0 setup entry, including exact species names, seeding density, lighting cycle, and initial photo.

---

### Week 3: Tropisms & Gravitropic Reorientation
* **Topics & Focus**: Gravity perception in plants (statoliths, starch-statolith hypothesis, Cholodny-Went model); root vs. shoot tropisms; introduction to agar growth plates.
* **Required Readings**:
  * [Stage IV: Microgreen Development and Gravitropic Response](../research-stage-iv-microgreen-development-and-gravitropic-response/README.md)
  * [Gravity and Mechanical Sensing in Plants](../research-stage-iv-microgreen-development-and-gravitropic-response/gravity-and-mechanical-sensing-in-plants.md)
* **Practical Lab Activity**: Germinate seeds vertically on plant-based agar or wet filter paper in Petri dishes. On Day 3, rotate the plates 90 degrees and document the gravitropic reorientation kinetics at multiple intervals.
* **Deliverable**: Log reorientation images taken at T=0h, T=2h, T=6h, and T=24h post-rotation in your lab notebook.

---

### Week 4: Image Processing & Root Architecture
* **Topics & Focus**: Image analysis theory; extracting quantitative metrics from plant biology photographs; computing Green Area Index (GAI) and root mapping algorithms.
* **Required Readings**:
  * [Measuring Root System Architecture](../research-stage-iv-microgreen-development-and-gravitropic-response/root-system-architecture-with-plantcv.md)
  * [Tools & Software](../tools.md)
* **Practical Lab Activity**: Run your Week 3 reorientation photos through Fiji/SmartRoot or the PlantCV pipeline to extract root length, root tip angle, and hypocotyl growth rates.
* **Deliverable**: Submit a structured table containing raw phenotypic data (root angle and growth rate) extracted from your images.

---

### Week 5: Statistics, Reproducibility, & Data Sharing
* **Topics & Focus**: Statistical analysis in plant biology (ANOVA, t-tests, standard error); data validation and ingestion; collaborative science tools.
* **Required Readings**:
  * [Assessment & Learning Gains](../assessment.md)
  * [For Citizen Scientists](../citizen-scientists.md)
* **Practical Lab Activity**: Clean the group dataset, run an ANOVA or t-test comparing the gravitropic response rates of your varieties, and upload the finalized, formatted dataset to [Epicollect5](https://five.epicollect.net/).
* **Deliverable**: Upload proof of your Epicollect5 data submission and paste the output of your statistical analysis (including p-values and graphs) in your lab journal.

---

### Week 6: Midterm Project Proposals
* **Topics & Focus**: Writing research proposals; formulating hypotheses; experimental design variations (e.g., adding abiotic stress, light quality variations, or chemical treatments).
* **Required Readings**:
  * [Project Management Page](../project_management/README.md)
* **Practical Lab Activity**: Work in groups to draft your midterm proposals. Peer-review other groups' experimental designs and resource budgets.
* **Deliverable**: Submit your Midterm Independent Project Proposal (max 3 pages, including hypothesis, methods, safety checklist, and timeline).

---

### Week 7: Plant Hormones & Tissue Cloning
* **Topics & Focus**: Plant hormones (auxin, cytokinin, gibberellin); tissue culture and callus induction; stem cell biology.
* **Required Readings**:
  * [Stage V: Auxin and Plant Cloning](../stage-v-auxin-and-plant-cloning.md)
* **Practical Lab Activity**: Prepare sterile growth medium containing auxin (2,4-D). Dissect microgreen seedlings under sterile conditions and place explants on callus induction medium.
* **Deliverable**: Log tissue setup details (sterilization workflow, hormone concentrations) and insert baseline microscope images of explants.

---

### Week 8: Simulated Microgravity & Advanced Assays
* **Topics & Focus**: Clinostats and Random Positioning Machines (RPMs); physics of simulated microgravity; 3D root mapping challenges.
* **Required Readings**:
  * [Stage VI: Micro-Gravi-tropism Assays](../research-stage-vi-gravitropism-assays.md)
  * [For Researchers — from skills to the microgravity RPM](../extension-research-track.md)
* **Practical Lab Activity**: Mount petri dishes onto a 2D clinostat or RPM (such as the CoSE SciSpinner). Set rotation parameters and monitor growth adaptation overnight compared to vertical controls.
* **Deliverable**: Document simulated microgravity rotation rates, exposure times, and comparative root-curvature plots.

---

### Week 9: Computational Biology & Modeling
* **Topics & Focus**: Functional-Structural Plant Modeling (FSPM); simulating auxin gradients; RNA-seq overview and transcriptomic analysis.
* **Required Readings**:
  * [Stage VII: Hormone Transport Modeling](../stage-vii-modelling-of-plant-hormone-transport.md)
  * [Stage VIII: Root Modeling](../stage-viii-root-modelling/README.md)
  * [Stage IX: Plant Modeling](../stage-ix-plant-modelling/README.md)
  * [Stage X: Mining RNA-seq](../stage-x-mining-rnaseq-for-cellular-metabolism-modelling.md)
  * [Stage XI: Mining Membrane-based Interactome Database](../stage-xi-mining-membrane-based-interactome-database.md)
* **Practical Lab Activity**: Run computational models to simulate plant hormone transport and root water flow. Query spaceflight transcriptomics datasets using the databases linked in Stage X.
* **Deliverable**: Submit a modeling write-up illustrating how simulated cellular auxin transporter distributions affect root tip hormone concentration gradients.

---

### Week 10: Student Project Work & Presentations
* **Topics & Focus**: Science communication; designing scientific slides; structuring arguments and conclusions from experimental data.
* **Required Readings**: None. Focus on analyzing individual project data.
* **Practical Lab Activity**: Analyze data collected from independent experiments (Unit 3). Assemble final presentation slides and present findings to the class.
* **Deliverable**: Submit your group's presentation slide deck (PDF or link).

---

### Week 11: Final Reports & Future Directions
* **Topics & Focus**: Writing a scientific manuscript; career pathways in astrobotany, plant biology, and space sciences.
* **Required Readings**:
  * [Literature & References](../references.md)
* **Practical Lab Activity**: peer-review draft manuscripts, finalize figures, compile the collective course database.
* **Deliverable**: Submit your Final Laboratory Report (formatted as a scientific paper, including Abstract, Intro, Methods, Results, Discussion, and References).

---

## 🔗 Quick Links
* **[Course Syllabus](SYLLABUS.md)**: Grading rubrics, policies, and assessment details.
* **[Undergraduate Track Overview](README.md)**: Back to the track home page.
