 - Tomar cuidado com a coesão de uma classe.
  Cada classe deve ser responsável por apenas uma coisa, e deve executar esta tarefa muito bem.


 - O encapsulamento sempre deve ser respeitado,
 as pessoas não precisam saber como sua implementação funciona, ela deve ser encapsulada em uma classe/método de um jeito que seja possível utilizar essa classe de modo simples.

 O fato de criar getters e setters para tudo, na verdade, quebra o encapsulamento da nossa classe.

 Ao encapsular o acesso a determinados dados, liberando acesso apenas ao necessário, os objetos da nossa classe se tornam mais fáceis de serem utilizados.


 - Uma abstração é menos propensa a modificações, então a quantidade de abstrações é proporcional ao nivel de maturidade necessário para não se ter tantas dependencias no sistema.

 É fato que, se estamos organizando o nosso código, seguindo as recomendações da orientação a objetos, algum acoplamento acontecerá. Algumas classes precisarão de outras, para que não tenham muitas responsabilidades. Cabe a nós medir quando faz sentido adicionar tal acoplamento com as dependências e como depender do que é seguro, ao invés de classes concretas.

     Coesão
        Uma classe coesa faz bem uma única coisa
        Classes coesas não devem ter várias responsabilidades
    Encapsulamento
        Getters e setters não são formas eficientes de aplicar encapsulamento
        É interessante fornecer acesso apenas ao que é necessário em nossas classes
        O encapsulamento torna o uso das nossas classes mais fácil e intuitivo
    Acoplamento
        Acoplamento é a dependência entre classes
        Acoplamento nem sempre é ruim, e que é impossível criar um sistema sem nenhum acoplamento
        Devemos controlar o nível de acoplamento na nossa aplicação (falaremos mais sobre isso)


Single Responsibility Principle
"Uma classe só deveria ter um único motivo para mudar"
Sua classe/método não deve ter mais de um motivo para ser modificada a não ser que sua regra de negócio mude !!


Open Closed Principle

"Entidades de software(classes, módulos, funções, etc) devem ser abgertas para expansão, porém fechadas para modificação".
Garantir que cada ação/responsabilidade esteja na classe correta faz com que você necessite repetir muito menos código, além de reduzir as alterações nos códigos já criados.

    Cada classe deve conhecer e ser responsável por suas próprias regras de negócio

    O princípio Aberto/Fechado (OCP) diz que um sistema deve ser aberto para a extensão, mas fechado para a modificação
        Isso significa que devemos poder criar novas funcionalidades e estender o sistema sem precisar modificar muitas classes já existentes
    
    Uma classe que tende a crescer "para sempre" é uma forte candidata a sofrer alguma espécie de refatoração

"Seja q(x) uma propriedade que se pode provar do objeto x do tipo T. Então, q(y) também é possivel provar para o objeto y do tipo S, sendo S um subtipo de T.
(Classes filhas nunca deveriam infringir as definições de tipo classe pai.)

    Embora a assinatura de um método esteja sendo respeitada em uma herança, ainda assim podemos estar quebrando algum contrato

    O Princípio de Substituição de Liskov (LSP) diz que devemos poder substituir classes base por suas classes derivadas em qualquer lugar, sem problema

    Não devemos alterar um comportamento de um método estendido, mesmo que a assinatura seja mantida

