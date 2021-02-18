# Teste Técnico SMARKIO
<br>
<p align="center">
  <img width=400 src="https://user-images.githubusercontent.com/56659549/108147693-1bebf100-70ae-11eb-92f3-c4e17b2621b0.png">
</p>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/progresso-100%25-greeb.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/versão-1.0-orange.svg?color=7bbde8&style=for-the-badge">
  <img src="https://img.shields.io/badge/Tamanho-8.2mb-orange.svg?color=7bbde8&style=for-the-badge">
</p>

### Objetivo
Este é um projeto proposto pela empresa para concorrer a vaga como estagiário em Data Science na SMARKIO.

### Descrição
Foi fornecido um Dataset pequeno em formato .xls (2 abas) e um arquivo PDF com alguns esclarecimentos, considerações e cinco perguntas que deveriam ser respondidas utilizando técnicas e conceitos de Data Science e Machine Learning. No final, foi requisitado que os resultados fossem exportados também em PDF para avaliação. Todos os arquivos usados e gerados também foram subidos para este repositório no GitHub.

### Tecnologias
<p>
    <a href="https://www.python.org//">
     <img src="https://img.shields.io/static/v1?label=Python&message=3.8.5&color=7bbde8&style=for-the-badge&logo=Python"/>
    </a><br>
    <a href="https://jupyter.org/">
     <img src="https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=5.6.0&color=7bbde8&style=for-the-badge&logo=Jupyter"/>
    </a><br>
    <a href="https://numpy.org/">
     <img src="https://img.shields.io/static/v1?label=Numpy&message=1.19.4&color=7bbde8&style=for-the-badge&logo=Numpy"/>
    </a><br>
    <a href="https://pandas.pydata.org/">
     <img src="https://img.shields.io/static/v1?label=Pandas&message=1.1.4&color=7bbde8&style=for-the-badge&logo=pandas"/>
    </a><br>
    <a href="https://matplotlib.org/">
     <img src="https://img.shields.io/static/v1?label=Matplotlib&message=3.3.3&color=7bbde8&style=for-the-badge&logo=Semantic-Web"/>
    </a><br>
    <a href="https://seaborn.pydata.org/">
     <img src="https://img.shields.io/static/v1?label=Seaborn&message=0.11.0&color=7bbde8&style=for-the-badge&logo=Sketchfab"/>
    </a><br>
    <a href="https://scikit-learn.org/stable/">
     <img src="https://img.shields.io/static/v1?label=Scikit-Learn&message=0.23.2&color=7bbde8&style=for-the-badge&logo=scikit-learn"/>
    </a>
</p>

### Como executar
Existe uma maneira simples de visualizar o notebook, basta acessar o arquivo **teste_final_smarkio.ipynb** que está junto os demais arquivos. Ele já foi previamente executado e preparado para uma visualização rápida. Caso deseja realmente executar o notebook, existem duas opções, você pode clicar no badge abaixo para acessar o Jupyter Notebook pelo Google Colab <br><br>
<a href="https://colab.research.google.com/drive/1I-EsN_VxSYKBsC35HnlxdUuhp-xRAT5W?usp=sharing">
  <img src="https://img.shields.io/static/v1?label=Google%20Colab&message=Link%20Direto&color=7bbde8&style=for-the-badge&logo=Google-Colab"/>
</a> <br>

No Colab, será necessário você fazer upload do arquivo **teste_smarkio_Lbs.xls**, que está dentro da pasta dados deste repositório. Após baixar o arquivo .xls, inicie a operação de upload clicando no ícone de pasta no canto esquerdo do Colab e clicando na opção de envio de arquivo e então fazer o upload, veja abaixo 
<br>

<img width=500 src="https://user-images.githubusercontent.com/56659549/108376370-b6008600-71e1-11eb-913b-d9ae66272b58.png"/> <br>

Em seguida, no menu, clique em Runtime -> Run all. Simples assim! <br>
**Obs: este colab estará disponível apenas até ser realizada a avaliação, após este evento o link será invalidado.**

_______________________________

Mas você também pode rodar localmente seguindo os procedimentos abaixo: <br><br>
Primeiramente, você deve ter instalado em seu computador o Python e o pip, você pode fazer isso executando as seguintes linhas de comando
```
sudo apt-get update
sudo apt-get install python3
sudo apt-get install python3-pip
```
Também é necessário a instalação do git, então execute
```
sudo apt-get install git
```
Em seguida instale o Jupyter Notebook, o comando é
```
pip3 install jupyter
```
Assim que o Jupyter for instalado, é necessário baixar o repositório em seu computador, então use o seguinte comando
```
git clone https://github.com/Dellonath/teste-smarkio.git
```
Uma pasta com os arquivos deste repositório estarão no mesmo diretório onde o terminal foi aberto. Em seguida, abra o Jupyter Notebook executando, no terminal, a seguinte linha de comando
```
jupyter notebook
```
Com o Jupyter Notebook aberto em seu navegador, busque a pasta onde o repositório foi clonado, você encontrará algo como abaixo
<p align="center">
  <img src="https://user-images.githubusercontent.com/56659549/108369873-cf520400-71da-11eb-9ea5-15073e928cfc.png">
</p>

Clique então em **teste_final_smarkio.ipynb**, uma nova janela será aberta com o Jupyter Notebook aberto. No menu do Jupyter Notebook, selecione Kernel e clique em Restart & Run All, veja abaixo

<p align="center">
  <img src="https://user-images.githubusercontent.com/56659549/108152652-46db4280-70b8-11eb-98a9-be6b3437f84d.png">
</p>

**Obs: a primeira célula é responsável apenas por instalar as ferramentas necessárias, caso já possua elas, pode ignorá-la, caso não, verifique a versão pip instalada em seu computador, dependendo da versão é necessário trocar as palavras pip na primeira célula por pip3 e refaça o procedimento descrito na imagem anterior.**

Aguarde a finalização das execuções, talvez demore alguns segundos.
