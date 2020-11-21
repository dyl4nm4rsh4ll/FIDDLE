# FIDDLE

### Flexible Integration of Data with Deep LEarning

A novel deep neural network approach towards functional genomic data integration, [slidedeck](https://docs.google.com/presentation/d/1xLzA3IWVae6o8UTExAk-zRoBym5v1rHMseL3wbXDyxY/edit?usp=sharing). The initial preprint can be found here: [User et al](https://www.biorxiv.org/content/10.1101/081380v1).

### [FIDDLE notebook 🎻](https://colab.research.google.com/github/churchmanlab/FIDDLE/blob/master/fiddle.ipynb)


```bash
directory architecture

├── < head_dir >
│   ├── logs/
│   ├── DATA/
│   │   ├── RAW/
│   │   │   ├── annotations
│   │   │   ├── bedgraphs
│   │   │   ├── txt
│   │   ├── COLLATED/
│   ├── MODELS/
│   │   ├── FIGURES_STATS/
│   │   ├── INPUTS/
│   │   ├── OUTPUTS/
│   │   ├── TRAINED/
│   │   ├── SCRIPTS/
│   │   │   ├── sc_train_split.py
│   │   │   ├── fiddle.py
│   │   │   ├── collate_outputs.py
```

![alt text](https://github.com/churchmanlab/FIDDLE/blob/master/architecture.png)

**_note_**: an HPC cluster with GPUs is recommended

[coding environment instructions](https://github.com/churchmanlab/FIDDLE/blob/master/HPC_instructions.md)
