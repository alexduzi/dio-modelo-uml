# dio-modelo-uml
UML de um aparelho celular, DIO


classDiagram
    class ReprodutorMusical {
        +tocar()
        +selecionarMusica(String exemplo)
        *pausar()
    }

    class AparelhoTelefonico {
        +atender()
        +ligar(String exemplo)
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +adicionarNovaAba()
        +exibirPagina(String exemplo)
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
