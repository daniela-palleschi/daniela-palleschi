### Daniela Palleschi

Research Data Manager, Data Science consultant, and psycholinguist at the Leibniz-Centre General Linguistics (ZAS) in Berlin. My work consists of research data infrastructure, statistical consulting, and psycholinguistic research. Across all my roles, `R` is the constant.

🎓 PhD, Humboldt-Universität zu Berlin.
🇨🇦➡️🇩🇪 Originally from Toronto, based in Berlin since 2012.

### Research and professional interests

- 📈 **R (all day, every day)**: my primary tool for over a decade, from dissertation (Rmarkdown) to webbooks (Quarto) to infrastructure scripting (R + PowerShell), I use it for *everything*
- 🗂️🔐 **Research Data Management:** building institutional data infrastructure, GDPR compliant data workflows, and FAIR data principles for the language sciences with an emphasis on Open Science practices
- 🧮📊 **Bayesian statistics:** mixed effects modeling in R/brms, applied to datasets spanning psycholinguistics, physiological speech data, and cross-linguistic research (and whatever else ZAS researchers throw at me!)
- 🧠👁️ **Psycholinguistics:** eye tracking and EEG methods, with a focus on language acquisition and sentence processing
- 📄🔁 **Reproducible research:** Quarto based workflows for manuscripts, teaching materials, and data dashboards
- 🐍🤝 **Python for research:** expanding my toolkit and organizing the ZAS Pythonistas working group for researchers learning Python

### Current projects

-  Collaborator on a preregistered, cross-linguistic replication of quantifier acquisition using Bayesian mixed models (R/brms)
- Using Python (MNE) to preprocess EEG data exploring the effects of prior world knowledge on language processing
- Infrastructure development for a SharePoint based research data catalogue at ZAS, facilitating GDPR compliance and Open Science practices

### ⛰️ Hill I will die on

Use **project relative filepaths**. *In R:* set up an `.Rproj` and use `here::here()` for all file paths, never absolute paths, never `setwd()`. If you don't, Jenny Bryan will [set your computer on fire](https://tidyverse.org/blog/2017/12/workflow-vs-script/). *In Python:* I like `pyprojroot`'s `here()` function, which anchors to any project root file (e.g. `.git`, `setup.py`, or `.here` failing all else), nesting within `os.path.join()` to avoid hardcoding slash separators (native behavior in R's `here::here()`).

Bonus: use `pacman::p_load()` over a wall of individual `library()` calls in R. It installs missing packages automatically and keeps your setup chunk to one line.

### Toolkit

**Languages & frameworks:** `R` · `Python` · `brms` · `tidyverse` · `Quarto`

**Tools & platforms:** `Git` · `GitHub` · `PowerShell` · `SharePoint`

**Editors:** `RStudio` · `Positron` · `VS Code`

### Get in touch

I'm always glad to connect with others working on reproducibility, open research data, or Bayesian methods in the language sciences. Feel free to explore my repositories or reach out.
