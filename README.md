Atividade Prática de Programação Orientada a Objetos em Java

Este repositório contém a implementação das atividades práticas de Programação Orientada a Objetos (POO) utilizando Java, conforme as instruções da disciplina.  
Cada exercício foi desenvolvido de forma independente, abordando entrada de dados, cálculos, estruturas condicionais e laços de repetição.

---

Estrutura do Projeto

atividade-poo-java/
│
├── src/
│ ├── CalculadoraDesconto.java
│ ├── CalculadoraITBI.java
│ ├── SistemaAvaliacao.java
│ ├── CalculadoraAposentadoria.java
│ ├── CircuitoResistencias.java
│ ├── SistemaLogin.java
│ └── GeradorTabuada.java
│
└── README.md



Cada arquivo `.java` representa uma das tarefas solicitadas.

---

Tarefas Desenvolvidas

Calculadora de Desconto
- Utiliza `Scanner` para receber o valor de um produto e a porcentagem de desconto.
- Calcula e exibe o valor do desconto e o preço final do produto.

Calculadora de ITBI
- Utiliza `JOptionPane` para entrada de dados.
- Recebe o valor de transação, valor venal e porcentagem do imposto ITBI.
- O imposto é calculado sobre o maior valor entre o valor de transação e o valor venal.

Sistema de Avaliação
- Utiliza `JOptionPane` para coletar as notas de duas provas e um trabalho.
- Calcula a média e informa se o aluno está aprovado (média ≥ 6) ou reprovado.

Calculadora de Aposentadoria
- Utiliza `Scanner` para coletar idade, sexo e anos de contribuição.
- Determina se a pessoa já pode se aposentar ou quantos anos faltam.
- Regras utilizadas:
  - Homens: 65 anos de idade ou 35 anos de contribuição.
  - Mulheres: 62 anos de idade ou 30 anos de contribuição.

Circuito de Resistências
- Utiliza `Scanner` para receber quatro valores de resistências em série.
- Calcula e exibe:
  - A resistência equivalente (soma das resistências),
  - A maior resistência e a menor resistência.

Sistema de Login
- Simula um sistema de login com até 3 tentativas.
- Usuário e senha corretos: `java8`
- Exibe mensagens informativas a cada erro e bloqueia o acesso após três tentativas.

Gerador de Tabuada
- Solicita um número via `Scanner` e exibe sua tabuada de 1 a 10 usando um loop.

---

Como Executar os Programas

Cada classe pode ser compilada e executada individualmente no terminal:

```bash
 Compilar
javac NomeDaClasse.java

 Executar
java NomeDaClasse


Conceitos Abordados
Encapsulamento: uso de variáveis e métodos para manipular dados de forma controlada.

Entrada e saída de dados: via Scanner e JOptionPane.

Estruturas condicionais: if, else if, else para decisões lógicas.

Laços de repetição: for e while para executar repetições controladas.

Organização modular: cada classe realiza uma tarefa independente, seguindo boas práticas de separação de responsabilidades.
