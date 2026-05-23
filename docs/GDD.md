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

| Hipótese                                                                                                                                                                                                                                                                                                                                                                          | Como será testada                                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| As primeiros minutos de gameplay são essenciais para o engajamento                                                                                                                                                                                                                                                                                                                | Ação primeiro e diálogo depois, prologo com gameplay em ambos os cenários (ar e terra / air and ground)                                                       |
| Dialogos não precisam ser excessivamente longos, ainda que seja uma aventura de roleplay, muitos dos jogadores buscam pelo constante ciclo de desafio e recompensa, um dos fatores que motiva o player a realmente jogar o jogo e criar interesse pela trama                                                                                                                      | Diálogos serão cuidadosamente "scriptados" para durar menos em cutscenes, além de ser mais objetivos, dependendo do propósito do direcionamento da gameplay   |
| Jogadores sentem falta profundidade dos personagens em muitos jogos "retro", Na época do NES por exemplo, muitos jovens se apegavam aos personagens que controlavam, embora as desenvolvedoras não tinham budget ou espaço no cartucho para incluir elementos que dessem mais caráter a esses personagens, cada jogador tinha uma visão / concepção específica daquele personagem | Durante a gameplay, o jogador pode ler e ouvir dialogos entre personagens, que podem ser engatilhados dependendo das ações do player                          |
| Usuários que testam o produto antes de ler as instruções... Muitos dos jogadores testam diferentes botões assim que assumem o controle da cena                                                                                                                                                                                                                                    | Haverá sim um tutorial, mas ele será suscinto e não nessessáriamente imediado, o jogador deve seguir o "feeling" e posteriormente será provisionado um manual |
| combate simples melhora acessibilidade                                                                                                                                                                                                                                                                                                                                            | protótipo com 1 botão de ataque                                                                                                                               |

## Pilares do jogo

-

# 5. Gameplay

## Core Loop

Engajar Missão (bullet hell) → derrotar ameaça aérea → coletar itens → concluir missão (boss) → explorar hangar (metroidvânia) → explorar cenário → adquirir/ encontrar itens → acatar missões secundárias → explorar hangar → aprimorar aeronave → engajar missão (volta ao bullet hell)

## Loops Secundários

## Mecânicas Principais

| Mecânica  | Descrição                 |
| --------- | ------------------------- |
| Movimento | como o jogador se desloca |
| Combate   | como o jogador ataca      |
| Interação | como interage com objetos |

## Camera

Gameplay: Side scroll 2D

Cutscenes: animações curtas de ângulos variados

## Sistemas

**Vitória**

Derrota de todos os inimigos em campo.

**Derrota**

Perda da aeronave ou do piloto.

**Progressão**

Em P-Factor, pilotos (personagens) com diferentes aeronaves adereçadas a eles, ganham experiência em missões e eventos na história do jogo. Ao subir de nível, aumentam atributos, desbloqueiam novos aprimoramentos e podem evoluir suas aeronaves através uma mecânica de adaptação de maquina, desbloqueada ao progredir a história. A quantidade de EXP necessária cresce a cada nível, tornando o progresso mais difícil. O sistema vai do nível 1 ao 100.

# 6. Escopo do Projeto

Defina claramente **o que será implementado**.

## O jogo inclui

- 7 fases
- 5 categorias de inimigos
- 4 mecânicas principais

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

### AIR

- D-Pad == Directional Pad
- RSB == Right Stick Button
- LSB == Left Stick Button
- RB == Right Bumper
- RT == Right Trigger
- LB == Left Bumper
- LT == Left Trigger
- Y == Y Button (Top)
- A == A Button (Bottom)
- X == X Button (Left)
- B == B Button (Right)

![xbox-button-layout](https://user-images.githubusercontent.com/580022/45268303-10a03e80-b4ce-11e8-883c-1f586566c040.png)

### GROUND

- D-Pad == Directional Pad
- RSB == Right Stick Button
- LSB == Left Stick Button
- RB == Right Bumper
- RT == Right Trigger
- LB == Left Bumper
- LT == Left Trigger
- Y == Y Button (Top)
- A == A Button (Bottom)
- X == X Button (Left)
- B == B Button (Right)

# 9. Direção Visual

## Direção de Arte

_Adicione imagens/prototipos/ mood board_

Exemplo:

- pixel art
- low poly
- cartoon

---

## Referências Visuais

📌 https://jp.pinterest.com/rgabrielfialho/pfctr/

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

| Categoria     | Ferramenta   |
| ------------- | ------------ |
| Engine        | Godot        |
| Linguagem     | GDScript     |
| Versionamento | Git + GitHub |
| Assets        | Aseprite /   |

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
