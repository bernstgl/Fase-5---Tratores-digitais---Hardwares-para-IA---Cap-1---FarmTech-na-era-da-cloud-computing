
# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Projeto FarmTech Solutions – Previsão de Rendimento Agrícola com Machine Learning

## 👨‍🎓 Integrantes:

<a href="https://www.linkedin.com/company/">Thiago Lima Bernardes</a>

## 👩‍🏫 Professores:

### Tutor(a)

- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>

### Coordenador(a)

- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição


## Entrega 1: 
Projeto de Machine Learning da FarmTech Solutions, desenvolvido para uma fazenda de médio porte que deseja prever o rendimento das suas culturas com base em variáveis meteorológicas e condições de solo.

O objetivo deste projeto é:

- Realizar uma análise exploratória dos dados fornecidos pela fazenda.
- Identificar tendências nos rendimentos das plantações por meio de técnicas de clusterização.
- Detectar cenários discrepantes (outliers).
- Desenvolver cinco modelos preditivos usando algoritmos distintos para prever o rendimento das safras.
O dataset utilizado está disponível no arquivo crop_yield.csv.

## 📁 Estrutura

- **ThiagoBernardes_rm560085_pbl_fase4.ipynb**: Arquivo `.ipynb` com as implementações.
- **Arquivos.zip**: Contém o conjunto de dados utilizado no projeto.
- **README.md**: Arquivo explicativo do projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

1. Clone o repositório em sua máquina local.
2. Certifique-se de ter Python 3.8+ instalado.
3. Para executar o projeto, você precisa ter:

- Python 3.8 ou superior.
- Jupyter Notebook.
   Bibliotecas Python:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

4. Navegue até a pasta `notebooks` e abra os notebooks na ferramenta de sua preferência (Jupyter Notebook ou Google Colab).
5. Siga os passos documentados em cada notebook.

## Estrutura do Notebook

O notebook está dividido nas seguintes seções:
- Introdução e carregamento de dados: Importação de bibliotecas e carregamento inicial do dataset.
- Análise Exploratória: Avaliação estatística inicial, gráficos e matrizes de correlação.
- Clusterização e Outliers: Técnicas de agrupamento para identificar tendências e cenários discrepantes.
- Modelos de Regressão: Construção e avaliação de cinco modelos preditivos diferentes.
- Conclusões: Análise comparativa entre modelos e avaliação crítica dos resultados.

## Entrega 2:

FarmTech Solutions - Implementação da API e Machine Learning na AWS

Este documento detalha a escolha técnica e econômica para a hospedagem da solução de Machine Learning da FarmTech Solutions na AWS, com a finalidade de prever rendimentos agrícolas com base em dados coletados por sensores.

### Especificações Técnicas

A solução desenvolvida demanda os seguintes requisitos mínimos:

Processamento: 2 vCPUs
Memória: 1 GiB RAM
Rede: Até 5 Gigabit
Armazenamento: 50 GiB HD

### Configuração Escolhida
A instância AWS selecionada para atender às necessidades acima é:

Tipo de instância: t3.small
vCPUs: 2
Memória: 2 GiB (acima do mínimo necessário para maior estabilidade)
Rede: Até 5 Gigabit
Volume EBS: gp3 (50 GiB)

### Por que t3.small?

A instância t3.small apresenta uma combinação otimizada de custo e desempenho para aplicações com demanda moderada, oferecendo um equilíbrio entre capacidade computacional e custos reduzidos.

### Estimativa de Custos

Comparação de custos mensais On-Demand entre as regiões AWS São Paulo (sa-east-1) e Virgínia do Norte (us-east-1):

![image](https://github.com/user-attachments/assets/5143fc98-3893-4486-88ec-62ff0fa288af)


### Justificativa da Escolha da Região

A escolha da região Virgínia do Norte (us-east-1) oferece uma economia significativa (~33%) em comparação com São Paulo, mantendo o desempenho necessário para a aplicação, tornando-a uma opção mais econômica para o projeto.

### Vantagens da AWS

- Escalabilidade: Facilidade para ampliar ou reduzir recursos.
- Alta Disponibilidade: Infraestrutura robusta com alta redundância.
- Custo-benefício: Preços competitivos com flexibilidade de contratação.

## Conclusão

A implementação da solução na região Virgínia do Norte na AWS utilizando a instância t3.small e armazenamento EBS de 50 GiB é uma opção eficiente e econômica, atendendo às especificações técnicas e garantindo desempenho satisfatório para a aplicação de Machine Learning da FarmTech Solutions.

## 🗃 Histórico de Lançamentos

- 1.0.0 - 18/03/2025

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

