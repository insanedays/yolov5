# Visão Computacional com YOLO 

Utilizamos a arquitetura YOLOv5 customizada para treinar um modelo com imagens rotuladas manualmente. 

## 🎯 Sistema de visão computacional com YOLOv5 

Neste projeto cria uma POF de um sistema de visão computacional utilizando o modelo YOLOv5. O objetivo era demonstrar na prática a aplicação e eficácia dessa tecnologia em um cenário escolhido livremente.

Os objetos escolhidos foram capacetes de segurança e drones, totalizando visando explorar a detecção de objetos tanto no contexto de segurança no trabalho quanto em tecnologias de monitoramento.

### Ferramentas utilizadas

- **Rotulação:** [Make Sense IA](https://www.makesense.ai/)
- **Ambiente de desenvolvimento:** Google Colab conectado ao Google Drive
- **Framework utilizado:** YOLOv5
- **Dataset** - Google Drive
  - **Total de imagens:** 80 imagens
    - 40 imagens de **capacetes de segurança**
    - 40 imagens de **drones**
  - **Divisão do dataset:**
    - Treinamento: 64 imagens (32 por objeto)
    - Validação: 8 imagens (4 por objeto)
    - Testes: 8 imagens (4 por objeto)

- Foram executadas duas simulações de treinamento com números distintos de épocas:
- **Primeira simulação:** 30 épocas
- **Segunda simulação:** 60 épocas

### Notebook de Treinamento

O experimento foi conduzido em um notebook Jupyter/Colab com integração ao Google Drive, utilizando a arquitetura YOLOv5s. O notebook documenta todas as etapas com explicações em Markdown e comentários no código.

Neste repositório está disponibilizada uma **versão sem outputs**, com fins exclusivamente demonstrativos.
O notebook completo, contendo as células executadas e os resultados, está disponível por esse [link](https://colab.research.google.com/drive/1AB1_zVO89Xih9t1GqknAmx9thRaxVzO0?usp=sharing).



