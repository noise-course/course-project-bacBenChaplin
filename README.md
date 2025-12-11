# OS Fingerprinting from Network Traffic - nPrint Leaderboard

**Author:** Ben Chaplin

## Project Overview
This project tackles the OS fingerprinting challenge from the nPrint leaderboard.

## Important Files
- **Jupyter Notebook:** `final/project_jupyter.ipynb`
- **Sphinx Documentation:** `docs/_build/html/index.html` (run `open docs/_build/html/index.html`)

## How to Read This Project

**I highly recommend reading section 1 (Introduction) and section 6 (Conclusion) first.** These sections present the findings and methodology clearly. Sections 2-5 contain all the experimental code that produced these results.

## Dependencies
- pcapml_fe
- scapy
- pandas
- numpy
- sklearn
- matplotlib
- xgboost
- autogluon
- and the nPrint software

## Data Files
- Originally, I wanted to add the data to the github, but they are too large. Please find them for download in the [Google Drive](https://drive.google.com/drive/folders/1vXRKuW0KuB50WY1vgi5GFwIn-coFk_25?usp=sharing)
- `data/100-packet-traffic.pcapng` - Original dataset
- `data/clean-traffic.pcap` - Processed PCAP file
- `data/print.npt` - nPrint feature file
- `AutogluonModels/ag-*` - AutoGluon models

## IMPORTANT Note on AutoGluon Models
I have uploaded the autogluon models into this [Google Drive](https://drive.google.com/drive/folders/1vXRKuW0KuB50WY1vgi5GFwIn-coFk_25?usp=sharing) because I dont want to spend a ton of time training them if you run them. Github doesnt support files this large, so I couldn't put it there. Just create a directory `final/AutogluonModels` and put the models there. If you want to train them, uncomment the relevant code.

## Misc.
This notebook takes a while to run because of the massive size of the concatenation data.


[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vzqInGyc)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21410593)
