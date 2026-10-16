# algeria-balance-of-payments-arima-forecasting
Modelado ARIMA y análisis econométrico de la balanza de pagos trimestral de Argelia.
# 📈 Previsión Macroeconómica: Balanza de Pagos Trimestral de Argelia (Modelo ARIMA)

> **Resumen Académico — Data Analytics y Business Intelligence aplicados a la econometría**

Este proyecto ilustra la aplicación práctica del análisis de datos y la inteligencia de negocio para la previsión macroeconómica, combinando el modelado de series temporales (ARIMA), validación estadística avanzada y análisis estratégico[cite: 1].

---

## Objetivo del Estudio
Analizar y predecir la evolución de la balanza de pagos trimestral de Argelia para anticipar riesgos macroeconómicos, evaluar la disponibilidad de divisas y determinar las implicaciones estratégicas para la gestión financiera y la inversión internacional[cite: 1].

---

## Preprocesamiento y Limpieza de Datos
- **Período analizado :** 2013 T4 – 2023[cite: 1].
- **Frecuencia :** Trimestral ($s = 4$)[cite: 1].
- **Fuentes de datos :** Fondo Monetario Internacional (FMI: *Balance of Payments Statistics*), Banco Mundial (*Algeria Economic Monitor*) y Banco de Argelia[cite: 1].
- **Tratamiento :** Conversión a formato numérico, eliminación de valores ausentes (NA) y ceros, y construcción estructurada de la serie temporal para obtener una serie econométricamente explotable[cite: 1].

---

## Stack Técnico y Metodología
- **Lenguajes / Herramientas :** R / Python (Econometría y Series Temporales).
- **Modelado :** Modelos ARIMA / SARIMA, pruebas de estacionariedad (ADF), análisis de autocorrección (ACF/PACF).
- **Business Intelligence :** Cuadros de mando e indicadores macroeconómicos clave.

---

## Estructura del Repositorio
├── data/                 # Serie temporal procesada (2013 T4 - 2023)
├── scripts/              # Código R/Python de modelado ARIMA y pruebas estadísticas
├── reports/              # Documentación académica y análisis estratégico
└── README.md
