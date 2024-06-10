# Questões de Programação Orientada a Objetos com Java

## Questão 1
**Em Java, qual das opções abaixo define a relação de herança entre duas classes?**

- A) `implements`
- B) `extends`
- C) `inherits`
- D) `uses`

**Resposta:** B) `extends`

**Comentário:** A palavra-chave `extends` é usada em Java para indicar que uma classe herda de outra, estabelecendo uma relação de herança entre a subclasse e a superclasse.

---

## Questão 2
**Qual das seguintes opções é verdadeira sobre o encapsulamento em Java?**

- A) Permite acessar os atributos diretamente de fora da classe
- B) Envolve esconder os detalhes de implementação e expor apenas métodos públicos
- C) É uma técnica para herdar atributos e métodos de outra classe
- D) Permite a criação de múltiplas instâncias de uma classe

**Resposta:** B) Envolve esconder os detalhes de implementação e expor apenas métodos públicos

**Comentário:** Encapsulamento é um princípio da POO que visa ocultar os detalhes internos de um objeto e fornecer uma interface pública controlada para acesso e modificação.

---

## Questão 3
**Em Java, qual modificador de acesso permite que uma variável ou método seja acessível apenas dentro da mesma classe?**

- A) `public`
- B) `protected`
- C) `private`
- D) `default`

**Resposta:** C) `private`

**Comentário:** O modificador `private` restringe o acesso a membros de classe, permitindo que eles sejam acessados apenas dentro da própria classe.

---

## Questão 4
**Qual é o objetivo de usar herança em Java?**

- A) Permitir a execução simultânea de múltiplos métodos
- B) Permitir que uma classe utilize atributos e métodos de outra classe
- C) Melhorar a eficiência do código
- D) Restringir o acesso a métodos e atributos

**Resposta:** B) Permitir que uma classe utilize atributos e métodos de outra classe

**Comentário:** Herança permite que uma classe (subclasse) herde atributos e métodos de outra classe (superclasse), promovendo a reutilização de código e a criação de hierarquias de classes.

---

## Questão 5
**Em Java, qual palavra-chave é usada para criar uma classe que não pode ser instanciada?**

- A) `static`
- B) `abstract`
- C) `final`
- D) `private`

**Resposta:** B) `abstract`

**Comentário:** A palavra-chave `abstract` é usada para declarar uma classe que não pode ser instanciada diretamente e pode conter métodos abstratos que devem ser implementados por subclasses.

---

## Questão 6
**Qual é a principal diferença entre métodos `overloading` e `overriding` em Java?**

- A) `Overloading` refere-se a herdar métodos; `overriding` refere-se a criar métodos
- B) `Overloading` permite criar múltiplos métodos com o mesmo nome mas assinaturas diferentes; `overriding` permite redefinir métodos da superclasse na subclasse
- C) `Overloading` permite acessar métodos privados; `overriding` permite acessar métodos protegidos
- D) `Overloading` é usado para métodos estáticos; `overriding` é usado para métodos de instância

**Resposta:** B) `Overloading` permite criar múltiplos métodos com o mesmo nome mas assinaturas diferentes; `overriding` permite redefinir métodos da superclasse na subclasse

**Comentário:** `Overloading` é a criação de métodos com o mesmo nome mas com diferentes parâmetros. `Overriding` é a redefinição de um método da superclasse em uma subclasse com a mesma assinatura.

---

## Questão 7
**Qual dos seguintes não é um princípio da programação orientada a objetos?**

- A) Encapsulamento
- B) Polimorfismo
- C) Herança
- D) Recursão

**Resposta:** D) Recursão

**Comentário:** Recursão não é um princípio da POO. Os principais princípios da POO são encapsulamento, polimorfismo, herança e abstração.

---

## Questão 8
**Em Java, qual é o efeito de declarar uma classe como `final`?**

- A) A classe não pode ser instanciada
- B) A classe não pode ser herdada
- C) A classe não pode conter métodos abstratos
- D) A classe só pode ser usada em pacotes específicos

**Resposta:** B) A classe não pode ser herdada

**Comentário:** A palavra-chave `final` impede que uma classe seja estendida, ou seja, outras classes não podem herdar dela.

---

## Questão 9
**Qual é a vantagem de usar interfaces em Java?**

- A) Permitem a implementação de múltiplas heranças
- B) Permitem a criação de atributos protegidos
- C) Permitem herdar o comportamento de várias classes ao mesmo tempo
- D) Permitem criar métodos concretos que não podem ser sobrescritos

**Resposta:** C) Permitem herdar o comportamento de várias classes ao mesmo tempo

**Comentário:** Interfaces permitem que uma classe implemente múltiplas interfaces, herdando comportamentos diversos, algo que não é possível com herança de classes (múltiplas heranças).

---

## Questão 10
**Em Java, qual é a função do modificador de acesso `protected`?**

- A) Permitir acesso somente dentro da própria classe
- B) Permitir acesso dentro da própria classe e subclasses
- C) Permitir acesso a qualquer classe em qualquer pacote
- D) Permitir acesso somente a subclasses em pacotes diferentes

**Resposta:** B) Permitir acesso dentro da própria classe e subclasses

**Comentário:** O modificador `protected` permite que membros de uma classe sejam acessíveis dentro da mesma classe e também por subclasses, mesmo que estejam em pacotes diferentes.

---

## Questão 11
**Qual das seguintes opções descreve corretamente o conceito de polimorfismo em Java?**

- A) Capacidade de uma classe herdar de múltiplas classes
- B) Capacidade de um método ter diferentes implementações com a mesma assinatura
- C) Capacidade de uma classe ser abstrata e concreta ao mesmo tempo
- D) Capacidade de um objeto mudar sua classe em tempo de execução

**Resposta:** B) Capacidade de um método ter diferentes implementações com a mesma assinatura

**Comentário:** Polimorfismo permite que métodos em diferentes classes tenham a mesma assinatura mas implementações distintas, promovendo flexibilidade no design de sistemas.

---

## Questão 12
**Qual é a função do método `super` em Java?**

- A) Acessar métodos e atributos estáticos da classe
- B) Chamar métodos e construtores da classe pai
- C) Chamar métodos e construtores da classe atual
- D) Criar instâncias de classes anônimas

**Resposta:** B) Chamar métodos e construtores da classe pai

**Comentário:** A palavra-chave `super` é usada para referenciar a superclasse imediata, permitindo chamar métodos e construtores da classe pai.

---

## Questão 13
**Qual é o propósito de usar um construtor em Java?**

- A) Destruir um objeto
- B) Inicializar um objeto
- C) Comparar dois objetos
- D) Criar métodos estáticos

**Resposta:** B) Inicializar um objeto

**Comentário:** Construtores são usados para inicializar novos objetos de uma classe, atribuindo valores iniciais aos atributos do objeto e executando outras configurações necessárias.

---

## Questão 14
**Em Java, qual palavra-chave é usada para implementar uma interface?**

- A) `extends`
- B) `implements`
- C) `inherits`
- D) `uses`

**Resposta:** B) `implements`

**Comentário:** A palavra-chave `implements` é usada para indicar que uma classe está fornecendo implementações para os métodos definidos por uma interface.

---

## Questão 15
**Em Java, qual é a principal diferença entre uma classe e uma interface?**

- A) Uma classe pode ter apenas métodos abstratos; uma interface pode ter métodos concretos
- B) Uma interface pode ter apenas métodos abstratos; uma classe pode ter métodos concretos e abstratos
- C) Uma classe não pode ser instanciada; uma interface pode
- D) Uma interface pode herdar de várias classes; uma classe pode herdar de uma só

**Resposta:** B) Uma interface pode ter apenas métodos abstratos; uma classe pode ter métodos concretos e abstratos

**Comentário:** Uma interface define um contrato com métodos abstratos que devem ser implementados por classes, enquanto uma classe pode conter métodos com implementação (concretos) e sem implementação (abstratos).

---

## Questão 16
**Qual das seguintes opções não é permitida em Java ao usar herança?**

- A) Uma classe pode herdar de outra classe
- B) Uma classe pode implementar múltiplas interfaces
- C) Uma classe pode herdar de múltiplas classes
- D) Uma interface pode herdar de outra interface

**Resposta:** C) Uma classe pode herdar de múltiplas classes

**Comentário:** Java não permite herança múltipla de classes. Uma classe só pode herdar de uma única classe, mas pode implementar múltiplas interfaces.

---

## Questão 17
**Qual das seguintes opções descreve corretamente a sobrecarga de métodos (`method overloading`) em Java?**

- A) Definir múltiplos métodos com o mesmo nome mas diferentes assinaturas
- B) Definir múltiplos métodos com o mesmo nome e mesma assinatura em diferentes classes
- C) Substituir o método de uma classe pai em uma classe filha
- D) Criar métodos com nomes diferentes mas assinaturas semelhantes

**Resposta:** A) Definir múltiplos métodos com o mesmo nome mas diferentes assinaturas

**Comentário:** Sobrecarga de métodos permite que uma classe tenha múltiplos métodos com o mesmo nome, desde que tenham diferentes parâmetros (assinaturas diferentes).

---

## Questão 18
**Em Java, o que significa que um método é `abstract`?**

- A) O método não pode ser chamado diretamente
- B) O método tem uma implementação padrão
- C) O método deve ser implementado por qualquer classe que herda a classe que o contém
- D) O método só pode ser usado em classes internas

**Resposta:** C) O método deve ser implementado por qualquer classe que herda a classe que o contém

**Comentário:** Métodos abstratos são definidos sem implementação em uma classe abstrata e devem ser implementados por qualquer classe concreta que herda a classe abstrata.

---

## Questão 19
**Em Java, qual é o comportamento de um método estático (`static`)?**

- A) Pode acessar diretamente variáveis de instância
- B) Não pode ser chamado por outras classes
- C) Pertence à classe em vez de a uma instância da classe
- D) Pode acessar apenas variáveis locais

**Resposta:** C) Pertence à classe em vez de a uma instância da classe

**Comentário:** Métodos `static` pertencem à classe como um todo e não a uma instância específica, podendo ser chamados diretamente usando o nome da classe.

---

## Questão 20
**Qual das seguintes afirmações sobre interfaces em Java é verdadeira?**

- A) Interfaces podem conter apenas métodos concretos
- B) Interfaces não podem ser instanciadas
- C) Interfaces podem herdar de classes
- D) Interfaces podem conter atributos não estáticos

**Resposta:** B) Interfaces não podem ser instanciadas

**Comentário:** Interfaces definem contratos de métodos que devem ser implementados por classes, mas não podem ser instanciadas diretamente.

---

## Questão 21
**Em Java, o que é um construtor padrão?**

- A) Um construtor que é gerado automaticamente pela JVM se nenhum construtor for definido
- B) Um construtor que aceita um número variável de argumentos
- C) Um construtor que precisa ser implementado manualmente
- D) Um construtor que sempre aceita parâmetros

**Resposta:** A) Um construtor que é gerado automaticamente pela JVM se nenhum construtor for definido

**Comentário:** Se nenhuma definição de construtor for fornecida em uma classe, a JVM cria um construtor padrão sem parâmetros que inicializa os atributos com valores padrão.

---

## Questão 22
**Qual é a principal vantagem de usar classes abstratas em Java?**

- A) Permitir múltiplas heranças
- B) Forçar subclasses a implementar métodos específicos
- C) Evitar a criação de métodos privados
- D) Permitir a criação de instâncias da classe

**Resposta:** B) Forçar subclasses a implementar métodos específicos

**Comentário:** Classes abstratas permitem definir métodos abstratos que devem ser implementados pelas subclasses, garantindo que certas funcionalidades sejam fornecidas por todas as subclasses.

---

## Questão 23
**Em Java, qual é o comportamento de uma variável estática (`static`)?**

- A) Pertence à instância da classe
- B) Pode ser acessada apenas dentro da classe
- C) Pertence à classe e não à instância específica
- D) É inicializada apenas uma vez, independentemente do número de instâncias

**Resposta:** C) Pertence à classe e não à instância específica

**Comentário:** Variáveis `static` pertencem à classe como um todo e compartilham o mesmo valor para todas as instâncias da classe.

---

## Questão 24
**Qual das seguintes opções é verdadeira sobre a palavra-chave `final` em Java?**

- A) Pode ser usada para impedir que classes sejam estendidas
- B) Pode ser usada para criar métodos abstratos
- C) Permite que variáveis sejam modificadas após inicialização
- D) Permite que classes sejam herdadas

**Resposta:** A) Pode ser usada para impedir que classes sejam estendidas

**Comentário:** A palavra-chave `final` pode ser usada para declarar classes que não podem ser estendidas, métodos que não podem ser sobrescritos e variáveis cujos valores não podem ser modificados após a inicialização.

---

## Questão 25
**Qual é o propósito do polimorfismo em Java?**

- A) Permitir a herança múltipla
- B) Permitir a substituição de métodos de uma classe pai por uma classe filha
- C) Permitir a criação de classes abstratas
- D) Permitir a criação de métodos estáticos

**Resposta:** B) Permitir a substituição de métodos de uma classe pai por uma classe filha

**Comentário:** Polimorfismo permite que métodos em subclasses substituam métodos da superclasse, proporcionando flexibilidade para que um método possa ser utilizado de diferentes formas com base no objeto que o chama.

---

## Questão 26
**Em Java, o que acontece se uma classe herdar de uma classe abstrata sem implementar todos os seus métodos abstratos?**

- A) A classe pode ser instanciada normalmente
- B) A classe se torna abstrata e precisa ser declarada como tal
- C) A classe gera um erro de compilação
- D) A classe não pode ser usada para herança

**Resposta:** B) A classe se torna abstrata e precisa ser declarada como tal

**Comentário:** Se uma classe herda de uma classe abstrata e não implementa todos os métodos abstratos, ela também deve ser declarada como abstrata, não podendo ser instanciada diretamente.

---

## Questão 27
**Qual das seguintes opções descreve corretamente a agregação em Java?**

- A) Uma relação "parte-todo" forte onde o ciclo de vida das partes depende do todo
- B) Uma relação "parte-todo" fraca onde o ciclo de vida das partes não depende do todo
- C) Uma técnica para implementar herança múltipla
- D) Uma técnica para sobrecarregar métodos

**Resposta:** B) Uma relação "parte-todo" fraca onde o ciclo de vida das partes não depende do todo

**Comentário:** Agregação é uma relação "parte-todo" onde os componentes podem existir independentemente do objeto que os agrega, representando uma relação menos rígida em comparação à composição.

---

## Questão 28
**Qual das seguintes opções melhor descreve o conceito de encapsulamento em Java?**

- A) Ocultar a implementação interna e expor apenas a interface pública
- B) Permitir herança múltipla
- C) Facilitar a sobrecarga de métodos
- D) Permitir que métodos privados sejam acessados externamente

**Resposta:** A) Ocultar a implementação interna e expor apenas a interface pública

**Comentário:** Encapsulamento é a prática de ocultar os detalhes de implementação de um objeto e expor apenas os métodos necessários para interagir com ele, promovendo a modularidade e a segurança do código.

---

## Questão 29
**Em Java, qual é o uso principal do modificador `abstract` em uma classe?**

- A) Indicar que a classe não pode conter métodos concretos
- B) Indicar que a classe não pode ser estendida
- C) Indicar que a classe não pode ser instanciada diretamente e pode conter métodos abstratos
- D) Indicar que a classe deve ser estendida para ser usada

**Resposta:** C) Indicar que a classe não pode ser instanciada diretamente e pode conter métodos abstratos

**Comentário:** O modificador `abstract` é usado para declarar uma classe que não pode ser instanciada diretamente e que pode incluir métodos abstratos, os quais devem ser implementados por subclasses concretas.

---

## Questão 30
**Em Java, o que é um bloco `static`?**

- A) Um bloco que é executado sempre que um método estático é chamado
- B) Um bloco que é executado apenas uma vez quando a classe é carregada
- C) Um bloco que é executado toda vez que uma instância da classe é criada
- D) Um bloco que só pode conter variáveis locais

**Resposta:** B) Um bloco que é executado apenas uma vez quando a classe é carregada

**Comentário:** Blocos `static` são executados uma única vez quando a classe é carregada pela JVM, sendo úteis para inicializar variáveis estáticas.

---

## Questão 31
**Em Java, qual é a principal função do polimorfismo?**

- A) Permitir que uma classe herde de múltiplas classes
- B) Permitir que um método se comporte de forma diferente com base no objeto que o invoca
- C) Permitir a criação de métodos privados
- D) Permitir a sobrecarga de métodos

**Resposta:** B) Permitir que um método se comporte de forma diferente com base no objeto que o invoca

**Comentário:** O polimorfismo permite que o mesmo método se comporte de forma diferente dependendo do objeto que o invoca, proporcionando flexibilidade e reutilização de código.

---

## Questão 32
**Qual das seguintes opções melhor descreve o conceito de composição em Java?**

- A) Uma relação "parte-todo" onde a parte depende completamente do todo
- B) Uma técnica para permitir múltiplas heranças
- C) Uma maneira de sobrecarregar métodos
- D) Uma técnica para garantir encapsulamento

**Resposta:** A) Uma relação "parte-todo" onde a parte depende completamente do todo

**Comentário:** Composição é uma relação "parte-todo" onde os componentes não podem existir independentemente do objeto pai, indicando uma forte dependência entre as partes e o todo.

---

## Questão 33
**Em Java, qual é a diferença principal entre uma classe abstrata e uma interface?**

- A) Uma classe abstrata pode ter métodos com corpo; uma interface não pode
- B) Uma classe abstrata não pode ser herdada; uma interface pode
- C) Uma interface pode ser instanciada diretamente; uma classe abstrata não pode
- D) Uma classe abstrata só pode ter métodos estáticos; uma interface pode ter qualquer tipo de método

**Resposta:** A) Uma classe abstrata pode ter métodos com corpo; uma interface não pode

**Comentário:** Classes abstratas podem ter métodos concretos com implementação, enquanto interfaces em versões anteriores do Java não podiam ter métodos com corpo, embora isso tenha mudado nas versões mais recentes com métodos default e static.

---

## Questão 34
**Qual das seguintes opções melhor descreve a sobrecarga de operadores em Java?**

- A) Java permite a sobrecarga de operadores para classes personalizadas
- B) Java permite a sobrecarga de operadores apenas para tipos primitivos
- C) Java não suporta a sobrecarga de operadores
- D) Java permite a sobrecarga de operadores apenas para classes internas

**Resposta:** C) Java não suporta a sobrecarga de operadores

**Comentário:** Java não suporta sobrecarga de operadores. Os operadores têm comportamentos definidos e não podem ser alterados para tipos personalizados.

---

## Questão 35
**Qual das seguintes afirmações sobre o uso de `super` em Java é verdadeira?**

- A) `super` pode ser usado para acessar membros privados da superclasse
- B) `super` pode ser usado para chamar o construtor da superclasse
- C) `super` pode ser usado para acessar variáveis locais da classe filha
- D) `super` pode ser usado para criar instâncias da superclasse

**Resposta:** B) `super` pode ser usado para chamar o construtor da superclasse

**Comentário:** `super` é usado para chamar o construtor da superclasse ou para acessar membros da superclasse que foram ocultados por membros de mesmo nome na subclasse.

---
