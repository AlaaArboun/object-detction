# Object Detection using YOLOv8 with Edge TPU Accelerator

Ce projet est une démonstration de détection d'objets en utilisant YOLOv8 avec l'accélérateur Edge TPU.

## Configuration

### Prérequis

Avant de commencer, assurez-vous de disposer des éléments suivants :
- Coral M.2 ou Mini PCIe Accelerator
- Python 3.x installé sur votre système

### Installation

1. **Configuration de Coral M.2 ou Mini PCIe Accelerator :**  
   Suivez les instructions dans la documentation officielle pour configurer votre accélérateur Edge TPU.

2. **Création de l'environnement virtuel :**  
   Utilisez les commandes suivantes pour créer et activer votre environnement virtuel :
   ```bash
   python -m venv myenv
   source myenv/bin/activate   # Pour Linux/MacOS
   myenv\Scripts\activate.bat  # Pour Windows
