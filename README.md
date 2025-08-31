
---

## ⚙️ Metodología

1. **Dataset**  
   Se utilizó un dataset con 12 clases de animales, anotado en formato YOLO.  
   Las imágenes fueron divididas en:
   - Entrenamiento (`train`)
   - Validación (`val`)
   - Test (`test`)

2. **Modelos Entrenados**  
   - YOLOv8n  
   - YOLOv8s  
   - YOLOv8m  

3. **Evaluación**  
   Para cada modelo se analizaron:
   - Precisión (P)  
   - Recall (R)  
   - mAP@0.5  
   - mAP@0.5:0.95  

## 📊 Resultados Comparativos

| Modelo   | Precisión (max) | Recall (max) | mAP@0.5 (max) | mAP@0.5:0.95 (max) |
|----------|-----------------|--------------|---------------|--------------------|
| YOLOv8n  | 0.891           | 0.936        | 0.904         | 0.591              |
| YOLOv8s  | 0.866           | 0.883        | 0.893         | 0.602              |
| YOLOv8m  | 0.899           | 0.902        | 0.927         | 0.618              |

Se observa que **YOLOv8m** alcanzó la mejor mAP@0.5 y mAP@0.5:0.95, mientras que **YOLOv8n** 
fue el más rápido, sacrificando un poco de precisión.


## Ejemplos de Inferencia

A continuación, ejemplos visuales de las predicciones realizadas:

- YOLOv8n → detección rápida con precisión aceptable  
- YOLOv8s → balance en detección  
- YOLOv8m → mejor detección, aunque más lento  


---

## 👨‍💻 Autor

- **Nombre:** David Carrión  
- **Curso:** Proyecto Individual – Módulo Deep Learning 2025  
- **Universidad:** UTPL  

---
