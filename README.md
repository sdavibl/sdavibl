<h1 align="center">Hi 👋, I'm Salomão Davi</h1>

<div align="center"><img width="1024" height="256" alt="image" src="https://github.com/user-attachments/assets/00eedcf6-9012-4ddb-8d45-f071416a3ca6" />
</div>

<p align="center">
<a href="https://www.linkedin.com/in/salomaodavi/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
  <a href="https://www.kaggle.com/sdavibl">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/>
</a>
</p>

<h3 align="center">I'm an Economics undergraduate with experience in Python, R and VBA, as well as data analysis, storytelling, machine learning, artificial intelligence, LLM, Embeddings and RAG. I'm passionate about programming, data science, artificial intelligence and economics (and soccer).</h3>

- 🌱 I’m currently learning **Java and C**

- 💬 Ask me about **Neural Networks, Artificial Intelligencem Data Science and Economics (specially, Monetary Policy)**

- 📄 Know about my experiences [here](https://www.linkedin.com/in/salomaodavi/)

## Languages and Tools

### Languages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![AssemblyScript](https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)

### Frameworks
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-6950EF?style=for-the-badge&logo=qwen&logoColor=white)
![LangChain](https://img.shields.io/badge/langchain-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white)

### Platforms
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Snowflake](https://img.shields.io/badge/snowflake-%2329B5E8.svg?style=for-the-badge&logo=snowflake&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

## 📚 Projects

### [Web Scraping em atas do COPOM](https://github.com/sdavibl/Web-Scraping-nas-Atas-do-COPOM) 🔓
> Precisávamos de uma coleção de textos do COPOM para verificar a mudança de direção na política adotada pelo Banco Central após a mudança de diretoria. A tarefa consistia em pegar o máximo de textos das atas disponíveis online, para isso, fiz um WebScraping que iterava sobre todos os textos disponíveis online e os guardava em um CSV. O resultado foi de ser possível verificar estatisticamente a diferença nas mudanças. Além disso, esse conjunto de textos é usado em outros projetos dentro do IBRE.

### [NLP em atas do COPOM](https://github.com/sdavibl/NLP-em-atas-do-COPOM) 🔓
> Precisei realizar um teste estatístico robusto para verificar se havia alguma alteração nos textos das atas do COPOM. A tarefa consistia em descobrir algum teste estatístico ou de machine learning que supria essa demanda. A partir daí, usei NLP e lemmetização para reduzir a dimensionalidade dos dados, assim como tokenização para transfomar cada lemma_ em uma matriz esparsa, no fim, o teste usado foi o U de Mann-Whitney. Como resultado, foi possível ver que há diferença estatística signifativa (p-valor < 1%) entre alguns termos dentro das atas.

### [EfficienteNetB7](https://github.com/sdavibl/EfficientNetB7-on-Animals10/tree/main) 🔓
> A situação consistia em realizar exercícios e experimentos com o meu aprendizado em Computação Visual (CV). Para isso, era necessário escolher algum modelo (pré-treinado ou não) para entender os princípios e como funciona o processo de CV, pré-processamento de dados, e machine learning. Para isso, usei o EfficienteNetB7, no conjunto de imagens Animals10, a fim de que eu pudesse treinar e testar o modelo, em datasets separados, e discutir minhas observações acerca desse tema. Como resultado, o modelo obteve uma acurácia média de 96%, e eu fui capaz de anotar observações e explicações que são úteis tanto para mim no processo de uso de CV, assim como para outros curiosos que desejam ingressar nesse mundo.

### Classificação de produtos aos consumidores 🔒
> Milhares de dados coletados pela Fundação Getúlio Vargas (FGV-Ibre) em seus índices devem ser corretamente classificados de acordo com a categoria que pertencem. Para isso, é eficiente que seja feito o uso de NLP e robôs, ao invés de puramente uma classificação humana que demandaria tempo. Através de bibliotecas como a já citada Spacy (lemmetização) e diversos modelos de Machine Learning (GaussianNB, por exemplo) tokenizei as descrições dos produtos. O resultado foi extremametne satisfatório, capaz de reduzir um trabalho que demandaria semanas para alguns minutos.

### Clusterização para auxílio de analistas 🔒
> Muitos dados recebidos pela FGV necessitam de atenção quanto ao contexto que estão inseridos. A tarefa consiste em receber esse grande volume de dados e pensar em alguma maneira de analisar se eles fazendo sentido no contexto existente. Para isso, utilizei algumas bibliotecas como IsolationForest ou DBSCAN e tratamento massivo de dados para auxiliar os analistas da FGV, além disso, utilizei CustomTkinter para adicionar interface gráfica mais amigável ao framework. Como resultado, é capaz de amenizar o viés humano, natural do processo, assim como permitir uma maior produtividade. No processo atual, esse framework está sendo codificado para o Streamlit

### [Analisador Econômico do Victoria 3](https://github.com/sdavibl/victoria3_economic_analyzer) 🔓⏳
> Victoria 3 é um jogo de estratégia desenvolvido pela Paradox, ele é ambientado no século XIX e funciona quase como um simulador de economia. Minha tarefa era basicamente analisar de que forma o jogo computa o PIB e em realizar testes estatísticos para ver de quê forma o usuário pode maximizar a economia do país escolhido, além disso. Para isso, criei um analisador do savegame para retornar o valor agregado de cada uma das construções no jogo e realizar testes mudando variáveis envolvidas a ela (nível da construção, número de funcionários nela, custo dos insumos, etc...), utilizei bilbiotecas Pandas e Numpy para extração dos dados em CSV, e frameworks como gretl e Eviews para análise estatística robusta, também utilizei Cheat Engine para manipulação da memória do jogo (como alterar instantaneamente o patamar da construção) para que o teste fosse feito de maneira mais eficiente, o uso de Regex nesse processo foi massivo. O resultado demonstrou que o número de variáveis que influenciam na economia do "país" é muito grande, é um projeto que tenho em meu tempo livre.

### [Reinforcement Learning em Pong do Atari](https://github.com/sdavibl/Rede-Neural-Atari) 🔓
> O contexto se resume em meu aprendizado e estudo de algoritmos de Reinforcement Learning, assim como de Deep Learning, além disso, gostaria de ter um esqueleto para esse tema caso me fosse necessário. Para isso, pensei em testar esses conhecimentos para fazer a máquina aprender a jogar um simples jogo de Atari, Pong. A tarefa consistiu em usar o gymnasium para gerar o ambiente do jogo, uso de StableBaselines como modelo de Reinforcement Learning e do PPO como algoritmo de aprendizagem. O resultado foi um (longo) processo de aprendizado da máquina, mas capaz de golear com facilidade a CPU do jogo.

### [Análise de indicadores econômicos e geoespaciais do Noroeste Fluminense com R](https://github.com/sdavibl/Noroeste-Fluminense-com-R) 🔓
> Esse trabalho está inserido no contexto de uma matéria "Economia Fluminense" na UERJ, em que meu grupo foi responsável para analisar economicamente o Noroeste Fluminense. Minha tarefa se resumia em gerar gráficos para melhor visualização, por municípios, de indicadores econômicos e sociais da região. Para isso, utilizei R e visualização geoespacial, vale lembrar que nem todos os indicadores estão inclusos no projeto disponível, deixei o código apenas como esqueleto para uso futuro. O resultado foi que meus gráficos foram usados na apresentação (ganhamos 10, inclusive).

### [Criando um modelo de CNN do 0 para reconhecer vegetais](https://github.com/sdavibl/Vegetable-Recognition/blob/main/Reconhecimento_Vegetais_(Acur%C3%A1cia___95_).ipynb) 🔓
> Estava interessado em criar um modelo de CNN do 0 para testar meus conhecimentos de CNN, Machine Learning e Tensorflow. Para isso, era necessário escolher uma base de dados e um modelo para construir e testar meus conhecimentos. Sendo assim, usei o Tensorflow e criei um modelo do 0 para reconhecimento de vegetais, atingindo acurácia de 95%.




