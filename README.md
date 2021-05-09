# [Project :NIPS-conference-Machine-Learning-Trends](https://nbviewer.jupyter.org/github/MMallah/NIPS-conference-Machine-Learning-Trends/blob/main/notebook.ipynb)

![](https://github.com/MMallah/Mallah_Portfolio/blob/main/images/ML%20recurring%20topics.png)

<p>The NIPS conference (Neural Information Processing Systems) is one of the most prestigious yearly events in the machine learning community. At each NIPS conference, a large number of research papers are published. These NIPS papers are stored in <code>datasets/papers.csv</code>. The dataset contains information on the different NIPS papers that were published from 1987 until 2017 <strong>(30 years!)</strong>. These papers discuss a wide variety of topics in machine learning, from neural networks to optimization methods and many more.

<p>First, we will explore the CSV file to determine what type of data we can use for the analysis and how it is structured. A research paper typically consists of a title, an abstract and the main text. Other data such as figures and tables were not extracted from the PDF files. Each paper discusses a novel technique or improvement. In this analysis, <strong>we will focus on analyzing</strong> these papers with <code>natural language processing</code> methods.</p>

* Read data and <code>preprocess for text data analysis</code>.
* Perform <code>word cloud visualization</code> to verify and check the data.
* Using <code>latent Dirichlet allocation (LDA)</code> on transformed text data for <code>topic detection</code>.
