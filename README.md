# APLICACIÓN – PYTHON FUNDAMENTALS (Streamlit)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Framework](https://img.shields.io/badge/Framework-Streamlit-red)
![Data](https://img.shields.io/badge/Data-Pandas-6f42c1)
![UI](https://img.shields.io/badge/UI-Custom%20CSS-informational)
![PRs](https://img.shields.io/badge/PRs-Welcome-orange)

Aplicación interactiva desarrollada en **Streamlit** como proyecto del **Módulo 1: Python Fundamentals**.  
Incluye **Home** y **4 ejercicios** que aplican fundamentos de programación: variables, condicionales, listas, diccionarios, funciones, programación funcional y POO.

---

## Funcionalidades principales

- **Interfaz tipo dashboard**: sidebar oscuro + área principal clara, con estilos CSS personalizados.
- **Home** con presentación del proyecto, objetivo y tecnologías.
- **Ejercicio 1**: verificador de presupuesto (variables y condicionales).
- **Ejercicio 2**: registro de actividades (lista de diccionarios) + tabla y estado.
- **Ejercicio 3**: retorno esperado usando **funciones + `map()` + `lambda`**.
- **Ejercicio 4**: modelado con **POO** (clase `Actividad` y métodos).

> Nota: cada ejercicio gestiona su propio estado con `st.session_state`, por lo que son independientes.

---

## Estructura del repositorio

```bash
# Carpeta raíz del proyecto
Proyecto-Python-Fundamentals/
├─ app.py                 # Archivo principal de la aplicación Streamlit
├─ README.md              # Documentación del proyecto
├─ requirements.txt       # Dependencias del proyecto
└─ logo.png               # Logo

