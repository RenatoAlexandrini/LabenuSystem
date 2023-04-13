<h1 align="center" >
<img src="https://user-images.githubusercontent.com/102265620/231877583-f4fb66e9-b502-4e49-b256-3b170a7ea0be.png" width="50" height="50"/>
Projeto Labenu System
<img src="https://user-images.githubusercontent.com/102265620/231877695-2cb6c96a-2b2b-4806-967a-48929ffc4046.png" width="50" height="50"/>
</h1>

<hr>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/231878490-608ecccb-061f-476d-a43b-708590d03f8d.png" width="20" height="20"/>
Labenu System é um projeto de Backend que tem a finalidade de introduzir a lógica da Programação Orientada a Objetos, utilzando os conceitos de Classes, Herança, polimorfismo e também no aprofundamento das estruturas de banco de dados, com algumas tabelas relacionais de um para muitos e muitos para muitos.
</h4>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/231880058-06ecbf5b-02ee-44e0-a491-aebe1238d5ad.png" width="20" height="20"/>
O projeto possui o tema da própria institução Labenu, com a criação de uma estrutura de turmas, estudantes e instrutuors com retornos de diferentes formas entre essas entidades.
</h4>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230518924-f1070954-5e4f-43fa-ba61-e069f2bd2701.png" width="35" height="35"/>
Como Testar
</h3>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/230519105-cde9cf7d-02fe-4561-8073-38e6ad1909dd.png" width="20" height="20"/> Link do Render:
 
https://projeto-labecommerce-backend-turma.onrender.com

<br></br>
</h4>

```
- git clone https://github.com/RenatoAlexandrini/Projeto-LabEcommerce-Backend
- npm install
- npm run migrations
- npm run start
```
<hr>



<h2>
<img src="https://user-images.githubusercontent.com/102265620/230520548-8ad92534-3dc5-404e-a71d-e2e13313e0ee.png" width="35" height="35"/> Endpoints:
<br></br>
</h2>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230521871-67ca7956-aa6e-4152-a991-ad3dfa981e42.png" width="30" height="30"/> Adicionar um usuário:
</h3>
<h5>
Endpoint que adiciona um novo usuário ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também a criação de um usuário com o email igual a outro usuário adicionado anteriormente.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230522729-493be4de-0665-4465-9d01-59962d7a5195.png" width="30" height="30"/> Buscar todos os usuários e compras:
</h3>
<h5>
Endpoint que não recebe nenhum tipo de parâmetro, apenas retorna um array com todos os usuários e todas as compras realizadas por ele, retornando um array de compras vazio caso o usuário não tenha realizado nenhuma compra anterior.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523061-210fba1e-dc0c-4e63-ada9-5f8aec3b9c68.png" width="30" height="30"/> Adicionar um produto:
</h3>
<h5>
Endpoint que adiciona um novo produto ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também a criação de um produto com o nome igual a outro produto adicionado anteriormente.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523369-0b310ba2-78d5-40cb-b188-db824b8728dd.png" width="30" height="30"/> Buscar todos os produtos:
</h3>
<h5>
Endpoint que retorna uma lista com todos os produtos do banco de dados, podendo ser passado através de uma query um termo para busca de produtos ou uma ordenação(crescente: "ASC" ou decrescente "DESC").
Todos os parâmetros("order" e "search") são opcionais, gerando diferentes resultados, de acordo com o solicitado.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523740-afcc9045-9373-4e69-947b-12e88ac040b4.png" width="30" height="30"/> Adicionar uma compra:
</h3>
<h5>
Endpoint que adiciona uma nova compra ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também havendo a verificação da existência do usuário e do produto pelo id informado.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230526640-fdbb8b79-2261-404c-8939-46a2fbfa2869.png" width="30" height="30"/> Buscar compras de um usuário:
</h3>
<h5>
Endpoint que recebe o id de um usuário através do "path.params", retornando as informações deste usuário junto com as compras realizadas por ele, havendo a verificação da existência do usuário através do id informado.
</h5>

<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230520839-647a68bd-8a3d-4c4f-890f-e3edbbadcb19.png" width="30" height="30"/> Técnicas e tecnologias utilizadas
<br></br>

- ``Typescript`` <img src="https://user-images.githubusercontent.com/102265620/230519766-2b4903ad-94f7-48e7-b949-4fc981ee519d.png" width="19" height="19"/>
- ``SQL`` <img src="https://user-images.githubusercontent.com/102265620/230519864-6ee2f9d0-1377-4528-a6a1-2b19b5b75d5e.jpg" width="22" height="22"/>

</h3>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230521150-79ed8394-6e7e-4188-80e9-d726e1500137.png" width="30" height="30"/>Autor:
</h3>

| [<img src="https://avatars.githubusercontent.com/u/102265620?v=4" width=115><br><sub>Renato Alexandrini</sub>](https://github.com/RenatoAlexandrini) | 
| :---: |






 <h1 align="center"><strong>Labenu System 01 Turma Jemison</b></strong></h1></div>

<h2>Projeto :books:</h2>
<hr>
Labenu System é um projeto de Backend que tem a finalidade de introduzir a lógica da Programação Orientada a Objetos, utilzando os conceitos de Classes, Herança, polimorfismo e também no aprofundamento das estruturas de banco de dados, com algumas tabelas relacionadas de um para muitos e muitos para muitos.

O projeto possui o tema da própria institução Labenu, com a criação de uma estrutura de :school:**turmas**, :man_student:**estudantes** e :man_teacher:**instrutuors** com retornos de diferentes formas entre essas entidades.
<hr>

### Integrantes do grupo:
* Leonardo Mizuki Koga
* Renato Alexandrini
* Rhuan Victor Virtudes Lourenço
---

<h3>Endpoinst do projeto<h3>
<h4>

:yellow_circle: Criar turma :school:
>Endpoint que recebe através de um "body" apenas o nome da nova turma, antes da confirmação da criação, será verificado se já existe alguma turma cadastrada            anteriormente com o mesmo nome.
</br>

:green_circle: Buscar turmas ativas :school:
>  Endpoint que retorna uma lista com todas as turmas que já iniciaram o curso, portanto estão em um dos seis módulos que o curso possui, ordenados em ordem crescente    do módulo que a turma se encontra.
</br>

:large_blue_circle: Mudar turma de módulo :school:
> Endpoint que drecebe por "path params" o id de uma turma e faz a verificação se a turma existe no banco de dados. Então recebe através da "query" o número do novo módulo, que deverá ser um número de 1 a 6 onde não é possível atribuir o valor de um módulo abaixo do módulo atual.
</br>

:green_circle: ***Buscar todas as pessoas através da turma*** 	:people_holding_hands:
> Endpoint que recebe o id de uma turma através da "query", verifica se a turma existe, então exibe uma relação de todos os instrutores desta turma e uma contendo os estudantes desta turma.
</br>

:yellow_circle: Criar instrutor :man_teacher:
> Endpoint que recebe através de um "body" um nome, um email uma data de nascimento e um array com as especialidades do instrutor, então antes da confirmação da criação, verifica se o email cadastrado já existe no banco de dados e também se as especialidades correspondem às seis especialidade existentes no banco de dados.
</br>

:large_blue_circle: Mudar instrutor de turma :man_teacher:
> Endpoint que recebe através do "path params" o id de um instrutor, fazendo a verificação se está cadastrado no banco de dados. Enãto recebe o nome de uma turma através da "query" fazendo a verificação se a turma existe no banco de dados, antes de atribuir a nova turma ao instrutor.
</br>

:green_circle: Buscar todos os instrutores :man_teacher:
> Endpoint que retorna uma lista com todos os dados dos instrutores, contendo também as especialidades dele.
</br>

:green_circle: Buscar todos os instrutores especialistas em Programação Orientada a Objetos :man_teacher:
>Endpoint que retorna todos os Instruturos que possuem a especialidade de Programação Orientada a Objetos.
</br>

:yellow_circle: Criar estudante :man_student:
> Endpoint que recebe através de um "body" um nome, um email uma data de nascimento e um array com os hobbies de um estudante, fazendo a verificação se o email informado já foi cadastrado anteriormente no banco de dados. Então verifica os hobbies informados, cadastrando aqueles que não correspondem a nenhum hobby cadastrado anteriormente, antes da confirmação da criação do novo estudante.
</br>

:large_blue_circle: Mudar estudante de turma :man_student:
> Endpoint que recebe através do "path params" o id de um estudante, fazendo a verificação se ele está cadastrado no banco de dados. Enãto recebe o nome de uma turma através da "query" fazendo a verificação se a turma existe no banco de dados, antes de atribuir a nova turma ao estudante.
</br>

:green_circle:Buscar estudantes através do nome :man_student:
>Endpoint que recebe através da "query" um termo então retorna todos os estudantes que possuam este termo em qualquer parte do nome ou sobrenome.
</br>

:green_circle:Buscar estudantes atrvés de um hobby:man_student:
>Endpoint que recebe através da "query" um hobby, então verifica se o hobby informado está cadastrado no banco de dados, para então retornar todos os estudantes que pssuam este hobby atribuído.
</br>

:green_circle:Buscar todas as pessoas através de um signo do Zodíaco:cancer:
>Endpoint que recebe através da "query" um dos 12 signos do Zodíaco e então retorna todas as pessoas cadastradas, entre estudantes e intrutores são do signo iformado. Neste Endpoint não existe separação entre estudantes e instrutores.

---

### Tecnologia Utilizada:
* Typescript

<img src="https://user-images.githubusercontent.com/102265620/205476749-786b35ae-cb86-44ab-bff9-4bd8833284b7.png" width="50px">

* SQL

<img src="https://user-images.githubusercontent.com/102265620/205476861-68520703-8f8b-4dc9-9336-fc7d8b4a0764.jpg" width="50px">

### Link da Documentação via Postman
https://documenter.getpostman.com/view/24755055/2s8Z75Spvm

### Link do Deploy através do Render
https://jemison-labesystem1.onrender.com
