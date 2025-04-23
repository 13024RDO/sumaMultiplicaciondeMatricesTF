# 🧠 Matriz TensorFlow.js - Generador y Operador de Matrices

Este proyecto permite al usuario generar matrices aleatorias utilizando la librería [TensorFlow.js](https://www.tensorflow.org/js) e interactuar con ellas visualmente desde una página web. El sistema permite sumar y multiplicar matrices generadas de forma aleatoria con valores entre 1 y 20.

---

## 🚀 Funcionalidades

✅ El usuario puede:
- Ingresar la cantidad de **filas** y **columnas** deseadas.
- Generar **dos matrices aleatorias** con valores enteros entre 1 y 20.
- Ver la **suma** y la **multiplicación elemento a elemento** directamente en la página.

---

## 🛠️ Tecnologías utilizadas

- HTML5 + CSS3
- JavaScript (ES6)
- [TensorFlow.js](https://cdn.jsdelivr.net/npm/@tensorflow/tfjs)

---

## 📷 Captura

![Captura del proyecto](screenshot.png)

> Si querés que se vea bien en GitHub, guardá una captura de pantalla como `screenshot.png` en la raíz del proyecto.

---

## ▶️ Cómo usar

1. Cloná o descargá el repositorio.
2. Abrí el archivo `index.html` con tu navegador favorito.
3. Ingresá las dimensiones de la matriz.
4. Hacé clic en **"Generar Matrices"**.
5. ¡Listo! Verás las matrices y los resultados en pantalla.

---

## 📌 Notas

- Las operaciones de suma y multiplicación se realizan **elemento a elemento**, no multiplicación matricial clásica (`A × B`). Si querés que se agregue esa operación, podés modificar `tf.mul(...)` por `tf.matMul(...)` (si las dimensiones son compatibles).
- Este proyecto es ideal para aprender a usar TensorFlow.js con operaciones básicas de matrices.

---

## 📄 Licencia

MIT License.
