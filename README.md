# ⚽ Soccer Ball Detection (YOLOv8)

Projeto de **Visão Computacional** para detecção de bolas de futebol utilizando o modelo **YOLOv8**.

## 🚀 Tecnologias

* Python
* YOLOv8 (Ultralytics)
* Roboflow (dataset)

## 🎯 Objetivo

Treinar um modelo capaz de identificar bolas de futebol em imagens e vídeos.

## 📊 Resultados

* mAP50: **0.995**
* Alta precisão e recall na detecção

![Resultados](resultados/results.png)

## 🖼️ Exemplo

![Detecção](exemplos/img1.jpg)

## ▶️ Como usar

```python
from ultralytics import YOLO

model = YOLO("best.pt")
model.predict(source="imagem_ou_video", save=True)
```

## 📁 Estrutura

```
├── treinar.py
├── data.yaml
├── best.pt
├── exemplos/
└── resultados/
```

---

Projeto desenvolvido para estudo de **IA aplicada e detecção de objetos**.
