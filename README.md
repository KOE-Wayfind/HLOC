# HLOC - Hierarchical Localization

Refer https://github.com/cvg/Hierarchical-Localization

## Notebooks

- HLOC_KOE - Localization KoE environment using indoor (InLoc) datasets. Using SuperPoint and SuperGlue. [Open in Colab](https://colab.research.google.com/github/KOE-Wayfind/HLOC/blob/main/HLOC_KOE.ipynb)

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

And add the code block with contents

```bash
!jupyter nbextension enable --py widgetsnbextension
```


