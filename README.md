# demo_renv_rstudio_connect
Demo of RENV and R Studio Connect integration. 

**High level steps for a fresh repo:**
- Activate renv with renv::activate()
- Installation of rsconnect with install.packages("rsconnect")
- Create R Studio Connect manifest file with rsconnect:writeManifest() 
- Generate renv lockfile with renv::snapshot()
- Commit to Github
- Follow remaining steps here: https://docs.posit.co/connect/user/git-backed/#:~:text=Linking%20Git%20to%20Posit%20Connect,-Connect%20users%20must&text=On%20the%20%22Content%22%20page%2C,launch%20a%20new%20content%20wizard.
