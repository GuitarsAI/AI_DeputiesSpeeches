# Speech Analysis of Deputies from the Chamber of Deputies (Brazil) using Artificial Inteligence: Word Embeddings, word2vec

**Renato Profeta**, Guitars.AI, Technische Universität Ilmenau <br>
Homepage: [http://www.rptecnologias.com/](http://www.rptecnologias.com/) <br>
Instagram: https://www.instagram.com/guitars.ai/ <br>
Twitter: https://twitter.com/guitars_ai <br>
Facebook: https://www.facebook.com/GuitarsAI/ <br>
Linkedin: https://www.linkedin.com/in/renato-profeta-6b678831/ <br>
Youtube: https://www.youtube.com/channel/UCyAyQAu_PTX5h1Ni4q0ShHQ

# Youtube Video

https://www.youtube.com/watch?v=8yunclUyeLY&list=PL6QnpHKwdPYgPAUH89aQN8uJl6QOvL9Nz

# Requirements:
For the requirements for this project to run, please check the following files at the 'binder' folder:
  - requirements.txt
  - apt.txt
  - postBuild
  
# Data Collection:
Webscraping: Selenium Pythin <br>
Official Website - Camara dos Deputados: https://www.camara.leg.br/internet/sitaqweb/pesquisaDiscursos.asp <br>
Deputado Miro Teixeira: https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=miro+teixeira&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar
Deputado Jair Bolsonaro: https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=jair+bolsonaro&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar <br>
Deputado Simão Sessim: https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=sim%C3%A3o+sessim&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar <br>

# Pre-Processing
Natural Language Toolkit: https://www.nltk.org/ <br>

# Analysis Methods
Gensim word2vec: https://radimrehurek.com/gensim/models/word2vec.html <br> 

# Model Parameters
Word Vectors Dimensionality: 500 <br>
Minimum Word Count Threshold: 10 <br>
Context Window Length: 25 <br>

# Visualization Tool
Google Tensorboard: https://www.tensorflow.org/guide/summaries_and_tensorboard <br>

# MyBinder

Launch Binder to Interact with this notebook in a live environment in the cloud:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/GuitarsAI/BasicAutoTranscriptionRepo/master)

# Guitars.AI

<p align="left">
<img src="./img/businesscard.jpg" width="500px" alt="Business Card" align="left" >
</p>
<br>

[www.rptecnologias.com](http://www.rptecnologias.com)
<br>
guitars.ai@rptecnologias.com
