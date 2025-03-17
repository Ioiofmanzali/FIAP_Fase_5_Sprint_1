# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="./assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# ENTERPRISE CHALLENGE INGREDION - SPRINT 1 
![SPRINY1](https://github.com/Ioiofmanzali/FIAP_Fase_5_Sprint_1/blob/main/assets/sprint1.jpg)

## Grupo 15

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/iolanda-helena-fabbrini-manzali-de-oliveira-14ab8ab0">Iolanda Helena Fabbrini Manzali de Oliveira</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Murilo Carone Nasser</a> 
- <a href="https://www.linkedin.com/in/pedro-eduardo-soares-de-sousa-439552309">Pedro Eduardo Soares de Sousa</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Yago Brendon Iama</a>
- <a href="https://www.linkedin.com/in/jonatasgomes">Jônatas Gomes Alves</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Andre Godoi Chaviato</a>

# ENTREGA 1 IMAGEM

## 📜 Descrição

Para o Entregável 1 será utilizada a platadforma [SATVEG](https://www.satveg.cnptia.embrapa.br) da EMBRAPA exploração do tutorial e das funcionalidades do site e para criacão de um dataset de imagens de satélite da região de Lucas do Rio Verde (MT). 

## 💻 Tecnologias utilizadas

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](#)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)](#)

## 📁 Estrutura de pastas

- **/docs/entrega_1** - Documentação do projeto
- **/src/entrega_1** - Código-fonte e scripts
- **/assets/entrega_1** - Banco de Imagens

## 🔧 Como executar o Projeto
  1. Acesse a Plataforma
  2. Entre no site oficial do [SATVEG](https://www.satveg.cnptia.embrapa.br)
  3. Crie uma conta ou faça o seu login.
  4. Selecione a Região de Interesse
     obs: há 3 formas de de selecionar uma região - utilizando o mapa interativo, inserir coordenadas geográficas ou pelo nome do local;
  5. Escolha o timeline a ser analisado
  6. No painel de controle, selecione um intervalo de tempo para visualizar imagens de diferentes épocas do crescimento da cultura.
  7. Selecione o Tipo de Imagem  utilizando os indices/sensores desejados (NVDI, EVI ou RGB)
  8.  Faça o doewnload ou exporte os dados e as imagens 
      obs: para análise mais detalhada das imagems podems ser utilizados softwares GIS como QGIS ou ArcGIS.
           informaçoes mais detalhadas podem ser encontradas no [Tutorial da SATVEG](https://www.satveg.cnptia.embrapa.br/satveg/pages/home.html) 
      

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.

---
# ENTREGA 2 

## 📜 Descrição

A Entrega 2 consiste na utilização da calculadora da AWS para estimar os custos de uma instância Linux On-Demand (100%), comparando os preços entre as regiões de São Paulo (BR) e Virgínia do Norte (EUA) e identificando a opção mais econômica, considerando que a máquina será responsável por hospedar uma API que recebe dados de sensores e executa um modelo de Machine Learning relacionado à Entrega 1.

## 💻 Tecnologias utilizadas
[![Amazon_AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=flat&logo=amazon-web-services&logoColor=white)](#).

## 📁 Estrutura de pastas

- **/docs/entrega_2** - Documentação do projeto
- **/assets/entrega_2** - Relatórios de Preços Orçados

## 🔧 Como executar o Projeto
  1. Acessar  a AWS Pricing Cauculeto através do link [https://calculator.aws/#/addService]
  2. Selecione as configurações necessárias para as regiões São Paulo (BR) e Virginia do Norte (EUA), conforme a descrição da atividade
     ### Componentes:
     
                 *  2 CPUs
                 *  1 GiB de memória
                 *  Até 5 Gigabit de rede
                 *  50 GB de armazenamento (HD)
     
  3. Salvar dos dados e realizar as devidas análises dos valores 


## 🎥 Demonstração

*[TODO: Adicionar link para vídeo demonstrativo no Youtube]*

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.


---
# IR ALÉM 1 

## 📜 Descrição

O projeto "Sistema de Coleta e Comunicação de Dados Usando ESP32 Integrado ao Wi-Fi" tem como objetivo desenvolver uma solução utilizando um ESP32 para coleta de dados via sensores e comunicação Wi-Fi. Os dados coletados são enviados diretamento a um banco de dados Oracle hospedado na Oracle Cloud. A comunicação é feita via api REST.

## 💻 Tecnologias utilizadas

#### Hardware
![microesp](https://github.com/user-attachments/assets/815e3951-ddec-4284-af49-368e83202b44)
  - **ESP32:** Microcontrolador wi-fi e Bluetooth, ideal para aplicações de IoT.
  - **DHT22:** sensor de temperatura e umidade
  - **LDR:** sensor de luz (resistor-dependente de luz) para medir a intensidade da luz
  - **Jumpers** e protoboard para conexões

#### Software
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![MicroPython](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)
![Oracle Cloud Database 23ai](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
  - **WokWi:** Software online and gratuito para simulação de ESP32.
  - **MicroPython:** Linguagem de programação usada para escrever o código que fará as leituras dos dados dos sensores e mandará para o banco de dados.
  - **API REST:** Método de comunicação utilizado para enviar os dados para o banco Oracle.
  - **JSON:** Formato dos dados enviados ao banco Oracle.
  - **Oracle Cloud Database 23ai:** Banco de dados Oracle hospedado na nuvem.
  - **Oracle ORDS:** Ferramenta disponibilizada pela Oracle Cloud que permite criar e disponibiliar a **API REST**.
  - **Oracle SQL Developer** Ferramenta para acessar o banco de dados Oracle e visualizar/alterar os dados das tabelas.

## 📁 Estrutura de pastas

- **/docs/ir-alem-1** - Documentação do projeto
- **/src/ir-alem-1** - Código-fonte e scripts
- **/assets/ir-alem-1** - Imagens do circuito e diagrama de conexão

## 🔧 Como executar o Projeto
  1. Construir o projeto no WokWi, adicionando os componentes e carregando o código.
  2. Executar o código no WokWi e alterar os valores simulados dos sensores.
  3. Conectar a base de dados Oracle e verificar as linhas da tabela **SENSOR_LEITURAS**.
  4. Também é possível ler os dados gravados através da API REST.

## 🎥 Demonstração

[Link para vídeo demonstrativo no Youtube](https://youtu.be/gSLD32WOulg)

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.

---

<p align="center">
<strong>Projeto desenvolvido para o curso de Inteligência Artificial da FIAP.</strong>
</p>
