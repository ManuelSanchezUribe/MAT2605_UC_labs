# MAT2605 - Cálculo Científico I | Laboratorios Computacionales

Bienvenido al repositorio oficial de los laboratorios del curso **MAT2605 Cálculo Científico**. Aquí encontrarás las guías, *notebooks* (Jupyter) y códigos fuente necesarios para las sesiones prácticas del semestre.

**Profesor:** Thomas Führer y Manuel A. Sánchez  
**Horario:** Viernes, m&oacute;odulo 4.  
**Lugar:** Laboratorio de Computación *CS103*

## 🛠 Requisitos y Entornos de Trabajo

Para estos laboratorios necesitarás Python 3.x y las librerías científicas `numpy`, `scipy` y `matplotlib`. Puedes elegir cualquiera de las siguientes tres opciones para trabajar:

| Entorno | Descripción | Instrucciones de uso |
| :--- | :--- | :--- |
| **1. Local (Recomendado)** | Instalación en tu propio computador. | Abre tu terminal y ejecuta:<br>`pip install numpy scipy matplotlib jupyterlab`<br>Luego inicia el entorno con:<br>`jupyter notebook` o  `jupyter lab`|
| **2. Google Colab** | Entorno en la nube (no requiere instalación). |  Abre los links directamente. Puedes adaemas guardar tu avance con una cuenta google al subir este archivo `.ipynb` a tu Google Drive. Las librerías ya vienen preinstaladas. |






## 📅 Calendario de Sesiones

A continuación se detalla la planificación del **segundo semestre de 2026** (05 de agosto -  27 de Noviembre).

<!-- | Semana | Fecha | Tópico / Actividad | Enlace al Material |
| :--- | :--- | :--- | :--- |
| **Lab 00** | 06 de Marzo | Introduccion a Jupyter Notebook (autoestudio, no es presencial) | [Lab 00](./LabIntro/)|
| **Lab 01** | 13 de Marzo | Introducción a Python Científico & Aritmética de Punto Flotante   | [Lab 01](./Lab01/) |
| **Lab 02** | 20 de Marzo | Sistemas Lineales: Métodos Directos - evaluaci&oacute;n  | [Lab 02](./Lab02/) |
| **Lab 03** | 27 de Marzo | Normas, n&uacute;mero de condici&oacute;n, m&eacute;todos iterativos | [Lab 03](./Lab03/) |
| **—** | **03 de Abril** | *Feriado: Viernes Santo* |  — |
| **Lab 04** | 10 de Abril | Métodos Iterativos (Jacobi, Gauss-Seidel) - evaluaci&oacute;n | [Lab 04](./Lab04/) |
| **—** | 17 de Abril | *Interrogacion I - 16 de Abril* |  — |
| **Lab 05** | 24 de Abril |  Valores propios | [Lab 05](./Lab05/) |
| **—** | **01 de Mayo** | *Feriado: Día del Trabajador* |  — |
| **—** | 08 de Mayo | *Interrogacion II - 06 de Mayo* |  — |
| **Lab 06** | 15 de Mayo | Ecuaciones no lineales - evaluaci&oacute;n|  [Lab 06](./Lab06/) |
| **—** | 22 de Mayo | Receso de docencia | — |
| **Lab 07** | 29 de Mayo | Interpolación Polinomial - evaluaci&oacute;n|  [Lab 07](./Lab07/) |
| **—** | 05 de Junio | *Interrogacion III - 02 de Junio* |  — |
| **Lab 08** | 12 de Junio | Aproximación de Funciones (Mínimos Cuadrados) - evaluaci&oacute;n|  [Lab 08](./Lab08/) |
| **Lab 09** | 19 de Junio | Diferenciación Numérica |  [Lab 09](./Lab09/) |
| **Lab 10** | 26 de Junio | Integración Numérica - evaluaci&oacute;n |  [Lab 10](./Lab10/) | -->

| Semana | Fecha | Tópico / Actividad | Enlace al Material | Enlace en Google Colab |
| :--- | :--- | :--- | :--- | :--- |
| **Lab 00** | 07 de agosto | Introduccion a Jupyter Notebook (autoestudio, no es presencial) | [Lab 00](./LabIntro/lab00.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/LabIntro/lab00.ipynb ) |
| **Lab 01** | 14 de agosto | Introducción a Python Científico & Aritmética de Punto Flotante   | [Lab 01](./Lab01/lab01.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab01/lab01.ipynb ) |
| **Lab 02** | 21 de agosto | Sistemas Lineales: Métodos Directos - evaluaci&oacute;n  | [Lab 02](./Lab02/lab02.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab02/lab02.ipynb ) |
| **Lab 03** | 28 de agosto | Normas, n&uacute;mero de condici&oacute;n, m&eacute;todos iterativos | [Lab 03](./Lab03/lab03.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab03/lab03.ipynb ) |
| **—** | 04 de septiembre | *Interrogaci&oacute;on 1*, 02 de septiembre | — | — | 
| **Lab 04** | 11 de septiembre |Métodos Iterativos (Jacobi, Gauss-Seidel) - evaluaci&oacute;n | [Lab 04](./Lab04/lab04.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab04/lab04.ipynb ) |
| **—** | 18 de septiembre |   Feriado legal | — | — |
| **—** |  25 de septiembre| Receso de docencia |  — | — |
| **Lab 05** | 02 de octubre | Valores y vectores propios | [Lab 05](./Lab05/lab05.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab05/lab05.ipynb ) |
| **-**  | 09 de octubre | *Interrogaci&oacute;n 2*, 07 de octubre | — | — |
| **Lab 06** | 16 de octubre | Ecuaciones no lineales - evaluaci&oacute;n|  [Lab 06](./Lab06/lab06.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab06/lab06.ipynb ) |
| **Lab 07** | 23 de octubre | Interpolación Polinomial - evaluaci&oacute;n|  [Lab 07](./Lab07/lab07.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab07/lab07.ipynb ) |
| **Lab 08** | 30 de octubre | Aproximación de Funciones (Mínimos Cuadrados) - evaluaci&oacute;n|  [Lab 08](./Lab08/lab08.ipynb) |[Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab08/lab08.ipynb ) |
| **—** | 06 de noviembre | *Interrogaci&oacute;n 3*, 04 de noviembre| — | — |
| **Lab 09** | 13 de noviembre | Diferenciación Numérica |  [Lab 09](./Lab09/lab09.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab09/lab09.ipynb ) |
| **Lab 10** | 20 de noviembre | Integración Numérica - evaluaci&oacute;n |  [Lab 10](./Lab10/lab10.ipynb) | [Open in Colab](https://colab.research.google.com/github/ManuelSanchezUribe/MAT2605_UC_labs/blob/main/Lab10/lab10.ipynb ) |
| **Lab rec.** | 27 de noviembre | — | — | — |

**Instrucciones de instalación vía `pip`:**
Abre tu terminal (o símbolo del sistema en Windows) y ejecuta el siguiente comando:
```bash
pip install numpy scipy matplotlib jupyterlab
```

<!---
## 📦 Instrucciones de Entrega

Las entregas se realizarán a través de [Canvas/GitHub Classroom] antes del inicio de la siguiente sesión. El formato esperado es un `notebook.ipynb` ejecutado y limpio.

1.  Clona este repositorio: `git clone https://github.com/tu-usuario/MAT2605-Labs.git`
2.  Actualiza tu repositorio semanalmente: `git pull origin main`
3.  Sube tu solución a tu repositorio personal o envíalo según las indicaciones del ayudante.
-->
---
*Última actualización: Agosto 2026*
