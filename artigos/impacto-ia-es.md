# Impacto da IA na Prática da Engenharia de Software

_Relato do seminário proferido pela Profa. Dra. Lina Garcés, da USP._

## Introdução

O seminário explorou, através da profa. Dra Lina Garcés, da Universidade de São Paulo (USP), aspectos relacionados à revolução que a Inteligência Artificial (IA), especialmente a IA Generativa (GenAI), vem causando nos processos de Engenharia de Software (ES). Foram abordados temas que abrangem desde as definições relacionadas à qualidade na Engenharia até as limitações e desafios atuais da IA {cite:p}`garces2025impacto`.

## Qualidade na Engenharia de Software

A apresentação iniciou questionando o que faz um produto de engenharia moderna ser de qualidade. Destacou características como previsibilidade, durabilidade e o seguimento de regras e requisitos. Além disso, mencionou a capacidade de resolver um problema, como aspectos relacionados à segurança - como em carros elétricos e espaçonaves - e sustentabilidade são muito importantes. Exemplos de falhas, como os acidentes da SpaceX, reforçaram a necessidade de seguir boas práticas para garantir a qualidade.

No contexto de uma sociedade digital, onde tecnologias e softwares permeiam praticamente todas as atividades diárias - de carros elétricos a simulações de pontes -, a qualidade do software se torna indispensável. Conforme mencionado por Garcés {cite:p}`garces2025impacto`, software é definido como um artefato que resolve problemas reais, agrega valor e vai além do código-fonte, englobando o trabalho de equipes, propriedade intelectual e inovações. Argumentou ainda que qualidade do software é, em última instância, decidida pelo usuário, que avalia critérios como desempenho (lentidão, consumo de recursos), usabilidade, segurança e confiabilidade. As boas práticas e ferramentas da engenharia de software visam concretizar essas qualidades, incluindo segurança, desempenho, confiabilidade, disponibilidade, longevidade e usabilidade.

## Atividades da Engenharia de Software

Conforme Garcés {cite:p}`garces2025impacto`, a Engenharia de Software envolve diversas atividades interdependentes, que podem ser realizadas por especialistas ou por engenheiros de ciclo completo ("Full Cycle Engineer"), como visto na Netflix. As principais atividades incluem:

- **Análise e Design**: onde envolve a especificação de requisitos (o que o software deve fazer) e o projeto da arquitetura (como o software será construído, incluindo padrões e infraestrutura).
- **Construção (Codificação)**: a implementação propriamente dita, utilizando tecnologias e linguagens de programação.
- **Teste e Validação**: visando verificar se o software funciona corretamente, atende aos requisitos e oferece a qualidade esperada (segurança, confiabilidade, usabilidade).
- **Operação**: onde lida com a infraestrutura e o ambiente de implantação do software.
- **Manutenção**: foca na detecção e correção de erros, gerenciamento de mudanças e refatorações.
- **Evolução**: abrange a adaptação do software a novas regras ou modelos de negócio e refatorações de arquitetura.
- **Gerenciamento do Projeto**: controla o escopo, custo e recursos do projeto.
- **Versionamento**: gerencia diferentes versões do software, crucial para equipes grandes.

## Linha do tempo da automação em ES e o papel da IA

Garcés {cite:p}`garces2025impacto` também apresentou uma linha do tempo que demonstra a automação na Engenharia de Software sendo realizada através dos anos:

- **Anos 60**: suporte básico com compiladores, depuradores e processadores de texto.
- **Anos 70**: surgimento das primeiras ferramentas CASE (Computer-Aided Software Engineering) e IDEs simples para análise e projeto.
- **Anos 80**: ascensão da Orientação a Objetos (OO), com linguagens OO, IDEs avançadas, UML e geração de código a partir de modelos.
- **Anos 90**: integração de software, com as primeiras ferramentas de versionamento, refatoração automática em IDEs e o início das práticas de Integração Contínua (CI) e testes automatizados (unitários, funcionais).
- **Anos 2000**: consolidação de CI/CD (Integração Contínua/Entrega Contínua) e testes automatizados com ferramentas como JUnit e Selenium.
- **Anos 2010**: início do uso de IA na ES, especialmente em DevOps e pipelines de CI/CD, com ferramentas como GitLab, GitHub e as primeiras versões do Copilot, utilizando IA para autocompletar e sugerir código, além de análise estática inteligente.
- **Anos 2020 (durante a pós-pandemia)**: expansão da IA na ES, com foco em Machine Learning, Infraestrutura como Código (IaC), automação completa de testes, deploy e monitoramento de serviços na nuvem.
- **Atualmente, através da Automação Preditiva**: a adoção da IA Generativa para geração de código (a partir de requisitos), detecção de bugs, revisão de código (linters) e documentação. A IA está integrada nas IDEs como assistente de desenvolvimento (ex: Gemini no Google Colab como "pair programmer").

Em **tendências futuras**, foi abordada a automação assistiva e preditiva, onde a IA atua como ferramenta de apoio a decisões para aumentar a produtividade das equipes, inclusive nas etapas mais intelectuais de design e ideação.

## Impacto da IA Generativa nas atividades de Engenharia de Software

Durante a apresentação, foi abordado por Garcés {cite:p}`garces2025impacto` que a IA Generativa já está transformando e continuará a transformar profundamente as diversas atividades da Engenharia de Software, mais do que inovações anteriores.

Conforme a Figura 1, foi mencionado que a exibição cronológica de lançamentos de LLMs criada por Naveed et. al. {cite:p}`naveed2024comprehensive` abordou os lançamentos de Large Language Models (LLMs) onde são divididos em dois tipos principais, representados por cores diferentes:

- Os cartões azuis representam modelos "pré-treinados".
- Os cartões laranja correspondem a modelos "ajustados por instruções" (fine-tuned).

 
Figura 1. Exibição cronológica de lançamentos de LLMs {cite:p}`naveed2024comprehensive`

Em um contexto mais amplo, foi mencionado que o mundo das LLMs é vasto e está em rápida evolução, com muitas opções surgindo constantemente. A dificuldade em acompanhar todas essas tendências é bastante notória, haja vista a quantidade de novas tecnologias que estão sendo criadas frequentemente. Além disso, a discussão sobre a figura destacou que alguns desses modelos são especializados em código-fonte, ou seja, em entender e gerar código, sendo mais eficientes para dar suporte ao desenvolvedor. Outros são mais genéricos para linguagem natural, podendo ser usados para gerar documentações, código, casos de teste e código de infraestrutura. 

Desta forma, para cada atividade da ES, a GenAI vem sendo utilizada da seguinte forma:

- **Requisitos de Software**
    - Uso atual na indústria: transcrições de entrevistas para texto e classificação de requisitos entre funcionais e não funcionais (segurança, disponibilidade etc.).
    - Pesquisas: geração de requisitos (histórias de usuário, BDD), diagramas de caso de uso e casos de teste a partir de textos de entrevistas.
    - Novas tendências: completar e verificar a consistência e completude dos requisitos, além de verificar se os requisitos estão sendo atendidos no código.
- **Design de Software**
    - Uso atual na indústria: identificação de "software smells" e sugestão de refatorações (o GitHub Copilot já auxilia nisso). No entanto, o design ainda é uma área que exige muito raciocínio intelectual humano.
    - Pesquisas: geração de diagramas UML (classes, casos de uso) a partir de especificações em linguagem natural, embora ainda com limitações em complexidade.
    - Novas tendências: extração e avaliação da arquitetura de software a partir do código, sugestão de melhores arquiteturas/padrões, previsão de riscos em arquiteturas, e design de interfaces de usuário seguindo práticas de IHC/UX (já com alguns avanços em plugins como no Figma).
- **Codificação**
    - Uso atual na indústria: correção de código, sugestões para completar código, detecção de código duplicado, explicação de código e geração de comentários.
    - Pesquisas: geração de código confiável e correto com base em comentários (ainda apresenta erros), inspeção de código para vulnerabilidades e sugestão de correções.
- **Teste de Software**, sendo uma das áreas mais pesquisadas para o uso de LLMs.
    - Uso atual/pesquisas: geração de casos de teste a partir de requisitos, geração de código de testes unitários, e a interação de agentes de IA para gerar código e seus respectivos testes.
    - Novas tendências: geração de casos de testes não funcionais (segurança, desempenho, acessibilidade) e testes automatizados para interfaces. A depuração e correção automática de código também são pesquisadas, mas com resultados ainda insatisfatórios para a indústria.
- **Engenharia de Plataformas (DevOps)**
    - Uso atual na indústria: menos uso direto de IA Generativa, mas Machine Learning já é empregado.
    - Linhas de pesquisa: geração de código para configuração de infraestrutura, verificação de vulnerabilidades no código de infraestrutura, previsão, prevenção e correção de problemas de operação, e previsão de necessidades de infraestrutura com autoconfiguração.

## Limitações Atuais e Desafios da IA na ES

Conforme Fan et. al. {cite:p}`fan2023large`, referenciado por Garcés {cite:p}`garces2025impacto`, apesar dos avanços, o uso da IA Generativa na Engenharia de Software apresenta limitações e desafios significativos:

- **Vulnerabilidades no código gerado**: pesquisas indicam que 40% do código gerado pelo Copilot apresenta vulnerabilidades. Isso ocorre porque as IAs são treinadas com dados de repositórios públicos que já contêm bugs e erros, replicando esses problemas.
- **Alto custo operacional e consumo de energia**: o treinamento e o uso de LLMs são extremamente caros e consomem muita energia. O treinamento do GitHub Copilot, por exemplo, resultou na emissão de 13.000 toneladas métricas de CO2, comparável ao consumo energético anual de um país. Para tarefas triviais, ferramentas de automação mais econômicas sem IA são preferíveis.
- **Violação de direitos autorais**: muitos modelos de IA Generativa são treinados com código público (p.e. GitHub) que pode ter diversas licenças de uso. Ao gerar novo conteúdo sem citar as fontes, as IAs podem estar violando direitos autorais e leis de propriedade intelectual.
- **Precisão e confiança**: as IAs podem apresentar "alucinações", gerando conteúdo impreciso. Não se pode confiar cegamente em tudo que é gerado, exigindo garantia de responsabilidade humana e revisão constante.
- **Segurança e privacidade**: há preocupações com o uso de dados privados e a necessidade de políticas claras para a implantação de GenAI.
- **Processos de negócio e custos**: a alta dependência de IAs Generativas pode aumentar o custo de desenvolvimento e atrelar as empresas às políticas de preços das grandes corporações donas dessas IAs.
- **Riscos éticos e legais**: Além dos direitos autorais, questões como vieses nos dados de treinamento e a falta de diretrizes para o uso ético e responsável da IA são grandes desafios.
- **Interpretabilidade**: as IAs frequentemente atuam como "caixas-pretas" (black-box models), tornando difícil entender como chegaram a uma determinada decisão ou solução. Isso gera pouca confiança e, como relatado, alunos muitas vezes não compreendem o código gerado pela IA. Esse cenário pode transformar o engenheiro em um mero "revisor" do trabalho da IA, em vez de um participante ativo no processo cognitivo de solução de problemas.
- **Qualidade dos datasets**: os modelos de IA foram treinados em datasets massivos que nem sempre foram curados para qualidade, contendo problemas e vieses que são replicados pela IA.
- **Avaliação dos modelos**: faltam benchmarks confiáveis e representativos, bem como avaliações quantitativas padronizadas, tornando difícil comparar a eficácia de diferentes modelos de IA.
- **Conhecimento de domínio**: ainda há dificuldades em explicar o contexto específico de uma tarefa de domínio para as LLMs.

## Discussão

O tema foi muito relevante e oportuno, dado o ritmo de inovações nesta área. O seminário permitiu que a discussão sobre temas complexos como a qualidade do software e o papel da IA se tornasse mais acessível. Um ponto marcante foi, como mencionado anteriormente, o elevado ritmo de pesquisas e soluções tecnológicas que estão sendo desenvolvidas nesta área. Houve total concordância sobre a dificuldade em acompanhar esta evolução. 

Com relação aos tópicos do seminário abordados em outros artigos, por exemplo, ao destacar o uso da IA para transcrição e classificação automática de requisitos (funcionais, não funcionais ou de desempenho), além da detecção de ambiguidades e inconsistências, vislumbra-se que, utilizando técnicas de Processamento de Linguagem Natural (PLN) e aprendizado de máquina, pode analisar grandes volumes de documentos, acelerando o processo e reduzindo a dependência de revisões manuais, que são propensas a erros humanos {cite:p}`cruz2025ia`. Na automação da codificação, sugestões para completá-lo, detecção de duplicidades, geração de código a partir de comentários, e explicação de código {cite:p}`meta2025ia`. Os artigos complementam essa visão, mostrando que ferramentas como GitHub Copilot e ChatGPT estão revolucionando a maneira como os desenvolvedores escrevem e otimizam códigos. O especialista em IA da Meta, Everton Lima Aleixo, explica que a IA não somente apoia, mas participa ativamente na criação de soluções, sugerindo trechos ou códigos completos {cite:p}`meta2025ia`. Contudo, a Profa. Lina, e os artigos, trouxeram um ponto crítico: o “retrabalho”. Ela mencionou que, muitas vezes, gasta-se mais tempo corrigindo o código gerado pela IA do que escrevendo-o do zero {cite:p}`garces2025impacto`, devido a vulnerabilidades e inconsistências {cite:p}`marinho2023seguranca`. Isso levanta a discussão sobre a precisão e a confiança no conteúdo gerado pela IA, sendo que 40% do código gerado pelo Copilot, por exemplo, pode apresentar vulnerabilidades, pois os modelos foram treinados com dados que já continham esses problemas {cite:p}`garces2025impacto`. A ideia de que a IA pode aprender a replicar erros é um alerta e isso reforça a necessidade de supervisão humana e revisão crítica, tratando o código da IA como um rascunho inicial. 

A palestra abordou a IA na geração de casos de teste, incluindo testes unitários, funcionais e até não funcionais. O artigo "The Role of Artificial Intelligence and Machine Learning in Software Testing" {cite:p}`ramadan2024role` é dedicado a este tema, reforçando que a IA e o Machine Learning (ML) impactaram significativamente os testes de software, tradicionalmente trabalhosos. As tecnologias de IA/ML aumentaram a eficiência e eficácia, automatizando tarefas como geração e execução de testes, e análise de resultados, podendo prever áreas potenciais de falha analisando dados históricos e identificando padrões, o que permite testes mais direcionados. Ferramentas como Eggplant AI, Test.ai, Selenium (com aprimoramentos de IA), Appvance, Applitools Eyes, Katalon Studio e Tricentis Tosca são exemplos práticos que demonstram melhorias na eficiência, precisão e qualidade geral do software  {cite:p}`ramadan2024role`. 

Um dos pontos mais ressonantes da palestra foi a discussão sobre os desafios e riscos éticos e legais da adoção da IA generativa.

- **Qualidade dos Dados e Propriedade Intelectual**: ela salientou que as IAs são treinadas com repositórios de código que podem conter vulnerabilidades e bugs, resultando em IAs que replicam esses problemas. Além disso, a questão da propriedade intelectual é crítica, pois muitos dados usados no treinamento de LLMs possuem direitos autorais, e a IA pode violar esses direitos ao gerar novo conteúdo sem citar as fontes. O relatório da Febraban {cite:p}`marinho2023seguranca` aprofunda esses riscos, incluindo a geração de código vulnerável, e o compartilhamento não intencional de informações confidenciais.
- **Interpretabilidade e Alucinações**: a falta de transparência ("caixas-pretas") nos modelos de IA é um desafio para entender como a IA chegou a certas decisões, gerando pouca confiança. As "alucinações" da IA, ou seja, a geração de informações falsas ou sem sentido, são um problema real que exige revisão humana {cite:p}`marinho2023seguranca`.
- **Vulnerabilidades em Aplicações de IA**: o relatório da Febraban {cite:p}`marinho2023seguranca` lista diversas vulnerabilidades em aplicações de LLMs, como *Prompt Injections* (injeção de comandos maliciosos), *Data Leakage* (vazamento de dados), *Inadequate Sandboxing* (ambiente isolado insuficiente), *Unauthorized Code Execution* (execução de código não autorizado), *Overreliance on LLM-generated Content* (confiança excessiva no conteúdo gerado pela LLM), *Inadequate AI Alignment* (falta de alinhamento ético da IA), *Insufficient Access Controls* (controles de acesso insuficientes), *Improper Error Handling* (tratamento inadequado de erros), e *Training Data Poisoning* (envenenamento de dados de treinamento), podendo levar à manipulação, roubo de dados, negação de serviço e outras atividades criminosas.

Em suma, a palestra, proporcionou uma visão clara de que a IA é uma força transformadora e inovadora na Engenharia de Software, trazendo inovações significativas em todas as fases do ciclo de desenvolvimento. No entanto, ela também introduz desafios complexos relacionados à qualidade, segurança, ética, custos e à necessidade de uma redefinição do papel do engenheiro de software. A professora Lina Garcés e a discussão ressaltam a necessidade de explorar as IAs para entender suas limitações e o ponto em que realmente auxiliam ou atrapalham. É um processo de aprendizado contínuo para toda a comunidade de Engenharia de Software, observando e tirando conclusões sobre as novidades que a IA Generativa está trazendo. 
