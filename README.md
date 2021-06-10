# DIO-Curso .NET
Curso de C# - DIO 

 - Iniciando com .net
 - Criando uma aplicação console
 - Estrutura de Programa
 - Tipos de Valor
   - Numéricos: sbyte, short, int, long, byte, ushort, uint, ulong
   - Caracteres Unicode: char
   - Pontos flutuantes: float, double, decimal
   - Booleano: bool
   - enum, struct e tipos nullable
 - Tipos de referencias
   - Tipos Classe: class, object, string
   - Tipos Arrays: int[], int[,], etc...
   - interface, delegate 
 - Utilizando instruções em programas
   - Declaração de variaveis e constantes locais
   - if
   - switch
   - while
   - do
   - for
   - foreach
 - Instruções auxiliares
   - break  
   - continue  
   - return
   - throw
   - try .. catch .. finally
   - using  
 - Exemplificando o conteudo
 - O Que são Classes e Objetos em C#
   - Classe: É uma estrutura de dados que combina estado (campos) e ações (métodos)
   - Objetos: São instancias de uma classe
 ## Exemplo de Classes e Objetos

 ``` public class Ponto
 {
     public int x, y;
     public Ponto (int x, int y)
     {
       this.x = x;
       this.y = y;
     } 
 } 
```

 - Como aplicar classes e objetos em projetos 
 - O que são Structs
   - Assim como as classes, as _structs_ são estruturas de dados que podem conter membros de dados e membros de ação, mas, diferentemente das classes, as _structs_ são tipos de valor e não requerem alocação de **heap** .
   Uma variável de um tipo de _struct_ armazena diretamente os dados da estrutura, quando uma variável de um tipo classe armazena uma referencia a um objeto alocado na memória.
   **_Structs_** não aceitam herança determinada pelo desenvolvedor
   São uteis para pequenas estruturas de dados que possuem semantica de valor: números complexos, pontos em um sistema de coordenadas ou pares de chave-valor em um dificionario são bons exemplos de utilização;
 - Entendendo a função de interfaces e enums