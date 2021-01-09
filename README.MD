 - Tomar cuidado com a coesão de uma classe.
  Cada classe deve ser responsável por apenas uma coisa, e deve executar esta tarefa muito bem.


 - O encapsulamento sempre deve ser respeitado,
 as pessoas não precisam saber como sua implementação funciona, ela deve ser encapsulada em uma classe/método de um jeito que seja possível utilizar essa classe de modo simples.

 O fato de criar getters e setters para tudo, na verdade, quebra o encapsulamento da nossa classe.

 Ao encapsular o acesso a determinados dados, liberando acesso apenas ao necessário, os objetos da nossa classe se tornam mais fáceis de serem utilizados.


 - Uma abstração é menos propensa a modificações, então a quantidade de abstrações é proporcional ao nivel de maturidade necessário para não se ter tantas dependencias no sistema.

 É fato que, se estamos organizando o nosso código, seguindo as recomendações da orientação a objetos, algum acoplamento acontecerá. Algumas classes precisarão de outras, para que não tenham muitas responsabilidades. Cabe a nós medir quando faz sentido adicionar tal acoplamento com as dependências e como depender do que é seguro, ao invés de classes concretas.
 
 