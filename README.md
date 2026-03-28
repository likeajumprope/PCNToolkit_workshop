## Normative Modelling in the Life Sciences
## Theory, Practice, and Applications with PCNtoolkit, MCMC, and PyMC

<img width="523" height="485" alt="image" src="https://github.com/user-attachments/assets/94a9cc41-1b4f-4588-8b99-18d76c9be8ad" />

---

## Running this notebook

### Option 1 — Google Colab (no setup required)

<a target="_blank" href="https://colab.research.google.com/github/likeajumprope/PCNToolkit_workshop/blob/main/code/04_HBR_SHASH_didactic.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

1. Click the badge above to open the notebook in Colab
2. Run the first cell to install PCNtoolkit. It will take a moment to instal it. Then,  a pop-up will ask you to **Restart Session**, click it. 
3. Continue running cells from the top

> **Troubleshooting:** If something goes wrong, go to **Runtime → Restart Session** to wipe the workspace and start fresh.

> **Attention**: Google Colab does NOT save your workspace, changes or output when you close the browser.

---

### Option 2 — Local machine (VS Code)

**Prerequisites:** [VS Code](https://code.visualstudio.com/) with the Jupyter extension, and [conda](https://docs.conda.io/en/latest/miniconda.html).

**1. Clone the repository**
```bash
git clone https://github.com/likeajumprope/PCNToolkit_workshop.git
cd PCNToolkit_workshop
```

**2. Create the environment**
```bash
conda create -n pcntoolkit_env python=3.12
conda activate pcntoolkit_env
pip install pcntoolkit ipykernel
```

**3. Open the notebook**
- Open VS Code and navigate to `code/04_HBR_SHASH_didactic.ipynb`
- Click **Select Kernel** (top-right) → **Python Environments** → **pcntoolkit_env**
- If the environment does not appear, run the following and restart VS Code:
```bash
python -m ipykernel install --user --name pcntoolkit_env --display-name "PCNtoolkit"
```

**4. Run the notebook**
- One cell at a time: **Shift+Enter**
- All cells: **Run All** (⇧⌘↩ Mac / Ctrl+Alt+Enter Windows)

> The first code cell checks your PCNtoolkit version and raises a clear error if the wrong version is installed.

---

## Links

| | |
|---|---|
| 📖 Documentation | https://pcntoolkit.readthedocs.io/en/stable/ |
| 📄 Paper (de Boer, Bayer et al. 2024) | https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00132 |
| 💻 GitHub | https://github.com/predictive-clinical-neuroscience/PCNtoolkit |
| 🎓 More tutorials | https://github.com/predictive-clinical-neuroscience/PCNtoolkit-demo |
