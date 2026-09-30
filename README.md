# 2627-analysis-efrei-m2-dev

## Créer un env. virtuel Python + installer ``Pandas``

Ca marche partout mais c'est lent :

```bash
# python3 (pour mac qui font rien comme les autres)
python -m venv .venv

# mac/linux
source ./.venv/bin/activate

# windows
./venv/Scripts/activate

pip install pandas
```

C'est pro et rapide (mais chiant à config sur Mac) :

- Installer `uv` (astral)

```bash
uv venv .venv
uv pip install pandas
```

## Préparer le setup Pandas

- Installer l'extension VSCode `Jupyter`
- Créer un fichier `analysis.ipynb`