# Visualization of the Analysis of Deputies' Speeches from the Chamber of Deputies (Brazil) using Artificial Inteligence: Word Embeddings, word2vec

**Renato Profeta**, Guitars.AI, Technische Universität Ilmenau <br>
Homepage: <a href="http://www.rptecnologias.com/" target="_blank">http://www.rptecnologias.com/</a><br>
Instagram: <a href="https://www.instagram.com/guitars.ai/" target="_blank">https://www.instagram.com/guitars.ai/</a><br>
Twitter: <a href="https://twitter.com/guitars_ai" target="_blank">https://twitter.com/guitars_ai</a><br>
Facebook: <a href="https://www.facebook.com/GuitarsAI/" target="_blank">https://www.facebook.com/GuitarsAI/</a><br>
Linkedin: <a href="https://www.linkedin.com/in/renato-profeta-6b678831/" target="_blank">https://www.linkedin.com/in/renato-profeta-6b678831/</a><br>
Youtube: <a href="https://www.youtube.com/channel/UCyAyQAu_PTX5h1Ni4q0ShHQ" target="_blank">https://www.youtube.com/channel/UCyAyQAu_PTX5h1Ni4q0ShHQ</a><br>

## Instructions
To correctly launch the the application with mybinder I recommend to watch the instructional videos available at Youtube. Link below. <br>
Para iniciar o aplicativo utilizando mybinder corretamente é recomendável assistir aos videos de instrução disponíveis no Youtube. Link abaixo.<br>

## Youtube Playlist

<a href="https://www.youtube.com/playlist?list=PL6QnpHKwdPYjrh1LzZSa8Lo8U36h5_uTl
" target="_blank">https://www.youtube.com/playlist?list=PL6QnpHKwdPYjrh1LzZSa8Lo8U36h5_uTl
</a><br>

## MyBinder

Launch Binder to Interact with this notebook in a live environment in the cloud:
<a href="https://mybinder.org/v2/gh/GuitarsAI/AI_DeputiesSpeeches/master?filepath=AI_SpeechesDeputies.ipynb" target="_blank"><img src="https://mybinder.org/badge.svg">
</a>

## Requirements:
For the requirements for this project to run, please check the following files at the 'binder' folder:
  - requirements.txt
  - apt.txt
  - postBuild
  
## Data Collection:
<ul>
<li>Webscraping: Selenium Pyton - <a href="https://selenium-python.readthedocs.io/" target="_blank">https://selenium-python.readthedocs.io/
</a></li>
<li>Camara dos Deputados Website: <a href="https://www.camara.leg.br/internet/sitaqweb/pesquisaDiscursos.asp " target="_blank">https://www.camara.leg.br/internet/sitaqweb/pesquisaDiscursos.asp 
</a>
  <dl>
<dt>Deputado Miro Teixeira: <a href="https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=miro+teixeira&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar" target="_blank">https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=miro+teixeira&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar 
</a></dt>
    <dd>- Number of words: 618919 </dd>
<dt>Deputado Jair Bolsonaro: <a href="https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=jair+bolsonaro&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar " target="_blank">https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=jair+bolsonaro&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar 
</a></dt>
    <dd>- Number of words: 466203 </dd>
<dt>Deputado Simão Sessim: <a href="https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=sim%C3%A3o+sessim&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar" target="_blank">https://www.camara.leg.br/internet/sitaqweb/resultadoPesquisaDiscursos.asp?txOrador=sim%C3%A3o+sessim&txPartido=&txUF=&dtInicio=&dtFim=&txTexto=&txSumario=&basePesq=plenario&CampoOrdenacao=dtSessao&PageSize=50&TipoOrdenacao=DESC&btnPesq=Pesquisar
</a> </dt>
    <dd>- Number of words: 719875 </dd>
    </dl>
    </li>
</ul>

### Pre-Processing
Basic Pre-Processing: Stop-words, tokenization, lowercasing, removing special characteres, etc. NOT A FULL PRE-PROCESSING of the speeches.<br>
Natural Language Toolkit: <a href="https://www.nltk.org/" target="_blank">https://www.nltk.org/
</a><br>

## Analysis Methods
Gensim word2vec: <a href="https://radimrehurek.com/gensim/models/word2vec.html" target="_blank">https://radimrehurek.com/gensim/models/word2vec.html 
</a><br> 

#### Model Parameters
Word Vectors Dimensionality: 500 <br>
Minimum Word Count Threshold: 10 <br>
Context Window Length: 25 <br>

## Visualization Tool
Google's Tensorboard: <a href="https://www.tensorflow.org/guide/summaries_and_tensorboard" target="_blank">https://www.tensorflow.org/guide/summaries_and_tensorboard
</a> <br>

## Guitars.AI

<p align="left">
<img src="./img/businesscard.jpg" width="500px" alt="Business Card" align="left" >
</p>
<br>

