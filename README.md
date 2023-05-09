<h1 align="center" >
<img src="https://user-images.githubusercontent.com/102265620/231919219-1afff750-9c8b-4773-83f1-8dc69e4893e2.png" width="50" height="50"/>
Projeto Labenu System
<img src="https://user-images.githubusercontent.com/102265620/231877695-2cb6c96a-2b2b-4806-967a-48929ffc4046.png" width="50" height="50"/>
</h1>

![Badge Finalizado](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

<hr>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/231878490-608ecccb-061f-476d-a43b-708590d03f8d.png" width="20" height="20"/>
Labenu System é um projeto de Backend que tem a finalidade de introduzir a lógica da Programação Orientada a Objetos, utilzando os conceitos de Classes, Herança, polimorfismo e também no aprofundamento das estruturas de banco de dados, com algumas tabelas relacionais de um para muitos e muitos para muitos.
</h4>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/231880058-06ecbf5b-02ee-44e0-a491-aebe1238d5ad.png" width="20" height="20"/>
O projeto possui o tema da própria institução Labenu, com a criação de uma estrutura com as entidades de turmas, estudantes e instrutuors, possuindo funções que poderiam existir neste tipo de sistema.
</h4>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/231886048-8d35264b-8e26-45ae-a01b-3ae70dfbb2c4.png" width="35" height="35" align="center"/>
Como Testar
</h3>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/231886670-84bbf853-61da-4e86-9e84-ed339e0869bb.png" width="20" height="20"/> Link da Documentação via Postman:
<br></br>
https://documenter.getpostman.com/view/24755055/2s8Z75Spvm
<br></br>
- Com o Postman instalado em seu computador, basta abrir a documentação e clicar no botão <img src="https://github.com/RenatoAlexandrini/LabenuSystem/assets/102265620/b4329b29-60d4-4ed4-8f94-0ca08cc866a9" width="170" height="50" align="center"/>  para testar diretamente no Postman.
<br></br>
</h4>
<h4>
<img src="https://github.com/RenatoAlexandrini/LabenuSystem/assets/102265620/9971d217-4632-474e-9194-9f3e907fcada" width="30" height="30" align="center"/> Para testar localmente:
</h4>

```
- inicie o Git Bash em uma pasta e digite:
- git clone https://github.com/RenatoAlexandrini/Projeto-LabEcommerce-Backend
- npm install
- npm run migrations
- npm run start
- Em cada endpoint, substitua o "https://jemison-labesystem1.onrender.com" por "http://localhost:3003"
```
<hr>


<h2>
<img src="https://user-images.githubusercontent.com/102265620/231894847-1bf41bed-966f-420b-8385-50e803e8eb09.png" width="35" height="35"/> Endpoints:
<br></br>
</h2>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/231898558-52c4f444-b2a0-49da-b4ad-33d6b4daa75d.png" width="35" height="35"/> Criar uma turma:
</h3>
<h5>
Endpoint que recebe através de um "body" apenas o nome da nova turma, antes da confirmação da criação, será verificado se já existe alguma turma cadastrada anteriormente com o mesmo nome.
</h5>


<h3>
<img src="https://user-images.githubusercontent.com/102265620/231899073-2eca1243-ef9d-435f-af54-12c0e403c39f.png" width="35" height="35"/> Buscar turmas ativas:
</h3>
<h5>
Endpoint que retorna uma lista com todas as turmas que já iniciaram o curso, portanto estão em um dos seis módulos que o curso possui, ordenados em ordem crescente do módulo que a turma se encontra.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231908641-d4496610-81ba-4705-a015-33aa867de5a2.png" width="35" height="35"/> Mudar turma de módulo:
</h3>
<h5>
Endpoint que drecebe por "params" o id de uma turma e faz a verificação se a turma existe no banco de dados. Então recebe através da "query" o número do novo módulo, que deverá ser um número de 1 a 6 onde não é possível atribuir o valor de um módulo abaixo do módulo atual.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231910415-ae7be7e4-1721-4984-bccf-f669cfdcf076.png" width="35" height="35"/> Buscar todas as pessoas da mesma turma:
</h3>
<h5>
Endpoint que recebe o id de uma turma através da "query", verifica se a turma existe, então exibe uma relação de todos os instrutores e estudantes desta turma.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231911041-9e76f5d3-fcf0-40b8-9724-e91eb25b7380.png" width="35" height="35"/> Cadastrar instrutor:
</h3>
<h5>
Endpoint que recebe através de um "body" um nome, um email uma data de nascimento e um array com as especialidades do instrutor, então antes da confirmação da criação, verifica se o email cadastrado já existe no banco de dados e também se as especialidades correspondem a uma das seis especialidade existentes no banco de dados.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231911251-ca40f563-7682-4104-a3a0-7808871fd633.png" width="35" height="35"/> Mudar instrutor de turma:
</h3>
<h5>
Endpoint que recebe através do "params" o id de um instrutor, fazendo a verificação se o mesmo está cadastrado no banco de dados. Então recebe o nome de uma turma através da "query" fazendo a verificação se a turma existe no banco de dados, para finalmente atribuir a nova turma ao instrutor.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231912845-a452669b-2803-443a-9bd4-ca610f2475e2.png" width="35" height="35"/> Buscar todos os instrutores:
</h3>
<h5>
Endpoint que retorna uma lista com todos os dados dos instrutores, incluindo as especialidades de cada um deles.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231915116-770e6a30-4015-4a89-b7e2-00ed1c60abee.png" width="35" height="35"/> Buscar todos os instrutores especialistas em Programação Orientada a Objetos:
</h3>
<h5>
Endpoint que retorna todos os Instruturos que possuem a especialidade de Programação Orientada a Objetos.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231916670-9e12f8f3-707a-4cb7-9a43-a11e106cb633.png" width="35" height="35"/> Cadastrar estudante:
</h3>
<h5>
Endpoint que recebe através de um "body" um nome, um email uma data de nascimento e um array com os hobbies de um estudante, fazendo a verificação se o email informado já foi cadastrado anteriormente no banco de dados. Então verifica os hobbies informados, cadastrando aqueles que não correspondem a nenhum hobby cadastrado anteriormente, antes da confirmação da criação do novo estudante.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231916771-1987928e-9898-42cf-9487-4777e1dcce6a.png" width="30" height="30"/> Mudar estudante de turma:
</h3>
<h5>
Endpoint que recebe através do "path params" o id de um estudante, fazendo a verificação se ele está cadastrado no banco de dados. Enãto recebe o nome de uma turma através da "query" fazendo a verificação se a turma existe no banco de dados, para finalmente atribuir a nova turma ao estudante.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231916834-e69c05ec-7f33-4dbe-a400-3e2c2af620c7.png" width="30" height="30"/> Buscar estudantes através do nome:
</h3>
<h5>
Endpoint que recebe através da "query" um termo então retorna todos os estudantes que possuam este termo em qualquer parte do nome ou sobrenome.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231917323-b7332df0-e554-427b-9302-6703f36cc501.png" width="30" height="30"/> Buscar estudantes atrvés de um hobby:
</h3>
<h5>
Endpoint que recebe através da "query" um hobby, então verifica se o hobby informado está cadastrado no banco de dados, para então retornar todos os estudantes que possuem este hobby atribuído.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/231917921-ada60476-2835-4d74-ad7d-06362b1ac75f.png" width="30" height="30"/> Buscar todas as pessoas através de um signo do Zodíaco:
</h3>
<h5>
Endpoint que recebe através da "query" um dos 12 signos do Zodíaco e então retorna todas as pessoas cadastradas, entre estudantes e intrutores são do signo iformado. Neste Endpoint não existe separação entre estudantes e instrutores.
</h5>

<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/231918447-10e51bc6-f7b3-4991-945b-f2f681a9490c.gif" width="40" height="40"/> Técnicas e tecnologias utilizadas
<br></br>

- ``Typescript`` <img src="https://user-images.githubusercontent.com/102265620/230519766-2b4903ad-94f7-48e7-b949-4fc981ee519d.png" width="19" height="19"/>
- ``SQL`` <img src="https://user-images.githubusercontent.com/102265620/230519864-6ee2f9d0-1377-4528-a6a1-2b19b5b75d5e.jpg" width="22" height="22"/>

</h3>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/231918732-0b45ddb5-bcc4-47e7-9b1f-05dff210534e.png" width="20" height="20"/>Autor:
</h3>

| [<img src="https://avatars.githubusercontent.com/u/102265620?v=4" width=115><br><sub>Renato Alexandrini</sub>](https://github.com/RenatoAlexandrini) | 
| :---: |
