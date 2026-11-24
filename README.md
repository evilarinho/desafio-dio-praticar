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

# ========================================================================

GAZETA DIÁRIA DA INTELIGÊNCIA ARTIFICIAL
"Crônicas Verificadas do Progresso Computacional"

## Edição de: Terça-feira, 24 de Novembro de 2026 | Janela: Últimas 24h

Seleção Editorial: 6 matérias verificadas (0 Artigos | 6 Vídeos)

### MANCHETE DO DIA (DESTAQUE PRINCIPAL)

**01. RECONDUÇÃO DE JENSEN HUANG À PRESIDÊNCIA DA NVIDIA REACENDE CONFIANÇA DE INVESTIDORES EM WALL STREET**

Em entrevista concedida à emissora CNBC, o investidor Brad Gerstner, da gestora Altimeter, manifestou apoio à decisão do conselho de administração da Nvidia de reintegrar o cofundador Jensen Huang ao posto de diretor-executivo. Segundo Gerstner, o colegiado agiu com sensatez ao reavaliar sua deliberação anterior após o encerramento de uma investigação de 14 meses conduzida por agências federais e pelo Departamento de Justiça dos Estados Unidos, que não apontou provas de violação às leis de segurança nacional.

O executivo sustentou que, embora Huang tenha reconhecido um erro de conduta pessoal ao qual pediu desculpas, o episódio envolvia o respeito ao devido processo legal e não justificava um julgamento precipitado. Gerstner rejeitou pedidos imediatos de reforma na estrutura enxuta da Nvidia — conhecida por seus cerca de 60 subordinados diretos —, exaltando a capacidade da fabricante de lançar novas gerações de chips e infraestrutura de IA em ritmo anual.

* **Canal:** CNBC Television | **Idioma Original:** Inglês
* **Audiência Verificada:** 110.159 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=XAVqD9E7upg](http://www.youtube.com/watch?v=XAVqD9E7upg)

---

### CRÔNICAS E DESPACHOS DA IMPRENSA (ARTIGOS)

*Nota da Redação: Nesta edição, o serviço de busca na web para portais de texto não esteve disponível para consulta direta. Em estrita observância à regra editorial de não inventar manchetes, links ou fontes, esta seção permanece sem despachos escritos, concentrando-se a apuração verificada nos registros audiovisuais abaixo.*

---

### CINEJORNAL E TRANSMISSÕES (VÍDEOS NO YOUTUBE)

**02. FUTUROS DE WALL STREET ENSAIOU REAÇÃO APÓS SEMANA SEVERA DE LIQUIDAÇÃO NO SETOR DE IA**

A transmissão *Bloomberg Daybreak Europe* registrou a tentativa de recuperação dos índices futuros norte-americanos após a forte onda vendedora da semana anterior, que empurrou o Nasdaq para território de correção e apagou os ganhos acumulados do índice em 2026. Estrategistas ouvidos pela emissora apontaram uma divergência marcante no setor de semicondutores: o índice da Filadélfia recuou cerca de 40% desde o pico de junho, ao passo que as estimativas de lucro das companhias avançaram perto de 35% no mesmo período.

O noticiário destacou ainda a pressão competitiva crescente após a estreia da Anthropic na bolsa, com relatos de que Apple e Microsoft desenvolvem modelos próprios de linguagem, somados à ofensiva de empresas chinesas e à queda contínua no preço dos tokens. Na esfera regulatória, o representante comercial dos EUA, Jamieson Greer, defendeu o endurecimento recente nos controles de exportação de chips avançados como medida para fechar brechas de acesso remoto em terceiros países, sem caráter de proibição absoluta.

* **Canal:** Bloomberg Television | **Idioma Original:** Inglês
* **Audiência Verificada:** 45.432 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=DeiqiwVsFgY](http://www.youtube.com/watch?v=DeiqiwVsFgY)

**03. RETORNO DE HUANG IMPULSIONA NVIDIA EM 31%, MAS DESPERTA DURA REAÇÃO NO CONGRESSO AMERICANO**

O telejornal *Meet the Press NOW*, da NBC News, relatou a reação explosiva dos mercados à volta unânime de Jensen Huang ao comando da Nvidia: os papéis da empresa dispararam 31% no pregão — recuperando cerca de US$ 1 trilhão em valor de mercado — e puxaram o Nasdaq para uma alta próxima de 7%. O presidente Donald Trump confirmou ter dialogado com membros do conselho e assegurado que o executivo não representa ameaça à segurança nacional.

Em Washington, contudo, a recondução provocou ceticismo bipartidário. A senadora democrata Elizabeth Warren classificou a decisão como "chocante", defendeu a instalação de rastreadores em chips para coibir desvios à China e exigiu investigação rigorosa, enquanto o Comitê Bancário do Senado marcou audiência pública com Huang para a próxima semana; paralelamente, persistem apurações da SEC sobre práticas contábeis da companhia e do Departamento de Justiça sobre suposto contrabando de processadores via Singapura.

* **Canal:** NBC News | **Idioma Original:** Inglês
* **Audiência Verificada:** 44.882 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=KA3KifJIAgM](http://www.youtube.com/watch?v=KA3KifJIAgM)

**04. DÚVIDAS SOBRE GASTOS DE CAPITAL, DÍVIDA E ENERGIA PRESSIONAM AÇÕES DE IA NOS EUA E NA ÁSIA**

No programa *Morning Bid*, a agência Reuters examinou os fundamentos por trás do mês turbulento para as companhias de inteligência artificial, com destaque para a queda superior a 50% do índice sul-coreano Kospi desde sua máxima. Analistas ouvidos pela redação apontaram que o mercado ainda busca respostas claras sobre o retorno financeiro efetivo dos investimentos bilionários em infraestrutura, a sustentabilidade do chamado financiamento circular entre fornecedores e clientes, o encarecimento do crédito para novas operadoras de nuvem (*neoclouds*) e a escassez de energia elétrica para novos data centers.

A análise ressaltou que o cenário de juros mais elevados — diante da expectativa de novo aperto monetário pelo Federal Reserve e da iminente divulgação do índice de inflação PCE — reduz a tolerância dos investidores a projetos altamente alavancados. Para os comentaristas, o ritmo futuro da construção de data centers enfrentará tanto restrições financeiras quanto maior escrutínio político no novo Congresso americano.

* **Canal:** Reuters | **Idioma Original:** Inglês
* **Audiência Verificada:** 17.388 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=wRUe2L-_1yE](http://www.youtube.com/watch?v=wRUe2L-_1yE)

**05. SEMICONDUTORES EUROPEUS ESBOÇAM ALÍVIO E OPERADORA DEFENDE IA SOBERANA NA BORDA**

A cobertura matinal da Bloomberg em Londres acompanhou a recuperação das ações europeias de tecnologia, lideradas pela holandesa ASML, que avançou entre 4% e 5% na abertura acompanhando o repique do Nasdaq. Estrategistas de mercado, porém, mantiveram tom cauteloso, advertindo que o movimento pode refletir cobertura de posições vendidas em uma semana encurtada pelo feriado de Ação de Graças, com as atenções voltadas ao balanço da Dell como termômetro da demanda por servidores de IA.

Na mesma edição, Dawn Childs, CEO da operadora europeia de data centers nLighten — detentora de 34 unidades em sete países —, argumentou que a monetização duradoura da inteligência artificial migrará dos megacentros de treinamento para a computação de borda (*edge*), onde ocorre a inferência próxima às empresas. A executiva defendeu que a Europa estruture uma infraestrutura soberana apoiada em modelos menores e mais eficientes, integrados de forma cooperativa às redes elétricas locais.

* **Canal:** Bloomberg Television | **Idioma Original:** Inglês
* **Audiência Verificada:** 13.231 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=amYNpTLDUAM](http://www.youtube.com/watch?v=amYNpTLDUAM)

**06. ESTREIA DA ANTHROPIC PERDE FÔLEGO EM WALL STREET E PROJETO CONTRA DEEPFAKES AVANÇA NO CAPITÓLIO**

O boletim *AI Weekly*, da Reuters, trouxe um balanço dos principais acontecimentos da semana, abrindo com o arrefecimento da aguardada oferta pública inicial (IPO) da Anthropic, avaliada em US$ 1,5 trilhão: as ações encerraram a sexta-feira abaixo de US$ 89, recuo de 8,5% frente ao pregão anterior. O informativo também registrou a advertência do presidente Donald Trump de impor pesadas tarifas a empresas americanas que ergam data centers no exterior, além de sua oposição a regulações globais de IA durante a cúpula da APEC na China.

O despacho destacou ainda que a Nvidia projetou receita de US$ 130 bilhões para o quarto trimestre — cifra acima das estimativas de analistas —, sinalizando vigor comercial apesar da turbulência societária. No campo legislativo, Paris Hilton uniu-se a parlamentares como Alexandria Ocasio-Cortez no Congresso dos EUA para pressionar pela aprovação do *Defiance Act*, proposta voltada a assegurar reparação judicial a vítimas de *deepfakes* sexuais não consensuais.

* **Canal:** Reuters | **Idioma Original:** Inglês
* **Audiência Verificada:** 10.293 visualizações
* **Acesso e Miniatura Original:** [http://www.youtube.com/watch?v=-lkjO6_RFSU](http://www.youtube.com/watch?v=-lkjO6_RFSU)

========================================================================
NOTA DA REDAÇÃO (AUDITORIA DA EDIÇÃO)

* **Total publicado:** 6/10 itens.
* **Escopo temporal efetivamente utilizado:** Últimas 24 horas (publicações de 23 de novembro de 2026, apuradas na virada para 24 de novembro de 2026).
* **Observações de apuração:** A ferramenta de busca na web para matérias em texto não foi acionada nesta sessão por restrição operacional vigente; por essa razão, a edição foi composta integralmente por transmissões verificadas de emissoras e agências internacionais consolidadas no YouTube (CNBC Television, Bloomberg Television, NBC News e Reuters), ordenadas rigorosamente pelo número real de visualizações públicas. Nenhum artigo, dado ou métrica foi inventado para completar o teto de 10 itens.
========================================================================

### Como Foi para Você

Essa versão inicial já ajudou muito manter-me atualizado diariamente com os principoais assuntos de IA.
