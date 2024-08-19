# Projeto IDS IoT com Rede DL

📡 **Projeto IDS IoT simplês com rede DL**  
🔍 Este projeto envolve a manipulação da base de dados, tratamento, criação do modelo, treinamento e validação.

🔥 **Foi utilizado o jupyter notebook** junto ao anaconda para dedsenvolver o projeto.
## 📂 Estrutura do Projeto

**Introdução**
O objetivo deste projeto é treinar uma rede neural para classificação de dados em um conjunto
de dados de ataques IoT. A rede neural será desenvolvida utilizando a biblioteca TensorFlow
com a interface Keras. O modelo será treinado para prever a classe correta para cada entrada
de dados.

**Conjunto de Dados**
O conjunto de dados CicIoT2023 que foi desenvolvido pelo
Instituto Canadense de
Segurança Cibernética (CIC) é utilizado nesse projeto contendo 33 dados de ataques que são
divididos em sete catégorias, sendo elas DDoS, DoS, Recon, Web-based, Brute Force,
Spoofing e Mirai.

**Pré-processamento dos Dados**
Antes do treinamento do modelo, os dados foram pré-processados da seguinte forma:
Como os dados originais são compostos por 33 rotulos distintos. Foi modificado os rotulos
conforme as classes de ataques, resultando em 8 classes para o treinamento do modelo. As
classes estão listadas a seguir:
DDoS, DoS, Mirai, Benign, Spoofing, Recon,Web, BruteForce.
Normalização das características para garantir que todas tenham a mesma escala.
Divisão do conjunto de dados em conjuntos de treinamento, validação e teste na proporção
X:Y:Z.
Foram criados bases de dados utilizando técnicas de smote e sampling para dados
desbalanceados.

**Arquitetura do Modelo**
Foi utilizado três arquiteturas de rede neural para o treinamento com os dados de IoT Figuras
1,2,3.



1. **Manipulação da Base de Dados**  
   - Importação e limpeza dos dados para garantir a integridade e qualidade da informação.

2. **Tratamento dos Dados**  
   - Normalização, codificação de variáveis categóricas e separação entre conjuntos de treino e teste.

3. **Criação do Modelo**  
   - Desenvolvimento de uma Rede DL (Deep Learning) adequada para a detecção de intrusões em IoT.

4. **Treinamento e Validação**  
   - Treinamento do modelo com os dados tratados e posterior validação para avaliação de desempenho.

