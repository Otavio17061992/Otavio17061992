
<h1 align="center">Hi 👋, I'm João Mesquita</h1>
<img align="right" alt="Coding" width="330" src="https://miro.medium.com/max/680/0*7Q3yvSIv_t0ioJ-Z.gif"/>

<br>
<p><em>Developer of Software at <a href="https://www.geosaude.com.br">GeoSaude</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"></em></p>

  <h3 align="center">Social Media 🌎</h3>
  <div align="center">

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/otavio17061992/)
  [![instagram](https://img.shields.io/badge/instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/codafofo.ocx/)
  [![tiktok](https://img.shields.io/badge/tiktok-000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@dev_dequebrada/)
</div>
<div align="center">
  <h3 align="left">👨‍💻Languages and Tools:</h3>

  <div style="display: inline_block"><br>
    <img align="left" alt="Jon-Csharp" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
    <img align="left" alt="Jon-HTML" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
    <img align="left" alt="Jon-CSS" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
    <img align="left" alt="Jon-Docker" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
    <img align="left" alt="Jon-Csharp" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
    <img align="left" alt="Jon-Ts" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
    <img align="left" alt="C++ Logo" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg">
  </div>
</div>
<br>
<br>
<br>
<br>
<br>

```csharp 
public class Pessoa 
{
  public string Pronomes {get; set;}
  public string Name {get; set;}
  public int Idade {get; set;}
  public List<string> Architecture {get; set;}
  public List<string> Tools {get; set;}
}

Pessoa pessoaDev = new Pessoa
{
    Pronomes = "He | His",
    Name = "João",
    Idade = 30,
    Architecture = new List<string> {"microservices", "event-driven", "design system pattern"},
    Tools = new List<string> { "TypeScript", "C#" , "JavaScript", "React", "Docker"}
};
```

```cpp
#include <iostream>
#include <string>
#include <vector>

using namespace std;

class Pessoa
{
    public:
        string Pronomes;
        string Name;
        int Idade;
        vector<string> Architecture;
        vector<string> Tools;


        Pessoa() : Pronomes(""), Name(""), Idade(0) {} 

        Pessoa(const string& pronomes, const string& name, int idade,
               const vector<string>& architecture,
               const vector<string>& tools)
             : Pronomes(pronomes), Name(name), Idade(idade),
               Architecture(architecture), Tools(tools) {}

            void exibirInfo() const
            {
                cout << "Nome: " << Name << endl;
                cout << "Pronomes: " << Pronomes << endl;
                cout << "Idade: " << Idade << " anos" << endl;

                cout << "Arquiteturas: ";
                for (const string& arch : Architecture)
                {
                    cout << arch << " | ";
                }
                cout << endl;

                cout << "Ferramentas: ";
                for (const string& tool : Tools)
                {
                    cout << tool << " | ";
                }
                cout << endl;
            }

};

int main() {
    Pessoa pessoaDev(
        "He | His",
        "João",
        30,
        {"microservices", "event-driven", "design system pattern"},
        {"TypeScript", "C#", "JavaScript", "React", "Docker"}
    );

    pessoaDev.exibirInfo();

    return 0;
};
```

<div>
  <h1 align="center"> Github Informations </h1>
</div>
<br>
<br>
<div style="display: inline_block" align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Otavio17061992&show_icons=true&locale=en&layout=compact" alt="Otavio17061992" width="350"/>
    <img src="https://github-readme-stats.vercel.app/api?username=Otavio17061992&show_icons=true&locale=en" alt="Otavio17061992" />
</div>

<br>
<br>
  

<br>
<br>
