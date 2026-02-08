# Deep-Iris-Classifier 🌸

Este repositório apresenta uma implementação de rede neural **Multilayer Perceptron (MLP)** utilizando a biblioteca `scikit-learn` para a classificação automatizada de espécies da flor Iris.

O projeto demonstra o fluxo completo de um pipeline de Machine Learning: desde o carregamento de dados brutos até a avaliação métrica de performance.

## 🧠 Arquitetura e Tecnologias
- **Modelo:** MLP (Multilayer Perceptron)
- **Framework:** Scikit-Learn
- **Camadas Ocultas:** 3 camadas de 10 neurônios cada
- **Função de Ativação:** ReLU (Rectified Linear Unit)
- **Otimizador:** Adam (Taxa de aprendizado adaptativa)



## 📊 O Dataset
Utilizamos o famoso **Iris Dataset** do repositório UCI. O modelo analisa 4 características das flores:
1. Comprimento da sépala
2. Largura da sépala
3. Comprimento da pétala
4. Largura da pétala



## 🛠️ Pré-processamento Aplicado
Para garantir a convergência da rede, o código realiza:
- **Standardization:** Escalonamento de variáveis para média zero e variância unitária.
- **Label & One-Hot Encoding:** Conversão de categorias textuais em formatos numéricos processáveis.
- **Train/Test Split:** Separação de 20% dos dados para validação independente.

## 📈 Performance
O modelo busca atingir uma acurácia superior a 95%, avaliada através de:
- Acurácia Global
- Precision, Recall e F1-Score (via `classification_report`)



## 🚀 Como Executar
1. Instale as dependências:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
