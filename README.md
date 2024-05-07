# Documento de Referência do Sistema "Classic Fantasy Imperative"

Versão 1.0, Setembro 2023

_Classic Fantasy Imperative_ é uma versão aberta, sob a licença ORC, do conjunto de regras _Mythras_, com foco na exploração de masmorras, alta aventura e encontros tensos envolvendo tesouros, magia e inimigos mortais. _Classic Fantasy Imperative_ emula a emoção original do primeiro jogo de roleplaying do hobby, mas aborda-a através das lentes do sistema de jogo _Mythras_, que usa 1d100 (percentual), em vez de usar um d20.

Este documento oferece um conjunto de regras abrangente, mas não exaustivo, incluindo criação de personagens, raças e classes de personagens, perícias, regras para situações específicas, combate e magia – mais do que suficiente para que jogadores e Mestres comecem e formem uma base sólida para posterior desenvolvimento. _Classic Fantasy Imperative_ é totalmente compatível com _Classic Fantasy Imperative_, as regras básicas de _Mythras_ e _Mythras Imperative_. Além disso, também é compatível com outros sistemas de jogos percentuais licenciados pela ORC.

---
## Licenciamento ORC

_Classic Fantasy Imperative_ é publicado usando a Licença ORC. A Licença ORC provê um modo de os criadores de jogos compartilharem abertamente a mecânica de seu jogo e permite que os usuários subsequentes usem, modifiquem e compartilhem livremente adaptações dessas mecânicas de jogo.

O que é compartilhado abertamente sob o ORC é conhecido como **Material Licenciado** e inclui os amplos elementos funcionais do jogo, como blocos de estatísticas, regras do jogo, atributos do personagem e os métodos e sistemas inerentes ao jogo, bem como como qualquer outra coisa que o licenciante queira compartilhar explicitamente. A licença é ampla e permite que você use os Materiais Licenciados globalmente em conexão com livros impressos, videogames, podcasts, IA ou qualquer outra tecnologia que possa existir ou ser criada no futuro. A grande parte do conteúdo encontrado em _Classic Fantasy Imperative_ constitui Material Licenciado.

O que não é compartilhado sob a ORC é conhecido como **Material Reservado** e inclui marcas registradas, histórias e descrições sobre mundos e cenários de jogo, arcos de história, personagens distintos e artes visuais. Listamos o Material Reservado no **Aviso ORC** abaixo.

Sob a Licença ORC, você pode usar, compartilhar, adaptar e desenvolver o Material Licenciado da maneira que achar melhor, desde que dê a devida atribuição na forma de um aviso em seu trabalho publicado. Este aviso credita os licenciantes anteriores e a sua contribuição para a obra, bem como fornece uma forma fácil para os licenciados posteriores creditarem o autor da obra em que o aviso aparece. Ao usar material licenciado sob o ORC, você concorda automaticamente em licenciar sua mecânica de jogo em seu trabalho publicado sob os mesmos termos. Se você desenvolver seu próprio Material Reservado, ele será de sua propriedade exclusiva.

#### Aviso ORC

_Classic Fantasy Imperative_ é licenciado sob a Licença ORC localizada na Biblioteca do Congresso dos EUA e disponível online em vários locais, incluindo [Paizo.com](https://paizo.com/community/blog/v5748dyo6sico?ORC-License-The-Final-Version-is-Here) e outros. Uma tradução da licença está disponível na [GURPZine Wiki](https://drive.google.com/uc?export=download&id=150AL_J-gwJC2FPvmJDJwb1bYU5rCjSoo).

Todas as garantias são excluídas conforme estabelecido na licença.

#### Atribuição

Este produto é baseado nos seguintes Materiais Reservados:

- _Mythras_, The Design Mechanism Copyright 2016, Escrito por Pete Nash e Lawrence Whitaker.
- _Classic Fantasy Imperative_, The Design Mechanism Copyright 2016, Escrito por Rodney Leary, Pete Nash, e Lawrence Whitaker.

Se você usar nosso Material Licenciado em seus próprios trabalhos publicados, por favor nos credite da seguinte forma:

_**Based on Classic Fantasy Imperative, Written by Rodney Leary, Pete Nash and Lawrence Whitaker, and published by The Design Mechanism, Copyright 2023.**_

#### Material Reservado

Observe que os jogos pais de _Classic Fantasy Imperative_, _Classic Fantasy_ e _Mythras_, publicados pela The Design Mechanism, são designados como Material Reservado sob a licença ORC.

Se você deseja aproveitar o conteúdo encontrado em _Classic Fantasy Imperative_ ou _Mythras_, entre em contato com a The Design Mechanism para obter uma licença separada chamada "Mythras Gateway", que permite o acesso ao Material Reservado, livre de royalties, mas com algumas condições em relação a aprovações e atribuição.

Também são considerados Materiais Reservados:

- _Classic Fantasy_ e _Classic Fantasy Imperative_ – como nome, salvo quando utilizado em atribuição, incluindo seu logotipo.
- _Mythras_ and _Mythras Imperative_ - como nome, salvo quando utilizado em atribuição, incluindo seus logotipos.
- Todos os trabalhos artísticos encontrados em _Classic Fantasy Imperative_
- _Alexandra the Pious_
- _Barony of Ostwyn_
- _Barony of Volstad_
- _County of Thale_
- _Grand Duchy of Bethany_
- _Grand Duchy of Pelende_
- _Greymyr_
- _Inwils Isle_
- _Inwils the Sage_
- _King Korac of Norsgard_
- _Lilly Tanglefoot_
- _Lorissa of Stormholm_
- _Miranda Drake_
- _Mystamyr_
- _Mystamyr and the Boarderlands_
- _Rengarth Hightower_
- _Runewood Forest_
- _Sorack Blackwolf_
- _Tashana Moonshadow_
- _The Dunfel Inn_
- _Faewood Vale_
- _The Elven Lands of Lorendel_
- _The Iron Kingdom of the Dwarves_
- _The Island Nations of Valencia_
- _The Kingdom of Greymyr_
- _The Northern Territories of Norsgard_
- _The Orc Blight Mountains_
- _The Pharaonic Lands of Aegypt_
- _The Shattered Territories_
- _The Shenzhou Monastery_
- _The Spider Wald_
- _The Undead Realms of Ravenholm_
- _The War-Torn Hinterlands_
- _The World of Areath_
- _Town of Dunfel_
- _Valamir Drake_

---
## Novo no d100?

_Classic Fantasy Imperative_ é um sistema d100 ou percentual. Os dados percentuais, ou 1d100, são usados para resolver ações-chave – uso de perícias, combate, conjuração de magia e assim por diante. É um sistema "menor ou igual", o que significa que o número alvo é expresso como uma porcentagem (Atletismo 65%, por exemplo), e tanto o Mestre do Jogo quanto o jogador procuram rolar igual ou menor que esse número alvo, usando 1d100, para alcançar um Sucesso. É muito fácil substituir 1d100 por um d20, se preferir, e todas as porcentagens podem ser divididas por 5 (arredondadas para cima) para obter o número alvo numa jogada de d20. Atletismo 65% passaria a ser Atletismo 13, no nosso exemplo. No entanto, 1d100 oferece muita flexibilidade e nuances que sustentam todo o jogo, então nossa recomendação é tentar primeiro a abordagem 1d100. Embora possa parecer contra-intuitivo ter que rolar _menos_ do que alguma coisa (em muitos jogos, maior geralmente é melhor!), ter um número alvo expresso como uma faixa percentual que é preciso rolar _dentro_ torna mais fácil e simples ver suas chances de sucesso, e permite alguns 'truques de dados', como Rolagens Opostas, Críticos e Trapalhadas, e algumas outras coisas exploradas posteriormente nestas regras. RPGs percentuais existem há muito tempo e são sistemas de jogo firmemente estabelecidos, com uma mecânica central testada e comprovada que é flexível, intuitiva e tende a nem ser notada durante o jogo.

---
## Simplificação

Proprietários de longa data de _Mythras_ e _Classic Fantasy_ notarão que em alguns lugares as regras de _Classic Fantasy Imperative_ foram simplificadas. Isto foi feito para que um Mestre do Jogo possa introduzir o jogo mais rapidamente a novos jogadores com um mínimo de problemas. Outra área em que _Classic Fantasy Imperative_ difere é na incorporação de medidas imperiais em vez de métricas. Incorporar ambos ocupa muito espaço e exigiria várias mesas ao lidar com armas de longo alcance e similares. O sistema Imperial foi escolhido simplesmente para facilitar o uso dos inúmeros grids de batalha já existentes e para tornar mais simples a conversão de aventuras de outros sistemas de jogo que usam medidas Imperiais. Ao preencher sua Ficha de Personagem, sinta-se livre para usar as Tabelas de Conversão no Apêndice e qualquer sistema de medição que você achar mais útil e familiar.

---
## Arredondamento de Números e Resultados

Em algumas ocasiões, você será solicitado a dividir números – normalmente o valor de uma perícia (como para determinar um Sucesso Crítico, que é 1/10 do valor da perícia). Sempre que o resultado de uma divisão criar uma fração, sempre arredonde para o próximo número inteiro. Assim, por exemplo, 1/10 de 64% é 6,4 e deve ser arredondado para 7.

---
## Dados Usados no Jogo

_Classic Fantasy Imperative_ usa o conjunto de dados poliédricos padrão: d4, d6, d8, d10, d12, d20 e d100. Além disso, os seguintes dados são necessários:

- **d2:** Jogue qualquer dado. Um número ímpar é igual a 1 e par é igual a 2. Ou jogue uma moeda.

- **d3:** Jogue um dado de seis lados; 1-2 = 1, 3-4 = 2, 5-6 = 3.