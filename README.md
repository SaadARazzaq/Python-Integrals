# Python-Integrals

![image](https://github.com/user-attachments/assets/a75b06bd-9601-43f4-864b-f8aac1397ecc)

This repository includes a Colab notebook that demonstrates how to perform definite and indefinite integration using Python libraries such as SciPy and SymPy. The examples cover a range of integration techniques, from single-variable integrals to double and triple integrals, as well as indefinite integrals with symbolic math. (MERGED ALL INTO ONE PLACE FROM FREECODECAMP)

## Overview

The notebook is organized as follows:

1. **Single-variable Definite Integrals** - Using `scipy.integrate.quad`
2. **Double and Triple Integrals** - Using `scipy.integrate.dblquad` and `tplquad`
3. **Infinite Limits** - Example of an integral from 0 to infinity
4. **Indefinite Integrals** - Using SymPy for symbolic integration

### Key Examples

- **Single-variable integrals**:
  - Definite Integral
    - ∫x^2 dx from 0 to 1
    - ∫{x+1}/{x^2} dx from 1 to 2
    - ∫log(sin(x)) dx from 0 to 2
    - ∫e^{-x} dx from 0 to ∞
  - Indefinite Integral
    - ∫(x^2) dx = (x^3)/x + C
    - ∫sin(x) dx = -cos(x) + C
    
- **Double Integral**:
  - ∫∫ x * y^2 dxdy
    
- **Triple Integral**:
  - ∫∫∫ z * (x + y + z) dxdydz

## Usage

Open the notebook in Google Colab and run the cells sequentially to execute the integration examples.

---

Feel free to clone this repository to modify or expand on these integration examples for other mathematical functions or intervals.
