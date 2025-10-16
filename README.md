# Clasificación de flores Iris con KNN

## 1️⃣ Descripción del modelo
Usé las variables numéricas del conjunto de datos **Iris** como entrada:
- sepal_length
- sepal_width
- petal_length
- petal_width

El modelo fue entrenado para clasificar la especie de una flor (Setosa, Versicolor o Virginica) basándose en estas medidas.

---

## 2️⃣ Pasos fundamentales para el éxito del algoritmo
1. **Preparación de los datos:** limpieza, normalización y selección de variables relevantes.
2. **División del conjunto de datos:** entrenamiento y prueba para evitar sobreajuste.
3. **Selección del modelo:** se usó **KNN con k=3**.
4. **Evaluación del modelo:** se utilizó la precisión y la matriz de confusión.

---

## 3️⃣ Entrenamiento y validación
- **Entrenamiento:** proceso donde el modelo aprende de los datos conocidos (X_train, y_train).
- **Validación (prueba):** se evalúa con datos no vistos (X_test, y_test) para medir su capacidad de generalización.
