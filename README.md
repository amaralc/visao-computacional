# Disciplina: Visao Computacional (http://www.lapix.ufsc.br/ensino/visao)

Os tópicos descritos fazem parte da disciplina Visão Computacional do LAPIX (http://www.lapix.ufsc.br/ensino/visao).

## Capítulo 0.0. Paradigmas  de VC e RP
## Capítulo 1.0. Técnicas no Domínio do Valor

Assunto: Métodos no Domínio do Valor: Thresholding, Histogramas

> Experimento 1: Centróide do carrinho

## Capítulo 1.1. Medidas de Similaridade e Distância Básicas
> Assunto: Distância de Hamming, Hamming+, Distância Euclidiana, Nearest Neighbour, kNN, Mahalanobis,

## Capítulo 1.2. Métodos no Domínio do Espaço, Parte 1: Convolução, Morfologia Matemática e Detecção de Bordas

Neste capítulo você vai ver técnicas de Condicionamento em Análise de imagens no Domínio do Espaço baseadas no uso de Matrizes de Convolução:
- Morfologia Matemática Binária
- Morfologia Matemática de Tons de Cinza
- Detecção Simples de Bordas
- Detecção de Bordas utilizando Canny

> Experimento 2: Ressaltar Objetos em Movimento e Sobrepor suas Silhuetas à ImagemTarefa

## Capítulo 1.3. Métodos no Domínio do Espaço, Parte 2: Segmentação por Crescimento de Regiões

Assunto: Bases Cognitivo-Filosóficas e Métodos Simples para Crescimento de Regiões
Crescimento de Regiões Simples
Crescimento de Regiões com Medidas Simples
Split & Merge

## Capítulo 1.4. Métodos no Domínio do Espaço, Parte 3: Rotulação

Neste capítulo você vai aprender e utilizar alguns métodos empregados na Etapa III da Pipeline de Processamento de Imagens: a Rotulação.A Rotulação é uma transforma ção I->M, transformando uma imagem de pixels em um Modelo, de acordo com critérios e parâmetros definidos durante o processo de rotulação. A sintaxe do resultado pode ser uma lista de valores, um grafo, uma rede semântica ou um conjunto de imagens, cada uma associada a um rótulo, ou o que for necessário para a aplicação. O importante é que, uma vez aplicado um passo de rotulação, deixamos o espaço de pixels sem significado e passamos a possuir pixels ou partes de imagens associados a algum tipo de significado.

A maioria dos métodos empregados na etapa de Rotulação são métodos da área do Reconhecimento de Padrões (o INE oferece  uma disciplina nesta área, INE 5443, oferecida como optativa à 7ª fase do curso de Bacharelado em Ciências da Computação, que você pode assistir como Aluno Especial). Há porém alguns métodos que, além de serem básicos e úteis em muitas aplicações diferentes, são específicos para Processamento de Imagens. Vamos ver alguns deles aqui:

### 1.4.1. Rotulação Simples

#### 1.4.1.1. Outros reconhecedores de características

### 1.4.2. Métodos Avançados de Descrição de Características: HoG, SIFT, SURF & ORB

#### HoG (Histogram of Gradients)

The histogram of oriented gradients (HoG) is a feature descriptor used in computer vision and image processing for the purpose of object detection. The technique counts occurrences of gradient orientation in localized portions of an image. This method is similar to that of edge orientation histograms, scale-invariant feature transform descriptors, and shape contexts, but differs in that it is computed on a dense grid of uniformly spaced cells and uses overlapping local contrast normalization for improved accuracy.

#### SIFT (Scale-Invariant Feature Transform)
#### Tutoriais interessantes de SIFT
#### SURF (Speeded-Up Robust Features)
#### ORB (Oriented FAST and Rotated BRIEF)

> Experimento 3: Rotulação dos Objetos em Movimento com Tamanho acima de um LimiarTarefa

## 3.6. Extração de Características - Métodos Geométricos - Transformada de Hough

Site de referência deste Capítulo: [3.Visão Computacional::Domínio do Espaço](http://www.lapix.ufsc.br/ensino/visao/#Dominio_do_Espaco)

## 5.0 Aula Introdutória de Redes Neurais

Site de referência deste Capítulo: [5. Deep Learning::Redes Neurais Convolucionais para Processamento de Imagens](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning)

Páginas de Apoio da Unidade:

1. [Reconhecimento de Padrões::Técnicas Sub-simbólicas: Redes Neurais](http://www.lapix.ufsc.br/ensino/reconhecimento-de-padroes/tecnicas-sub-simbolicas-redes-neurais/)
1. [Deep Learning::PyTorch & fast.ai](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningpytorch)

Material de Apoio Externo:

1. [Simulador online de TensorFlow Deep Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.47515&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false) (escrito em TypeScript e d3.js)
1. Outro simulador simples online: http://experiments.mostafa.io/public/ffbpann/

## 5.1. Deep Learning: Introdução às Redes Neurais Convolucionais

Site de referência deste Capítulo: 5. Deep Learning::Redes Neurais Convolucionais para Processamento de Imagens

Páginas de Apoio da Unidade:

1. [Deep Learning::Introdução ao Novo Coneccionismo](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningintroducao-ao-novo-coneccionismo)
1. [Deep Learning::Aprendizado por Transferência e Ajuste Fino](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningaprendizado-por-transferencia-e-ajuste-fino)
1. [Deep Learning::Usando a Nuvem para seus Trabalhos](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningintroducao-ao-novo-coneccionismo/deep-learningusando-nuvem-para-seus-trabalhos)
1. [Deep Learning::Coisas Prontas & Datasets](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningcoisas-prontas-datasets)
1. [Deep Learning::Entenda o Babel: Glossário](http://www.lapix.ufsc.br/ensino/visao/visao-computacionaldeep-learning/deep-learningglossario/)

Material de Apoio Externo:

1. [Simulador online ConvNetJS MNIST demo (LeNet-5)](https://cs.stanford.edu/people/karpathy/convnetjs/demo/mnist.html) (Andrej Kárpathy)
1. [Simulador interativo online 2D do MNIST  (LeNet-5)](http://scs.ryerson.ca/~aharley/vis/conv/flat.html) (Adam Harley)
1. [Simulador interativo online 3D do MNIST  (LeNet-5)](https://scs.ryerson.ca/~aharley/vis/conv/) (Adam Harley)

## 5.2. Deep Learning: Reconhecimento de Imagens

Site de referência deste Capítulo: 5. Deep Learning::Redes Neurais Convolucionais para Processamento de Imagens

Páginas de Apoio da Unidade:

Deep Learning::Reconhecimento de Imagens
Deep Learning::Aprendizado por Transferência e Ajuste Fino
Deep Learning::Usando a Nuvem para seus Trabalhos
Deep Learning::Coisas Prontas & Datasets
Deep Learning::Entenda o Babel: Glossário
Material de Apoio Externo:

Simulador online: ConvNetJS CIFAR-10 demo (Andrej Kárpathy)

## 5.3. Deep Learning: Detecção de Objetos

Site de referência deste Capítulo: 5. Deep Learning::Redes Neurais Convolucionais para Processamento de Imagens

Páginas de Apoio da Unidade:

Deep Learning::Detecção de Objetos em Imagens
Deep Learning::Usando a Nuvem para seus Trabalhos
Deep Learning::Coisas Prontas & Datasets
Deep Learning::Entenda o Babel: Glossário
No Browser:

Hackernoon::TensorFlow.js — Real-Time Object Detection in 10 Lines of Code
TensorFlow.js:: Real-Time Object Detection Demo
TensorFlow.js:: Real-Time Object Detection Demo (Full Code)

## 5.4. Deep Learning: Segmentação Semântica

Site de referência deste Capítulo: 5. Deep Learning::Redes Neurais Convolucionais para Processamento de Imagens

Páginas de Apoio da Unidade:

Deep Learning::Segmentação de Imagens com CNNs
Deep Learning::Ensinando à Rede: Ferramentas de Anotação
Deep Learning::Coisas Prontas & Datasets
Deep Learning::Entenda o Babel: Glossário

## 5.5.Aula de Discussão dos Problemas de Cada um à Luz de uma Solução usando Redes Neurais Convolucionais

Poster Session - Apresentação das Soluções com CNNs