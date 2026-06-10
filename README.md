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
Here's the translation:

---

### [Web Scraping on COPOM Minutes](https://github.com/sdavibl/Web-Scraping-nas-Atas-do-COPOM) 🔓
> We needed a collection of COPOM texts to verify the shift in direction of monetary policy adopted by the Central Bank following a change in board leadership. The task involved gathering as many meeting minutes as possible from those available online, so I built a web scraper that iterated over all available texts and saved them to a CSV. The result was the ability to statistically verify the differences brought about by the change. Additionally, this text corpus is used in other projects within IBRE.

### [NLP on COPOM Minutes](https://github.com/sdavibl/NLP-em-atas-do-COPOM) 🔓
> I needed to run a robust statistical test to determine whether there had been any meaningful shift in the language of COPOM meeting minutes. The task was to identify a statistical or machine learning approach that could meet this need. I applied NLP and lemmatization to reduce data dimensionality, along with tokenization to transform each lemma into a sparse matrix; the test ultimately used was the Mann-Whitney U test. The result showed a statistically significant difference (p-value < 1%) in certain terms across the minutes.

### [EfficientNetB7](https://github.com/sdavibl/EfficientNetB7-on-Animals10/tree/main) 🔓
> The goal was to run exercises and experiments as part of my learning in Computer Vision (CV). This required choosing a model (pre-trained or otherwise) to understand the underlying principles of CV, data preprocessing, and machine learning. I used EfficientNetB7 on the Animals10 image dataset to train and evaluate the model on separate splits, and documented my observations on the topic. The model achieved an average accuracy of 96%, and I was able to record notes and explanations useful both for my own future work in CV and for others looking to get started in this field.

### Product Classification for Consumers 🔒
> Thousands of data points collected by Fundação Getúlio Vargas (FGV-IBRE) across its price indices must be correctly classified according to their category. Using NLP and automated pipelines rather than purely manual classification — which would be far too time-consuming — I leveraged libraries including spaCy (for lemmatization) and several machine learning models (e.g. GaussianNB) to tokenize product descriptions. The result was extremely satisfying: work that would have taken weeks was reduced to a matter of minutes.

### Clustering to Support Analysts 🔒
> Much of the data received by FGV requires careful attention to the context in which it sits. The task involved handling this large volume of data and finding a way to assess whether it made sense within the existing context. I used libraries such as Isolation Forest and DBSCAN, along with extensive data processing, to assist FGV analysts, and added a friendlier graphical interface using CustomTkinter. The result is a reduction in the natural human bias inherent to the process, along with a meaningful productivity gain. The framework is currently being ported to Streamlit.

### [Victoria 3 Economic Analyzer](https://github.com/sdavibl/victoria3_economic_analyzer) 🔓⏳
> Victoria 3 is a strategy game developed by Paradox, set in the 19th century and functioning almost as an economic simulator. My goal was to analyze how the game computes GDP and run statistical tests to determine how a player can maximize the economy of their chosen country. I built a save-game parser to return the aggregate value of each building in the game and ran tests varying the relevant parameters (building level, number of employees, input costs, etc.). I used pandas and NumPy for data extraction to CSV and frameworks such as Gretl and EViews for robust statistical analysis, and also used Cheat Engine for memory manipulation (e.g. instantly changing a building's tier) to make testing more efficient — with heavy use of regex throughout. The results showed that the number of variables influencing the in-game economy is very large. This is a personal side project.

### [Reinforcement Learning on Atari Pong](https://github.com/sdavibl/Rede-Neural-Atari) 🔓
> The context here was my study and learning of Reinforcement Learning and Deep Learning algorithms, and a desire to build a reusable skeleton for this type of project. I decided to test this knowledge by teaching a machine to play the classic Atari game Pong. The approach used Gymnasium to generate the game environment, Stable Baselines as the RL framework, and PPO as the learning algorithm. The outcome was a (lengthy) training process that ultimately produced an agent capable of easily defeating the game's built-in CPU opponent.

### [Economic and Geospatial Analysis of the Northwest of Rio de Janeiro State using R](https://github.com/sdavibl/Noroeste-Fluminense-com-R) 🔓
> This work was part of a course called "Fluminense Economy" at UERJ, in which my group was responsible for analyzing the economy of the Northwest region of Rio de Janeiro state. My specific contribution was generating charts for better visualization — broken down by municipality — of the region's economic and social indicators. I used R and geospatial visualization techniques; note that not all indicators are included in the published project, as the code was left as a skeleton for future use. Our charts were used in the final presentation — and we received a perfect score.

### [Building a CNN from Scratch to Recognize Vegetables](https://github.com/sdavibl/Vegetable-Recognition/blob/main/Reconhecimento_Vegetais_(Acur%C3%A1cia___95_).ipynb) 🔓
> I wanted to build a CNN from scratch to test my knowledge of CNNs, machine learning, and TensorFlow. This required selecting a dataset and designing a model to build and evaluate. Using TensorFlow, I constructed an architecture from the ground up for vegetable image recognition, achieving 95% accuracy.

### Embeddings and Transformers on Salary Spreadsheets 🔒
> Every month we received a spreadsheet containing salary data and construction material prices compiled by trade unions. Given the volume, processing these spreadsheets and entering the data into the database was extremely time-consuming. The task required building an automated pipeline for classifying and reading the spreadsheet and transforming it into a structure the database could ingest. I used text embedding models (multilingual-e5-small and all-MiniLM-L6-v2) for automatic classification and semantic analysis, then used pandas to transform the data into the required format. The result is that work that previously took days — and was highly labor-intensive — is now completed in under a day, with the collaborator only needing to review the final table produced by the model.
