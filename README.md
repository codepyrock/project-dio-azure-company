# project-dio-azure-company
Criação de uma instância na Azure e de um banco de dados no Workbench; e integração do Power BI com MySQL na Azure a fim de processar os dados no Power Query. 
- Bootcamp: Ciência de dados com Python.
- Instituição: DIO.
- Instrutora: Juliana Mascarenhas.

Para a confecção do relatório, algumas atividades foram desenvolvidas cuja ordem está abaixo discriminada:

1. Criei uma instância na Azure para MySQL
![image](https://github.com/codepyrock/project-dio-azure-company/assets/115929030/17cb0b53-a8a5-44ad-959c-a8703850a6b7)
3. Criei um banco de dados no Workbench com base em scripts fornecidos pela instrutora da DIO
4. Integrei o Power BI com MySQL no Azure
![image](https://github.com/codepyrock/project-dio-azure-company/assets/115929030/b5ae6b0a-9f55-4f23-9db5-65dd2f7c806f)
6. Analisei a base de dados a fim de identificar valores discrepantes, nulos e redundantes e situações que pudessem comprometer a compreensão e utilidade do relatório.
7. Confecção do relatório

## Desafios encontrados

1. Conectar o Power BI com a Azure, pois ao baixar a versão mais atual do conector disponível, não conseguia estabelecer a conexão. Após algumas pesquisas, fui orientado a baixar outras versões até encontrar a mais compatível com o Power BI.
2. Após finalmente conseguir estabelecer a conexão, deparei-me com outro problema: as tabelas employee e departament estavam sem registros. Então após carregar, atualizei os dados e os mesmos foram carregados.

## Respondendo questionamentos do desafio

### Passo a passo da transformação realizada no Power Query
1. Substitui o valor null por um dos chefes de departamento
2. Alterei o tipo de dado da coluna 'salary'
3. Juntei colunas FName e Lname
4. Mesclei as tabelas a fim de identificar: quais empregados são gerentes de departamentos; quais empregados são managers; colaboradores por departamento; manager de cada colaborador; localização por departamento
5. Agrupei dados a fim de identificar quantos colaboradores existem por gerente

### Diferenças entre 'acrescentar' e 'mesclar' no Power Query:
- Acrescentar: combina tabelas ou colunas juntando os registros / linhas ao total
- Mesclar: combina tabelas e o resultado final apresenta uma junção de colunas segundo critérios de correspondência

  

   
