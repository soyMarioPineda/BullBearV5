
---

<img width="1260" height="857" alt="image" src="https://github.com/user-attachments/assets/d800b4e5-a8b4-46c8-9ec5-3e450dbb4f4e" />
<img width="1260" height="857" alt="image" src="https://github.com/user-attachments/assets/6eaba7fd-4e11-447e-ad7d-677b31a086db" />


# 📈 BullBearV5 — Zero-Lag Trend Indicator & Strategy

**BullBearV5** es un indicador/estrategia de trading basada en **Zero-Lag EMA con bandas dinámicas de volatilidad**, diseñado para identificar **cambios claros de tendencia**, reducir el lag tradicional de las EMAs y generar **señales limpias de compra y venta**.
Incluye **presets optimizados**, **alertas**, y **4 EMAs configurables** para análisis multi-tendencia.

---

## 🚀 Características Principales

* ✅ **Zero-Lag EMA (ZLEMA)** para reducir retraso en señales
* ✅ **Bandas de volatilidad adaptativas** basadas en ATR
* ✅ **Detección automática de tendencia** (Bull / Bear)
* ✅ **Señales BUY / SELL no repetitivas**
* ✅ **Presets preconfigurados** por activo y temporalidad
* ✅ **4 EMAs totalmente configurables**
* ✅ **Compatible con alertas de TradingView**
* ✅ **Funciona como indicador o estrategia**

---

## ⚙️ Presets Incluidos

El indicador permite seleccionar configuraciones optimizadas según el mercado:

| Preset    | Timeframe | Zero Lag Length | Multiplier |
| --------- | --------- | --------------- | ---------- |
| Custom    | —         | Manual          | Manual     |
| NVDA 15M  | 15 Min    | 14              | 1.25       |
| EURUSD 4H | 4 Horas   | 27              | 0.7        |

> El modo **Custom** permite modificar todos los parámetros manualmente.

---

## 📊 Lógica del Indicador

### 1. Zero-Lag EMA

Se utiliza una fórmula Zero-Lag para compensar el retraso clásico de las EMAs:

* Reduce ruido
* Reacciona más rápido a cambios de precio
* Mantiene suavidad visual

### 2. Bandas de Volatilidad

Las bandas se calculan a partir del **ATR máximo** en una ventana ampliada:

* Se expanden en alta volatilidad
* Se contraen en consolidación
* Filtran falsas rupturas

### 3. Cambio de Tendencia

* 📈 **Tendencia alcista**: el precio rompe la banda superior
* 📉 **Tendencia bajista**: el precio rompe la banda inferior
* Las señales solo aparecen **cuando la tendencia cambia**, evitando spam.

---

## 🔔 Señales y Alertas

### Señales Visuales

* 🟢 **BUY**: Cambio confirmado a tendencia alcista
* 🔴 **SELL**: Cambio confirmado a tendencia bajista

### Alertas Disponibles

* Señal de compra
* Señal de venta
* Cualquier nueva señal generada

Compatible con:

* Notificaciones móviles
* Webhooks
* Bots externos

---

## 📐 4 EMAs Configurables

Incluye **4 EMAs independientes**, cada una con:

* Activación individual
* Longitud configurable
* Fuente de precio
* Color personalizado
* Offset visual

Valores por defecto:

* EMA 9
* EMA 21
* EMA 50
* EMA 200

Ideal para:

* Confirmación de tendencia
* Soportes y resistencias dinámicas
* Análisis institucional

---

## 🧠 Casos de Uso

* Scalping (con presets o ajustes cortos)
* Intraday
* Swing trading
* Confirmación de tendencia
* Backtesting de estrategias
* Automatización con alertas

---

## 🛠️ Requisitos

* Plataforma: **TradingView**
* Lenguaje: **Pine Script v6**
* Mercado: Cualquiera (Forex, Crypto, Stocks, Índices)

---

## ⚠️ Disclaimer

Este indicador **no garantiza resultados** y **no constituye asesoría financiera**.
Úsalo como herramienta de apoyo junto con:

* Gestión de riesgo
* Confirmaciones adicionales
* Contexto del mercado

---

## 📌 Roadmap (Opcional)

* [ ] Stop Loss / Take Profit automáticos
* [ ] Filtro de sesión (London / NY)
* [ ] Confirmación multi-timeframe
* [ ] Dashboard estadístico

---

## 📄 Licencia

Uso libre para fines educativos y personales.
Si lo publicas o modificas, se agradece la atribución.

---


