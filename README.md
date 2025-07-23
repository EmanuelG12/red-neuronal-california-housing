# 🧠 Predicción de Precios de Viviendas con Redes Neuronales (California Housing Dataset)

Este proyecto aplica una Red Neuronal Multicapa (MLP) utilizando Keras/TensorFlow para predecir el valor medio de viviendas en California, basado en el dataset `California Housing`.

---

## 📊 Dataset

- **Fuente**: Scikit-learn (`fetch_california_housing`)
- **Tamaño**: 20.640 registros
- **Variables**: Ingresos medios, número de habitaciones, ubicación, entre otras.

---

## 🧱 Arquitectura de la Red

- Modelo **Sequential**
- Capas densas con funciones de activación `ReLU`
- Función de pérdida: `mse` (error cuadrático medio)
- Optimizador: `adam`
- Métrica: `mae` (error absoluto medio)

```python
model = Sequential([
    Input(shape=(X_train.shape[1],)),
    Dense(64, activation='relu'),
    Dropout(0.3),
    Dense(32, activation='relu'),
    Dense(1)  # Salida continua
])
```

## 📈 Resultados
- Se alcanzaron métricas aceptables de error (mae y mse)
- Se visualizó el progreso del entrenamiento
- Se realizó una evaluación del desempeño del modelo sobre el set de test


## 📚 Herramientas utilizadas
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## 🤝 Contribuciones
¡Contribuciones y sugerencias son bienvenidas! Podés abrir un issue o hacer un pull request.


## 🧠 Autor
Emanuel Gallo 
🔗 [LinkedIn](https://www.linkedin.com/in/emanuel-gallo-0abab71ba/)
🐙 [GitHub](https://github.com/EmanuelG12)

Técnico en Ciencia de Datos e Inteligencia Artificial