📊 Sistema de Banco de Dados de Ocorrências Criminais

Este projeto é um sistema de análise e consulta de ocorrências criminais utilizando Spring Boot 
e um banco de dados SQL. O sistema permite a consulta de estatísticas criminais por região e cidade, fornecendo insights sobre a taxa de criminalidade 
e indicadores socioeconômicos, como o IDH (Índice de Desenvolvimento Humano).

🚀 Tecnologias Utilizadas

Java + Spring Boot - Backend da aplicação

Spring Data JPA - Manipulação do banco de dados

MySQL / PostgreSQL - Banco de dados relacional

Postman - Testes das requisições API

Docker (opcional) - Para conteinerização do banco de dados


🗂 Estrutura do Banco de Dados

O banco de dados é estruturado em quatro tabelas principais:

Região: Contém informações sobre as regiões administrativas.

Cidade: Relacionada à região, armazena cidades e seus dados.

Tipo_de_Crime: Define os diferentes tipos de crime registrados.

IDH: Contém informações socioeconômicas relacionadas a cada cidade.


🔍 Funcionalidades

Consulta por cidade: Retorna estatísticas de criminalidade, como "Sorocaba, 54% de homicídios culposos".

Filtragem por tipo de crime: Permite buscar informações sobre crimes específicos.

Análise do IDH: Relaciona a criminalidade com os índices de desenvolvimento humano.

Geração de relatórios (em desenvolvimento): Exporta estatísticas para CSV/JSON.

🛠 Instalação e Configuração

Clone este repositório:

git clone https://github.com/SeuUsuario/Sistema-Ocorrencias-Criminais.git
cd Sistema-Ocorrencias-Criminais

Configure o banco de dados:

Crie um banco de dados MySQL ou PostgreSQL.

Atualize o arquivo application.properties com as credenciais do banco.

Instale as dependências e execute a aplicação:

mvn clean install
mvn spring-boot:run

Testando as consultas via Postman ou cURL:

curl -X GET "http://localhost:8080/ocorrencias/sorocaba"


📌 Contribuição

Se deseja contribuir com o projeto:

Fork o repositório.

Crie uma branch com sua funcionalidade (git checkout -b feature/minha-feature).

Faça commit das alterações (git commit -m 'Adicionando nova funcionalidade').

Envie para o repositório remoto (git push origin feature/minha-feature).

Abra um Pull Request.


📜 Licença

Este projeto está sob a licença MIT - veja o arquivo LICENSE para mais detalhes.


Desenvolvido por Murilo Pires Andrade Cruz, *ADICIONEM SEUS NOMES* 🚀
