# vuejs
Curso Treinaweb

O que é o Vue.js?
A web existe desde o início dos anos 1990 e, de lá para cá, a forma como os sites são apresentados mudou drasticamente, com uma clara evolução das técnicas de desenvolvimento de aplicações Web. Isso é justificado em parte por causa da relevância que a plataforma Web assumiu, principalmente nos últimos anos, "tomando" o espaço de aplicações desktop, por exemplo. Com essa evolução, começaram a surgir ferramentas, bibliotecas e frameworks que visam acelerar o processo de aplicações Web.

Uma destas modernas bibliotecas que surgiram com essa evolução foi o Vue.js ou simplesmente Vue (pronuncia-se "viu", como se fosse view). O Vue é uma biblioteca que tem como objetivo auxiliar na construção de interfaces web.

O Vue (pronuncia-se "viu", como View) é um framework para a construção de interfaces de maneira simples. Ele possui algumas semelhanças com o AngularJS quando vamos criar nossas views, mas seu funcionamento reativo o iguala ao React. Qualquer alteração em alguma variável é refletida na view.

Outra semelhança com o React é que o Vue também trabalha com Virtual DOM, uma implementação do DOM que, por estar na memória, é muito mais rápido do que acessar o DOM real. Qualquer mudança é feita primeiramente no Virtual DOM e, quando localizados os lugares onde as alterações devem ser feitas, o resultado é passado ao DOM.

O Vue faz a mesma coisa que outros frameworks como o Angular, o React e o Aurelia, tanto é que ele possui recursos muito populares em outros frameworks front-end; como two-way data binding, programação reativa, eventos, criação de componentes e outros recursos. Mas o que difere o Vue dos demais é sua extrema simplicidade. Trabalhar com o Vue é muito, mas muito simples. Essa simplicidade acaba sendo refletida em outros pontos, como performance. O próprio site do Vue (https://vuejs.org/ ) realiza algumas comparações entre o próprio e outros frameworks, inclusive fazendo comparações com relação à velocidade.

Para que você tenha uma ideia, um dos testes que foram realizados foi a carga de duas versões de uma mesma página: uma com Vue e outra com React. No caso médio, a versão da página desenvolvida com Vue foi completamente carregada em 51ms, enquanto a versão com React foi carregada em 94ms!

Outra decorrência em relação à facilidade de utilização do Vue frente outras tecnologias é a simplicidade em usar o mesmo em conjunto com outras tecnologias. É perfeitamente possível utilizar o Vue com outras tecnologias, como o JSX e o TypeScript, sem maiores problemas.

Veremos melhor cada ponto aqui descrito conforme formos avançando no curso.

O padrão MVVM
O Vue utiliza bastante a ideia do padrão MVVM (Model, View, ViewModel), já que utilizamos um objeto que cuida das informações e da view, mas não se limita a isso. Podemos trabalhar com MVC, Flux e outras arquiteturas.

Basicamente, o padrão MVVM consiste em três grandes camadas: a view, que pode ser compreendida como sendo o nosso HTML; o model, que é a estrutura responsável por representar as informações a serem exibidas na view; e o view-model, que é o componente responsável por fazer a interação e coordenar o fluxo de informações entre a view e o model. Por exemplo: se fizermos uma alteração no estado de um model de nossa aplicação, essa alteração deve obrigatoriamente ser refletida na view. Quem vai coordenar esse processo de "reflexo" da alteração do model para a view vai ser justamente o view model.

Instalação
O Vue já começa a pregar a simplicidade quando tratamos da maneira de o obter para começarmos a utilizá-lo.

Você pode obter o Vue simplesmente criando um apontamento para uma CDN. Poderíamos, dessa maneira, importa-lo através de uma simples tag "script":

<script src="https://unpkg.com/vue/dist/vue.js" ></script>

Você também pode obtê-lo através do NPM com o comando abaixo:

$ npm install vue

Você ainda pode obtê-lo através do Bower com o comando abaixo:

$ bower install vue

Até mesmo através do download do site oficial (https://vuejs.org/ ) você consegue obter o Vue e adicioná-lo em sua aplicação!
