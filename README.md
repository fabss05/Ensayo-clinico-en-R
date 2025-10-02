# 🚀 Simulación de Ensayo Clínico Aleatorizado en R

**Autores:** Fabrizio Flores & Julia Sagastegui

Este repositorio contiene un **tutorial en R** para simular un ensayo clínico con **1000 participantes**, considerando:

- La **distribución de edad** de la población peruana 👩‍🦱
- El **nivel socioeconómico** de la población peruana 💰  
- La **frecuencia cardiaca típica de corredores amateurs en fase 2** 🏃‍♂️  

El código genera un **archivo Excel** con dos hojas:  

- **Datos** 📊 : las observaciones simuladas  
- **Metadata** 📝 : descripción y documentación de cada variable  

---

## 📂 Contenido del repositorio

- `ensayo_clinico.qmd` : Script principal en Quarto/R  
- `README.md` : Este archivo de documentación  

---

## ⚙️ Requisitos

- R >= 4.0  
- Paquetes: `truncnorm`, `openxlsx`  

Instalación de paquetes en R:

```r
install.packages(c("truncnorm", "openxlsx"))
