***Relatório sobre Tarefas de Processamento de Imagem***

Tendo em vista os possíveis processamentos de imagem e a aplicação do conteúdo discutido nesse relatório com o projeto a ser desenvolvido no presente módulo de visão computacional com imagens de satélite, a escolha das tarefas envolvou os processamentos mais úteis. Por isso, as seguintes tarefas foram escolhidas:     

**Tarefas Selecionadas:**

1. Segmentação de Imagem
2. Detecção de Borda e Contorno


1) Segmentação de Imagem:
   
- A segmentação de imagem é o processo de dividir uma imagem em partes, em, como sugere o nome, segmentos. A divisão pode ser realizada com base em atributos da imagem como cor, intensidade, textura ou bordas, em que regiões que possuam diferenças na característica em questão são separadas. Um exemplo de segmentação é a segmentação por limiar, em que os pixels da imagem são atribuídos a diferentes segmentos com base em um valor de limiar. A segmentação de imagem é utilizada em áreas como medicina, agricultura, setor automotivo e robótica, como detalhado a seguir.

- Possíveis Aplicações:

  - **Medicina:** utilizada na identificação e análise de imagens médicas, como a identificação de órgãos em tomografias, ou tumores em ressonâncias.
  - **Agricultura:** segmentação de culturas ou áreas agricultáveis em imagens de campo para monitoramento de crescimento e ou definição de empréstimos ao agricultor.
  - **Robótica:** localização e reconhecimento de objetos para navegação autônoma de robôs.
  
- Produtos Comerciais Relacionados:

  - **MATLAB Image Processing Toolbox:** oferece uma variedade de funções para segmentação de imagem, incluindo técnicas de limiarização e segmentação por região. [Documentação vista nesse link](https://www.mathworks.com/help/images/image-segmentation.html).
  - **OpenCV:** é uma biblioteca de visão computacional e processamento de imagem de código aberto que fornece ferramentas para segmentação de imagem usando métodos como limiarização adaptativa e segmentação baseada em região. [Documentação vista nesse link](https://docs.opencv.org/4.x/d3/db4/tutorial_py_watershed.html)
   
- Segmentos de Mercado dos Produtos Comerciais Relacionados:
  
  - Os produtos explicitados acima atendem a uma ampla gama de setores, incluindo medicina, agricultura, setor automotivo, automação industrial e pesquisa acadêmica.

- Teste do OpenCV:

  - A documentação do teste pode ser encontrada no [seguinte Colab](https://colab.research.google.com/drive/1AjfxUBUgbbRi1xOviNvK4-cGVWeuKdD8?usp=sharing)

2) Detecção de Borda e Contorno:
   
- A detecção de borda e contorno refere-se à identificação das bordas ou contornos dos objetos em uma imagem. Isso é fundamental para análises de forma, reconhecimento de objetos e segmentação de imagem, assim como o problema de delimitar terrenos produtivos com base em imagens de satélites. Existem várias técnicas para detecção de borda, incluindo o operador de Sobel, o operador de Canny e o operador de Laplaciano da gaussiana (LoG).

- Possíveis Aplicações: 

  - **Reconhecimento de Objetos:** identificação e classificação de objetos com base em suas bordas, como a distinção de vários objetos em uma imagem a partir de suas bordas.
  - **Visão Industrial:** inspeção de qualidade em linhas de produção para detectar defeitos em peças cujas delimitações não correspondam ao esperado.
  - **Biometria:** extração de características para reconhecimento de íris ou impressão digital.
  
- Produtos Comerciais Relacionados:

  - **MATLAB Image Processing Toolbox:** oferece funções para detecção de bordas usando operadores como Sobel e Canny. [Documentação vista nesse link](https://www.mathworks.com/help/images/ref/edge3.html?searchHighlight=canny&s_tid=srchtitle_support_results_1_canny).
  - **OpenCV:** fornece métodos para detecção de bordas, incluindo o algoritmo de Canny e o detector de contornos. [Documentação vista nesse link](https://docs.opencv.org/4.x/dd/d49/tutorial_py_contour_features.html).
  
- Segmentos de Mercado dos Produtos Comerciais Relacionados:
  
  - Os produtos acima são utilizados em uma variedade de setores, incluindo o setor automotivo, eletrônico, medicina e pesquisa acadêmica.

- Teste do OpenCV:

  - A documentação do teste pode ser encontrada no [seguinte Colab](https://colab.research.google.com/drive/1MN4yGN4MC4w5OKiwfc5WDzAZIhFLAwCX?usp=sharing)
