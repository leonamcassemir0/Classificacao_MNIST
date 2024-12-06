# Classificação usando o banco de dados MNISt

O Capítulo 3 do livro "Mãos à Obra: Aprendizado de Máquina com Scikit-Learn & TensorFlow" aborda o tema de **Classificação**, uma das tarefas mais comuns do aprendizado supervisionado. O capítulo utiliza o conjunto de dados **MNIST**, composto por 70 mil imagens de dígitos escritos à mão. Este conjunto é frequentemente utilizado para o ensino de aprendizado de máquina e é considerado um "Hello World" da área. 

**Tópicos abordados no Capítulo 3:**

* **MNIST:** Introdução ao conjunto de dados MNIST e como baixá-lo utilizando o Scikit-Learn.
* **Treinando um Classificador Binário:** Simplificando o problema de classificação para identificar apenas um dígito, o capítulo demonstra como treinar um classificador binário utilizando o **Gradiente Descendente Estocástico** (SGD).
* **Medição de Desempenho:** O capítulo explora diferentes métricas para avaliar o desempenho de um classificador, incluindo:
    * **Medição da Acurácia com a Utilização da Validação Cruzada:** Uma técnica para obter uma estimativa mais precisa da performance do modelo.
    * **Matriz de Confusão:** Uma ferramenta para visualizar o desempenho do classificador, mostrando o número de vezes que ele classificou corretamente e incorretamente cada classe.
    * **Precisão e Revocação:** Métricas que medem a capacidade do classificador de identificar corretamente as instâncias positivas e evitar falsos positivos.
    * **Compensação da Precisão/Revocação:** Como equilibrar a precisão e a revocação para encontrar o ponto ideal para a tarefa em questão.
    * **Curva ROC:** Uma ferramenta gráfica para visualizar o desempenho do classificador em diferentes limiares de decisão.
    * **Pontuação ROC AUC:** Uma métrica que resume o desempenho global do classificador representado pela curva ROC.
* **Classificação Multiclasse:** Como treinar classificadores que podem distinguir entre mais de duas classes.
* **Análise de Erro:** Utilizando a matriz de confusão para identificar os tipos de erros que o classificador está cometendo.
* **Classificação Multilabel:** Treinando classificadores que podem atribuir múltiplas classes a uma única instância.
* **Exemplo de Remoção de Ruído:** Um exemplo prático de como treinar um classificador para remover ruído de imagens.


**Exercícios:** O capítulo inclui exercícios para consolidar os conceitos aprendidos, desafiando o leitor a:

* Construir um classificador para o conjunto de dados MNIST com alta acurácia.
* Experimentar diferentes hiperparâmetros e técnicas de pré-processamento de imagem para melhorar o desempenho do classificador.
* Aplicar os conceitos aprendidos em outros conjuntos de dados, como o Titanic e conjuntos de dados de spam.


**O Capítulo 3 oferece uma introdução abrangente aos conceitos de classificação em aprendizado de máquina, explorando diversas métricas de desempenho e técnicas para construir e avaliar classificadores. A utilização do conjunto de dados MNIST e a variedade de exercícios práticos tornam o aprendizado mais intuitivo e aplicável a diferentes problemas do mundo real.**

