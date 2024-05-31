# Projeto iPhone

Este projeto contém a implementação das interfaces e classes que representam as funcionalidades do iPhone como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Estrutura do Projeto
/desafio-de-projeto-iPhone <br>
│<br>
├── resources<br>
│ ├── modelagem.pdf<br>
│ ├── modelagem.png<br>
│ └── diagrama.md<br>
| <br>
├── src<br>
│ ├── AparelhoTelefonico.java<br>
│ ├── iPhone.java<br>
│ ├── NavegadorInternet.java<br>
│ └── ReprodutorMusical.java<br>
│ <br>
└── README.md


## Recursos

- [Modelagem UML (PDF)](resources/modelagem.pdf)
- [Modelagem UML (Imagem)](resources/modelagem.png)
- [Diagrama de Classes (Markdown)](resources/classDiagram.md)

## Diagrama de Classes

O diagrama de classes do iPhone foi modelado utilizando Mermaid e pode ser visualizado no arquivo `diagrama.md`.

### Diagrama em Mermaid

```markdown
# Diagrama de Classes do iPhone

```mermaid
classDiagram
    class iPhone {
    }

    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    iPhone --|> ReprodutorMusical
    iPhone --|> AparelhoTelefonico
    iPhone --|> NavegadorInternet 


Para visualizar o diagrama em Mermaid, abra o arquivo `diagrama.md` no VS Code e utilize a pré-visualização de Markdown (`Ctrl+Shift+V` ou `Cmd+Shift+V` no macOS).

## Conclusão

Este projeto demonstra como modelar e implementar as funcionalidades principais de um iPhone utilizando Java e UML. A estrutura do projeto é organizada para facilitar a manutenção e a expansão futura.
