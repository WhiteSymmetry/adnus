# adnus (AdNuS):  Advanced Number Systems.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15874178.svg)](https://doi.org/10.5281/zenodo.15874178)

[![WorkflowHub DOI](https://img.shields.io/badge/DOI-10.48546/WORKFLOWHUB.DATAFILE.19.1-blue)](https://doi.org/10.48546/WORKFLOWHUB.DATAFILE.19.1)

[![figshare DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.29554532-blue)](https://doi.org/10.6084/m9.figshare.29554532)

[![ResearchGate DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.30518.41284-blue)](https://doi.org/10.13140/RG.2.2.30518.41284)

[![Anaconda-Server Badge](https://anaconda.org/bilgi/adnus/badges/version.svg)](https://anaconda.org/bilgi/adnus)
[![Anaconda-Server Badge](https://anaconda.org/bilgi/adnus/badges/latest_release_date.svg)](https://anaconda.org/bilgi/adnus)
[![Anaconda-Server Badge](https://anaconda.org/bilgi/adnus/badges/platforms.svg)](https://anaconda.org/bilgi/adnus)
[![Anaconda-Server Badge](https://anaconda.org/bilgi/adnus/badges/license.svg)](https://anaconda.org/bilgi/adnus)
[![Open Source](https://img.shields.io/badge/Open%20Source-Open%20Source-brightgreen.svg)](https://opensource.org/)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Python CI](https://github.com/WhiteSymmetry/adnus/actions/workflows/python_ci.yml/badge.svg?branch=main)](https://github.com/WhiteSymmetry/adnus/actions/workflows/python_ci.yml)
[![codecov](https://codecov.io/gh/WhiteSymmetry/adnus/graph/badge.svg?token=T9XPI1HSKF)](https://codecov.io/gh/WhiteSymmetry/adnus)
[![Documentation Status](https://readthedocs.org/projects/adnus/badge/?version=latest)](https://adnus.readthedocs.io/en/latest/)
[![Binder](https://terrarium.evidencepub.io/badge_logo.svg)](https://terrarium.evidencepub.io/v2/gh/WhiteSymmetry/adnus/HEAD)
[![PyPI version](https://badge.fury.io/py/adnus.svg)](https://badge.fury.io/py/adnus)
[![PyPI Downloads](https://static.pepy.tech/badge/adnus)](https://pepy.tech/projects/adnus)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md) 

---

<p align="left">
    <table>
        <tr>
            <td style="text-align: center;">PyPI</td>
            <td style="text-align: center;">
                <a href="https://pypi.org/project/adnus/">
                    <img src="https://badge.fury.io/py/adnus.svg" alt="PyPI version" height="18"/>
                </a>
            </td>
        </tr>
        <tr>
            <td style="text-align: center;">Conda</td>
            <td style="text-align: center;">
                <a href="https://anaconda.org/bilgi/adnus">
                    <img src="https://anaconda.org/bilgi/adnus/badges/version.svg" alt="conda-forge version" height="18"/>
                </a>
            </td>
        </tr>
        <tr>
            <td style="text-align: center;">DOI</td>
            <td style="text-align: center;">
                <a href="https://doi.org/10.5281/zenodo.15874178">
                    <img src="https://zenodo.org/badge/DOI/10.5281/zenodo.15874178.svg" alt="DOI" height="18"/>
                </a>
            </td>
        </tr>
        <tr>
            <td style="text-align: center;">License: MIT</td>
            <td style="text-align: center;">
                <a href="https://opensource.org/licenses/MIT">
                    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License" height="18"/>
                </a>
            </td>
        </tr>
    </table>
</p>

---


adnus (AdNuS):  Advanced Number Systems.

---
### **Türkçe Tanım:**
**adnus Sayıları**, 14. yüzyılda Nicole adnus tarafından incelenen matematiksel serilerdir. adnus sayıları harmonik seriye ait toplamları ifade eder. İki türü vardır:  
1. **\( \frac{n}{2^n} \) serisi** (adnus'nin orijinal çalışması),  
2. **Harmonik sayılar** (\( H_n = 1 + \frac{1}{2} + \cdots + \frac{1}{n} \)).  
Bu sayılar, analiz ve sayı teorisinde önemli rol oynar.

---

### **English Definition:**
**adnus Numbers** are mathematical series studied by Nicole adnus in the 14th century. adnus (AdNuS):  Advanced Number Systems. They include two types:  
1. The **\( \frac{n}{2^n} \) sequence** (adnus's original work),  
2. **Harmonic numbers** (\( H_n = 1 + \frac{1}{2} + \cdots + \frac{1}{n} \)).  
These numbers play a key role in analysis and number theory.

---

### **Fark/Karşılaştırma (Difference):**
- **adnus'nin \( \frac{n}{2^n} \) serisi** ıraksaklık kanıtları için önemlidir.  
- **Harmonik sayılar** (\( H_n \)) ise logaritmik büyüme gösterir ve \( n \to \infty \) iken ıraksar.  
- Modern literatürde "adnus numbers" terimi daha çok tarihsel bağlamda kullanılır.

---

## Kurulum (Türkçe) / Installation (English)

### Python ile Kurulum / Install with pip, conda, mamba
```bash
pip install adnus -U
python -m pip install -U adnus
conda install bilgi::adnus -y
mamba install bilgi::adnus -y
```

```diff
- pip uninstall adnus -y
+ pip install -U adnus
+ python -m pip install -U adnus
```

[PyPI](https://pypi.org/project/adnus/)

### Test Kurulumu / Test Installation

```bash
pip install -i https://test.pypi.org/simple/ adnus -U
```

### Github Master Kurulumu / GitHub Master Installation

**Terminal:**

```bash
pip install git+https://github.com/WhiteSymmetry/adnus.git
```

**Jupyter Lab, Notebook, Visual Studio Code:**

```python
!pip install git+https://github.com/WhiteSymmetry/adnus.git
# or
%pip install git+https://github.com/WhiteSymmetry/adnus.git
```

---

## Kullanım (Türkçe) / Usage (English)

```python
import adnus as oj
import numpy as np
import jax
import jax.numpy as jnp
import time
from adnus import *
import matplotlib.pyplot as plt

# Simple usage example
plt.figure(figsize=(10, 5))
plt.plot(oj.harmonic_numbers_jax(500))
plt.title("First 5000000 Harmonic Numbers")
plt.xlabel("n")
plt.ylabel("H(n)")
plt.show()
```

```python
import adnus
adnus.__version__
```

```python
import importlib
import inspect
import adnus as oj  # Varsa import hatasını yakalamak için
import jax.numpy as jnp

def diagnose_module(module_name):
    try:
        # Modülü yükle
        module = importlib.import_module(module_name)
        
        print(f"\n{' Modül Tanılama Raporu ':=^80}")
        print(f"Modül adı: {module_name}")
        print(f"Modül dosya yolu: {inspect.getfile(module)}")
        
        # Modülün tüm özelliklerini listele
        print("\nModülde bulunan özellikler:")
        members = inspect.getmembers(module)
        public_members = [name for name, _ in members if not name.startswith('_')]
        print(public_members)
        
        # Özel olarak kontrol edilecek fonksiyonlar
        required_functions = [
            'adnus_sequence',
            'harmonic_numbers',
            'harmonic_number',
            'harmonic_number_jax',
            'harmonic_numbers_jax',
            'harmonic_generator_jax',
            'harmonic_number_approx'
        ]
        
        print("\nEksik olan fonksiyonlar:")
        missing = [fn for fn in required_functions if not hasattr(module, fn)]
        print(missing if missing else "Tüm gerekli fonksiyonlar mevcut")
        
        # __all__ değişkenini kontrol et
        print("\n__all__ değişkeni:")
        if hasattr(module, '__all__'):
            print(module.__all__)
        else:
            print("__all__ tanımlı değil (tüm public fonksiyonlar içe aktarılır)")
            
    except ImportError as e:
        print(f"\nHATA: Modül yüklenemedi - {e}")
    except Exception as e:
        print(f"\nBeklenmeyen hata: {e}")

# Tanılama çalıştır
diagnose_module('adnus')

# Alternatif olarak doğrudan kontrol
print("\nDoğrudan fonksiyon varlığı kontrolü:")
try:
    print("harmonic_numbers_jax mevcut mu?", hasattr(oj, 'harmonic_numbers_jax'))
    if hasattr(oj, 'harmonic_numbers_jax'):
        print("Fonksiyon imzası:", inspect.signature(oj.harmonic_numbers_jax))
    else:
        print("Eksik fonksiyon: harmonic_numbers_jax")
except Exception as e:
    print("Kontrol sırasında hata:", e)
```

```python
# 1. Alternatif içe aktarma yöntemi
from adnus import harmonic_numbers_jax  # Doğrudan import deneyin
import adnus as oj
import jax.numpy as jnp

# 2. Modülü yeniden yükleme
import importlib
importlib.reload(oj)

# 3. Fonksiyonun alternatif isimle var olup olmadığını kontrol
print("Alternatif fonksiyon isimleri:", [name for name in dir(oj) if 'harmonic' in name.lower()])
```
---

### Development
```bash
# Clone the repository
git clone https://github.com/WhiteSymmetry/adnus.git
cd adnus

# Install in development mode
python -m pip install -ve . # Install package in development mode

# Run tests
pytest

Notebook, Jupyterlab, Colab, Visual Studio Code
!python -m pip install git+https://github.com/WhiteSymmetry/adnus.git
```
---

## Citation

If this library was useful to you in your research, please cite us. Following the [GitHub citation standards](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-citation-files), here is the recommended citation.

### BibTeX


### APA

```
Keçeci, M. (2025). Dynamic vs Static Number Sequences: The Case of Keçeci and adnus Numbers. Open Science Articles (OSAs), Zenodo. https://doi.org/10.5281/zenodo.15833351

Keçeci, M. (2025). adnus [Data set]. ResearchGate. https://doi.org/10.13140/RG.2.2.30518.41284

Keçeci, M. (2025). adnus [Data set]. figshare. https://doi.org/10.6084/m9.figshare.29554532

Keçeci, M. (2025). adnus [Data set]. WorkflowHub. https://doi.org/10.48546/WORKFLOWHUB.DATAFILE.19.1

Keçeci, M. (2025). adnus. Open Science Articles (OSAs), Zenodo. https://doi.org/10.5281/zenodo.15874178
```

### Chicago

```
Keçeci, Mehmet. Dynamic vs Static Number Sequences: The Case of Keçeci and adnus Numbers. Open Science Articles (OSAs), Zenodo, 2025. https://doi.org/10.5281/zenodo.15833351

Keçeci, Mehmet. adnus [Data set]. ResearchGate, 2025. https://doi.org/10.13140/RG.2.2.30518.41284

Keçeci, Mehmet (2025). adnus [Data set]. figshare, 2025. https://doi.org/10.6084/m9.figshare.29554532

Keçeci, Mehmet. adnus [Data set]. WorkflowHub, 2025. https://doi.org/10.48546/WORKFLOWHUB.DATAFILE.19.1

Keçeci, Mehmet. adnus. Open Science Articles (OSAs), Zenodo, 2025. https://doi.org/10.5281/zenodo.15874178

```


### Lisans (Türkçe) / License (English)

```
This project is licensed under the MIT License.
```
# AdNuS: Advanced Number Systems

`adnus` is a Python library that provides an implementation of various advanced number systems. This library is designed for mathematicians, researchers, and developers who need to work with number systems beyond the standard real and complex numbers.

## Features

- **Harmonic and Oresme Sequences**: Functions to generate harmonic numbers and Oresme sequences.
- **Bicomplex Numbers**: A class for bicomplex numbers with full arithmetic support.
- **Neutrosophic Numbers**: Classes for neutrosophic numbers, including their complex and bicomplex extensions.
- **Hyperreal Numbers**: A conceptual implementation of hyperreal numbers.
- **Extensible Design**: Built with an abstract base class to easily extend and add new number systems.
- **Fully Typed**: The library is fully type-hinted for better code quality and maintainability.

## Installation

To install the library, clone the repository and use Poetry:

```bash
git clone https://github.com/WhiteSymmetry/adnus.git
cd adnus
poetry install
```

## Usage

Here's a quick overview of how to use the different number systems available in `adnus`.

### Bicomplex Numbers

```python
from adnus.main import BicomplexNumber

z1 = BicomplexNumber(1 + 2j, 3 + 4j)
z2 = BicomplexNumber(5 + 6j, 7 + 8j)

print(f"Addition: {z1 + z2}")
print(f"Multiplication: {z1 * z2}")
```

### Neutrosophic Numbers

```python
from adnus.main import NeutrosophicNumber

n1 = NeutrosophicNumber(1.5, 2.5)
n2 = NeutrosophicNumber(3.0, 4.0)

print(f"Addition: {n1 + n2}")
print(f"Multiplication: {n1 * n2}")
```

## Running Tests

To ensure everything is working correctly, you can run the included tests using `pytest`:

```bash
poetry run pytest
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

