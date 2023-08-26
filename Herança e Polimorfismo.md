# Herança em C#

A herança é um conceito fundamental na programação orientada a objetos (POO) que permite criar novas classes baseadas em classes existentes. A classe derivada (subclasse) herda os membros da classe base (superclasse), incluindo campos, propriedades e métodos. Isso promove a reutilização de código e a criação de hierarquias de classes.

# Sintaxe de Herança
```csharp

json public class ClasseBase
{
    // Membros da classe base
}

public class ClasseDerivada : ClasseBase
{
    // Membros adicionais e/ou sobreescrita
}
```
# Polimorfismo em C#

O polimorfismo é um conceito que permite que um único nome (método ou propriedade) tenha diferentes implementações em classes diferentes. Isso é alcançado por meio de herança e interfaces. O polimorfismo permite tratar objetos de diferentes classes de forma uniforme, melhorando a flexibilidade e a extensibilidade do código

# Polimorfismo de Método (Sobrescrita)

```csharp

public class ClasseBase
{
    public virtual void Metodo()
    {
        // Implementação na classe base
    }
}

public class ClasseDerivada : ClasseBase
{
    public override void Metodo()
    {
        // Implementação na classe derivada
    }
}
```
# Polimorfismo de Interface

```csharp
public interface IForma
{
    void Desenhar();
}

public class Circulo : IForma
{
    public void Desenhar()
    {
        // Implementação do desenho de um círculo
    }
}

public class Quadrado : IForma
{
    public void Desenhar()
    {
        // Implementação do desenho de um quadrado
    }
}
```

O polimorfismo de método (sobrescrita) e o polimorfismo de interface são maneiras poderosas de criar código flexível e reutilizável em C#. Eles permitem que você trabalhe com classes derivadas ou classes que implementam a mesma interface de maneira uniforme.

Espero que esses guias em Markdown tenham sido úteis! Se tiver mais dúvidas ou precisar de mais informações, sinta-se à vontade para perguntar.
