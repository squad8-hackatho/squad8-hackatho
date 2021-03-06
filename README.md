<h1 align='center'>Squad 8</h1> <br/>
<div align='center'>
        <a href='#'><img src='https://i.imgur.com/aKiNSth.png' alt='Logo Technical Share.' width='300px'/></a>
</div>


<br/>

<p align='center'>
  <a href='#projeto'>Projeto</a> | 
  <a href='#tech'>Tecnologias</a> | 
  <a href='#layout'>Layout</a> | 
  <a href='#comorodaroprojeto'>Como Rodar o Projeto</a> | 
  <a href='#features'>Features</a> | 
  <a href='#conteudoxterno'>Conteúdo Externo</a> | 
  <a href='#nossaequipe'>Nossa Equipe</a>

</p>

<br/>

<h2 id='projeto'>:computer: Projeto:</h2>
<p>
  Este projeto, aqui apresentado foi desenvolvido durante o <a href='https://digital.fcamara.com.br/programadeformacao'><strong>Programa de Formação - Season 3</strong></a>, promovido pela <a href='https://www.fcamara.com.br'><strong>FCamara</strong></a>. Foram 15 dias incriveis de Hackathon, cercados por tecnologia e adquirindo grandes conhecimentos!
</p>
<p>
É com grande prazer que chegou a hora de aprensentar nosso trabalho, Technical Share, fruto de grandes dias de produção e ttrabalho em equipe, mas antes uma breve explicação sobre a problemática e a proposta que recebemos para trabalhar durante o Hackathon.  
</p>

<ul>
        <li><strong><em>Problemática:</em></strong> 
Sabemos que quem decide trabalhar com tecnologia estuda constantemente para estar sempre atualizado, pois o avanço das informações está cada vez mais rápido.
Em contrapartida, muitas pessoas que decidem entrar na área e não sabem por onde começar ou onde encontrar.
Além disso, não são apenas pessoas que estão decidindo sua primeira carreira para a vida. Muitas pessoas estão infelizes com suas formações ou empregos, ou se identificam mais com a área de tecnologia, e decidiram migrar de carreira, ou seja, elas têm muitos afazeres no dia e, por consequência, não tem tanto tempo.</li>
  <br>
        <li><strong><em>Proposta:</em></strong> Diante da nossa problemática surge a Technical Share: uma plataforma onde você encontra pessoas da tecnologia com conhecimentos diversos para tirar suas dúvidas sobre a área ou te orientar no aprendizado de novas habilidades.
Dentro da plataforma você poderá achar um profissional ideal para sua área de estudo e ter a oportunidade de agendar desde um bate-papo mais rápido até uma mentoria mais complexa, onde vocês poderão trocar conhecimentos.
Na Technical Share, pessoas com diferentes níveis de experiência poderão se encontrar para trocar experiências, sanar dúvidas e criar networking, sempre priorizando o aprendizado.</li>
</ul>

<br>




<h2 id='tech'>:rocket: Tecnologias:</h2>
<p align='center'>
        <img src='https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg' width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="80px"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg"  width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"  width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg"  width='80px'/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width='80px'/>
</p>

<br/>
<ul>
        <li><strong><em>Front End: </em></strong>"O projeto foi desenvolvido utilizando a biblioteca React com a linguagem Typescript. Para a estilização das paginas uitilizamos o Styled-Components, que nos permitiu componentizar partes do layout, permitindo a reusabilidade do mesmo codigo em várias páginas. Foram utilizadas tambem o React-router-dom para criação de rotas, Axios para integração com o Back-End, e no cogigo utilizamos ESLint e Prettier para padronização na indentação."</li>
        <li><strong><em>Back End: </em></strong>"O desenvolvimento da API foi realizado empregando o framework do Swagger como interface para acesso direto às rotas do sistema implementado em Spring Boot 2.6.6 e Java 11. O banco de dados utilizado foi PostgresSQL do próprio Heroku onde a aplicação está disponibilizada. Não são necessárias instalações de programas terceiros para executar e manipular a API."</li>
</ul>

<br>

<h2 id='layout'>:iphone: Layout:</h2>
<div align='center'>
        <img src="https://user-images.githubusercontent.com/88353298/163655476-5b886564-1e66-4589-afe5-d6d9ef658282.png" width='800'/>
</div>
<h3 align='center'>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width='20px'/>
        Acesse o layout completo do projeto pelo Figma: <a href='https://www.figma.com/proto/JJoZaltf2AublPKPlSiR1r/TechnicalShare-%2F-Squad-8?node-id=720%3A5982&scaling=scale-down&page-id=0%3A1&starting-point-node-id=720%3A5974&show-proto-sidebar=1'><strong>Technical Share - Protótipo final</strong></a>
</h3>

<br/>

<h2 id="comorodaroprojeto">:gear:Como rodar o projeto?</h2>

Nosso projeto está disponivel na web - Acesse [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/heroku/heroku-original.svg" width='30px'/>](https://fcamara-technicalshare.herokuapp.com)

Mas caso queria rodar localmente aqui vai as instruções :small_red_triangle_down:

Recursos Necessários 
- Editor de codigo bom (recomenda-se o VSCode)
- Node.js
- .

<h3>- BACK-END</h3>

O Back está disponivel na Web atraves da url https://technicalsharesquad8.herokuapp.com. Para utilização de qualquer rota basta completar a url com algum dos complementos mostrados na próxima sessão. Pode-se utilizar também o [Swagger-UI](https://technicalsharesquad8.herokuapp.com/swagger-ui/index.html) da aplicação.

Mas caso queira acessar localmente ao site:
        
``` bash
git clone https://github.com/squad8-hackatho/squad8-hackathon-back.git
```
- Abra o projeto em um editor de codigo para Spring Boot de sua preferencia (recomendamos o [VSCode](https://code.visualstudio.com)
- Caso escolhar rodar utilizando o VSCode certifique-se de que possue as seguintes extensões instaladas
  - [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
<img src="https://user-images.githubusercontent.com/88353298/163655204-b6ce2524-efcc-40a5-852e-d4d57309eb92.png" width="800"/>

  - [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack)
<img src="https://user-images.githubusercontent.com/88353298/163655232-cb2910b1-b49f-43cb-a4ee-aa5598d31e22.png" width="800"/>

- Agora apenas inicie sua aplicação utilizando a guia "spring-boot-dashboard":
<img src="https://user-images.githubusercontent.com/88353298/163655038-ff7da9cd-80d8-42db-89c6-5ad5e7ef81e8.png"/>


*A aplicação (backend) está conectada com o Swagger e será aberta na porta:8080 - acesse http://localhost:8080.*

<hr>

<h3>- FRONT-END</h3>

~~~bash 
# Clone esse repositório 
$ git clone https://github.com/squad8-hackatho/squad8-hackathon-front.git 

# Instale as dependências do projeto

$ npm install

# Inicie o projeto

$npm run dev

#A aplicação(frontend) será aberta na porta:3000 - acesse http://localhost:3000. 
~~~
*OBS: Para que a aplicação funcione, não é necessário rodar o Back localmente pois ele está online na nuvem*

<br>

<h2 id="comoEntrar">🚪 Como entrar?</h2>
<ul>
  <li><strong>Crie sua conta:</strong></li>
  <br />
  <strong>OU</strong>
  <br />
  <br />
  <li><strong>Entre com:</strong></li>
  <ul>
    <li>email: teste@teste.com</li>
    <li>senha: teste</li>
  </ul>
</ul>
<br>
<hr>

Gostaria de saber mais sobre a produção em cada frente ( back-end / front-end)?
- Criamos um readme exclusivo para cada uma - Acesse: <br>
        * FRONT-END - https://github.com/squad8-hackatho/squad8-hackathon-front <br> 
        * BACK-END - https://github.com/squad8-hackatho/squad8-hackathon-back

<br>

<h2 id="features">✨Features</h2>

* O que será que pensamos para o futuro da nossa aplicação...? :sunglasses:
    * **01** - Campo para adicionar foto do usuário
    * **02** - Permitir usuário editar seu perfil
    * **03** - ??

<br>

<h2 id="conteudoxterno">:file_folder:Conteúdo Externo</h2> 

* :clapper: Veja o nosso [vídeo de funcionalidades](#)! 
* :page_facing_up: Também nosso [artigo](https://medium.com/@eduardaribeirodg/technicalshare-encontrar-pessoas-ideais-para-compartilhar-conhecimento-e-trocar-experi%C3%AAncias-nunca-2dc92a750352) desenvolvido pela nossa dupla de UX Design, relatando todo o processo de desenvolvimento. 
* :loudspeaker: Nosso [Pitch](https://www.youtube.com/watch?v=DXwLFCw6NAU). <br>
* -- [MIRO](https://miro.com/app/board/uXjVOAKbHZA=/) <br>
* -- [TRELLO](https://trello.com/b/8MfsWPcR/squad8) <br>
* -- [DBDESIGNER](https://user-images.githubusercontent.com/88353298/163578766-cebc9f4e-1e2c-4e40-8ebd-0fdf524414d3.png)

        
<br>

<h2 id="nossaequipe">:busts_in_silhouette:Nossa Equipe</h2> 


|_Beatriz Paixão_|_Bruno Mundim_|_Bruno Soares_|_Carlos Eduardo_|_Maria Eduarda_|_Yulli Rezende_|
|---|---|---|---|---|---|
|<img src="https://avatars.githubusercontent.com/u/88353298?v=4g" width="140">|<img src="https://user-images.githubusercontent.com/88353298/163576759-32a7947b-8ae8-4295-a5ce-c2df4a17e88b.png" width="140">|<img src="https://avatars.githubusercontent.com/u/48768035?v=4" width="140">|<img src="https://avatars.githubusercontent.com/u/47821159?v=4" width="140">|<img src="https://user-images.githubusercontent.com/88353298/163576731-774f4bad-adc7-4cec-9628-620a25adca12.png" width="140">|<img src="https://user-images.githubusercontent.com/88353298/163650780-413ab49e-1915-4d71-a6e9-56044ea60054.png" width="140">
|_*Desenvolvedora*_|_*Desenvolvedor*_|_*Desenvolvedor*_|_*Desenvolvedor*_|_*UX Designer*_|_*UX Designer*_|
|[<img src="https://user-images.githubusercontent.com/88353298/163484213-0db62648-671b-43eb-bdf1-c19b435fe264.svg" width="24"/>](https://github.com/biiah-paixao) - [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/beatriz-paixao/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](biaperon2001@gmail.com)|[<img src="https://user-images.githubusercontent.com/88353298/163484213-0db62648-671b-43eb-bdf1-c19b435fe264.svg" width="24"/>](https://github.com/BrunoMundim) - [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/in/bruno-mundim/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](brunomundimfranco@gmail.com)|[<img src="https://user-images.githubusercontent.com/88353298/163484213-0db62648-671b-43eb-bdf1-c19b435fe264.svg" width="24"/>](https://github.com/brunosas88) - [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/in/brunosas/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](bruno.sas@live.com)|[<img src="https://user-images.githubusercontent.com/88353298/163484213-0db62648-671b-43eb-bdf1-c19b435fe264.svg" width="24"/>](https://github.com/Carlos-Xavier) - [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/in/carlos-e-x-bezerra/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](cexbezerra@gmail.com)|[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/in/mariaeduardabribeiro/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](eduardaribeirodg2@gmail.com)|[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"/>](https://www.linkedin.com/in/yullibrito/) - [<img src="https://user-images.githubusercontent.com/88353298/163483362-a3b1e4fe-5d03-46a9-ad93-4fcc7af98a9f.png" width="24"/>](design.yullibrito@gmail.com)
<br>

<hr>

<p> Feito com muito 🧡 pelo Squad-8<br> #FuturosSangueLaranja 🚀 <p>
