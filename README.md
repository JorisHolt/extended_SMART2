# Improving 10-year cardiovascular risk prediction in patients with established cardiovascular disease: flexible addition of risk predictors on top of the SMART2 risk score

This repository accompanies the manuscript: *"Improving 10-year cardiovascular risk prediction in patients with established cardiovascular disease: flexible addition of risk predictors on top of the SMART2 risk score."*

The manuscript describes how 10-year risk of recurrent cardiovascular (CV) events, as estimated by the SMART2 model, can be re-estimated in the presence of additional risk factors not included in the original model.

## 📌 Context

Applies to the SMART2 population: adults aged 40–80 years with stable atherosclerotic cardiovascular disease and describes how other risk factors, such as NTproBNP may be integrated on top of the SMART2 model.

## 📂 Repository Structure

```
reestimatingSMART2/
├── reestimatingSMART2.Rmd       # RMarkdown guide illustrating re-estimation of SMART2 risk
├── docs/
│   └── reestimatingSMART2.html  # HTML rendering of the RMarkdown for viewing in browser
└── README.md                    # This file
```

## 📄 Usage

The included RMarkdown (`reestimatingSMART2.Rmd`) demonstrates:

- Step-by-step adjustment of SMART2 10-year CV risk for:
  - Binary variables (e.g. heart failure)
  - Ordinal variables (e.g. education level)
  - Continuous variables (e.g. BMI, biomarkers)
- Use of a general-purpose function for applying prevalence-adjusted hazard reweighting

To view the formatted guide directly, open: `docs/reestimatingSMART2.html`

## 🌐 Online Calculator

An example interactive calculator implementing this method is [available here](https://holtropjoris.shinyapps.io/flexiblesmart2/).

This demonstrates how SMART2 risk can be re-estimated in the presence of additional predictors (for research purposes). 

## 📚 Citation

If using this code or methodology in your work, please cite:

> Holtrop J, et al.  
> Flexible addition of new clinical predictors to existing cardiovascular risk models using a prevalence-adjusted hazard reweighting approach.  
> *To be updated upon publication.*

## 📬 Contact

- 📧 [j.holtrop-3@umcutrecht.nl](mailto:j.holtrop-3@umcutrecht.nl)
- 📧 [holtropjoris@gmail.com](mailto:holtropjoris@gmail.com)
