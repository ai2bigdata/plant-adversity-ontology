# Plant Adversity Ontology (PAO)

**PAO** is a community-driven, FAIR-compliant ontology for standardized description and annotation of **biotic, abiotic, compound, and regulator-induced adversities (stresses)** in plants.

- **Permanent ID space**: `PAO`
- **PURL**: http://purl.obolibrary.org/obo/pao.owl
- **OBO Foundry**: https://obofoundry.org/ontology/pao.html
- **Browser**: https://www.ontobee.org/ontology/PAO
- **Current release**: v1.0 (22 November 2025) – 283 terms

### Why PAO?
- >15,000 plant stress papers published annually, yet no unified vocabulary for experimental conditions
- Covers high-frequency compound stresses (2020–2025): heat+drought, salt+drought, ozone+chilling, high night temperature, etc.
- Three orthogonal axes + four extensible facets enable precise descriptions (e.g., "severe chronic heat+drought stress in field conditions")

### Ontology Structure
PAO:0000000 plant adversity
├── PAO:1000000 abiotic adversity
├── PAO:2000000 biotic adversity
└── PAO:3000000 exogenous regulator-induced response
textFacets (annotation properties):
- `PAO_severity` – mild | moderate | severe | extreme
- `PAO_duration` – acute | chronic | intermittent
- `PAO_combination` – e.g., heat+drought
- `PAO_experimental_setup` – field | greenhouse | growth chamber | PEG-simulated

### Quick Links
- **OWL file**: http://purl.obolibrary.org/obo/pao.owl
- **Latest release**: https://github.com/plant-adversity-ontology/pao/releases
- **Online annotator** (upload Excel → get PAO IDs): https://annotator.plantadversity.org
- **Issue tracker** (propose new terms): https://github.com/plant-adversity-ontology/pao/issues
- **Citation** (2026 NAR Database Issue, in press):  
  Yang et al. (2026) Plant Adversity Ontology (PAO): a community resource for standardizing plant stress conditions. *Nucleic Acids Research* Database Issue.

### Principal Investigator
Qing-Yong Yang  
National Key Laboratory of Crop Genetic Improvement  
Huazhong Agricultural University, Wuhan, China  
yqy@mail.hzau.edu.cn

### How to Contribute
1. Open an issue using the **"New Term Request"** template
2. Or submit a pull request to `src/ontology/pao-edit.owl`
3. All contributions follow the Plant Adversity Ontology Consortium governance (see CONTRIBUTING.md)

### License
Creative Commons Attribution 4.0 International (CC BY 4.0)

### Acknowledgements
Started as a fork and major update of the Plant Stress Ontology (PSO) with permission from Planteome. Built with ROBOT, Protégé, and GitHub Actions.

We gratefully acknowledge early adopters: Gramene, TAIR, MaizeGDB, BAR, and the global plant stress research community.
