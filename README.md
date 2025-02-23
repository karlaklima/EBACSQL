## SQL Aplicado à Análise de Dados de Crédito 
### Projeto de Conclusão do Curso "SQL para Análise de Dados" – EBAC

### Descrição dos Dados
Os dados contêm informações sobre os clientes de um banco, incluindo as seguintes colunas:

- idade = idade do cliente
- sexo = sexo do cliente (F ou M)
- dependentes = número de dependentes do cliente
- escolaridade = nível de escolaridade do cliente
- salario_anual = faixa salarial do cliente
- tipo_cartao = tipo de cartao do cliente
- qtd_produtos = quantidade de produtos comprados nos últimos 12 meses
- iteracoes_12m = quantidade de iterações/transacoes nos ultimos 12 meses
- meses_inativo_12m = quantidade de meses que o cliente ficou inativo
- limite_credito = limite de credito do cliente
- valor_transacoes_12m = valor das transações dos ultimos 12 meses
- qtd_transacoes_12m = quantidade de transacoes dos ultimos 12 meses

##### Esses dados são gerados para simular cenários em análises de dados e não representam informações reais.

## Exploração de dados:
A primeira etapa da análise consiste em entender as informações presentes na base de dados. Para isso, são feitas as seguintes verificações:

- Tamanho da Base de Dados e Estrutura;
- Qualidade dos Dados.

![image](https://github.com/user-attachments/assets/17f351ca-ffb2-497b-944f-a248a769235f)

- Tipos de Dados;

![image](https://github.com/user-attachments/assets/66b138fc-f35f-44ec-8c15-b862f5a9032a)

#### Após garantir a consistência da tabela e dos dados, realiza-se a análise estatística e de distribuição alinhada aos objetivos de negócios.

# Conclusões Analíticas com Base nos Perfis de Clientes

- Maior concentração de clientes no sexo masculino: 

 ![image](https://github.com/user-attachments/assets/b39d04fc-67f9-4932-8a55-9234ee18cf1c)

Perfil Educacional dos Clientes por Cluster

- **Cluster 1 (Nível Alto):** 1.045 clientes
- **Cluster 2 (Escolaridade Intermediária):** 806 clientes
- **Cluster 3 (Baixa Escolaridade):** 367 clientes
- **Cluster 4 (N/A):** 346 clientes

![image](https://github.com/user-attachments/assets/4ecb3edf-7430-4eee-908b-d185f997a240)

- A maior parte dos clientes está concentrada nas faixas salariais menos que $40K

![image](https://github.com/user-attachments/assets/bcbbef53-d0e0-4726-887d-39b506485a0c)

> Durante a análise, foi identificado um volume considerável na categoria "N/A", o que pode indicar uma área de atenção. É importante garantir que os dados sejam coletados corretamente ou que os clientes recebam informações mais claras sobre como preencher essas informações.

- Não há variação significativa nos limites de crédito entre escolaridade, tipos de cartão ou sexo.

![image](https://github.com/user-attachments/assets/b401337a-5d38-4d1e-bd69-d6eaf9f0176f)

> O maior limite é concedido a um homem sem educação formal. Além disso, o tipo de cartão não parece estar relacionado com a escolaridade e limite de crédito. 

- As mulheres apresentaram maior valor e média de gastos, ligeiramente superior ao dos homens;

![image](https://github.com/user-attachments/assets/8932e7d1-e3c5-4889-aacb-856342df8b0b)

# Resumo de outros pontos importantes que foram observados:

- Os clientes com limites de crédito mais altos são, em sua maioria, homens.
- As mulheres predominam entre os clientes com limites mais baixos.
- Não há clientes com cartão platinum entre os de menores limites.
- A faixa salarial tem uma relação direta com o limite de crédito.
- Não há clientes do sexo feminino com salário anual superior a 60K.





