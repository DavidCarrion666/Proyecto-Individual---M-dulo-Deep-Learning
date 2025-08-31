
---

## Metodología

1. **Dataset**  
   Se utilizó un dataset con 12 clases de animales, anotado en formato YOLO.   https://www.kaggle.com/datasets/lokeshvloki/animal-dataset-image-with-annotation
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

## Resultados Comparativos

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
<img width="2400" height="1200" alt="results" src="https://github.com/user-attachments/assets/2a52bbaf-b7b8-486e-9495-a871bb619168" />
<img width="1058" height="598" alt="image" src="https://github.com/user-attachments/assets/6be67a86-3a59-43cb-9da6-be3a48ef9968" />
<img width="3000" height="2250" alt="confusion_matrix_normalized" src="https://github.com/user-attachments/assets/65c6ec92-8cf0-4cb9-87f7-fc0ba78f30b9" />

- YOLOv8s → balance en detección
 <img width="2400" height="1200" alt="results" src="https://github.com/user-attachments/assets/7f2b45dd-31ea-4342-a33f-579d1e67b5ee" />
<img width="3000" height="2250" alt="confusion_matrix" src="https://github.com/user-attachments/assets/7d06fc62-302f-4c9c-b933-e501afe5107f" />
<img width="1050" height="600" alt="image" src="https://github.com/user-attachments/assets/674e0d39-4ae4-4167-af2a-b9efc9c44a47" />

- YOLOv8m → mejor detección, aunque más lento  
<img width="2400" height="1200" alt="results" src="https://github.com/user-attachments/assets/98371ff2-e288-4672-b7e2-a81630d921ae" />
<img width="1051" height="599" alt="image" src="https://github.com/user-attachments/assets/3709e5fb-4764-4540-a10c-dc3c77201cb0" />
<img width="3000" height="2250" alt="confusion_matrix_normalized" src="https://github.com/user-attachments/assets/5d45e3d8-2d63-4bc7-8dd1-180e41399741" />

---

##  Autor

- **Nombre:** David Carrión  
- **Curso:** Proyecto Individual – Módulo Deep Learning 2025  
- **Universidad:** UTPL  

---
