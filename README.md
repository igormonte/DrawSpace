<pre>
  __________________________________      ________
 |                                  |    |        |
 |    ______________________________|    |____    |
 |   |                                        |   |
 |   |     __________      ______________     |   |
 |   |    |          \    |              |    |   |  
 |   |    |    ____   \   |     _________|    |   |
 |   |    |   |    \   \  |    |              |   |
 |   |    |   |     |   |  \    \________     |   |
 |   |    |   |     |   |   \            |    |   |              ___   ___  __             ___   __   __   ___  ___
 |   |    |   |     |   |    \_______    |    |   |             |   | |__/ |__| \    /    |___  |__| |__| |    |__
 |   |    |   |     |   |            |   |    |   |             |__/  |  | |  |  \/\/      ___| |    |  | |___ |___
 |   |    |   |____/    |  __________|   |    |   |
 |   |    |            /  |              |    |   |
 |   |    |___________/   |______________|    |   |
 |   |                                        |   |
 |   |___________________________________     |   |
 |                                       |    |   |
 |_______________________________________|    |___|

</pre>

# DrawSpace

# Objetivo

O objetivo deste app é proporcionar ao usuário a possibilidade de realizar apresetações ou lecionar com maior facilidade e clareza. Será um overlay de tela, para que possa desenhar traços ou objetos por cima de qualquer area de trabalho ou aplicativo, para fins de explicação ou documentação.

Este é um projeto desenvolvido dentro da Universidade San Franscisco no curso de Análise e Desenvolvimento de Sistemas, na materia de "PRÁTICA PROFISSIONAL: PROJETO E DESENVOLVIMENTO DE SOFTWARE"

# Desenvolvimento

Este projeto é totalmente em java, e, tem suporte para operar no sistema operacional Microsoft Windows. Atualmente o projeto estará efetuando o primeiro entregável dia 30/11/2020, porém o projeto permanecerá em constante evolução.

# Requisitos

Até o momento, não será necessário instalações adicionais, ou hardware. Mas recomenda-se uma quantidade de ao menos 4GB de memória Ram por conta do uso de elementos gráficos.

O fluxo de processo do projeto foi projetado da seguinte forma:
https://drive.google.com/file/d/1GEm6I0x-qGtRJ-2irU02zsHqc-5VVzQR/view?usp=sharing

# Histórico de decisões
```
1. O projeto inicialmente será desenvolvido em Java Swing.
```
```
2. Foram desenvolvidas as primeiras interfaces utilizando o conceito Glasspane da Oracle. Mas foi constatado que o projeto avançado por este meio seria insustentável e complexo, ficaria fora da margem de tempo, assim houve um retrabalho: A busca por uma tecnologia que facilitasse o desenvolvimento e agregasse em componentes.
```
```
3. Foi decidido que o projeto seria totalmente desenvolvido em JavaFx.
```

# How to Work with JavaFx

Este projeto foi executado totalmente em JavaFx, para uma estrutura MVC simples, de fácil entendimento e correspondência mais ágil na codificação.

  ## Considereções
  "A API JavaFX é usada para a criação de aplicações RIA (Rich Internet Application) que se comportam de maneira consistente em todas as plataformas, não sendo necessário recompilar o código fonte para ser executada em diferentes JVMs, desde que estas estejam na mesma versão na qual o código foi compilado.

  O termo RIA é usado para descrever Aplicações Ricas para a Internet, ou seja, aplicações que são executadas em ambiente web, mas que possuem características similares a softwares desenvolvidos para execução em ambientes desktop.

  O desenvolvimento de aplicações em JavaFX pode fazer uso de qualquer biblioteca Java, acessar recursos nativos do sistema ou se conectar a aplicativos de middleware baseados em servidor." --DevMedia: https://www.devmedia.com.br/javafx-8-uma-introducao-a-arquitetura-e-as-novidades-da-api/33702
  
Arquitetura JavaFX:

![Arquitetura JAVAFX](https://arquivo.devmedia.com.br/REVISTAS/easyjava/imagens/55/1/1.png)

  O JavaFX através de sua linguagem FXML baseada em XML, permite a criação de interfaces podendo utilizar de recursos em HTML e CSS. Apesar deste, não existe apenas uma maneira de desenvolvimento de interfaces, existe ainda uma biblioteca de moldagem disponibilizada pela oracle chamada de Scence Builder ([instalação](https://www.youtube.com/watch?v=voRcD0cZCjA). Ainda você pode realizar o desenvolvimento "inCode", que apartir da inicialização dos elementos você pode ir instanciando e estilizando os aspectos de interface.

## Curso recomendado:
[![Link para Curso de JavaFX](http://img.youtube.com/vi/P13ycvI-17Q/0.jpg)](http://www.youtube.com/watch?v=P13ycvI-17Q "Curso de JavaFX")

# Utilização
Ao iniciar o software, o usuário como padrão estará com a opção pincel, cor branca e tamanho 18, assim, caso o usuário clique e arraste o seu mouse pela tela, as linhas serão
desenhadas na tela:

![Primeiro Desenho](https://github.com/igormonte/DrawSpace/blob/master/1.jpg)

Para acessar o menu, clique no botão "[>>]" no topo direito:

![Acesso ao Menu](https://github.com/igormonte/DrawSpace/blob/master/2.jpg)

Para mudar os aspectos do menu selecione as opções desejadas:

![Acesso ao Menu](https://github.com/igormonte/DrawSpace/blob/master/3.jpg)

## Aspectos:

  ### Arquivo
  Em arquivo você pode salvar seu desenho, persistindo o arquivo na arvore do projeto
  
  ### Formas
  Em formas você pode selecionar a opção circulo ou retângulo para faciliar a circulação de algum elemento na tela
  
  ### Tamanho
  O tamanho default da linha é 18, alterando o valor, você poderá aumentar ou diminuir da forma que desejar
  
  ### Cor
  A cor default é branca, clicando neste objeto você terá acesso a mais opções de cor.
  
  ### Pincel
  Ao clicar neste botão você estará apto a desenhar elementos gráficos a mão livre.
  
  ### Borracha  
  Ao clicar neste botão você estará apto a apagar qualquer elemento gráfico do canvas.
