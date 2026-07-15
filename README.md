<div align="center">

<img src="game/src/main/resources/images/environment/DRAGON%20BALL%20ADVENTURES.png" alt="Dragon Ball Z: Cell's Revenge" width="900">

# Dragon Ball Z: Cell's Revenge

Um jogo 2D desenvolvido em JavaFX no qual Gohan enfrenta os Cell Juniors e as diferentes formas de Cell.

![Java](https://img.shields.io/badge/Java-11-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-16-1B74BB?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-3.8%2B-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

</div>

## Sobre o projeto

Esta é a versão temática de Dragon Ball do **chonGame**, um projeto acadêmico criado para aplicar conceitos de programação orientada a objetos por meio do desenvolvimento de jogos.

Na pele de Gohan, o jogador deve atravessar três fases, coletar itens, enfrentar inimigos e derrotar Cell antes que ele alcance sua forma perfeita.

## Principais recursos

- Combate em tempo real com ataques de energia.
- Três fases com câmera lateral e cenários inspirados em Dragon Ball.
- Cell Juniors e batalha contra as diferentes transformações de Cell.
- Sistema de vida, energia, pontuação e itens coletáveis.
- Sprites animados para movimento, ataque, dano, transformação e derrota.
- Trilha sonora e efeitos sonoros para menus, combate, vitória e game over.
- Menu inicial, pausa, reinício, tela de vitória e tela de derrota.

## Controles

| Tecla | Ação |
| --- | --- |
| `↑` `↓` `←` `→` | Movimentar Gohan e navegar pelos menus |
| `Espaço` | Atacar |
| `P` | Pausar ou continuar o jogo |
| `Enter` | Confirmar uma opção do menu |

## Tecnologias

- **Java 11** — linguagem e orientação a objetos.
- **JavaFX 16** — interface gráfica, canvas, animações e áudio.
- **Maven** — dependências, compilação e execução do projeto.
- **Git e GitHub** — versionamento e organização das branches.

## Como executar

### Pré-requisitos

- JDK 11 ou superior.
- Apache Maven 3.8 ou superior.

### Passo a passo

```bash
git clone https://github.com/Nilokrtz/chonGame.git
cd chonGame
git checkout dragon-ball
cd game
mvn clean javafx:run
```

## Estrutura do projeto

```text
chonGame/
├── game/
│   ├── pom.xml
│   └── src/main/
│       ├── java/        # Engine, entidades, menus, armas e regras do jogo
│       └── resources/   # Imagens, sprites, fontes e efeitos sonoros
├── documentation/       # Documentação e modelagem do projeto
├── presentation/        # Material de apresentação
└── README.md
```

## Contexto acadêmico

O chonGame foi utilizado nas disciplinas **Linguagens e Técnicas de Programação II** e **Introdução à Orientação a Objetos**. Esta branch apresenta uma adaptação temática desenvolvida para consolidar conceitos como herança, encapsulamento, polimorfismo, composição e separação de responsabilidades.

## Autor desta versão

Desenvolvido e personalizado por [Nilo Silva](https://github.com/Nilokrtz).
<br>
Confira nossa Engine em [Kadu Pantoja](https://github.com/profpantoja/chonGame)

## Aviso

Projeto de fã, sem fins comerciais, criado exclusivamente para estudo. Dragon Ball e seus personagens pertencem aos seus respectivos detentores de direitos autorais.
