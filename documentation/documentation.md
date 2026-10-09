# Ozzy Finances --- Documentação Oficial de Hipóteses e Estratégia de Validação

**Projeto:** Ozzy Finances\
**Etapa:** Product Discovery e validação inicial\
**Data de encerramento da validação:** outubro de 2026\
**Status final:** **Perseguir com ajustes**\
**Objetivo do documento:** registrar o problema investigado, as
hipóteses formuladas, a solução inicialmente proposta, os experimentos
realizados, os critérios de decisão e as conclusões sustentadas pelas
evidências coletadas.

------------------------------------------------------------------------

## 1. Contexto e objetivo da Product Discovery

A proposta do Ozzy Finances surgiu da hipótese de que
microempreendedores e profissionais autônomos enfrentam dificuldades
para controlar as finanças do negócio, especialmente quando utilizam
registros informais, não mantêm as movimentações atualizadas ou têm
dificuldade para transformar receitas e despesas em informações úteis
para tomar decisões.

O objetivo da Product Discovery foi investigar se esse problema ocorre
na prática, compreender suas consequências, identificar uma oportunidade
de produto digital com apoio de inteligência artificial (IA) e avaliar
se a proposta desperta interesse em potenciais usuários.

O foco desta etapa não foi construir um produto completo nem comprovar a
viabilidade comercial definitiva. O objetivo foi reunir evidências
suficientes para decidir se a ideia deveria ser perseguida, ajustada,
pivotada ou abandonada.

A IA foi utilizada como apoio ao processo de descoberta e organização
das informações. A validação, entretanto, foi fundamentada nas respostas
e manifestações de potenciais usuários, e não nas opiniões geradas pelo
modelo.

## 2. Problema identificado, público e oportunidade

### 2.1 Problema investigado

A hipótese inicial era que parte dos MEIs e profissionais autônomos não
possui um processo simples e consistente para controlar as finanças do
negócio. Isso pode dificultar a separação entre despesas pessoais e
profissionais, a atualização dos registros e a compreensão de quanto o
negócio realmente gera de resultado.

Durante a investigação, o problema foi refinado. As respostas sugeriram
que a dificuldade não se limita à mistura entre dinheiro pessoal e
profissional. Também envolve manter os registros atualizados e
interpretar os dados para compreender lucro, custos, dinheiro disponível
e adequação dos preços.

**Formulação refinada do problema:**

> Pequenos empreendedores que controlam as finanças de maneira manual ou
> irregular têm dificuldade para manter os registros atualizados e
> transformar as movimentações em uma visão clara de receitas, despesas
> e lucro. Essa falta de clareza pode dificultar decisões como definir
> preços, controlar custos, retirar dinheiro para uso pessoal e avaliar
> o resultado de cada serviço ou produto.

Essa formulação representa a interpretação das evidências iniciais. Não
significa que todas as pessoas do público enfrentem o problema com a
mesma intensidade.

### 2.2 Público inicialmente considerado

A investigação começou considerando um público amplo:

-   MEIs;
-   profissionais autônomos;
-   prestadores de serviços;
-   freelancers;
-   pequenos comerciantes e produtores.

As respostas indicaram que a oportunidade pode ser mais relevante para
pessoas que trabalham por conta própria e ainda utilizam controles
informais, como anotações, cadernos ou registros irregulares.

**Público prioritário sugerido para uma próxima etapa:** pequenos
prestadores de serviços e profissionais autônomos que não mantêm um
controle financeiro consistente e têm dificuldade para identificar
quanto realmente lucram.

Essa priorização é uma decisão de foco para futuras validações, não uma
comprovação de que esse segmento seja definitivamente o melhor mercado.

### 2.3 Oportunidade identificada

A oportunidade consiste em reduzir o esforço necessário para registrar e
organizar movimentações financeiras e, principalmente, transformar esses
registros em informações compreensíveis e úteis para decisões
cotidianas.

Entre as necessidades identificadas estão:

-   saber quanto entrou, quanto saiu e quanto sobrou;
-   compreender custos e resultado por serviço, obra ou produto;
-   distinguir despesas pessoais e profissionais;
-   reduzir esquecimentos e a dependência de registros manuais;
-   receber alertas ou identificar situações que mereçam atenção.

A oportunidade não depende necessariamente de oferecer muitas
funcionalidades. A proposta inicial deve priorizar simplicidade de
registro e clareza do resultado financeiro.

## 3. Hipóteses de problema, solução e valor

As hipóteses foram organizadas em três grupos. O resultado de cada uma é
apresentado de acordo com a evidência disponível ao final da validação.

### 3.1 Hipóteses de problema

  -----------------------------------------------------------------------
  ID                      Hipótese                Resultado ao encerrar a
                                                  validação
  ----------------------- ----------------------- -----------------------
  HP01                    MEIs e profissionais    **Parcialmente
                          autônomos               confirmada.** A mistura
                          frequentemente misturam apareceu nas respostas,
                          dinheiro pessoal e      mas não foi demonstrada
                          profissional.           como o problema
                                                  principal para todos os
                                                  participantes.

  HP01.1                  A mistura entre         **Parcialmente
                          finanças pessoais e     confirmada.** Foram
                          profissionais gera      relatadas dificuldades
                          consequências           e consequências, mas a
                          financeiras relevantes. amostra não permite
                                                  generalizar a
                                                  frequência ou a
                                                  gravidade.

  HP02                    A dificuldade de manter **Sinal favorável.** As
                          controle financeiro     respostas mencionaram
                          está relacionada ao     falta de tempo,
                          esforço, à falta de     esquecimento,
                          tempo, ao esquecimento  dificuldade de
                          ou à complexidade das   organização e
                          ferramentas             dificuldade com
                          disponíveis.            ferramentas. Não foi
                                                  possível determinar uma
                                                  causa única
                                                  predominante.

  HP03                    Os usuários têm         **Reforçada pelas
                          dificuldade para        respostas.** Surgiram
                          entender o lucro real e necessidades
                          usar os dados           relacionadas a lucro,
                          financeiros em decisões custos, preços e
                          práticas.               dinheiro disponível.
  -----------------------------------------------------------------------

### 3.2 Hipóteses de solução

  -----------------------------------------------------------------------
  ID                      Hipótese                Resultado ao encerrar a
                                                  validação
  ----------------------- ----------------------- -----------------------
  HS01                    Um processo simples de  **Ainda não validada em
                          registro e organização  uso real.** As
                          das movimentações pode  respostas demonstram
                          reduzir o esforço do    interesse na
                          controle financeiro.    simplicidade, mas não
                                                  houve teste funcional
                                                  que medisse a redução
                                                  de esforço.

  HS02                    Uma interface           **Não validada.**
                          conversacional, como    Alguns respondentes
                          WhatsApp, com           mencionaram
                          possibilidade de        espontaneamente
                          registrar informações   mensagens ou áudio, mas
                          por texto ou áudio será não foi realizado um
                          conveniente para o      teste comparativo de
                          público.                canais.

  HS03                    Relatórios e            **Sinal favorável,
                          informações simples     ainda não comprovado
                          sobre receitas,         por uso.** Os
                          despesas e lucro        respondentes
                          ajudarão o usuário a    manifestaram interesse
                          compreender melhor o    nessas informações, mas
                          resultado do negócio.   não utilizaram um
                                                  relatório funcional da
                                                  solução.
  -----------------------------------------------------------------------

### 3.3 Hipóteses de valor

  -----------------------------------------------------------------------
  ID                      Hipótese                Resultado ao encerrar a
                                                  validação
  ----------------------- ----------------------- -----------------------
  HV01                    Uma visão clara do      **Reforçada como
                          resultado financeiro    necessidade
                          ajudará o usuário a     percebida.** Os relatos
                          tomar decisões melhores indicaram relevância
                          sobre custos, preços e  dessas decisões, mas
                          retiradas.              ainda não comprovam
                                                  mudança efetiva de
                                                  comportamento.

  HV02                    Usuários perceberão     **Parcialmente
                          valor suficiente para   sustentada.** Entre 15
                          demonstrar interesse em respondentes, 6
                          experimentar a solução. demonstraram interesse
                                                  em testar
                                                  gratuitamente, 6
                                                  responderam "talvez" e
                                                  3 não demonstraram
                                                  interesse.

  HV03                    Os usuários estarão     **Não validada.** O
                          dispostos a pagar pelo  experimento avaliou
                          produto.                interesse em um teste
                                                  gratuito, não
                                                  disposição real para
                                                  pagar.
  -----------------------------------------------------------------------

**Observação metodológica:** "parcialmente confirmada", "reforçada" e
"sinal favorável" indicam o nível de evidência disponível nesta etapa, e
não uma prova estatística de validade da hipótese.

## 4. Solução inicialmente proposta e definição do MVP

### 4.1 Visão inicial da solução

O Ozzy Finances foi concebido como um assistente financeiro com apoio de
IA para ajudar MEIs e profissionais autônomos a registrar movimentações,
organizar receitas e despesas e compreender melhor o resultado do
negócio.

O fluxo ideal inicialmente imaginado incluía:

1.  registro de uma movimentação por texto ou áudio;
2.  classificação e categorização assistida por IA;
3.  confirmação ou correção da informação pelo usuário;
4.  organização dos dados financeiros;
5.  apresentação de relatórios simples;
6.  geração de alertas e insights para apoiar decisões.

A visão completa também considerava uma aplicação com banco de dados,
interface de acompanhamento e integração com serviços de IA. Essa
arquitetura permaneceu como uma possibilidade futura, não como algo
necessário para validar a hipótese inicial.

### 4.2 MVP de validação

O MVP foi definido de acordo com o objetivo de cada experimento,
priorizando baixo custo e rapidez de aprendizagem.

**Primeira etapa --- descoberta do problema**

-   formulário para levantar práticas atuais de controle financeiro;
-   perguntas sobre separação das finanças, dificuldades, frequência e
    consequências;
-   coleta de exemplos e relatos dos participantes.

**Segunda etapa --- teste de interesse pela proposta**

-   landing page pública do Ozzy Finances;
-   apresentação da proposta de valor e de exemplos ilustrativos;
-   chamada para ação para manifestar interesse em participar de um
    teste gratuito;
-   formulário de interesse conectado a uma planilha para registrar as
    respostas.

Landing page divulgada: <https://ozzy-finances.my.canva.site/>

**Importante:** a landing page foi um MVP de validação da proposta e do
interesse, não um MVP funcional do sistema financeiro. Os respondentes
avaliaram a descrição da solução, sem utilizar o produto completo.

### 4.3 Limites de escopo

Nesta etapa, não foi necessário desenvolver:

-   aplicativo completo;
-   banco de dados de produção;
-   integração funcional com WhatsApp;
-   categorização financeira automatizada em ambiente real;
-   painel financeiro conectado a movimentações reais;
-   mecanismo de cobrança ou assinatura.

Esses itens só deveriam ser priorizados depois que a proposta de valor e
as necessidades essenciais fossem melhor compreendidas.

## 5. Como a IA foi utilizada durante o processo de Discovery

A IA foi empregada como ferramenta de apoio ao raciocínio e à execução
do processo, sem substituir a coleta de evidências com potenciais
usuários.

### 5.1 Exploração e organização de ideias

A IA auxiliou na exploração de oportunidades de produto digital, na
organização das ideias e na estruturação de hipóteses iniciais de
problema, solução e valor.

### 5.2 Estruturação da investigação

A IA apoiou a elaboração e a revisão das perguntas de descoberta, com
foco em compreender comportamentos atuais, dificuldades, consequências e
alternativas já utilizadas. A estratégia buscou evitar que as perguntas
iniciais induzissem os participantes a concordar com uma solução
previamente escolhida.

### 5.3 Construção dos artefatos de validação

A IA auxiliou na estruturação do formulário, na definição da proposta de
valor, na organização do conteúdo da landing page e no planejamento dos
critérios de sucesso do experimento.

### 5.4 Organização e interpretação das respostas

A IA foi utilizada como apoio à síntese dos dados coletados, à
identificação de padrões nos relatos e à comparação entre as hipóteses
iniciais e as evidências observadas.

As interpretações foram tratadas como análises de apoio, sujeitas às
limitações da amostra e à necessidade de conferir os relatos originais.

### 5.5 Limites do uso da IA

A IA não foi considerada evidência de demanda de mercado. Ela não
substituiu entrevistas, respostas de usuários ou manifestações reais de
interesse.

Também não foram tratados como comprovados, apenas por terem sido
sugeridos pela IA:

-   a existência de um mercado comercialmente viável;
-   a disposição dos usuários para pagar;
-   a preferência geral por WhatsApp ou áudio;
-   a eficácia da categorização automática;
-   a melhoria efetiva das decisões financeiras.

A validação foi orientada pelos dados coletados com pessoas reais,
conforme o princípio de que a IA apoia a descoberta, mas não valida o
mercado sozinha.

## 6. Experimentos escolhidos e critérios de sucesso

A estratégia foi dividida em duas etapas complementares: descoberta do
problema e teste inicial de interesse pela proposta.

### 6.1 Experimento 1 --- descoberta do problema

**Objetivo:** investigar se as dificuldades de controle financeiro
ocorrem na prática e compreender como afetam o cotidiano dos
participantes.

**Método:** formulário com perguntas sobre perfil, métodos de controle,
separação das finanças, dificuldades, consequências, ferramentas já
utilizadas e necessidades de informação.

**Critérios inicialmente considerados:**

-   pelo menos 4 de 5 participantes confirmariam a mistura entre
    finanças pessoais e profissionais;
-   pelo menos 3 de 5 registrariam movimentações durante sete dias em um
    teste acompanhado;
-   pelo menos 4 de 5 considerariam útil o relatório;
-   pelo menos 3 de 5 demonstrariam disposição para pagar R\$ 30 ou mais
    por mês.

Os critérios de registro durante sete dias, utilidade de relatório e
disposição a pagar pertenciam ao plano de um teste acompanhado que não
foi executado. Por isso, não devem ser apresentados como resultados
alcançados.

**Resultado obtido:** foram analisadas 4 respostas na etapa inicial de
descoberta. Os relatos sugeriram dificuldades relacionadas à manutenção
dos registros, à clareza sobre o lucro e à tomada de decisões
financeiras. A amostra foi pequena e não permitiu generalizações.

**Limitação:** os resultados foram suficientes para refinar o problema e
orientar o próximo experimento, mas não para concluir que a hipótese
inicial sobre a mistura das finanças fosse universal ou central para
todos os segmentos.

### 6.2 Experimento 2 --- landing page e manifestação de interesse

**Objetivo:** avaliar se a apresentação de uma solução para simplificar
o controle financeiro e melhorar a clareza sobre o resultado do negócio
despertaria interesse em potenciais usuários.

**Hipótese experimental:**

> Se pequenos empreendedores que controlam suas finanças de forma manual
> ou irregular puderem registrar movimentações de maneira simples e
> obter uma visão clara de receitas, despesas e lucro, então
> demonstrarão interesse em experimentar essa solução.

**Artefato:** landing page do Ozzy Finances com descrição da proposta,
benefícios esperados, representação ilustrativa da solução e chamada
para participar de um teste gratuito.

**Ação observada:** preenchimento voluntário do formulário de
manifestação de interesse.

**Resultados coletados:**

  Indicador                                Resultado
  -------------------------------------- -----------
  Respostas ao formulário de interesse            15
  Interesse em testar gratuitamente          6 (40%)
  Talvez tenha interesse                     6 (40%)
  Sem interesse no momento                   3 (20%)

As porcentagens se referem exclusivamente às 15 respostas recebidas.
Como o total de visitantes da landing page e o número de pessoas que
visualizaram ou clicaram na chamada para ação não foram registrados, não
foi possível calcular a taxa de conversão da página.

### 6.3 Critérios de sucesso planejados para a landing page

Antes da divulgação, foram considerados os seguintes parâmetros internos
para avaliar o experimento:

-   alcançar de 20 a 30 visitantes qualificados;
-   pelo menos 30% dos visitantes chegarem à chamada para ação;
-   pelo menos 15% clicarem na chamada para ação;
-   pelo menos 10% concluírem o formulário;
-   obter pelo menos 5 pessoas qualificadas dispostas a participar do
    teste;
-   identificar pelo menos 3 comentários espontâneos alinhados ao
    problema investigado.

Esses valores eram **limiares internos definidos para orientar a
decisão**, e não benchmarks de mercado.

**Avaliação final dos critérios:**

-   Foram obtidas 15 respostas, mas o total de visitantes não foi
    registrado.
-   Seis pessoas manifestaram interesse explícito em testar
    gratuitamente, superando o limiar numérico de cinco interessados.
-   Não há dados suficientes para verificar os critérios baseados em
    visitantes, visualizações ou cliques.
-   As respostas abertas revelaram dificuldades concretas relacionadas a
    lucro, custos, preços e controle financeiro.

Portanto, o critério de cinco manifestações positivas foi atingido em
quantidade absoluta, mas o conjunto de critérios não pode ser
considerado integralmente comprovado. Além disso, o interesse declarado
não comprova utilização recorrente, valor percebido após o uso ou
disposição para pagar.

## 7. Critérios previamente definidos para a decisão

A estratégia de decisão considerou quatro caminhos possíveis. Os
critérios abaixo devem ser entendidos como regras de orientação
definidas para reduzir decisões baseadas apenas em preferência pessoal.

### 7.1 Perseverar

**Critério:** as principais hipóteses de problema, utilidade e interesse
seriam sustentadas pelos resultados, e os indicadores de sucesso
previamente definidos seriam atingidos.

**Decisão correspondente:** manter a direção da solução e avançar para
um teste de uso mais concreto, com um grupo pequeno de potenciais
usuários.

### 7.2 Ajustar

**Critério:** o problema seria confirmado, mas a proposta, o formato, o
canal ou as funcionalidades inicialmente imaginadas não demonstrariam
valor suficiente ou precisariam de refinamento.

**Decisão correspondente:** manter o problema central e ajustar o
público prioritário, a proposta de valor ou a forma de entrega.

### 7.3 Pivotar

**Critério:** as evidências indicariam uma necessidade real, mas em
outro segmento, com outra causa principal ou com uma solução
significativamente diferente da inicialmente proposta.

**Decisão correspondente:** reformular a hipótese central e realizar
nova validação antes de desenvolver.

### 7.4 Abandonar

**Critério:** menos de 3 de 5 participantes confirmariam o problema e
nenhum demonstraria disposição para pagar, ou as evidências apontariam
baixa relevância da necessidade para o público investigado.

**Decisão correspondente:** interromper o desenvolvimento daquela
proposta e registrar os aprendizados antes de selecionar outra
oportunidade.

O critério original de abandono foi concebido para uma investigação com
cinco participantes e incluía disposição a pagar. Como o experimento
final da landing page não mediu disposição a pagar, esse critério não
pode ser considerado testado integralmente.

## 8. Veredito final da validação

### 8.1 Decisão: PERSEGUIR COM AJUSTES

A decisão final é continuar explorando a oportunidade, mas sem iniciar o
desenvolvimento completo do produto.

Essa decisão se apoia nos seguintes sinais:

-   foram relatadas dificuldades concretas para manter controles
    financeiros atualizados;
-   apareceram necessidades relacionadas a entender lucro, custos,
    preços e dinheiro disponível;
-   6 de 15 respondentes manifestaram interesse explícito em testar
    gratuitamente;
-   as respostas indicam que a clareza financeira e a redução do esforço
    de registro podem ser mais relevantes do que o uso de IA,
    isoladamente.

A decisão também considera as limitações:

-   amostras pequenas nas etapas de descoberta;
-   ausência de teste funcional da solução;
-   ausência de dados completos de tráfego e conversão da landing page;
-   falta de validação de uso recorrente;
-   disposição a pagar ainda não investigada;
-   ausência de comprovação da viabilidade comercial.

### 8.2 Ajuste recomendado para a proposta de valor

A proposta inicial enfatizava um assistente financeiro com IA. A partir
das evidências, recomenda-se comunicar primeiro o resultado esperado:

> **Um assistente financeiro simples que ajuda profissionais autônomos a
> registrar suas movimentações e entender quanto realmente ganham,
> gastam e lucram com o próprio trabalho.**

A IA deve ser apresentada como um meio de reduzir o esforço e organizar
informações, não como benefício suficiente por si só.

### 8.3 Próxima etapa recomendada

Embora a validação acadêmica deste ciclo seja encerrada aqui, uma
próxima etapa de produto deveria testar um protótipo simples com pessoas
que manifestaram interesse. O teste deveria observar se elas conseguem
registrar movimentações, interpretar o resultado e identificar utilidade
concreta para uma decisão financeira.

Somente depois dessa evidência seria recomendável decidir quais
funcionalidades automatizar e se faz sentido investir em integrações,
banco de dados e interface própria.

## 9. Síntese para apresentação acadêmica

  -----------------------------------------------------------------------
  Elemento                            Síntese
  ----------------------------------- -----------------------------------
  Problema                            Dificuldade para manter controles
                                      financeiros atualizados e
                                      compreender o lucro real do
                                      negócio.

  Público prioritário sugerido        Pequenos prestadores de serviços e
                                      profissionais autônomos com
                                      controle financeiro informal ou
                                      irregular.

  Solução proposta                    Assistente financeiro que
                                      simplifica o registro e organiza
                                      receitas, despesas e informações
                                      sobre o resultado.

  Papel da IA                         Apoiar classificação, organização,
                                      síntese e geração de informações,
                                      sem substituir a validação com
                                      usuários.

  Experimentos realizados             Formulário de descoberta do
                                      problema e landing page com
                                      formulário de manifestação de
                                      interesse.

  Evidência de interesse              6 de 15 respondentes disseram ter
                                      interesse em testar gratuitamente.

  Hipótese ainda em aberto            Uso recorrente, eficácia prática,
                                      preferência por canal, valor
                                      adicional da IA e disposição a
                                      pagar.

  Decisão                             **Perseguir com ajustes**, sem
                                      desenvolver o produto completo
                                      neste momento.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 10. Considerações finais

A Product Discovery permitiu transformar uma ideia ampla de controle
financeiro com IA em uma hipótese de produto mais específica: reduzir o
esforço de controle financeiro e ajudar pequenos empreendedores a
compreender o resultado real de seu trabalho.

Os experimentos trouxeram sinais favoráveis sobre a existência do
problema e sobre o interesse inicial pela proposta. Contudo, não
comprovam que a solução funcione na prática ou que exista disposição
para pagar por ela.

O resultado desta etapa é, portanto, uma decisão fundamentada de
**perseguir com ajustes**, preservando os aprendizados, reconhecendo as
limitações das evidências e evitando investir prematuramente no
desenvolvimento completo.
