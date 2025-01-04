# README
## 1. PREPARAR CODESPACE
-instalar python y jupyter desde extensiones
-crear el archivo git ignore con:
```bash
echo -e ".venv\n.env"> .gitignore
```
- crear entorno virtual y activarlo
```bash
python -m venv .venv
source .venv/bin/activate
```
- instalar librerias de python para trabajar con jupyter, pandas, matplotlib
```bash
python -m pip install ipykernel nbformat pandas seaborn
```
-crear carpetas de trabajo
```bash
mkdir notebooks src app docs
mkdir -p data/{raw,baking,final}
```
- editar un archivo
```bash
touch mitexto.txt
nano mitexto.txt
```