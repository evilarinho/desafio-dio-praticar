# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

_Qual tarefa da sua semana você escolheu e por que ela vale a pena?_

### Meus Atalhos

_Conte quais modelos do kit você adaptou, o que ficou fixo e o que muda a cada uso._

```text
01-prompts/01-escrever-e-melhorar-textos.md
```

```text
04-skills/01- auditor-viabilidade-ideias.md
```

### Minha Delegação

```text
Criar uma skill para o Gemini AI no modo DELEGAÇÃO. 
objetivo: Pesquisar matérias diárias sobre o desenvolvimento das IA e resumir com até dois parágrafos
Contexto: Pesquisa em exclusivamente em fontes de referência copmprovadas com domínio na Internet
Recursos: Pesuisas textos e vídeos no YouTube
Limites: Selecionar até 10 materiais diárias onde o requisito de seleção é a quantidade de visualizações
Sucesso: Sempre as 08:00 da manhã ou quando for solicitado. Apresentar o relatório em formato de mensagens no estilo jornal antigo e anexar fotos se a matéria apresentar.

Apresente o seu plano de execução antes de executar.
```

### O Plano da IA

## **Plano de Execução — Skill "Gazeta Diária de IA" (Gemini AI / Modo Delegação)**

Antes de construir o prompt completo da Skill para você configurar manualmente no Gemini, segue o plano estruturado da arquitetura, os ajustes técnicos necessários para respeitar os limites reais da plataforma e as etapas de entrega.

### **1\. Arquitetura Prevista da Skill**

A Skill será estruturada sob a lógica de **Delegação com Limites** (Objetivo, Contexto, Recursos, Limites, Critérios de Sucesso e Tratamento de Exceções):

* **Nome sugerido:** gazeta-diaria-ia (ou *Curador Diário de IA — Edição Jornalística*).  
* **Escopo temático:** Avanços, lançamentos, pesquisas, regulamentação e movimentações relevantes sobre Inteligência Artificial publicados nas últimas 24 horas.  
* **Curadoria de fontes:** Lista curada de domínios jornalísticos, científicos e blogs oficiais verificáveis (ex.: *MIT Technology Review, Reuters, TechCrunch, The Verge, Ars Technica, Nature*, blogs oficiais da Google DeepMind, OpenAI, Anthropic, além de portais brasileiros de referência) \+ canais verificados no YouTube.  
* **Estrutura de entrega (Jornal Antigo):**  
  * Cabeçalho de edição (título da gazeta, data, edição do dia e contagem de matérias selecionadas).  
  * Blocos individuais por notícia (até 10 itens), divididos entre **Artigos** e **Vídeos (YouTube)**.  
  * **Manchete** \+ **Resumo estritamente limitado a até 2 parágrafos** (linguagem sóbria de jornal impresso clássico, sem perder precisão técnica).  
  * Rodapé de cada nota com: nome da fonte, link clicável, métrica de alcance (quando disponível) e referência visual/imagem.  
  * Nota editorial de transparência ao final (caso menos de 10 matérias atendam aos critérios de qualidade nas últimas 24h).

### **2\. Alertas Técnicos da Plataforma (Alinhamento Obrigatório)**

Para que a Skill funcione na prática sem gerar alucinações ou falhas silenciosas no Gemini, três pontos precisam de desenho explícito:

1. **Execução automática às 08:00 vs. sob demanda:**  
   * Uma Skill/Gem define *como* executar a tarefa, mas não se autoexecuta por relógio sozinha.  
   * **Como resolver:** No plano de instalação, vou entregar o prompt da Skill \+ a instrução exata para vinculá-la a uma **Ação Agendada (Scheduled Action)** diária às 08:00 no Gemini, mantendo o acionamento manual livre a qualquer hora.  
2. **Critério de seleção por "quantidade de visualizações":**  
   * **YouTube:** A contagem de visualizações é pública e pode ser usada diretamente para ranquear e selecionar vídeos.  
   * **Portais de notícias (texto):** A grande maioria dos sites jornalísticos **não exibe contagem pública de visualizações**. Exigir esse número em artigos força a IA a travar ou inventar métricas.  
   * **Como resolver:** Manter **visualizações reais** como critério obrigatório para o YouTube e adotar um **critério substituto verificável** para textos (ex.: destaque nas buscas de notícias das últimas 24h e recorrência em múltiplos veículos de referência), com regra explícita proibindo a IA de inventar números de visualizações.  
3. **"Anexar fotos se a matéria apresentar":**  
   * O Gemini na interface de chat pode citar links das matérias e exibir pré-visualizações/cards quando suportado, mas **não consegue baixar e anexar automaticamente arquivos de imagem de sites de terceiros** por restrições de hotlinking, renderização e direitos autorais.  
   * **Como resolver:** Instruir a Skill a incluir o link direto da matéria (e da imagem/thumbnail pública, quando exposta na busca) sem inventar URLs quebradas — ou, opcionalmente, acionar geração de imagem apenas se você desejar ilustrações autorais em estilo gravura vintage.

### **3\. Etapas que Serão Executadas Após sua Aprovação**

Assim que você aprovar este plano, entregarei o pacote completo seguindo a estrutura profissional:

1. **Resumo da Skill** (nome, objetivo, problema resolvido, público-alvo e plataforma).  
2. **Arquitetura detalhada** (entradas, fluxo passo a passo, saídas e ferramentas do Gemini utilizadas).  
3. **Prompt Completo da Skill** pronto para copiar e colar na criação manual no Gemini (com regras de delegação, formato de jornal antigo, critérios de fonte, limite de 2 parágrafos e tratamento de falhas).  
4. **3 Exemplos de Utilização** (comandos prontos para uso sob demanda e agendamento).  
5. **Plano de Testes** (cenário padrão, cenário complexo e cenário com informações escassas/falhas, com critérios objetivos de aprovação).  
6. **Guia de Instalação e Agendamento** no Gemini (passo a passo para criar a Skill/Gem e configurar o disparo diário às 08:00).  
7. **Limitações Conhecidas e Evoluções Futuras.**

### **4\. Perguntas Rápidas Antes de Executar**

Para eu calibrar a Skill exatamente como você precisa, confirme apenas estes 4 pontos:

1. **Idioma das fontes:** Devo buscar em **português e inglês** (entregando o jornal sempre em português brasileiro) ou apenas em um dos idiomas?  
2. **Métrica para artigos em texto:** Aprova usar **relevância/repercussão em fontes de referência** como critério substituto para textos, mantendo **visualizações reais** para o YouTube?  
3. **Imagens:** Prefere que a Skill apenas **indique o link da matéria/thumbnail real** (sem inventar imagens) ou deseja que ela **gere uma gravura ilustrativa estilo jornal antigo** quando não houver como exibir a foto original?  
4. **Fontes obrigatórias:** Existe algum portal específico ou canal do YouTube que você já quer incluir na lista prioritária?

Assim que confirmar, executo a criação completa da Skill.  

### O Resultado

_Cole o print do resultado e conte como você conferiu antes de usar._

### Como Foi para Você

_Conte em poucas linhas o que mudou no seu dia a dia._
