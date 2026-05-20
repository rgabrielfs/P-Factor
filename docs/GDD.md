# Game Design Document (GDD)

# P-Factor

**Aluno:** Ricardo Gabriel
**E-mail:** ricardo.gabriel@catolica.edu

**Status do Projeto:**  
Produção
**Versão do Documento:** v0.3  
**Última atualização:** 08/04/2026

# 1. Visão Geral

## Elevator Pitch

A coming of age set in a WW2 Bullet Hell with metroidvania mechanics

## Gênero

- Bullet Hell
- Metroidvania
- RPG

## Público-Alvo

Jogadores de Bullet Hell e RPG de 15 a 45 anos que apreciam histórias longas, histórias de época, aeronaves diversas, e desafios envolvendo jogatinas frenéticas.

## Plataformas

- PC

# 2. Acesso ao Projeto

| Item                   | Link                                            |
| ---------------------- | ----------------------------------------------- |
| Build jogável          | Itch.io / WebGL / Download                      |
| Repositório            | [GitHub ](https://github.com/Demasoft/P-Factor) |
| Gameplay               | YouTube                                         |
| Instruções de execução | Requisitos técnicos                             |

# 3. Pesquisa e Referências

## Jogos de Referência

| Item                                              | Inspiração                                                                                                                                                                                                                                                                                                                                                                                                                            | Referência                                                                                                                                                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Progear                                           | Este é a principal inspiração do projeto P-Factor. Se trata de um Bullet Hell desenvolvido pela CAVE, que além de possuir uma aparência vibrante e um visual "steampunk", gira em torno de uma curta história sobre um grupo de jovens dedicados a mudar o rumo do conflito abordado no jogo.                                                                                                                                         | ![Alt Text](https://img.pastemagazine.com/wp-content/uploads/2022/06/21034759/progear_main.jpg)                                                                      |
| Megaman Zero                                      | O Jogo da franquia Megaman, desenvolvido a princípio para o gameboy advance, inspira fortemente o sistema de exploração "a pé" no projeto, visto que seus níveis estão todos conectados, como um "metroidvânia", mesmo sendo considerado um platformer baseado em missões. Além disso, o dialogo e a forma como cutscenes são renderizadas no game, também inspiram P-Factor, sendo elas relativamente "Low Budget"                   | ![Alt Text](https://i.ytimg.com/vi/r9cybJ4bcy8/hqdefault.jpg?sqp=-oaymwEmCOADEOgC8quKqQMa8AEB-AHuAYACoAGKAgwIABABGGUgUihUMA8=&rs=AOn4CLDrvDN_WItVJ-FFOVM9oRJN36ZgDA) |
| Record of Lodoss War: Deedlit in Wonder Labyrinth | Desenvolvido pelo Team Ladybug, este é um metroidvânia inspirado em títulos como Castlevania SOTN, mas o que chama atenção é seu design de som, cores, UI intuitiva e sua mecânica com o arco, que permite o player atirar projeteis de uma maneira interessante, que faz sentido com o projeto                                                                                                                                       | ![Alt Text](https://i0.wp.com/waytoomany.games/wp-content/uploads/2022/01/2022012613410800-8D5DA3F4CA5D98FAA574C2346CF80226.jpg?ssl=1)                               |
| Nier Automata                                     | Yoko Taro, seu criador, diz na palestra documentada "Making Weird Games For Weird People" que os jogos são apenas mais uma maneira de contar histórias, e Nier faz isso de forma excepcional, dando profundidade aos personagens durante a gameplay, além de mesclar os gêneros hack'em Slash e Shoot'em Up de uma maneira inusitada, assim como P-factor busca revitalizar o Gênero chamando a atenção de um novo nicho de jogadores | ![Alt Text](https://i.ytimg.com/vi/OLq4L_zBZK4/maxresdefault.jpg)                                                                                                    |

## Análise das Referências

Explique brevemente:

- o que esses jogos fazem bem
- quais ideias inspiraram seu projeto

---

# 4. Hipóteses de Design

Liste hipóteses que serão testadas durante o desenvolvimento.

| Hipótese                               | Como será testada               |
| -------------------------------------- | ------------------------------- |
| jogadores gostam de progressão rápida  | playtest com fases curtas       |
| combate simples melhora acessibilidade | protótipo com 1 botão de ataque |

## Pilares do jogo

- 3 a 5 no máximo

---

# 5. Gameplay

## Core Loop

Descreva o ciclo principal do jogo.

Exemplo:

Explorar → enfrentar inimigos → coletar recursos → melhorar personagem → continuar explorando

## Loops Secundários

---

## Mecânicas Principais

| Mecânica  | Descrição                 |
| --------- | ------------------------- |
| Movimento | como o jogador se desloca |
| Combate   | como o jogador ataca      |
| Interação | como interage com objetos |

## Camera

- Tipo de câmera

---

## Sistemas

**Vitória**

Condição para vencer.

**Derrota**

Condição para perder.

**Progressão**

Sistema de níveis, pontos ou upgrades.

---

# 6. Escopo do Projeto

Defina claramente **o que será implementado**.

## O jogo inclui

- X fases
- X tipos de inimigos
- X mecânicas principais

## O jogo não inclui

- multiplayer online
- sistema complexo de crafting
- geração procedural avançada

---

# 7. Prototipagem

Descreva os protótipos realizados durante o desenvolvimento.

| Protótipo        | Objetivo         | Resultado       |
| ---------------- | ---------------- | --------------- |
| movimento básico | validar controle | aprovado        |
| combate          | testar ritmo     | precisa ajustes |

---

# 8. Interface (UI/UX)

## HUD

Elementos visíveis durante o jogo.

_Adicione imagens/prototipos/mockups de tela_

Exemplo:

- barra de vida
- pontuação
- timer

---

## Menus

_Adicione imagens/prototipos/mockups de tela_

- menu principal
- pause
- game over
- configurações

## Flow de menus

- diagrama

## Controles

- diagrama e disposição dos inputs e o que fazem

---

# 9. Direção Visual

## Direção de Arte

_Adicione imagens/prototipos/ mood board_

Exemplo:

- pixel art
- low poly
- cartoon

---

## Referências Visuais

Links ou imagens que inspiram o estilo do jogo.

---

# 10. Áudio (tabela/onde usar/loop/descrição)

Tipos de áudio utilizados:

- música de fundo
- efeitos sonoros
- narração (se houver)

---

# 11. Animação (tabela/onde usar/loop/descrição)

- Todos as animações usadas eonde

---

# 12. Arquitetura de Software

Descreva a estrutura geral do código.

Exemplo:

- GameManager central
- sistema de eventos
- scripts separados por responsabilidade

---

## Tecnologias Utilizadas

| Categoria     | Ferramenta                |
| ------------- | ------------------------- |
| Engine        | Unity / Godot / Unreal    |
| Linguagem     | C# / GDScript / C++       |
| Versionamento | Git + GitHub              |
| Assets        | Asset Store / OpenGameArt |

---

# 12. Testes e Playtests

## Playtests

| Data  | Participantes | Principais problemas |
| ----- | ------------- | -------------------- |
| DD/MM | 5 pessoas     | controles confusos   |
| DD/MM | 10 pessoas    | dificuldade elevada  |

---

## Melhorias Implementadas

Problema → solução aplicada.

Exemplo:

Jogadores não entendiam o objetivo inicial → tutorial adicionado.

---

# 13. Cronograma

detalhe os principais milestones do projeto.

# 14. Riscos do Projeto

| Risco             | Impacto           | Mitigação                    |
| ----------------- | ----------------- | ---------------------------- |
| IA muito complexa | atraso no projeto | simplificar comportamento    |
| performance baixa | experiência ruim  | otimizar ou reduzir inimigos |

---

# 15. Limitações Conhecidas

Liste funcionalidades planejadas mas não implementadas.

Exemplo:

- multiplayer online
- sistema de save em nuvem
- novas fases

---

# 16. Decisões Importantes

Registro de mudanças relevantes durante o projeto.

| Data  | Decisão                     | Motivo              |
| ----- | --------------------------- | ------------------- |
| março | remover sistema de crafting | escopo muito grande |
| abril | adicionar dash              | melhorar mobilidade |

---

# 17. Créditos

Liste assets externos utilizados.

| Recurso | Fonte        | Licença |
| ------- | ------------ | ------- |
| sprites | OpenGameArt  | CC0     |
| música  | compositor X | CC-BY   |

---

# 17. Reflexão Final

Explique brevemente:

- principais desafios
- aprendizados técnicos
- o que faria diferente

1–3 parágrafos são suficientes.
