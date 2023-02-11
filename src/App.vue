<template>
  <div id="app">


    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
      <img src="./assets/logo.jpg" alt="" width="50" height="60">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <b-link href="#application">Home</b-link>
          </li>
          <li class="nav-item">
            <b-link href="#eu">Quem Sou Eu?</b-link>
          </li>
          <li class="nav-item">
            <b-link href="#faco">O que faço?</b-link>
          </li>
          <li class="nav-item">
            <b-link href="#hobbies">Hobbies</b-link>
          </li>
          <li class="item">
              <b-link v-b-modal="'modalHobbies'">Mais</b-link>
          </li>

        </ul>
      </div>

    </nav>

    <main role="main" class="container" style="margin-top:30px;">
      <div class="jumbotron p-3 p-md-5 text-white rounded bg-dark">
        <div class="col-md-6 px-0">
          <h1 class="display-4 font-italic">Ornélio Jotamo</h1>
          <h3 class="display-4 font-italic">nr 75283</h3>
            <p class="lead">Bem vindo a Minha página para o Mestrado em Engenharia Informática e Tecnologia Web - UTAD/UAB.</p>
            <p class="lead my-3">
              Single Page Application para UC de Programação Web Avançada. <br>
            </p>
       <div>
  <!-- The Hobbies -->
  <b-modal id="modalHobbies">
          <h3>Hobbies</h3>

        <div class="modal-body">
          <div class="row" style="padding: 20px">
            <p>Gosto de aproveitar o máximo os meus tempos livres.</p>
              <p>Em suma, meus hobbies são : </p>
              <ul>
                <li> Fotografia</li>
                <li> Leitura</li>
                <li> Filme de ação </li>
                <li> Filme de ficção </li>
                <li> Desporto </li>
              </ul>
              <p>E mais.</p>
          </div><!-- /.row -->
        </div>




  </b-modal>
</div>



        </div>
      </div>
    </main>

    <main role="main" class="container">
      <div class="row">
            <h2>Apresentação Geral</h2> <br>
            <p>Sou Ornélio Jotamo, de Moçambique, licenciado em Ensino de Informática.
                Tenho 12 anos de experiência na área de TI, tendo actuado como HelpDesk, desenvolvedor, 
                Network & Sys Admin, docente e actualmente Admin de Aplicações Web no CEDSIF (uma entidade responsável 
                pela modernização de processos de gestão de finanças públicas)
                Gosto e estou em constante processo de formação.</p>
        </div><!-- /.row -->
    </main>

    <section class="container conteudo" id="eu">
      <div class="row">
          <h2>Quem Sou Eu</h2>
          <br>
          <p>Abaixo seguem alguns detalhes sobre mim.</p>
          <br>
          <p>Meu nome é Ornélio Jotamo.</p>
          <br>
          <blockquote>
            <p>Sou de Moçambique.</p>
          </blockquote>
          <p>Tenho 34 anos de idade.</p>
          <br>
          <p>Sou Licenciado em ensino de informática.</p>
          <br>
          <p>Mestrando em Engenharia Informática e tecnologia WEB na UTAD/UAB.</p>
          <br>
          <p>Certificado como RedHat System Administrator. </p>
          <p>A</p>
      </div><!-- /.row -->
    </section>

    <section class="container conteudo" id="faco">
      <div class="row">
          <h2>O que faço?</h2>
          <br>
          <p>Abaixo seguem as informações sobre o meu percurso profissional.</p><br>
           <blockquote>
            <p><p>Actualmente trabalho como Administrador de Aplicações Web no CEDSIF (uma entidade responsável pela modernização de processos de gestão de finanças públicas) mas já trabalhei como:</p>
          </blockquote>
          <p>Actualmente trabalho como Administrador de Aplicações Web no CEDSIF (uma entidade responsável pela modernização de processos de gestão de finanças públicas) mas já trabalhei como:</p>
			    <p> 2011 – 2013 – Docente e Técnico de Informática no Instituto de Formação de Professores da Matola.</p>
			    <p> 2010 – 2011 – Docente (assistente) de Tecnologias Educativas na Universidade Pedagógica.</p>
			    <p> 2010 – 2011 – Programador/desenvolvedor de Softwares no projecto de concepção/implementação do Sistema Integrado de Planificação, Monitoria e Avaliação da Justiça no Ministério da Justiça (SIPMAJ).</p>
			    <p> 2009 – 2010 – Técnico de Informática (Hardware & Administração e Manutenção da rede) no Instituto de Formação de Professores da Matola..</p>
          <blockquote>
            <p>Já trabalhei como formador de utilizadores de ActivClassroom da PrometheanPlanet.</p>
          </blockquote>
			    <p>Trabalho como formador de administradores de sistemas Linux.</p>
      </div><!-- /.row -->
    </section>

    <section class="container conteudo" id="hobbies">
      <div class="row">
          <h2>Hobbies</h2>
          <blockquote>
				    <p>Gosto de fotografar.</p>
				    <p>Leitura de Romances policiais.</p>
			    </blockquote>
			    <blockquote>
			      <p>Filmes de ação e ficção científica</p>
			    </blockquote>
          <p>Praticar desportos.</p>
      </div><!-- /.row -->

    </section>


    <footer class="footer">
      <p>Copyright &copy; Ornelio Jotamo (ojotamo@gmail.com) </a>.</p>
        <a href="#">  <img src="./assets/facebook.png"  width="30" height="30"/> </a>
        <a href="#"> <img src="./assets/google+.png" alt="" width="30" height="30"/>  </a>
        <a href="#"> <img src="./assets/twitter.png" alt="" width="30" height="30"/>  </a>
        <a href="https://www.linkedin.com/in/ornelio-jotamo-850556100/"> <img src="./assets/Linkedin.png" alt="" width="30" height="30"/>  </a>
        <p>
          <a href="#"> 
            <img src="./assets/up.png" height="19px"/>
          
          </a>
        </p>
      </footer>


  </div>

</template>
<script>
export default {
  name: 'app',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}

</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

</style>
