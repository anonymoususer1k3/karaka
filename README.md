# Folder Structures

This high level structure for our material is as follows:

```
.
├── Dataset & Results PDF
└── Experiment data
    └── Bug reports
        ├── match results
        │   ├── matches
        │   └── paths
        ├── reproduction results
        │   ├── screenshots
        │   └── view hierarchy xml
        └── log file
```

## Dataset & Results PDF
This PDF file provides the information on bug reports we used for our experiments. The bug report details include a link to the report and stats of the bug report, such as the number of provided steps and missing steps.

Additionally, this PDF contains details on each Research Question (RQ) experiment, including results for all approaches, specifically the matching accuracy, running time, and reproduction results.

## Experiment Data
The folder contains the output of our tool for each bug report. We included results for all the 72 bug reports we used for our experiments.
Each bug report folder has a log file, match results, and reproduction results of the tool. 

### Log File
The raw log file of our tool.

### Match Results
The match results have two types of information.

* **matches:** The matches are the UI events generated by the analysis explained in **Section 3.2**.
* **paths:** The paths are the reproduction event paths generated by the analysis explained in **Section 3.3**.


### Reproduction Results
In this folder, you will find screenshots and view hierarchy files taken on the target app when executing the reproduction paths

Please note that due to the storage limitations of Github, we were unable to include these files in the repository. However, you can access the files using the following links:

[Google Drive](https://drive.google.com/drive/folders/1EVCYOFD5FgDiStd01aUiMZVL4uVBwofx?usp=sharing)
