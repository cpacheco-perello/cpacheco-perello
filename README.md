<h1 align="center">Carlos Pacheco Perelló</h1>
<p align="center"><b>Físico · Datos &amp; Machine Learning</b><br>
Pipelines de datos, modelos predictivos y simulación física, del laboratorio a la nube.</p>

<p align="center">
  <a href="https://cpacheco-perello.com"><img src="https://img.shields.io/badge/Portfolio-cpacheco--perello.com-2b4c7e?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/carlos-pacheco-perello/"><img src="https://img.shields.io/badge/LinkedIn-carlos--pacheco--perello-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <a href="mailto:cpacheco.perello@outlook.com"><img src="https://img.shields.io/badge/Email-cpacheco.perello@outlook.com-555?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
  <a href="https://datosmeteo.com"><img src="https://img.shields.io/badge/Proyecto-datosmeteo.com-1f8a70?style=flat-square" alt="DatosMeteo"></a>
</p>

---

### 👋 Sobre mí

- 🎓 Graduado en **Física** (UIB, TFG con 9,5) y estudiante del **Máster en Física Avanzada y Matemática Aplicada**: visión por computador, deep learning, oceanografía numérica y tratamiento masivo de datos.
- 💼 Algo más de un año de experiencia con datos reales: **forecasting con Machine Learning en Azure Databricks**, un **espacio de datos federado sobre Kubernetes (AKS)**, predicción meteorológica operativa y análisis geoespacial con QGIS/ArcGIS.
- 🛠️ En mi tiempo libre construyo y opero **[DatosMeteo](https://datosmeteo.com)**, una plataforma de datos meteorológicos en producción, y un homelab que ejecuta su pipeline.
- 📍 Vivo en **Vitoria-Gasteiz**. Busco mi **puesto junior en datos o Machine Learning**, especialmente en **energía, meteorología o clima**: con muchas ganas de aprender de un buen equipo y de mejorar cada día.

---

###  Proyectos destacados

<a href="https://github.com/DatosMeteo/datosmeteo"><img src="https://raw.githubusercontent.com/DatosMeteo/datosmeteo/main/capturas/mapa-tormentas.png" alt="DatosMeteo: mapa con CAPE de GFS, rayos del satélite MTG y avisos de AEMET" width="100%"></a>

**[DatosMeteo](https://github.com/DatosMeteo/datosmeteo)** · [datosmeteo.com](https://datosmeteo.com)
Datos meteorológicos de España en una sola web, diseñada, programada y operada en solitario.
- **Más de 20 organismos oficiales** (AEMET, Euskalmet, ECMWF, Copernicus, EUMETSAT…): 1.506 estaciones en directo, 106 boyas, 638 aforos, 400 embalses y 9 modelos de previsión.
- **Pipeline en Python** (FastAPI, GDAL, NumPy) con un servicio Docker por fuente en servidor propio; **52 GB** en Backblaze B2 servidos por Cloudflare; CI/CD con GitHub Actions.
- **Previsión inmediata del radar a +120 min** con pysteps en producción, comparada con una **U-Net (PyTorch)** mediante métricas de verificación.
- Coste total: **menos de 11 € al mes**, electricidad del servidor incluida.

**[aemetdata](https://github.com/DatosMeteo/ametdata-py)** · [PyPI](https://pypi.org/project/aemetdata/)
Paquete de Python asíncrono para AEMET OpenData: **73 funciones en 11 módulos** (observación, predicción, climatología, avisos, radar, modelos…) y **120 tests**. Es la capa de descarga de DatosMeteo.

**[Remolinos del Mediterráneo · IMEDEA](https://github.com/cpacheco-perello/Practicas_Oceonografia_IMEDEA)**
Prácticas de oceanografía (IMEDEA, CSIC-UIB): filtrado de trayectorias de remolinos a partir de altimetría por satélite (AVISO META3.2), mapas de densidad por celdas, relación entre tiempo de vida y tamaño, y animaciones. MATLAB.

<details>
<summary><b>Otros proyectos</b></summary>

| Proyecto | Qué es | Stack |
|---|---|---|
| [BudgetDashboard](https://github.com/vbc-projectes/BudgetDashboard) | App de escritorio de finanzas personales con gráficos y 6 idiomas | Electron · SQLite · JavaScript · Docker |
| [StreamWithVPN](https://streamwithvpn.web.app) | Web para saber en qué plataforma y país ver cada película | React · TypeScript · Tailwind · Firebase |
| [Deck-BatteryBadge](https://github.com/cpacheco-perello/Deck-BatteryBadge) | Plugin de Steam Deck que muestra el consumo por juego y estima la autonomía | TypeScript · React |
| Homelab | Proxmox VE con VMs aisladas y NAS, Docker Compose, VPN WireGuard, DNS propio y monitorización con Beszel | Self-hosting |
| [TFG](https://cpacheco-perello.com) | Caracterización experimental y simulación de un dispositivo de emisión de campo (9,5/10) | COMSOL · LabVIEW · Python |

</details>

<!-- Cuando exista, añadir aquí arriba, en primer lugar:
**[⚡ Previsión de producción solar/eólica](enlace)**
Previsión D+1 con modelos meteorológicos (HARMONIE, ECMWF) y ML; skill de X % frente a la persistencia.
-->

---

### 💼 Experiencia

| Cuándo | Dónde | Qué |
|---|---|---|
| 2025 – 2026 | **FUEIB** · Espacio de Datos Turísticos de Baleares | Ingeniero de Espacios de Datos / Científico de Datos: SIMPL-Open sobre AKS, conectores federados, pipelines ETL en Python y forecasting con ML en Azure Databricks |
| 2025 | **MeteoClim** | Técnico y meteorólogo junior: predicciones operativas para medios y monitorización de servidores. Antes, consultoría de movilidad (análisis de datos sobre el cupo de vehículos en Ibiza) |
| 2024 – 2025 | **EMAYA** | Prácticas: series pluviométricas con Python y cartografía con QGIS/ArcGIS para la red de aguas regeneradas |
| 2025 | **IMEDEA (CSIC-UIB)** | Prácticas de oceanografía: remolinos del Mediterráneo con MATLAB |

---

### 🧰 Stack

**Datos y ML** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sqlite&logoColor=white)

**Cloud e infraestructura** &nbsp;
![Azure](https://img.shields.io/badge/Azure_(AKS)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Geoespacial y ciencia** &nbsp;
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square)
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square)
![COMSOL](https://img.shields.io/badge/COMSOL-368CCB?style=flat-square)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**Idiomas:** español y catalán (nativo) · inglés B2 ([EF SET C2, 85/100](https://cert.efset.org/es/aDU7Ks))

---

<p align="center"><i>Physicist working on data pipelines, forecasting and ML. Based in Vitoria-Gasteiz (Spain), looking for a junior data / ML role, ideally in energy or weather.</i><br>
📫 <a href="mailto:cpacheco.perello@outlook.com">cpacheco.perello@outlook.com</a> · <a href="https://cpacheco-perello.com">cpacheco-perello.com</a></p>
