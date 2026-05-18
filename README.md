# Awesome Visual Analytics in Healthcare

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A community-curated list of awesome resources for visual analytics in healthcare. This list will be of interest to wide audience, including, students, academics, practitioners and healthcare professionals.

AMIA Visual Analytics Working Group maintains this list, although we do not endorse any resource in particular. We welcome suggestions as GitHub [Pull Requests](https://github.com/visualanalyticshealthcare/awesome-visual-analytics-healthcare/blob/main/contributing.md) or [Discussion posts](https://github.com/visualanalyticshealthcare/awesome-visual-analytics-healthcare/discussions) or via this [Airtable form (no login required)](https://airtable.com/shry5YQ14yHQEyw57).

Related Awesome lists:

- [`fasouto/awesome-dataviz`](https://github.com/fasouto/awesome-dataviz)
- [`javierluraschi/awesome-dataviz`](https://github.com/javierluraschi/awesome-dataviz)
- [`mathisonian/awesome-visualization-research`](https://github.com/mathisonian/awesome-visualization-research)
- [`kakoni/awesome-healthcare`](https://github.com/kakoni/awesome-healthcare)

---

## Table of Contents

- [Books](#books)
- [Checklists & Guidelines](#checklists--guidelines)
- [Collections](#collections)
- [Conferences](#conferences)
- [Courses](#courses)
- [Publications](#publications)
- [Tools](#tools)

## Books

- [Effective Data Visualization: The Right Chart for the Right Data](https://stephanieevergreen.com/) by Stephanie Evergreen (not specific to healthcare)
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/index.html) by Claus O. Wilke (not specific to healthcare but freely accessible under the Creative Commons License)
- [Storytelling with Data: A Data Visualization Guide for Business Professionals](https://www.storytellingwithdata.com/books) by Cole Nussbaumer Knaflic (not specific to healthcare)
- [Tableau for Healthcare](https://healthdataviz.com/resources/) by Daniel Benevento, Katherine Rowell, Janet Steeger
- [The Functional Art: An Introduction to Information Graphics and Visualization](http://www.thefunctionalart.com/) by Alberto Cairo (not specific to healthcare)
- [The Visual Display of Quantitative Information](https://www.edwardtufte.com/book/the-visual-display-of-quantitative-information/) by Edward R. Tufte (not specific to healthcare)
- [Visualize This: The FlowingData Guide to Design, Visualization, and Statistics](https://flowingdata.com/visualize-this/) by Nathan Yau (not specific to healthcare)
- [Visualizing Health and Healthcare Data](https://healthdataviz.com/resources/) by Lindsay Betzendahl, Cambria Brown & Katherine Rowell

## Checklists & Guidelines

### Guides & Principles

- [Data Visualization Design](https://guides.lib.berkeley.edu/data-visualization/design) - UC Berkeley Library guide on data visualization design principles, including chart selection, color, and accessibility (not specific to healthcare).
- [Designing Effective Data Visualizations](https://dataservices.library.jhu.edu/wp-content/uploads/sites/41/2024/03/DesigningEffectiveDataVisualizations.pdf) ([guide page](https://dataservices.library.jhu.edu/data-visualization/)) - Johns Hopkins University Libraries guide on designing effective data visualizations, with companion PDF handout (not specific to healthcare).
- [Data Visualization Guide](https://guides.library.yale.edu/datavisualization) - Yale University Library research guide covering data visualization principles, tools, and resources.
- [Development of a usability checklist for public health dashboards to identify violations of usability principles](https://academic.oup.com/jamia/article/29/11/1847/6670608) by Bahareh Ansari & Erika G Martin from University at Albany on JAMIA - A usability checklist for public health dashboards with 86 items covering 11 areas of considerations.
- [The Development of Heuristics for Evaluation of Dashboard Visualizations](https://www.thieme-connect.com/products/ejournals/html/10.1055/s-0038-1666842) by Dawn Dowding & Jacqueline A. Merrill from University of Manchester & Columbia University on Appl Clin Inform - A checklist of usability heuristics for evaluating information visualization systems that can contribute to assuring high quality in electronic data systems developed for health care.
- [Visual Mapping – The Elements of Information Visualization](https://www.interaction-design.org/literature/article/visual-mapping-the-elements-of-information-visualization) by the Interaction Design Foundation - introductory article on the visual encoding building blocks of information visualization (not specific to healthcare).

### Misleading Visualizations & Common Pitfalls

- [How to Spot Visualization Lies](https://flowingdata.com/2017/02/09/how-to-spot-visualization-lies/) by Nathan Yau on FlowingData - a field guide to identifying common deceptive chart patterns.
- [Misleading Graph (Wikipedia)](https://en.wikipedia.org/wiki/Misleading_graph) - reference article cataloging common misleading-graph techniques (truncated axes, distorted scales, etc.).
- [Replacement of the Aortic Root with a Pulmonary Autograft in Children and Young Adults with Aortic-Valve Disease](https://www.nejm.org/doi/full/10.1056/NEJM199401063300101) on New England Journal of Medicine - frequently cited as an "extra-dimension" 3D chart pitfall in healthcare visualization (not specific to healthcare best practices, but a healthcare-domain example of misleading design).
- [Why the National Review's global temperature graph is so misleading](https://www.washingtonpost.com/news/the-fix/wp/2015/12/14/why-the-national-reviews-global-temperature-graph-is-so-misleading/) on The Washington Post - canonical example of a scaled / compressed y-axis distorting interpretation.

### Bad-Chart Galleries

- [Karl Broman – The Top Ten Worst Graphs](https://www.biostat.wisc.edu/~kbroman/topten_worstgraphs/) - a curated gallery of poorly designed graphs from the scientific literature with critiques.
- [Junk Charts](https://www.junkcharts.com/) by Kaiser Fung - long-running blog critiquing real-world charts and proposing improved redesigns.
- [r/dataisugly](https://www.reddit.com/r/dataisugly/) - community-curated subreddit collecting bad data visualizations from the wild.
- [viz.wtf](http://viz.wtf/) - a curated gallery of egregiously bad data visualizations.

## Collections

### Healthcare-Specific

- [EHR STAR](https://ehr.wangqiru.com/table/) by Qiru Wang - a collection of literature and datasets included in the state-of-the-art (STAR) report, [EHR STAR: The State-of-the-art in Interactive EHR and PopHR Visualization](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14424)
- [GenoCAT](http://genocat.tools) by [Gehlenborg Lab](http://gehlenborglab.org) - a database of genomic visualization tools
- [Visualization Design Studio](https://tinyurl.com/y6rlv72a) led by [Adriana Arcia](https://www.nursing.columbia.edu/profile/adriana-arcia-phd) more info on this [page](https://vis-studio.mailchimpsites.com).
  - [A list of Online Visualization Resources](https://drive.google.com/file/d/1IlxBx_5JEZ2wVLcRXBmYz99nD2wYZuaZ/view) by Adriana Arcia

### Examples & Demos (Why Visualization Matters)

- [100 Data Viz Project](https://100.datavizproject.com/) - 100 different visualizations of the same dataset, illustrating how chart choice changes the story.
- [Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet) - four datasets with near-identical summary statistics but very different visual distributions; classic demonstration of why summary stats alone are insufficient.
- [One Dataset Visualized 25 Ways](https://flowingdata.com/2017/01/24/one-dataset-visualized-25-ways/) by Nathan Yau on FlowingData - shows how the same data can be communicated very differently across 25 chart forms.
- [Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing](https://doi.org/10.1371/journal.pbio.1002128) by Justin Matejka & George Fitzmaurice (Autodesk Research) - the "DataSaurus dozen" extension of Anscombe's quartet, demonstrating that statistically identical datasets can look radically different.

### General Data-Viz Blogs & Resource Sites

- [blog.datawrapper.de](https://blog.datawrapper.de/) - Datawrapper's blog with practical articles on chart design, color, and storytelling.
- [FlowingData](https://flowingdata.com/) by Nathan Yau - long-running blog on data visualization design, tutorials, and projects.
- [Perceptual Edge](https://www.perceptualedge.com/) by Stephen Few - articles and resources on quantitative information presentation.
- [Towards Data Science](https://towardsdatascience.com/) - Medium publication with many data-visualization tutorials and case studies (not specific to healthcare).
- [Visualising Data](https://www.visualisingdata.com/) by Andy Kirk - resources, references, and commentary on data visualization practice.

## Conferences

- [ACM CHI](https://chi.acm.org) - the ACM CHI Conference on Human Factors in Computing Systems, the premier international conference on Human-Computer Interaction, hosted annually by ACM SIGCHI.
- [IEEE VIS](https://ieeevis.org) - the premier forum for advances in visualization and visual analytics, hosting the IEEE Transactions on Visualization and Computer Graphics (TVCG) conference track annually.
- [VAHC Workshop](https://www.visualanalyticshealthcare.org) - Visual Analytics in Healthcare Workshop is an annual academic event hosted alternatively at AMIA (on even years) and IEEE VIS (on odd years). The workshop is dedicated to the study of visual analytics in healthcare. The workshop is a forum for researchers and practitioners to present and discuss their work, and to identify research challenges and opportunities in the field.

## Courses

- [Data Analytics and Visualization in Health Care](https://www.edx.org/course/data-analytics-and-visualization-in-health-care) from Rochester Institute of Technology on edX
- [Information Visualization Specialization](https://www.coursera.org/specializations/information-visualization) from New York University on Coursera (not specific to healthcare)

## Publications

### Featured in AMIA Year in Review

#### 2024

- [TrajVis: a visual clinical decision support system to translate artificial intelligence trajectory models in the precision management of chronic kidney disease](https://pubmed.ncbi.nlm.nih.gov/38916922/) by Zuotian Li, et al, J Am Med Inform Assoc. 2024 Nov 1;31(11):2474-2485. doi: 10.1093/jamia/ocae158. PMID: 38916922; PMCID: [PMC11491615](https://pmc.ncbi.nlm.nih.gov/articles/PMC11491615/).

- [Hybrid visualization-based framework for depressive state detection and characterization of atypical patients](https://pubmed.ncbi.nlm.nih.gov/37926393/) by Leon Kopitar, et al, J Biomed Inform. 2023 Nov;147:104535. doi: 10.1016/j.jbi.2023.104535. Epub 2023 Nov 4. PMID: 37926393.

- [Analysing disease trajectories in a cohort of 71,849 Patients: A visual analytics and statistical approach](https://pubmed.ncbi.nlm.nih.gov/37926393/) by Jon Kerexeta-Sarriegi, et al, Int J Med Inform. 2024 Aug;188:105466. doi: 10.1016/j.ijmedinf.2024.105466. Epub 2024 May 1. PMID: 38761458.

- [Design of an interface to communicate artificial intelligence-based prognosis for patients with advanced solid tumors: a user-centered approach](https://pubmed.ncbi.nlm.nih.gov/37847666/) by Catherine J Staes, et al, J Am Med Inform Assoc. 2023 Dec 22;31(1):174-187. doi: 10.1093/jamia/ocad201. PMID: 37847666; PMCID: [PMC10746322](https://pmc.ncbi.nlm.nih.gov/articles/PMC10746322/).

- [Inpatient nurses' preferences and decisions with risk information visualization](https://pubmed.ncbi.nlm.nih.gov/37903375/) by Alvin D Jeffery, et al, J Am Med Inform Assoc. 2023 Dec 22;31(1):61-69. doi: 10.1093/jamia/ocad209. PMID: 37903375; PMCID: PMC10746300.

- [HealthPrism: A Visual Analytics System for Exploring Children's Physical and Mental Health Profiles with Multimodal Data](https://pubmed.ncbi.nlm.nih.gov/37874717/) by Zhihan Jiang, et al, IEEE Trans Vis Comput Graph. 2023 Oct 24;PP. doi: 10.1109/TVCG.2023.3326943. Epub ahead of print. PMID: 37874717.


#### 2023

- [Integrating statistical and visual analytic methods for bot identification of health-related survey data](https://pubmed.ncbi.nlm.nih.gov/37419375/) by Annie T. Chen, ..., Yan Zhang from University of Washington and UT Austin. Journal of Biomedical Informatics, July 2023

#### 2022

- [Loon: Using Exemplars to Visualize Large-Scale Microscopy Data](https://ieeexplore.ieee.org/abstract/document/9552235/) by Devin Lange, ..., Alexander Lex from University of Utah on IEEE Transactions on Visualization and Computer Graphics - a visualization tool for analyzing drug screening data based on quantitative phase microscopy imaging for patient-specific cancer drug selection. [GitHub Repo](https://github.com/visdesignlab/Loon)
- [VBridge: Connecting the Dots Between Features and Data to Explain Healthcare Models](https://ieeexplore.ieee.org/abstract/document/9555810/) by Furui Cheng, ..., Kalyan Veeramachaneni from Hong Kong University and MIT on IEEE Transactions on Visualization and Computer Graphics - VBridge incorporates ML explanations into clinicians’ decision-making workflow. [GitHub Repo (MIT License)](https://github.com/sibyl-dev/VBridge)
- [A flexible framework for visualizing and exploring patient misdiagnosis over time](https://www.sciencedirect.com/science/article/pii/S1532046422001897) by Wathsala Widanagamaachchi, ..., Mkoto Jones from University of Utah on JBI - Framework for exploring the cohorts diagnoses over time

#### 2020

- [Visual analogies, not graphs, increase patients' comprehension of changes in their health status](https://academic.oup.com/jamia/article-abstract/27/5/677/5717999) by Meghan Reading Turchio, ..., Ruth Masterson Creber from Cornell, Columbia, others on JAMIA - Patient comprehension of their self-reported outcomes

#### 2019

- [A federated EHR network data completeness tracking system](https://academic.oup.com/jamia/article-abstract/26/7/637/5423491) by Hossein Estiri,..., Shawn N. Murphy from Massachusetts General Hospital on J Am Med Inform Assoc - DQe-c is an open source tool for evaluating completeness in EHR data repositories
- [A smartwatch-based framework for real-time and online assessment and mobility monitoring](https://www.sciencedirect.com/science/article/pii/S1532046418302120) by Matin Kheirkhahan, ..., Sanjay Ranka from University of Florida on J Biomed Inform

#### 2018

- [A visual analytics approach for pattern-recognition in patient-generated data](https://academic.oup.com/jamia/article-abstract/25/10/1366/5037318) by Daniel Feller, ..., Lena Mamykina from Columbia University on JAMIA - Authors developed Glucolyzer to help dieticians interpret glucose and meal data
- [Eye-Tracking Study to Enhance Usability of Molecular Diagnostics Reports in Cancer Precision Medicine](https://ascopubs.org/doi/abs/10.1200/PO.17.00296) by Vishakha Sharma, ..., Subha Madhavan from Georgetown University on JCO Precision Oncology.

### Academic Informatics

- [Data-Driven Healthcare: Challenges and Opportunities for Interactive Visualization](https://ieeexplore.ieee.org/abstract/document/7466736) by David Gotz & David Borland from University of North Carolina at Chapel Hill on IEEE Computer Graphics and Applications

### Human-Computer Interaction / Human-centered Design

### Consumer Health Informatics

### Clinical Decision Support

- [Best practices for data visualization: creating and evaluating a report for an evidence-based fall prevention program](https://doi.org/10.1093/jamia/ocz190) by Srijesa Khasnabish, Zoe Burns, Madeline Couch, Mary Mullin, Randall Newmark, Patricia C Dykes from Brigham and Women's Hospital on J Am Med Inform Assoc. 2020;27(2):308-314. doi: 10.1093/jamia/ocz190 - Iterative design and evaluation of a fall-prevention dashboard report; identifies best practices for clinician-facing data displays (high data-ink ratio, conservative color use, clear performance-vs-goal communication).

### Visual Analytics System

### Review Paper

- [EHR STAR: The State-of-the-art in Interactive EHR and PopHR Visualization](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14424) by Qiru Wang & Robert Laramee from University of Nottingham on Computer Graphics Forum
- [Evaluating visual analytics for health informatics applications: a systematic review from the American Medical Informatics Association Visual Analytics Working Group Task Force on Evaluation](https://academic.oup.com/jamia/article/26/4/314/5320044) by Danny Wu, ..., David Gotz from AMIA Visual Analytics Working Group on JAMIA
- [Principles of Effective Data Visualization](https://pmc.ncbi.nlm.nih.gov/articles/PMC7733875/) by Stephen R. Midway from Louisiana State University on Patterns (N Y). 2020;1(9):100141. doi: 10.1016/j.patter.2020.100141. PMID: 33336199 - Ten foundational principles for creating effective scientific data visualizations, covering geometry selection, color use, uncertainty representation, and communication strategies (not specific to healthcare).
- [Tasks, Techniques, and Tools for Genomic Data Visualization](https://onlinelibrary.wiley.com/doi/10.1111/cgf.13727) by Sabrina Nusrat, Theresa Harbig, and Nils Gehlenborg from Harvard University on Computer Graphics Forum

## Tools

### Chart Catalogs & Pickers

- [Data Viz Project](https://datavizproject.com/) - a catalog of chart types with filters by data shape, function, and family, useful for picking the right chart.
- [Data Visualisation Catalogue](https://datavizcatalogue.com/index.html) by Severino Ribecca - a catalog of visualization methods organized by the task they support.
- [From Data to Viz](https://www.data-to-viz.com/) - a decision-tree explorer that recommends suitable chart types based on the structure of your data, with code examples.

### Healthcare & Visual Analytics Platforms

- [CadenceEVA](https://github.com/VACLab/CadenceEVA) - a visual analytics platform for event sequence analysis.
- [PyHealth](https://github.com/sunlabuiuc/PyHealth) - a Python library for healthcare predictive tasks.
- [SandDance](https://microsoft.github.io/SandDance/app/) - a web-based application that enables you to more easily explore, identify, and communicate insights about tabular data.

### General-Purpose Platforms

- [Observable](https://observablehq.com/) - a collaborative notebook platform for building reactive data visualizations in JavaScript, widely used for prototyping bespoke charts.
- [Plotly Dash](https://dash.plotly.com/) - an open-source Python framework for building analytical web applications and interactive dashboards.
- [Tableau](https://www.tableau.com/) - a widely used commercial BI and data visualization platform; see also the "Tableau for Healthcare" book listed under Books.

### Color & Accessibility

- [Coblis – Color Blindness Simulator](https://www.color-blindness.com/coblis-color-blindness-simulator/) - upload an image and preview how it appears under different forms of color vision deficiency.
- [Color Oracle](http://www.colororacle.org/) - free desktop color-blindness simulator (macOS / Windows / Linux) that applies a full-screen filter for designers.
- [Colorblind palette comparison](https://davidmathlogic.com/colorblind/) by David Nichols - an interactive tool to preview and compare categorical color palettes under different types of color vision deficiency.
- [Datawrapper - A detailed guide to colors in data vis style guides](https://www.datawrapper.de/blog/colors-for-data-vis-style-guides) - an extensive reference on building organizational color palettes for data visualization.
- [Datawrapper - How to pick more beautiful colors for your data visualizations](https://www.datawrapper.de/blog/beautifulcolors) - practical guidance on choosing accessible and aesthetically effective colors for charts.

### AI-Assisted & Agent-based

AI-driven design generators and coding agents that can be used to prototype or implement healthcare data visualizations from natural-language prompts.

- [Claude Code](https://www.anthropic.com/claude-code) by Anthropic - a command-line coding agent that can read, modify, and run code in your repository, suitable for building or extending visualization apps.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) by Google - an open-source command-line agent powered by Gemini models, for terminal-based coding and automation workflows.
- [Google Gemini](https://gemini.google.com/) - Google's multimodal AI assistant for chat-based coding help, image/data understanding, and quick visualization sketches.
- [Google Stitch](https://stitch.withgoogle.com/) - Google Labs experiment that turns natural-language prompts into UI designs, useful for rapidly prototyping dashboard layouts.

