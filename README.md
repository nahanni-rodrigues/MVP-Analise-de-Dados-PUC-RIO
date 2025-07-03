# MPV-An-lise-de-Dados-PUC-RIO
MVP desenvolvido para a disciplina de Análise de Dados da Pós Graduação em Ciência de Dados da PUC-Rio

Nome: Nahanni Taynah Jácome Rodrigues

Matrícula: 4052025000359

Dataset: Smiles Dataset

Descrição do Problema abordado
A espectroscopia de infravermelho (IR) é uma técnica amplamente utilizada na química para identificação de grupos funcionais em moléculas com base em suas vibrações moleculares. Cada grupo funcional apresenta um padrão específico de absorção de energia em determinadas faixas de frequência, permitindo que os espectros IR funcionem como "impressões digitais" moleculares.

Com o avanço de métodos computacionais, como a Teoria do Funcional da Densidade (DFT), tornou-se possível simular espectros IR de milhares de compostos orgânicos com precisão e rapidez. Isso gera uma oportunidade de aplicar técnicas de aprendizado de máquina (machine learning) para automatizar a interpretação desses espectros e classificar compostos com base em suas características químicas.
Neste experimento, busca-se construir modelos de ML capazes de:

Identificar automaticamente a presença do grupo funcional carbonila (classificação binária);

Distinguir entre os tipos de grupos carbonila (cetonas, ácidos carboxílicos e outros) a partir do espectro IR simulado (classificação multiclasse).

A aplicação de algoritmos de ML a esse problema pode acelerar significativamente análises químicas, reduzir erros humanos e oferecer suporte a pesquisas em química computacional, farmacologia e materiais.

Seleção dos dados

Os dados que serão utilizados nesse MVP usa a Alexandria Library, um conjunto de dados computacional contendo uma variedade de propriedades moleculares calculadas para 2.704 compostos diferentes usando diferentes modelos químicos. Na Engenharia Química, ferramentas computacionais, como a Análise de dados, assim como modelos de Machine Learning, podem auxiliar na investigação de dados como os presentes nesse projeto.O conjunto de dados específico usado neste experimento contém as frequências vibracionais de 2.337 moléculas calculadas usando a teoria da densidade funcional (DFT) com o funcional híbrido B3LYP e o conjunto base aug-cc-pVTZ, designado como B3LYP-aug-cc-pVTZ. As frequências vibracionais calculadas são uma série de linhas com intensidades correspondentes à força do oscilador de cada modo vibracional. Para simular espectros de absorção IR, essas frequências vibracionais devem ser convolutas com uma função que representa a forma do pico.

Dos espectros resultantes, 90% (2.104 espectros) devem ser usados como dados de treinamento e 10% (233 espectros) devem ser usados como dados de teste. Para a tarefa de classificação multiclasse na Parte III deste experimento, o conjunto de dados total contém os espectros de 351 moléculas contendo carbonila, das quais 90% (316 espectros) são usados como dados de treinamento e 10% (35 espectros) são usados como dados de teste .

As demais explicações a respeito dos dados, escolha das técnicas de pré-processamento, balanceamento dos dados, e modelos de machine learning usados estão presentes no arquivo nomeado: 

MVP - Análise de Dados e Boas Práticas.

Os arquivos csv usados para leitura dos dados de treinamento e teste estão disponibilizados no repositório para download e consulta, e posterior uso em estudos semelhantes. 


