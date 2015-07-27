Antes de chegar onde interessa e começar a codar, vamos voltar um pouco e entender melhor como surgiu o JS... 

Quando codamos páginas web, utilizamos o HTML (linguagem de marcação) que compõe toda a estrutura do documento a partir de tags, possibilitando a identificação e interpretação do código pelo browser para montar alguns elementos. A estilização desses elementos na página acontece através do CSS (Cascading Style Sheets), deixando tudo mais bonito com vários elementos visuais como backgrounds, imagens, rotação, gradiente e etc. Entretanto,  utilizando HTML + CSS temos apenas documentos **estáticos**, sem interação com o usuário, como conteúdos dinâmicos e validação de formulários.

Isso tudo mudou quando houve a grande sacada de mestre e na década de 90  um carinha chamado Brendan Eich que trabalhava na Netscape teve a brilhante ideia e desenvolveu uma linguagem de script chamada Mocha, que posteriormente foi renomeada para Livescript e por fim Javascript, sendo lançada para o browser Netscape 2.0.

![](http://t.qkme.me/3oin0m.jpg)


Aplicações que utilizam javascript, nos oferecem 

**Interatividade**

Interação entre pessoas e sistemas. No caso, quando há uma ação e reação que modifica o estado atual do sistema. Exemplos: calculadoras, personalização de páginas pelo usuário e etc. 

**Validação de Formulários**

Validação dos dados inseridos pelos usuários através de formulários. 
A verificação ocorre ainda no browser, antes do envio dos dados ao servidor para processamento/armazenamento. Além de ser mais eficiente, evita que o formulário seja recarregado e retornado vazio. Afinal é super legal preencher 2348 campos, esquecer de algum obrigatório e ser obrigada a preencher todos os campos novamente. #sqn

![](http://3.bp.blogspot.com/-4gO-6j8KirM/UbPypqqpKaI/AAAAAAAAAdo/ufPdHapfxmE/s1600/Nooo.jpg)


**Controle de Comportamento e Personalização da Página** 

O comportamento dos elementos bem como a formatação do layout da página podem ser controlados via scripts. Como por exemplo, definir alguma ação quando o usuário clicar, digitar, selecionar e etc.
Para isso podemos utilizar uma combinação muito legal de HTML, JS, CSS e DOM, o famoso **DHTML**. Que deixou de ser tão falado assim com a chegada do HTML5 que também é utilizado para se referir a união de toda essa galerinha.

**Dinamismo**

Com o JS é possível atualizar o conteúdo de partes específicas da página sem precisar dar reload na página inteira. Isso ocorre graças a técnica de programação AJAX, que une HTML, CSS, XML/JSON e JS em conjunto com alguma outra tecnologia server-side  + banco de dados. 



Um pouco sobre as **principais características**:


**Client-Side**

Sua execução ocorre diretamente no browser, independente do servidor. Não necessita ser compilada ! 


**Fracamente/Dinamicamente Tipada**

Quando declaramos uma variável não definimos qual o tipo dela (int, bool, etc). Isso permite o armazenamento da informação que quisermos, pois não é definido na declaração. É também considerado dinamicamente tipada pois durante a execução podem alterar o tipo de dados contido em uma variável.

**Exemplo:**

var qualquerCoisa= 10;
qualquerCoisa = "JSGirls";

**Obs.:** A variável qualquerCoisa não tem tipo definido, mas recebeu conteúdo do tipo int e depois string;


**Case Sensitive**

Em JS deve-se respeitar as letras maiúsculas e as minúsculas. 

**Exemplo:** 
var qualquerCoisa = "JS";
var qualquercoisa = "GIRLS";
alert(qualquercoisa);


**Estruturada/Orientada à Objetos** 

Apesar da linguagem ter sido criada seguindo o paradigma de programação Estruturada, ela também pode ser programada no paradigma Orientado à Objetos (OO). 


**Hello World**

https://goo.gl/vNN86I


### ATENÇÃO

Inicialmente o nome **JavaScript** foi motivo de confusão devido a semelhança com o nome da linguagem Java, mas essas duas tecnologias não estão diretamente relacionadas. Ou seja, JavaScript não é uma implementação especial do Java. Ok !?

Assim como o próprio site do [Java](http://www.java.com/pt_BR/download/faq/java_javascript.xml) diz:

A linguagem de programação JavaScript, desenvolvida pela Netscape, Inc., não faz parte da plataforma Java.

Diferenças-chave entre o Java e o JavaScript:
  + Java é uma linguagem de programação OOP, ao passo que Java Script é uma linguagem de scripts OOP.
  + Java cria aplicações executadas em uma máquina virtual ou em um browser, ao passo que o código JavaScript é executado apenas em um browser.
  + O código Java precisa ser compilado, ao passo que os códigos JavaScript estão totalmente em texto.
  + Eles requerem plug-ins diferentes.


----
*Itens faltantes:

- ECMAScript
- Ferramentas
- Mercado Atual
- Referências
