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

### [Web Scraping on COPOM Minutes](https://github.com/sdavibl/Web-Scraping-nas-Atas-do-COPOM) 🔓
> The Central Bank of Brazil's monetary policy direction shifted following a change in board leadership, and we needed a way to verify this statistically. I built a web scraper that collected all publicly available COPOM meeting minutes and stored them in a CSV file. The corpus was later reused in other projects within IBRE, and the results confirmed a statistically significant difference in language across the two periods.

### [NLP on COPOM Minutes](https://github.com/sdavibl/NLP-em-atas-do-COPOM) 🔓
> Building on the scraped corpus, the next challenge was finding a rigorous statistical method to detect shifts in the minutes' language. I applied lemmatization and tokenization to reduce dimensionality and convert each lemma into a sparse matrix, then ran a Mann-Whitney U test on the resulting data. The test found a statistically significant difference (p-value below 1%) in the frequency of several key terms across the two board periods.

### [EfficientNetB7](https://github.com/sdavibl/EfficientNetB7-on-Animals10/tree/main) 🔓
> As part of my studies in Computer Vision, I needed a hands-on project to understand data preprocessing, model training, and evaluation in practice. I fine-tuned EfficientNetB7 on the Animals10 dataset, training and testing on separate splits while documenting observations throughout the process. The model reached 96% average accuracy, and the notes I recorded serve as a practical reference for anyone starting out in CV.

### Product Classification for Consumers 🔒
> FGV-IBRE collects thousands of data points across its price indices, and classifying each one manually by category was taking far too long. I tokenized product descriptions using spaCy for lemmatization and trained several machine learning models, including GaussianNB, to automate the classification. Work that previously took weeks was reduced to a matter of minutes.

### Clustering to Support Analysts 🔒
> Analysts at FGV needed a way to quickly assess whether large incoming data batches made sense within their existing context, without relying purely on manual review. I built a pipeline using Isolation Forest and DBSCAN for anomaly detection, wrapped in a CustomTkinter GUI to make the tool accessible to non-technical users. The result reduced human bias in the review process and significantly increased analyst productivity. The framework is currently being ported to Streamlit.

### [Victoria 3 Economic Analyzer](https://github.com/sdavibl/victoria3_economic_analyzer) 🔓⏳
> Victoria 3 functions almost like an economic simulator, and I wanted to understand how the game actually computes GDP and whether there was an optimal strategy for maximizing a country's economy. I built a save-game parser to extract the aggregate value of each building type, then tested variations across parameters such as building level, workforce size, and input costs, using Gretl and EViews for statistical analysis and Cheat Engine for efficient in-game manipulation. The results revealed how many interdependent variables influence the in-game economy, and the project is still ongoing in my spare time.

### [Reinforcement Learning on Atari Pong](https://github.com/sdavibl/Rede-Neural-Atari) 🔓
> I wanted a concrete project to consolidate my studies in Reinforcement Learning and Deep Learning, and to have a reusable base for future work in this area. Using Gymnasium for the game environment, Stable Baselines as the RL framework, and PPO as the learning algorithm, I trained an agent to play Atari Pong from scratch. After a lengthy training process, the agent learned to consistently beat the game's built-in CPU opponent.

### [Economic and Geospatial Analysis of Northwest Rio de Janeiro State with R](https://github.com/sdavibl/Noroeste-Fluminense-com-R) 🔓
> For a university course on the economy of Rio de Janeiro state, my group was assigned to analyze the Northwest region and present findings to the class. I used R to produce municipality-level geospatial visualizations of key economic and social indicators. The charts were featured in our final presentation, which received a perfect score.

### [Building a CNN from Scratch for Vegetable Recognition](https://github.com/sdavibl/Vegetable-Recognition/blob/main/Reconhecimento_Vegetais_(Acur%C3%A1cia___95_).ipynb) 🔓
> I wanted to test my understanding of CNNs and TensorFlow by building a model entirely from scratch rather than relying on a pre-trained architecture. I designed and trained a CNN on a vegetable image dataset using TensorFlow, evaluating it on a held-out test split. The model reached 95% accuracy.

### Embeddings and Transformers on Salary Spreadsheets 🔒
> Every month, FGV received spreadsheets of salary and construction material price data compiled by trade unions, and manually processing and entering this data into the database was taking days. I built a pipeline using multilingual-e5-small and all-MiniLM-L6-v2 embedding models for semantic classification, combined with pandas to transform the output into a database-ready structure. The process now runs in under a day, with the analyst only needing to review the final table before upload.
