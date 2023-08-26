# Meu Projeto Orientado a Objetos em C#

## Tecnologias Usadas

- Linguagem: C#
- Plataforma: .NET
- IDE Recomendada: Visual Studio
- Controle de Versão: Git

## Resumo das Melhorias no Projeto Orientado a Objetos

Neste projeto, foram implementadas diversas melhorias para tornar o código mais organizado, orientado a objetos e de fácil manutenção. Aqui está um resumo das principais melhorias realizadas:

1. **Organização em Pastas e Namespaces:**
   - Classes e tipos foram agrupados logicamente em pastas e namespaces.
   - O namespace `ScreenSound.Modelos` foi aplicado às classes `Album`, `Banda` e `Musica`, e seus arquivos foram separados na pasta `Modelos`.

2. **Orientação a Objetos no Program.cs:**
   - As classes `Banda` e `Album` foram incorporadas no arquivo `Program.cs`.
   - Isso tornou a aplicação mais orientada a objetos, melhorando a estrutura e a legibilidade.

3. **Encapsulamento de Notas:**
   - O encapsulamento de notas como parte de uma banda foi implementado.
   - Isso resultou em um código mais limpo e de fácil manutenção no futuro.

4. **Melhoria de Tipos Primitivos:**
   - Princípios de embrulho de tipos primitivos em conceitos maiores foram aplicados.
   - Isso permitiu adicionar comportamentos como validação e tradução.

5. **Visibilidade de Classes:**
   - Utilização das palavras-chave `internal` e `public` para definir a visibilidade de classes.
   - Classes `internal` só podem ser vistas dentro do projeto, enquanto classes `public` são visíveis por outros projetos.

6. **Métodos Estáticos:**
   - Identificação e uso de métodos estáticos, que não acessam informações de objetos específicos.
   - Exemplos de métodos estáticos incluem `Console.WriteLine()`, `int.Parse()` e `Thread.Sleep()`.

7. **Utilização da Classe `Program` e Método `Main()`:**
   - Explicação sobre a classe `Program` e seu método estático `Main()`.
   - A classe `Program` é o ponto de entrada de qualquer programa .NET.

8. **Evitando Classes e Métodos Extensos:**
   - A importância de evitar classes e métodos com muitas linhas para melhorar a manutenção e a legibilidade do código.

9. **Herança e Sobrescrita:**
   - Introdução ao conceito de herança para compartilhar comportamentos entre classes.
   - Uso das palavras-chave `virtual`, `override` e `base` para indicar comportamentos substituídos ou sobrescritos.

10. **Interfaces:**
    - Explanação sobre o uso de interfaces para garantir que diferentes tipos implementem os mesmos métodos e propriedades.
    - Interfaces são abstratas e não possuem código concreto.

## Exercício

Agora que você conheceu as melhorias feitas no projeto, é hora de praticar! Siga as instruções abaixo:

1. **Organização e Namespace:**
   - Crie um novo projeto C# ou utilize o existente.
   - Organize suas classes em pastas e utilize namespaces para agrupá-las logicamente.

2. **Orientação a Objetos:**
   - Incorpore classes em seu arquivo principal (por exemplo, Program.cs) para melhorar a orientação a objetos.

3. **Encapsulamento e Melhoria de Tipos:**
   - Escolha um conceito e encapsule tipos primitivos em um novo conceito maior.
   - Adicione comportamentos a esse conceito encapsulado.

4. **Visibilidade de Classes:**
   - Crie classes com diferentes níveis de visibilidade (`internal` e `public`) e observe como elas interagem.

5. **Métodos Estáticos e Classe `Program`:**
   - Crie um método estático em sua classe `Program` que realize uma tarefa específica.

6. **Evitando Extensões Excessivas:**
   - Divida um método extenso em partes menores e mais gerenciáveis.

7. **Herança e Interfaces:**
   - Crie uma hierarquia de classes usando herança e interfaces para compartilhar comportamentos.

8. **Comentários e README:**
   - Documente todas as etapas do seu exercício em um README para que outros possam entender o que você fez.

Lembre-se de que a prática é fundamental para aprimorar suas habilidades em programação orientada a objetos. Divirta-se explorando esses conceitos!


