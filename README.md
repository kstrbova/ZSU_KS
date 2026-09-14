## Základy strojového učení  
---
Příprava prostředí  

Můžete pracovat přes colab.google.com  
Na školních počítačích pomocí jupyter lab  
Na svých počítačích např. s VS Code


# Cvičení v Google Colab

| Exercise1 | Odkaz na Google Colab |
|---|---|
|Exercise1 | [Otevřít v Colabu](https://colab.research.google.com/github/kstrbova/ZSU_KS/blob/main/Exercise1_student.ipynb)|


### Aktivace `venv`

* Activate `venv` in **Windows**
```
.\venv\Scripts\Activate.ps1
```

* Activate `venv` in **Linux**
```
source venv/bin/activate
```


### Intall python packages

```
pip install jupyter "jupyterlab>=3" "ipywidgets>=7.6"
pip install pandas matplotlib requests seaborn scipy scikit-learn optuna tensorflow plotly==5.18.0
```

Balíky lze také instalovat přímo uvnitř buněk jupyter notebooku pomoci prikazu:

```
%pip install pandas matplotlib requests seaborn scipy scikit-learn optuna 
```

### 🚀 Run Jupyter lab

```
jupyter lab
