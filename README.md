# Detección de Melanoma con Vision Transformer (ViT)

Este repositorio contiene un modelo de inteligencia artificial basado en **Vision Transformer (ViT)** optimizado con **Optuna**, diseñado para la detección de melanoma en imágenes de lesiones cutáneas. 

El modelo ha sido entrenado para clasificar imágenes en **benignas** y **malignas (melanoma)**, con un enfoque especial en mejorar la detección de la clase maligna mediante **Focal Loss**. 

## 📌 Características
- **Modelo basado en ViT-B16**, una arquitectura de Vision Transformer.
- **Optimización de hiperparámetros con Optuna** para mejorar el rendimiento del modelo.
- **Entrenamiento en TPU** para mejorar la velocidad de procesamiento.
- **Uso de Focal Loss** para priorizar la detección de lesiones malignas.
- **Preprocesamiento y combinación de múltiples datasets** en un solo conjunto de datos.

## 📂 Bases de Datos Usadas
El modelo ha sido entrenado utilizando múltiples bases de datos públicas de imágenes de lesiones cutáneas:

- **HAM10000**: [Enlace](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)
- **BCN20000**: [Enlace](https://figshare.com/articles/journal_contribution/BCN20000_Dermoscopic_Lesions_in_the_Wild/24140028/1?file=49291684)
- **ISIC**: [Enlace](https://www.kaggle.com/competitions/siim-isic-melanoma-classification/data?select=jpeg)
- **Kaggle Melanoma Dataset**: [Enlace](https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images)

## 📜 Licencia
Este proyecto está bajo la **Licencia Pública General Affero de GNU v3.0 (AGPL-3.0)**, con la siguiente restricción adicional:

> **No se permite el uso comercial de este código ni de sus derivados sin la autorización expresa del autor original.**

Para más detalles, consulta el archivo [LICENSE](LICENSE).

## 📩 Contacto
Si tienes dudas, mejoras o sugerencias, puedes crear un **Issue** en este repositorio o contactarme a través de:

✉️ **Email:** [marc.perez.guerrero@estudiantat.upc.edu]  
🐙 **GitHub:** [https://github.com/marcperezg](https://github.com/marcperezg)  

---
