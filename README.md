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

### [Web Scraping of COPOM Minutes](https://github.com/sdavibl/Web-Scraping-nas-Atas-do-COPOM) 🔓

> We needed a collection of COPOM meeting minutes to assess changes in the monetary policy direction adopted by the Brazilian Central Bank after a change in its board of directors. The objective was to gather as many publicly available minutes as possible. To accomplish this, I developed a web scraping solution that iterated through all available documents and stored them in a CSV file. The resulting dataset made it possible to statistically evaluate differences in policy communication over time. In addition, this corpus is currently used in other projects within IBRE.

### [NLP on COPOM Minutes](https://github.com/sdavibl/NLP-em-atas-do-COPOM) 🔓

> I was tasked with performing a robust statistical analysis to determine whether there were meaningful changes in the language used in COPOM meeting minutes. The challenge was to identify a statistical or machine learning approach capable of addressing this question. I applied NLP techniques, including lemmatization to reduce dimensionality and tokenization to transform lemmas into sparse matrices. The final statistical test used was the Mann-Whitney U test. The results showed statistically significant differences (p-value < 1%) in the frequency of certain terms across different periods of the minutes.

### [EfficientNetB7](https://github.com/sdavibl/EfficientNetB7-on-Animals10/tree/main) 🔓

> This project was developed as part of my studies and experimentation in Computer Vision. The objective was to select a model, either pre-trained or built from scratch, and gain a deeper understanding of computer vision workflows, data preprocessing, and machine learning concepts. I used EfficientNetB7 on the Animals10 dataset to train and evaluate the model using separate datasets. The model achieved an average accuracy of 96%. The project also allowed me to document observations and explanations that are useful both for my own learning process and for others interested in entering the field of computer vision.

### Consumer Product Classification 🔒

> Thousands of records collected by Fundação Getulio Vargas (FGV IBRE) for its economic indexes must be correctly categorized according to their respective product classes. Given the scale of the task, NLP techniques and automation provide a much more efficient solution than manual classification. Using libraries such as SpaCy for lemmatization and machine learning models such as Gaussian Naive Bayes, I tokenized product descriptions and built classification pipelines. The results were highly successful, reducing a process that would normally take weeks to only a few minutes.

### Clustering Framework for Analyst Support 🔒

> Large volumes of data received by FGV require contextual validation to ensure consistency with existing information. The challenge was to process this data and identify anomalies or inconsistencies efficiently. To address this, I used techniques such as Isolation Forest, DBSCAN, and extensive data processing pipelines to support analysts. I also implemented a graphical interface using CustomTkinter to improve usability. The resulting framework helps reduce human bias in the analysis process while increasing productivity. The project is currently being migrated to Streamlit.

### [Victoria 3 Economic Analyzer](https://github.com/sdavibl/victoria3_economic_analyzer) 🔓⏳

> Victoria 3 is a grand strategy game developed by Paradox Interactive, featuring a highly detailed economic simulation set in the 19th century. My goal was to understand how the game calculates GDP and to perform statistical analyses to identify strategies for maximizing economic growth. I developed a save-game analyzer capable of extracting the value generated by each building and testing how variables such as building level, workforce size, and input costs affect economic performance. Pandas and NumPy were used for data extraction and processing, while Gretl and EViews were employed for statistical analysis. I also used Cheat Engine to manipulate game memory and automate experimental scenarios more efficiently. Regex played a major role throughout the data extraction process. The project demonstrated that the number of variables influencing a country's economy is remarkably large. It remains an ongoing personal project.

### [Atari Pong Reinforcement Learning](https://github.com/sdavibl/Rede-Neural-Atari) 🔓

> This project was developed as part of my studies in Reinforcement Learning and Deep Learning. I also wanted to create a reusable foundation for future RL projects. The objective was to train an AI agent capable of playing the Atari game Pong. Using Gymnasium to generate the environment, Stable-Baselines3 as the reinforcement learning framework, and PPO as the learning algorithm, I trained the agent through repeated interactions. The result was a lengthy training process that ultimately produced an agent capable of consistently outperforming the game's CPU opponent.

### [Economic and Geospatial Analysis of Northwestern Rio de Janeiro State with R](https://github.com/sdavibl/Noroeste-Fluminense-com-R) 🔓

> This project was developed for a university course called "Economia Fluminense" at UERJ. My group's responsibility was to conduct an economic analysis of the Northwestern region of Rio de Janeiro State. My contribution focused on creating visualizations and geospatial representations of economic and social indicators at the municipal level. I used R and geospatial analysis tools to generate the visualizations. Not all indicators were included in the public repository, as the available code was intentionally left as a reusable framework for future projects. The resulting visualizations were used in the final presentation, which received the highest possible grade.

### [Building a CNN from Scratch for Vegetable Recognition](https://github.com/sdavibl/Vegetable-Recognition/blob/main/Reconhecimento_Vegetais_%28Acur%C3%A1cia___95_%29.ipynb) 🔓

> I wanted to build a convolutional neural network from scratch to validate and strengthen my understanding of CNNs, machine learning, and TensorFlow. After selecting an appropriate dataset, I designed, trained, and evaluated the model entirely from the ground up. Using TensorFlow, I developed a vegetable recognition model that achieved 95% accuracy.

### Embeddings and Transformers for Salary Spreadsheet Processing 🔒

> Every month, we received spreadsheets containing salary data and construction material prices collected by industry associations. Due to the volume of information, manually processing and entering the data into the database was extremely time-consuming. The challenge was to automate spreadsheet classification, information extraction, and transformation into a format compatible with the database. To accomplish this, I used text embedding models such as multilingual-e5-small and all-MiniLM-L6-v2 for semantic analysis and automatic classification. Pandas was then used to transform and structure the data. As a result, a process that previously took several days and required significant manual effort can now be completed in less than a day, with analysts only needing to review the final output generated by the system.

