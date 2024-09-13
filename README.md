# Containerised `rstudio-server` for reproducible analytics

This repository contains the `Dockerfile`, `docker-compose.yml` and a project setup script.
The setup will allow to install R packages with `renv` and all files will persist locally on the host machine.

This setup makes all our analytics environments portable. We can simply use the renv.lock file created and move that to any machine, cloud, local or otherwise.

# Next Steps
- Include the insigene R package so we can combine all analysis best practive in one.  
- Set up something similar with `vscode` and `conda`, so we can be programming language independent.

# Author
Sebastian Rauschert, PhD
