Re-estimating SMART2
This repository accompanies the manuscript:

"Flexible addition of new clinical predictors to existing cardiovascular risk models using a prevalence-adjusted hazard reweighting approach."

The manuscript describes how 10-year risk of recurrent cardiovascular (CV) events, as estimated by the SMART2 model, can be re-estimated in the presence of additional risk factors not included in the original model.

📌 Context
Applies to the SMART2 population: adults aged 40–80 years with stable atherosclerotic cardiovascular disease and describes how other risk factors, such as NTproBNP may be integrated on top of the SMAT2 model. 

📂 Repository Structure
reestimatingSMART2/
├── reestimatingSMART2.Rmd       # RMarkdown guide illustrating re-estimation of SMART2 risk
├── docs/
│   └── reestimatingSMART2.html  # HTML rendering of the RMarkdown for viewing in browser
└── README.md                    # This file

📄 Usage
The included RMarkdown (reestimatingSMART2.Rmd) demonstrates:

Step-by-step adjustment of SMART2 10-year CV risk for:

Binary variables (e.g. heart failure)

Ordinal variables (e.g. education level)

Continuous variables (e.g. BMI, biomarkers)

Use of a general-purpose function for applying prevalence-adjusted hazard reweighting.

To view the formatted guide directly, open:
docs/reestimatingSMART2.html

🌐 Online Calculator
An example interactive calculator implementing this method is available at:
🔗 https://holtropjoris.shinyapps.io/flexiblesmart2/

This provides individualised SMART2 risk re-estimation with user-defined additional predictors and parameters.

📚 Citation
If using this code or methodology in your work, please cite:

Holtrop J, et al.
Flexible addition of new clinical predictors to existing cardiovascular risk models using a prevalence-adjusted hazard reweighting approach.
To be updated upon publication.

📬 Contact
📧 j.holtrop-3@umcutrecht.nl
📧 holtropjoris@gmail.com

