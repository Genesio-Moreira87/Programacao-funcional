# Programaçao Funcional

Antes de começar

Faça login na sua conta da Google. Acesse o **Google Colab** e faça o download do arquivo notebook “Profissão Analista de dados M5 Material de apoio”. 

# Nesta tarefa, iremos praticar 3 exercícios.

Prepare o ambiente

Vamos trabalhar com o arquivo csv com dados de crédito disponível no material de apoio. Execute cada uma das células de código para escrever os arquivos na sua máquina virtual.
Leia o conteúdo do arquivo em uma lista onde cada elemento é um dicionário representando as linhas do arquivo.

# 1º Exercício: Função map

Aplique a função map na lista de empréstimos para extrair os valores da chave

valor_emprestimos na lista valor_emprestimos_lista. Faça também a conversão de str para float

# 2º Exercício: Função filter

Aplique a função filter na lista de valor_emprestimos_lista para filtrar apenas os valores maiores que zero (os valores negativos são erros na base de dados). Salve os valores na lista valor_emprestimos_lista_filtrada.

# 3º Exercício: Função reduce

Com a nossa lista de valores de empréstimo pronta, extraia algumas métricas:

**1ª Parte**: Função reduce para extrair a soma

Aplique a função reduce para somar os elementos da lista valor_emprestimos_lista_filtrada na variavel soma_valor_emprestimos.

**2ª Parte**: Função reduce para extrair a média aritmética

Aplique a função reduce para extrair a média aritmética dos elementos da lista valor_emprestimos_lista_filtrada na variavel media_valor_emprestimos.

Dica: Para calcular o tamanho da lista, isto é a quantidade de elementos, utilize a função len(), dentro do argumento da função coloque a lista valor_emprestimos_lista_filtrada.

**3ª Parte**: Função reduce para extrair o desvio padrão amostral

Aplique a função reduce para extrair a média aritmética dos elementos da lista valor_emprestimos_lista_filtrada na variavel desvio_padrao_valor_emprestimos.

## Autor: Genésio Moreira Coutinho 
- Graduado: Bacharelado em Sistemas de Informação | Pós Graduando:  MBA em Gestão da Qualidade em Tecnologia da Informação |Analista de Dados| 1x Azure - AZ900
- Date Analyst | Cloud Infrastructure | Azure | Analista Cloud | Analista Dados | Infraestrutura Cloud | Python
- Linkedin: https://www.linkedin.com/in/genesio-coutinho-554733124/
- Kaggle:https://www.kaggle.com/genesiomoreira

- Notebook para execução dos códigos Google Collab: https://colab.research.google.com/drive/1Xo0xsMeHfEp1ojsiLO62x5GfwX9Zuz10?usp=sharing
