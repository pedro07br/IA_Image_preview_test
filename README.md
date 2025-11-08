# IA_Image_preview_test

## Descrição
Este projeto utiliza **Deep Learning** com **TensorFlow e Keras** para identificar imagens de frutas e legumes.  
O modelo é baseado em **MobileNetV2** e utiliza **data augmentation** para melhorar a performance com um dataset próprio.

O sistema também permite integrar com uma planilha Excel (`HealthyPredict.xlsx`) para fornecer **informações nutricionais** e **grupo alimentar** do alimento previsto.

---

## Funcionalidades

- Treinamento do modelo com dataset de frutas e legumes.  
- Previsão automática da classe de uma imagem enviada pelo usuário.  
- Processamento de múltiplas imagens ao mesmo tempo.  
- Integração com planilha Excel para retornar:
  - Grupo do alimento
  - Calorias
  - Carboidratos
  - Proteínas
  - Gorduras totais
  - Classificação nutricional

---

## Tecnologias utilizadas

- Python 3.x  
- TensorFlow / Keras  
- Pandas  
- Google Colab

---

## Como usar

### 1. Upload do dataset
No Google Colab, faça upload do ZIP do dataset (`sem_classificacao.zip`) usando:

```python
from google.colab import files
uploaded = files.upload()
