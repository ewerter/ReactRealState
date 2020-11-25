## First TODO List: MVP de um site de negociação de imóvel no Canadá

Referências dadas pelo cliente:
- See [Royar LePage](https://www.royallepage.ca/fr/])
- See [Sutton Group](https://www.suttonquebec.com/)

Referências sugeridas pelo time de desenvolvimento
- See [QuintoAndar](https://www.quintoandar.com.br/)
- See [AirBNB](https://www.airbnb.com.br/)

### Definição de Tecnologias
- [ ] Definir Tecnologias que serão utilizadas.
  - [ ] Definir servidor de hospedagem (Windows x Linux)
  - [ ] Definir provedor de hospedagem (Locaweb | BlueHost | AWS | Google Sites | Etc)
  - [ ] Definir framework/linguagem front-end (React | WordPress | HTML+CSS+JQuery) 
  - [ ] Definir framework/linguagem back-end (C# | Node.js | PHP)
  - [ ] Definir banco de dados (SQL | NOSQL)

--------------
### Modelagem do Banco de dados
- [ ] Definir as tabelas | documentos | campos necessários para o banco de dados

### Front-end
- [ ] Fechar o escopo geral do projeto 
  - [ ] Page: Home
  - [ ] Page: Properties for sale
  - [ ] Page: Properties for rent
  - [ ] Page: Show Properties for Rent (with Search Engine)
  - [ ] Page: Blog
  - [ ] Form: Contact me
  - [ ] Form: Newsletter
  - [ ] Form: I want to sell my property 
  - [ ] Form: Cadastro de Notícias
  - [ ] *Form: Login* [?]
  - [ ] *Form: Property Registration* [?]
  - [ ] *Form: User Registration* [?]
  
### Back-end
- [ ] Fechar o escopo geral do projeto 
  - [ ] API de consultas
  - [ ] Endpoint: GetProperties(for_sale)
  - [ ] Endpoint: GetProperties(for_rent)
  - [ ] Endpoint: GetProperties(for_similarity)
  - [ ] Endpoint: GetProperty(byId)
  - [ ] Endpoint: GetProperty(byAddress)
  - [ ] Endpoint: SaveNewsletterData(contactInfo)
  - [ ] *Endpoint: Auth(client)*
  - [ ] *Endpoint: RegisterUser(client)*
  - [ ] *Endpoint: RegisterProperty(client, property)*
