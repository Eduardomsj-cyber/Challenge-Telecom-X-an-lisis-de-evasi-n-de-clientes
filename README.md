# 📉 Análisis de Fuga de Clientes (Churn) - TelecomX LATAM

Este repositorio contiene un análisis exploratorio de datos (EDA) profesional enfocado en la retención de clientes para una empresa de telecomunicaciones x. El objetivo es identificar por qué los usuarios cancelan su servicio y proponer soluciones basadas en datos.

## 📌 Resumen del Proyecto
La deserción de clientes es uno de los mayores desafíos en el sector Telco. En este análisis, procesamos un dataset de más de 7,000 registros para encontrar los disparadores de la fuga.

**Hallazgos clave:**
* **Tasa de Abandono:** 26.5%.
* **Factor de Riesgo:** Cargos mensuales superiores a $70 USD.
* **Periodo de Alerta:** Primeros 12 meses de contrato (fase de "Luna de Miel").
* **Contratos:** Los planes "Mes a mes" presentan la mayor volatilidad.

---

## 🛠️ Instalación y Configuración (Conda)

Para asegurar que el proyecto corra perfectamente, utiliza el gestor de paquetes **Conda**. Sigue estos pasos en tu terminal:

```bash
# 1. Clonar el repositorio
git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
cd nombre-del-repo

# 2. Crear el entorno virtual con Python 3.10
conda create --name telecom_analysis python=3.10 -y

# 3. Activar el entorno
conda activate telecom_analysis

# 4. Instalar las dependencias necesarias
pip install pandas matplotlib seaborn notebook
