

<h5> Sou implantador de sistemas web ERP voltados para indústrias, já atuei como desenvolvedor web, e atualmente estou focado em aprimorar minhas habilidades no desenvolvimento backend e desbravar novas tecnologias.</h5>


### About me
---
```csharp
public class SobreMim
{
    public string Nome { get; set; } = "Vitor Brito";
    public string[] Tecnologias { get; set; } = new string[]
    {
        "C#", "ASP.NET Core", "Entity Framework", "SQL Server", "Docker",
        "HTML", "CSS", "Bootstrap"
    };
    public override string ToString()
    {
        return $"Me chamo {Nome}, e desenvolvo habilidades utilizando as tecnologias: {string.Join(", ", Tecnologias)}.";
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
        "Postman Json",
        "Visual Studio Code",
        "GitHub"
    };
}
```

