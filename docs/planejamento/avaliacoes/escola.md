Bruno Martins Valério Bomfim, **211039297**

Disciplina de Interação Humano-Computador, 2023.1

Prof. André Barros de Sales

<br>

# **Estudo de caso: Avaliação Heurística de um Site da Web**

Este artigo possui como propósito realizar uma avaliação heurística do site da [Escola de Música de Brasília (EMB)](https://www.escolademusicadebrasilia.com/), como parte do processo de aprendizagem e formação da disciplina de Interação Humano-Computador do curso de Engenharia de Software da Universidade de Brasília (UnB), sob a orientação do prof. André Barros de Sales.

A princípio, o planejamento propunha utilizar a avaliação via inspeção através do Método do Percurso Cognitivo. Todavia, em razão da quantidade limitada de tempo, recursos e materiais disponíveis, será empregada em seu lugar as Heurísticas de Nielsen - sem que haja prejuízos de ordem pedagógica ou acadêmica.

### A Escola de Música em Brasília (EMB)

"Considerada uma das melhores em educação musical e profissional da América Latina, está entre as mais conceituadas do mundo. Pública, a instituição fica sob a coordenação da Secretaria de Educação do Distrito Federal e tem como missão ser democrática e atender os mais diversos tipos de alunos. Fundada pelo maestro Levino de Alcântara em 1974, ela é mantida pelo GDF e fica sob a coordenação da Secretaria de Educação do Distrito Federal" - (Figuras 1.1 e 1.2).

"Os professores dão aulas de matérias básicas, canto e instrumentos para 3.370 alunos nos diversos cursos oferecidos. Localizada na 602 Sul e com uma área construída de 5,5 mil m², a EMB possui 83 salas de aula, duas grandes salas de ensaio reversíveis para apresentação de música de câmera e um teatro com 480 lugares".

### **As Heurísticas de Nielsen**

A Avaliação Heurística, método de avaliação mais popular de medição de usabilidade, é baseada na verificação de uma lista de regras (heurísticas) ou na própria experiência dos avaliadores que visam descobrir grandes problemas potenciais de usabilidade de forma econômica, simples e eficiente. Pode ser aplicada em qualquer fase do ciclo de desenvolvimento de um software, permitindo apoiar a implementação de projetos e sendo aconselhável nas fases iniciais.

Embora seja recomendado o uso de pelo menos dois avaliadores com conhecimentos em usabilidade, dada a subjetividade do método e a possível difícil aceitação dos resultados pelos projetistas da interface, aqui será realizada por **somente um avaliador** , em virtude do caráter individual da atividade.

Características a serem avaliadas:

1. **Status do sistema:** O site deve manter o usuário informado sobre sua localização e a ação que está sendo executada: feedbacks adequados para informar ao usuário se a ação desejada foi realizada com sucesso ou não; informar constantemente o usuário em qual etapa ele se encontra e quantas são necessárias para concluir a ação (para ações que são divididas em etapas).
2. **Compatibilidade do sistema com o mundo real:** Empregar a linguagem do público-alvo e organizar as informações de forma lógica e natural para cada tipo de público. Evitar utilizar termos técnicos ou jargões desconhecidos do público alvo do sítio.
3. **Controle do usuário e liberdade:** Os usuários precisam ter a sensação de que controlam o site ele responde às suas ações. Não utilizar pop-ups abertas automaticamente sem a solicitação do usuário. Disponibilizar links para as principais seções do sítio, de modo que o usuário consiga acessá-las a partir de qualquer página.
4. **Consistência e padrões:** Ser consistente em todo o site, criando um padrão de hierarquização da informação, criando páginas específicas para cada nível de navegação. Padronizar o esquema de cores, a tipologia, a diagramação, o cabeçalho, os botões e os links utilizados em todas as páginas. Padronizar também a linguagem utilizada e o formato das mensagens de erro. Sequências de ações devem ser repetidas em situações de operação semelhantes, para facilitar o aprendizado.
5. **Prevenção de Erros:** O site deve ser arquitetado de modo a prevenir que o usuário cometa equívocos. Informações organizadas, elementos clicáveis bem descritos, etc. Em formulários de cadastro, informar quais campos são de preenchimento obrigatório e também a forma correta de preenchimento.
6. **Reconhecimento ao invés de lembrança:** O usuário não deve precisar lembrar uma informação que estava em uma página acessada anteriormente no mesmo site. Manter o usuário informado sobre sua localização dentro do sítio. Uma boa solução que está sendo muito adotada é exibir o caminho percorrido pelo usuário dentro do site.
7. **Flexibilidade e eficiência de uso:** O site deve ser projetado para atender a todos os perfis de usuários, de iniciantes a experientes. Uma prática comum é oferecer uma página especial para os usuários que estão acessando o site pela primeira vez. É importante também fornecer atalhos para que os usuários mais experientes acessem a informação desejada com um menor número de cliques.
8. **Estética e design minimalista:** Evitar a utilização de elementos desnecessários que possam distrair ou confundir o usuário, os quais competem com as informações relevantes. As informações devem ser disponibilizadas em níveis de detalhe progressivo.
9. **Ajudar os usuários a reconhecer, diagnosticar e corrigir erros:** As mensagens de erro devem oferecer informações para o usuário corrigir o problema.
10. **Ajuda e documentação:** Fornecer o recurso de ajuda integrado com as páginas do sítio. É desejável que a ajuda seja contextualizada ou indexada de acordo com possíveis dúvidas que o usuário possa ter ao acessar determinada página ou seção de um sítio. A ajuda deve ser facilmente acessível a partir de qualquer página.

### **Prática**

O método proposto neste artigo considera as seguintes etapas:

1. **Classificar o problema:** quando um problema qualquer for detectado, classificá-lo em alguma das dez heurísticas de Nielsen.
2. **Registrar na tabela:** registrar o problema na tabela correspondente.
3. **Atribuir o grau de severidade:** índice que varia de 0 a 4 para tal problema.
4. **Recomeçar novamente:** aplicar o método novamente até não encontrar mais problemas de usabilidade.

Critérios de avaliação e classificação
1. Contexto: é a situação de uso em que o problema pode ser verificado ou diagnosticado.
2. Causa: refere-se ao aspecto do sistema que propicia o problema.
3. Efeito sobre o usuário: corresponde à consequência da interação com o usuário, podendo haver, entre outros, sobrecarga cognitiva, desorientação ou hesitação.
4. Efeito sobre a tarefa: refere-se à decorrência da ação sobre a tarefa executada, podendo ocasionar trabalho adicional, perda de dados ou perda de tempo.
5. Correção possível: indica ao projetista possíveis alterações no sistema.
6. Natureza de um problema de usabilidade:
  1. Barreira: aspecto da interface no qual o usuário esbarra sucessivas vezes e não aprende a suplantá-lo. Uma barreira voltará a se apresentar ao usuário na próxima realização da tarefa.
  2. Obstáculo: aspecto da interface no qual o usuário esbarra e aprende a suplantá-lo.
  3. Ruído: aspecto da interface que causa uma diminuição de seu desempenho na tarefa. O usuário pode desenvolver uma má impressão do sistema.
7. Problema de usabilidade, a partir do tipo de tarefa em que ele se manifesta:
  1. Principal: frequentes ou importantes.
  2. Secundário: pouco frequentes ou pouco importantes.
8. Perspectiva do usuário:
  1. Geral: qualquer tipo de usuário durante a realização de sua tarefa.
  2. Preliminar: usuários novatos ou intermediários durante a realização de sua tarefa.
  3. Especial: tipos de usuários especiais (portadores de deficiência) durante a realização de sua tarefa.
9. Possíveis efeitos de uma revisão de projeto:
  1. Falso problema: refere-se a um aspecto da interface que, apesar de classificado como problema, na realidade não traz qualquer prejuízo ao usuário, nem à sua tarefa.
  2. Novo: refere-se a um novo problema de usabilidade que surgiu como consequência da correção de um problema anterior.
10. Escala de severidade (em ordem crescente):
  1. Sem Importância: não afeta a operação da interface para todos usuários, não sendo encarado necessariamente como um problema de usabilidade.
  2. Cosmético: não necessita ser reparado, a menos que haja tempo disponível.
  3. Simples: pode ser reparado, com baixa prioridade de correção.
  4. Grave: deve ser reparado, com alta prioridade de correção.
  5. Catastrófico: deve ser reparado de qualquer forma antes do produto ser disponibilizado.

Posto isso, podemos começar a analisar o site.

1. **Status do sistema**

Verificação: O site mantém o usuário informado sobre sua localização e a ação que está sendo executada?

Grau de Severidade: Simples

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Preliminar

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial e tentou acessar um dos itens do menu lateral à esquerda.
2. Causa: Ao deslizar o cursor por cima do botão, produz-se uma pequena variação de cor, de branco para cinza claro. No entanto, _não é o suficiente_ para dar feedback para usuários idosos e/ou com problemas de visão, como pode ser notado nas Figuras 2.1 e 2.2.


1. Efeito sobre o usuário: Desorientação e incerteza se o botão estava ativo e/ou funcionando.
2. Efeito sobre a tarefa: Não identificado.
3. Correção possível: _Aumentar o contraste de cor_ quando o cursor passar em cima de um botão ou link.

1. **Compatibilidade do sistema com o mundo real**

Verificação: A plataforma emprega a linguagem do público-alvo e organiza as informações de forma lógica e natural para cada tipo de público?

Grau de Severidade: Grave

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Geral

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial e deslizou o scroll do cursor para descer na página.
2. Causa: Os comunicados da secretaria e das coordenações são expressos de _maneira formal e acessível_ para os diversos públicos (Figuras 3.1 e 3.2). No entanto, as informações estão _absurdamente desorganizadas_, de modo que um usuário inexperiente ficará consideravelmente desorientado com tantas informações espalhadas e irrelevantes para a ação que deseja realizar (Figura 3.3).

![](RackMultipart20230423-1-pdcq81_html_a8c618520e44882c.png) ![](RackMultipart20230423-1-pdcq81_html_b750497ac7459aff.png)

(Figura 3.1) (Figura 3.2)

![](RackMultipart20230423-1-pdcq81_html_b377ff2b17004a3e.png)

(Figura 3.3)

1. Efeito sobre o usuário: Desconforto, desorientação.
2. Efeito sobre a tarefa: Desperdício de tempo para encontrar a informação desejada.
3. Correção possível: Criar seções separadas para avisos, horários, etc.

1. **Controle do usuário e liberdade**

Verificação: O usuário possui a sensação de que controla o site e que o mesmo responde às suas ações?

Grau de Severidade: Cosmético

Natureza do problema: Ruído

Perspectiva do usuário: Problema Preliminar

Perspectiva da tarefa: Problema Secundário

Perspectiva do Projeto: Problema Falso

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial.
2. Causa: O site da EMB possui um menu lateral à esquerda através do qual o usuário pode navegar até uma página a partir de qualquer outra (Figura 4.1). Além disso, a plataforma conta com uma search bar no canto superior direito, _ainda que não esteja tão aparente_ para os usuários inexperientes (Figura 4.2).

![](RackMultipart20230423-1-pdcq81_html_34646d1e240d5c60.png) ![](RackMultipart20230423-1-pdcq81_html_e26a9c97c5156ca4.png)

(Figura 4.1) (Figura 4.2)

1. Efeito sobre o usuário: Sensação de controle e orientação.
2. Efeito sobre a tarefa: Produtividade para acessar diferentes páginas sem ter que voltar primeiramente à inicial.
3. Correção possível: Deixar a search bar _mais visível._

1. **Consistência e padrões**

Verificação: Os itens são agrupados logicamente e os padrões de formatação são seguidos consistentemente em todas as telas da interface?

Grau de Severidade: Grave

Natureza do problema: Ruído

Perspectiva do usuário: Problema Geral

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial.
2. Causa: Uma paleta de cores _não padronizada_ e faixas distribuídas _sem algum critério aparente_. Ademais, alguns links possuem coloração amarela enquanto outros possuem coloração azul (Figura 5.1).

![](RackMultipart20230423-1-pdcq81_html_f9f08809915cafc.png)

(Figura 5.1)

1. Efeito sobre o usuário: Desconforto e breve desorientação.
2. Efeito sobre a tarefa: Quase nenhum.
3. Correção possível: _Padronizar_ as páginas do site de acordo com a identidade visual da Escola.

1. **Prevenção de erros**

Verificação: O site é projetado de forma a evitar que o usuário cometa erros?

Grau de Severidade: Simples

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Preliminar

Perspectiva da tarefa: Problema Secundário

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial e depois navegou até a área de contatos.
2. Causa: Alguns títulos, como o "Horário de Atendimento das Coordenações" possuem um botão de link ao lado. Embora os links (geralmente) não levem a lugar nenhum, induzem o usuário a clicá-los (Figura 6.1).

![](RackMultipart20230423-1-pdcq81_html_241074a25a17dded.png)

(Figura 6.1)

1. Efeito sobre o usuário: Incerteza, dúvida, desconforto.
2. Efeito sobre a tarefa: Atraso.
3. Correção possível: Revisão de título com aspecto de link para evitar as _falsas affordances_.

1. **Reconhecimento ao invés de relembrança**

Verificação: É necessário que o usuário precise se lembrar de uma informação que estava em uma página acessada anteriormente no mesmo site?

Grau de Severidade: Grave

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Preliminar

Perspectiva da tarefa: Problema Secundário

Perspectiva do Projeto: Problema Novo

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial e, em seguida, navegou até a área de contatos.
2. Causa: O usuário _não é informado_ sobre sua localização dentro do site. E mais: ao invés de abrir uma nova página na mesma guia, são abertas mais e mais guias para cada link ou botão clicado, provocando _poluição visual e excesso de utilização de memória do dispositivo_ pelo navegador.
3. Efeito sobre o usuário: Desorientação.
4. Efeito sobre a tarefa: Acúmulo de informações (muitas guias abertas).
5. Correção possível: As páginas devem ser abertas numa mesma guia, com uma pequena seção indicando o caminho percorrido. Ex: Home → Contatos → Coordenações → Coordenação de piano erudito.

1. **Flexibilidade e eficiência no uso**

Verificação: O site foi projetado de modo a atender a todos os perfis de usuários?

Grau de Severidade: Catastrófico

Natureza do problema: Barreira

Perspectiva do usuário: Problema Especial

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial.
2. Causa: O site não oferece nenhum tipo de acessibilidade para usuários com problemas visuais, auditivos ou de idade, tornando a sua utilização _impossível_. Soma-se a isto o fato de não existir um menu de acesso rápido no qual os usuários pudessem realizar as tarefas com maior demanda: consultar horários, solicitar declarações de passe livre estudantil, etc.
3. Efeito sobre o usuário: Impossibilidade ou muita dificuldade de uso.
4. Efeito sobre a tarefa: Impossibilidade ou muita dificuldade de realizar uma tarefa.
5. Correção possível: Implementar funções relativas à acessibilidade (alto contraste, ajuda auditiva, etc).

1. **Estética e design minimalista**

Verificação: O site evita a utilização de elementos desnecessários que possam distrair ou confundir o usuário?

Grau de Severidade: Grave

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Geral

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário acessou a página inicial.
2. Causa: O site mistura informações de eventos que já se passaram, além de exibir links espalhados no decorrer do site sem nenhum critério de classificação.

![](RackMultipart20230423-1-pdcq81_html_59d8048c3c67f908.png)

(Figura 7.1)

1. Efeito sobre o usuário: Desorientação.
2. Efeito sobre a tarefa: Atraso de tempo para encontrar o link correto.
3. Correção possível: Organizar os links do site em seções organizadas.

1. **Ajuda aos usuários no reconhecimento, diagnóstico e correção de erros**

Verificação: O site apresenta mensagens de erro amigáveis e auxilia seus usuários a se recuperar de seus equívocos?

Grau de Severidade: Simples

Natureza do problema: Obstáculo

Perspectiva do usuário: Problema Preliminar

Perspectiva da tarefa: Problema Secundário

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário tenta acessar uma página que não existe.
2. Causa: O site não apresenta mensagens de erro _amigáveis_. Como um usuário sem conhecimentos básicos de informática saberá o que é um _Erro 404?_ (Figura 8.1).

![](RackMultipart20230423-1-pdcq81_html_ec3aa9a3ff64d2c2.png)

(Figura 8.1)

1. Efeito sobre o usuário: Desorientação, frustração.
2. Efeito sobre a tarefa: Empecilho para realizar as tarefas, já que o site não oferece mensagens realmente úteis.
3. Correção possível: Exibir uma mensagem de erro comunicativa para o caso em que uma página não existir.

1. **Ajuda e documentação**

Verificação: A plataforma oferece o recurso integrado de ajuda com as diversas páginas?

Grau de Severidade: Catastrófico

Natureza do problema: Barreira

Perspectiva do usuário: Problema Geral

Perspectiva da tarefa: Problema Principal

Perspectiva do Projeto: Não se aplica

Descrição do Problema:

1. Contexto: O usuário não consegue realizar uma tarefa e então recorre em última instância à seção de ajuda do site.
2. Causa: A seção de ajuda **não existe**.
3. Efeito sobre o usuário: Frustração, aborrecimento, indignação.
4. Efeito sobre a tarefa: Impossibilidade de realizar uma tarefa que poderia ser simples.
5. Correção possível: Construir uma seção de ajuda, como uma FAQ (Frequently Asked Questions).

[1](#sdfootnote1anc)Texto adaptado do portal do MEC: "Escola de Brasília é referência no mundo em educação musical." MEC, \<[http://portal.mec.gov.br/component/tags/tag/escola-de-musica-de-brasilia](http://portal.mec.gov.br/component/tags/tag/escola-de-musica-de-brasilia)\>. Acesso em 15 de abril de 2023.

[2](#sdfootnote2anc)Conteúdo adaptado do artigo " **Avaliação Heurística de Sítios na Web**", de Cristiano Maciel, José Luis T. Nogueira, Leandro Neumann Ciuffo, e Ana Cristina Bicharra Garcia, pertencente ao repositório online do Instituto de Computação da Universidade Federal Fluminense (UFF). Disponível em \<[http://www.ic.uff.br/](http://www.ic.uff.br/)\>. Acesso em 16 de abril de 2023.