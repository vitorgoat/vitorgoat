---

### Sou apaixonado por tecnologia!

Já atuei como desenvolvedor web, sou implantador de sistemas web ERP voltado para indústria e atualmente estou concentrado em aprimorar minhas habilidades com desenvolvimento backend e novas tecnologias.

```csharp
public class SobreMim
{
    public string Nome { get; set; } = "Vitor";
    public string[] Tecnologias { get; set; } = new string[]
    {
        "C#", "ASP.NET Core", "Entity Framework", "SQL Server", "Docker",
        "HTML", "CSS", "Bootstrap"
    };
    public override string ToString()
    {
        return $"Me chamo {Nome}, e estou desenvolvendo habilidades utilizando as tecnologias: {string.Join(", ", Tecnologias)}.";
    }
}

public class Habilidades
{
    public string[] Linguagens { get; set; } = new string[]
    {
        "C#"
    };

    public string[] BancoDeDados { get; set; } = new string[]
    {
        "Microsoft SQL Server"
    };

    public string[] Ferramentas { get; set; } = new string[]
    {
        "Azure Data Studio",
        "Postman",
        "Visual Studio Code",
        "GitHub"
    };

   public override string ToString()
   {
     return $"Habilidades" +
            $"Linguagens: {string.Join(", ", Linguagens)} "+
            $"Banco de Dados: {string.Join(", ", BancoDeDados)} "+
            $"Ferramentas: {string.Join(", ", Ferramentas)}";
   }

}
