# HLOC - Hierarchical Localization Script

The scripts is taken and modified from [Hierarchical Localization's Demo script](https://github.com/cvg/Hierarchical-Localization#quick-start-%EF%B8%8F-) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MrVs9b8aQYODtOGkoaGNF9Nji3sbCNMQ)

## Notebooks

- **`HLOC_KOE.ipynb`** - Localization KoE environment using indoor (InLoc) datasets. Using SuperPoint and SuperGlue. [![badge](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KOE-Wayfind/HLOC/blob/main/HLOC_KOE.ipynb)
- **`HLOC_KOE_codespace.ipynb`** - Same as above, but it is runnable on GitHub codespace. To get started, read the section below. [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/KOE-Wayfind/HLOC)
- **`HLOC_KOE_DATA.ipynb`** - Slightly modified code than above to enable matrix testing. [![badge](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KOE-Wayfind/HLOC/blob/main/HLOC_KOE_DATA.ipynb)

## Get started

(Tested in GitHub Codespaces)

Run

```bash
sudo apt update && sudo apt install -y libsm6 libxext6 ffmpeg libfontconfig1 libxrender1 libgl1-mesa-glx
```

[[Source]](https://stackoverflow.com/a/67088720/13617136) If failed, just try again. Then, run:

```bash
pip install ipywidgets widgetsnbextension pandas-profiling
```

And add the code block with contents.

```bash
!jupyter nbextension enable --py widgetsnbextension
```

Then, you can run the notebook.
