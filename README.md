<h1>Implementação de Data Warehouse com Pentaho</h1>

## [ ⚠️ ]  Recursos necessários para o ambiente local:

1. UniServer Zero XIII
2. HeidiSQL
3. Pentaho Data Integration (PDI) - Versão 8.3


### Para rodar o projeto local faça:

1. Instale o UniServer Zero XIII e configure uma senha
2. Instale o HeidiSQL
3. Abra o UniServer Zero XIII e clique em "Start MySQL"
4. Abra o HeidiSQL e insira uma senha
5. Crie uma nova aba para consulta com (Ctrl + T)
6. Copie e cole o comando DDL_north.sql e execute com F9
6. No HeidiSQL clique com o botão direito do mouse sobre o "MySQL" e selecione "Atualizar". Pronto, o banco de dados de produção "north" foi criado.
7. Crie o banco de dados para "stg" (Stage Area) e "dw" (Data Warehouse)

### Para configurar e rodar o Pentaho faça:

1. Crie uma pasta em "Downloads" e dê o nome de "pentaho-project-02"
2. Abrir local de arquivo de onde o Pentaho foi instalado e execute com dois cliques o "Spoon.bat"
3. Com o Pentaho aberto no canto superior a direita, clique em "Connect"
4. Crie o repositório do seu projeto com o nome "pentaho-project-02"
5. Cole o arquivo do GitHub "repository_project_02" na pasta "pentaho-project-02"
5. Vá em Tools >> Repository >> Import Repository e abra o arquivo "pentaho-project-02"
6. Pronto ! Todos os Jobs e Transformações foram importadas para dentro repositório do projeto 
7. Crie as conexões com o bando de dados de stg e dw 
8. No Pentaho, abra a transformação e navegue até a pasta jobs e clique em "job_principal"
9. Com o F9 execute o "job_principal" e clique em "run"
10. Pronto !!! Data Warehouse implementado com sucesso. 
11. Abra o HeidiSQL e execute novas queries e faça análises análises.





 

