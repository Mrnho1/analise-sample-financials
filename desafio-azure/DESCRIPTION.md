# Descrição do Projeto.

## Criação de uma instância na Azure.
<img width="1297" height="106" alt="Captura de tela 2025-12-29 154817" src="https://github.com/user-attachments/assets/884d9a62-ad57-405c-91dc-c82839ea3773" />

## Disponibilizando banco de dados no Github.
- [Criando tabelas de Company](script_bd_company.sq)
- [Inserindo dados das tabelas](insercao_de_dados_e_queries_sql.sql)

## Conexão Azure e Power BI.
- powerbiservice.database.windows.net

## Iniciar Tratamento dos Dados.
- Realizada a verificação dos cabeçalhos e seus tipos de dados.
- Valores monetários modificados.
- Verificado se existe valores nulos.
- Existe um colaborador sem gerente que no caso seria o próprio gerente.
- Todos os departamentos tem um gerente.
- Separando endereço para virar colunas mais simples.
- Mesclar consultas employee e departament.
- Elimine Colunas desnecessárias.
- Realizada e mescla de tabelas para ter o nome de gerentes.
- Mescla de nomes e sobrenomes.
- Mesclar nome e localização de departamento.
- O caso abaixo seria uma relação 1:N e necessário manter a tabela base mantida.
<img width="1046" height="414" alt="image" src="https://github.com/user-attachments/assets/5695f8c7-857d-40c5-8c45-efb4fa3650dc" />
- Agrupando dados para saber quantos colaboradores tem por gerente.
- <img width="1041" height="609" alt="image" src="https://github.com/user-attachments/assets/a98282a2-6a67-4c01-877d-af627e65adfc" />
