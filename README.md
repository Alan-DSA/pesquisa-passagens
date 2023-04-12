# pesquisa-passagens
Este projeto consiste em um script Python que utiliza a biblioteca Selenium WebDriver para automatizar a busca de passagens aéreas no site Melhores Destinos


## Stack utilizada

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


## 💻 Pré-requisitos

Pré-requisitos
Antes de executar o script, você deve ter o Python instalado em seu computador, bem como as seguintes bibliotecas:

Selenium WebDriver
undetected_chromedriver
BeautifulSoup
Você também deve ter o Google Chrome instalado em seu computador.


## Como funciona
O script acessa o site Melhores Destinos, insere informações de busca (origem, destino e datas), clica no botão de pesquisa e extrai o preço das passagens aéreas disponíveis na primeira janela de resultados.

O código utiliza a biblioteca Beautiful Soup para analisar o HTML da página e encontrar o preço das passagens aéreas disponíveis.

## Como usar
Para executar o script, abra o arquivo Pesquisa_passagem.py em seu editor de código Python e execute-o.

Ao ser executado, o script abrirá o site Melhores Destinos, inserirá as informações de busca, extrairá o preço das passagens aéreas disponíveis e imprimirá na tela.
