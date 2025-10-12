::: titlepage
::: center
**Chamada CNPq Nº 16/2025**

Faixa 1 -- Colaboração Internacional

**Fusão de Dados CSI e Imagens Térmicas Para Identiticação Confiável de
Atividades Humanas**
:::
:::

::: center
**Proposta de Projeto -- CNPq Chamada nº 16/2025**\
Faixa 1 -- Colaboração Internacional\
**Título do Projeto:** Seleção de Portadoras e Fusão de Dados CSI com
Imagens Térmicas Para Identiticação Confiável de Atividades Humanas\
**Coordenador:** Prof. Dr. Cledson de Sousa -- Universidade Federal
Fluminense (UFF)\
**Instituição Parceira no Exterior:** Brunel University of London --
Prof.: George Ghinea\
:::

# Resumo

O cenário pós-COVID-19 evidenciou a urgência de soluções eficazes e de
baixo custo para o monitoramento remoto de pacientes, especialmente
idosos e portadores de doenças infectocontagiosas, que necessitam de
acompanhamento contínuo sem exposição a ambientes hospitalares. O
barateamento de dispositivos sem fio e a ubiquidade das redes Wi-Fi,
particularmente aquelas capazes de disponibilizar a Informação do Estado
do Canal (CSI), que descreve, com alta resolução, como o sinal
eletromagnético é afetado pelo ambiente em cada subportadora Orthogonal
Frequency Division Multiplexing (OFDM). Tal tecnologia abre caminho para
sistemas capazes de inferir movimentos e atividades humanas a partir de
variações no campo eletromagnético causadas pela presença e deslocamento
de pessoas [@sousa2024subcarrier; @soto2023single; @galdino2023ehealth].
Esse avanço ampliou as possibilidades de monitoramento ambiental
acessível e não intrusivo. Nesse contexto, cresce o interesse por
tecnologias que conciliem eficiência, privacidade e baixo custo,
eliminando a necessidade de câmeras ou sensores corporais.

A Identificação de Atividades Humanas (HAR) surge como elemento central
em aplicações de saúde [@allan2025TransformerCSI], segurança e automação
residencial [@bouchabou2021survey], viabilizando desde o acompanhamento
clínico remoto até a detecção precoce de quedas e comportamentos
anômalos. Contudo, persistem desafios técnicos relevantes. Abordagens
visuais, embora precisas, comprometem a privacidade e são vulneráveis a
oclusões e variações de iluminação. Já as soluções baseadas
exclusivamente em CSI, obtido a partir de sinais Wi-Fi ubíquos e pontos
de acesso de baixo custo, preservam a privacidade e dispensam sensores
vestíveis, mas ainda carecem de maior precisão e robustez em ambientes
reais e dinâmicos.

O objetivo principal deste projeto é contribuir com o estado da arte no
sentido de indicar soluções para as limitações de cada modalidade
individual, propondo e validando uma arquitetura inovadora de fusão de
dados CSI e imagens térmicas. A combinação da robustez do CSI frente a
oclusões físicas com a resiliência das imagens térmicas a variações de
iluminação, decorrente da detecção do calor corporal, resultará em um
sistema HAR mais confiável, preciso e aplicável a ambientes reais. Este
projeto também dá continuidade ao trabalho iniciado em
[@sousa2024subcarrier], aprofundando a análise da seletividade espectral
e da complementaridade entre subportadoras, agora estendida ao domínio
multimodal.

A metodologia central se concentra no desenvolvimento de um framework de
Deep Learning para lidar com a alta dimensionalidade inerente aos dados
brutos e ao volume de amostras CSI e de imagens térmicas. Serão
investigadas técnicas de redução de dimensionalidade e seleção de
features, com o objetivo de otimizar a representação dos dados
multimodais e, consequentemente, reduzir o custo computacional e de
inferência. Esse esforço permitirá a implementação do sistema HAR em
plataformas de borda de rede (*edge computing*), tornando-o viável para
implantação em ambientes residenciais e clínicos.. A expertise em fusão
multissensorial da parceria internacional será crucial para o
desenvolvimento de arquiteturas de Redes Neurais Profundas (DNNs)
capazes de extrair e combinar essas características de forma
inteligente.

Este projeto também propõe uma contribuição incremental ao dataset
eHealth [@galdino2023ehealth], ampliando-o com novos cenários
experimentais e métricas derivadas. Além disso, visa o desenvolvimento
de modelos de última geração para sensoriamento sem fio e a divulgação
dos resultados em periódicos de alto impacto. A colaboração
internacional prevista é estratégica para o intercâmbio de conhecimento
e o fortalecimento da capacidade científica e tecnológica nacional,
consolidando uma rede de pesquisa em sensoriamento de baixo custo e
monitoramento não intrusivo.

# Justificativa e Relevância

O presente projeto de pesquisa se situa na confluência de duas das mais
promissoras áreas da Engenharia de Telecomunicações e Computação
modernas: o sensoriamento baseado em Sinais de Rádio (CSI/sensoriamento
sem fio), Visão Computacional e o Aprendizado de Máquinas. A proposta
não apenas aborda uma demanda tecnológica premente, mas também promove a
necessária cooperação científica internacional para superar desafios
complexos.

#### Contextualização do Tema dentro da Linha de Pesquisa:

\
Além das motivações de saúde e segurança já mencionadas no Resumo, a
Identificação de Atividades Humanas constitui um elemento central para a
evolução da Internet das Coisas (IoT) e de sistemas de monitoramento
inteligentes. Serve como o pilar para aplicações cruciais em saúde 4.0
(monitoramento de idosos) e segurança. No campo das Telecomunicações, o
CSI obtido de APs de baixo custo, oferece sensoriamento não invasivo e
preserva a privacidade, sendo robusto a oclusões. No entanto, sua
precisão sofre com variações de *multipath* e ruído em ambientes
dinâmicos.

A Imagem Térmica oriunda de dispositivos de baixo custo
[@flir-van2019validation] é complementar, fornecendo dados visuais
resistentes à variação luminosa. O projeto move a linha de pesquisa de
métodos unimodais para uma abordagem multimodal adaptativa, focada na
fusão sinérgica de CSI e Imagens Térmicas. Este avanço metodológico visa
criar um sistema HAR não só preciso, mas também robusto e com baixo
custo de implementação, essencial para a adoção em larga escala.

#### Lacunas Científicas e Tecnológicas que a Colaboração Internacional Visa Superar:

\
A lacuna científica que este projeto busca preencher situa-se na
ausência de uma abordagem integrada que opere desde as camadas físicas
(Camada 1), explorando de forma articulada a seleção espectral de
subportadoras, a fusão de dados multimodais e o uso combinado de
sensores híbridos CSI e térmicos. Até o momento, a fusão otimizada entre
dados de rádio (CSI) e dados térmicos permanece um campo em aberto, com
poucas abordagens que explorem de forma sistemática a complementaridade
entre informações sensíveis à movimentação, às oclusões e aquelas
robustas variações de iluminação e do canal físico propriamente dito. O
projeto também prevê a extensão do dataset eHealth [@galdino2023ehealth]
com novas coletas CSI--térmicas, contribuindo para o aumento de uma base
experimental aberta e padronizada.

A cooperação com o grupo de pesquisa da Brunel University London é
estratégica para mitigar essa lacuna. A reconhecida atuação do grupo em
*Mulsemedia Computing* e Experiência de Qualidade (QoE) permitirá
integrar, de forma coerente, informações de diferentes modalidades
(rádio e imagem), garantindo que o sistema HAR resultante seja avaliado
não apenas por acurácia, mas também por estabilidade, responsividade e
usabilidade em tempo real. Além disso, a experiência do grupo em
processamento avançado de sinais, incluindo filtros distribuídos e
análise de sistemas tempo-variantes como o CSI, será essencial para o
desenvolvimento de etapas robustas de pré-processamento e filtragem,
reduzindo ruído e erros de fase. Essa colaboração consolida a base
técnica e científica necessária para a construção de um *framework*
multimodal de próxima geração, unindo rigor metodológico e
aplicabilidade prática.

#### Alinhamento com as Metas do CNPq e as Prioridades Estratégicas do Edital:

\
Este projeto entre outras ações, busca fomentar a colaboração
internacional de pesquisas que visem contribuir para o desenvolvimento
científico, tecnológico e a inovação do país.

-   **Internacionalização e Formação:** a proposta fortalece a
    cooperação técnico-científica e promove a inserção de alunos e
    pesquisadores brasileiros em ambientes de pesquisa de excelência. A
    parceria com o grupo de pesquisa da Brunel University London
    possibilitará o intercâmbio de conhecimento em *multimodal sensing*
    e *deep learning*, contribuindo para a formação avançada de recursos
    humanos e a consolidação de uma rede ativa de cooperação entre
    Brasil e Europa.

-   **Excelência Científica e Inovação:** o desenvolvimento de um novo
    *dataset* público CSI--Térmico e de um *framework* multimodal de
    *Deep Learning* representa uma contribuição científica e tecnológica
    relevante, ampliando a visibilidade internacional das instituições
    envolvidas. O projeto integra a produção de conhecimento de
    fronteira com aplicações práticas em monitoramento remoto, detecção
    de quedas e segurança de ambientes, respondendo a desafios
    contemporâneos de saúde e envelhecimento populacional.

-   **Sustentabilidade e Impacto:** a consolidação desta rede
    internacional de pesquisa favorece a continuidade e expansão da
    cooperação científica, estimulando a captação de novos recursos e o
    fortalecimento da infraestrutura nacional em sensoriamento sem fio e
    sistemas inteligentes. O intercâmbio de metodologias e a aplicação
    conjunta de técnicas de processamento de sinais e fusão
    multissensorial asseguram a transferência efetiva de tecnologia e o
    desenvolvimento sustentável da linha de pesquisa no Brasil.

#### Produções anteriores e colaboração pré-existente:

\
O proponente possui trajetória consolidada na pesquisa com séries
temporais CSI aplicadas à inferência de atividades humanas indoor, com
foco nos níveis mais baixos da pilha de protocolos, notadamente camada
física e de enlace. Sua atuação concentra-se em temas como seleção de
subportadoras, correlação espectral e redução de dimensionalidade para
treinamento com Aprendizado de Máquina (ML). Essa vertente técnica,
voltada à análise estrutural e espectral do sinal, vem sendo
desenvolvida no âmbito da UFF de forma independente, em parceria com
alunos de iniciação científica e pós-graduação, e já resultou em
publicações indexadas, datasets anotados e apresentações em eventos
nacionais e internacionais. Destaca-se, nesse escopo, a produção recente
que aprofunda os fundamentos da seleção espectral
[@sousa2024subcarrier], sem participação da Brunel University London.

Em linha paralela e complementar, desde 2023 o proponente atua em
colaboração com a Brunel University London, sob liderança do Professor
George Ghinea, e com outros pesquisadores do Laboratório Mídiacom (UFF),
em iniciativas voltadas à aplicação de metodologias de aprendizado de
máquina e à integração de sensores híbridos multissensoriais
(mulsemídia). Essa frente colaborativa foca na modelagem de soluções
assistivas baseadas em redes neurais, visão computacional e
interpretabilidade de modelos, e já resultou em publicações conjuntas
[@allan2025TransformerCSI; @allan2025metodologia; @allan2024computer].

A presente proposta apoia-se, portanto, na convergência dessas duas
frentes já consolidadas: uma alicerçada na análise espectral e
estruturada do sinal (UFF), e outra na modelagem aplicada e multimodal
(UFF-Brunel), refletindo tanto a produção autônoma do proponente quanto
os avanços obtidos por meio da cooperação internacional.

# Objetivos Gerais e Específicos

Propor, desenvolver e validar uma arquitetura de *Deep Fusion* de alto
desempenho e baixo custo, baseada na fusão otimizada de CSI e Imagens
Térmicas, com o propósito de estabelecer um sistema de Identificação de
Atividades Humanas robusto e eficiente para aplicações de monitoramento
não intrusivo em cenários reais de saúde e segurança.

## Objetivos Específicos {#objetivos-específicos .unnumbered}

1.  *Setup* Multimodal e Aquisição: projetar e implementar o setup
    experimental multimodal utilizando dispositivos IEEE 802.11\*,
    estabelecendo o protocolo de coleta e calibração conjunta de dados
    brutos CSI e imagens térmicas, com sincronização precisa. Em
    seguida, realizar medições experimentais com os dispositivos *IEEE
    802.11* e sensores térmicos, garantindo sincronização precisa e
    coleta consistente de dados multimodais, incluindo a análise de
    correlações espectrais, estabilidade, ruído e variabilidade do CSI
    no ambiente de coleta.

2.  Pré-processamento e Otimização do CSI (Com Foco na Parceria):
    desenvolver técnicas avançadas de mitigação de ruído e
    interferências e implementar a seleção de subportadoras relevantes
    para o CSI. Esta etapa de otimização espectral e redução de
    dimensionalidade será realizada em estreita colaboração com o grupo
    de pesquisa da Brunel University.

3.  Arquitetura de Fusão Profunda: projetar e treinar Redes Neurais
    Profundas (DNNs) para extrair características complementares das
    duas modalidades e desenvolver um *framework* de fusão inteligente
    que maximize a acurácia, a estabilidade e a responsividade do
    sistema HAR.

4.  Validação de Robustez e Comparação: Validar o desempenho das
    soluções propostas em experimentos reais (cenários controlados e de
    campo), comparando o sistema de fusão com abordagens unimodais da
    literatura para demonstrar a superioridade e a redução do custo
    computacional.

5.  Disseminação e Formação de RH: Disseminar os resultados por meio de
    publicações conjuntas em periódicos de alto impacto e promover a
    formação de recursos humanos nas áreas de fusão multissensorial,
    aprendizado de máquina e processamento de sinais, capacitando a
    equipe brasileira com o know-how internacional.

# Plano de Trabalho e Metodologia

O plano de trabalho está estruturado em quatro Pacotes de Trabalho
(*Work Packages* -- WP1 a WP4), organizados ao longo de 24 meses. A
metodologia contempla desde a coleta e calibração conjunta de dados
térmicos e CSI, até a modelagem estatística e treinamento de modelos
multimodais para inferência de atividades humanas em ambientes indoor.
As ações previstas incluem etapas experimentais, computacionais e
colaborativas, conforme descrito a seguir.

## WP1 -- Coleta de Dados e Infraestrutura (meses 1 a 6) {#wp1-coleta-de-dados-e-infraestrutura-meses-1-a-6 .unnumbered}

-   Delineamento dos cenários experimentais *indoor*, contemplando
    diferentes atividades humanas;

-   Instrumentação do ambiente com dispositivos wi-fi modificados para
    extração de CSI e câmeras térmicas radiométricas;

-   Elaboração de protocolo de sincronização e rotulagem cruzada para
    coleta paralela de dados CSI e térmicos, com mapeamento temporal e
    espacial das atividades;

-   Submissão do protocolo ao Comitê Nacional de Ética em Pesquisa e
    obtenção da devida autorização para realização dos experimentos com
    voluntários;

-   Realização de sessões de coleta com diversidade temporal e espacial;

-   Anonimização dos dados e armazenamento seguro em repositório
    institucional versionado, com controle de integridade e acesso
    restrito.

.

## WP2 -- Pré-processamento e Modelagem Bayesiana (meses 4 a 12) {#wp2-pré-processamento-e-modelagem-bayesiana-meses-4-a-12 .unnumbered}

-   Implementação de filtros de suavização, compensação de fase e
    remoção de anomalias em ambos os domínios (CSI e térmico);

-   Seleção de subportadoras relevantes com base em métricas
    estatísticas como entropia, informação mútua e energia espectral;

-   Desenvolvimento de modelos probabilísticos para inferência *a
    posteriori* via Teorema de Bayes, considerando evidências
    independentes $E_1 =$ CSI e $E_2 =$ Imagem Térmica;

-   Avaliação da consistência dos classificadores isolados e dos ganhos
    obtidos com a fusão de evidências.

## WP3 -- Aprendizado Profundo e Arquitetura Multimodal (meses 7 a 18) {#wp3-aprendizado-profundo-e-arquitetura-multimodal-meses-7-a-18 .unnumbered}

-   Treinamento de redes neurais convolucionais (CNNs) específicas para
    cada domínio;

-   Exploração de arquiteturas multimodais do tipo *early fusion*, *late
    fusion* e *dual-head*, com e sem atenção cruzada;

-   Construção de curvas de calibração (reliability diagrams) para
    aferir a confiança das inferências;

-   Validação cruzada com diferentes estratégias de generalização (por
    pessoa, posição e subportadora).

## WP4 -- Validação, Disseminação e Cooperação (meses 13 a 24) {#wp4-validação-disseminação-e-cooperação-meses-13-a-24 .unnumbered}

-   Consolidação dos resultados em um protótipo funcional de inferência
    híbrida CSI--térmica, com potencial de aplicação em ambientes
    clínicos e domésticos;

-   Realização de reuniões mensais e workshops técnicos com o grupo
    parceiro no exterior, além de missões presenciais de curta duração
    para alinhamento metodológico, avaliação conjunta e produção
    científica colaborativa;

-   Redação de artigos científicos para conferências e periódicos
    internacionais de alto impacto, com priorização do modelo de acesso
    aberto;

-   Liberação pública e documentada de um novo dataset CSI--térmico
    anotado, promovendo transparência e reprodutibilidade, conforme
    diretrizes do CNPq para ciência aberta;

-   Participação em ações estruturadas de divulgação científica voltadas
    a públicos não especializados, com foco em acessibilidade, impacto
    social e alinhamento ao Plano de Divulgação Científica da Chamada.
    As atividades incluirão:

    -   Apresentações públicas em eventos como semanas científicas,
        mostras acadêmicas e feiras de ciências, voltadas a estudantes e
        professores da educação básica;

    -   Elaboração de materiais acessíveis, infográficos, cartilhas e
        conteúdos digitais para redes sociais institucionais;

    -   Participação em eventos de popularização da ciência promovidos
        por universidades, museus e centros de ciências parceiros;

    -   Estímulo à participação de estudantes do ensino médio em
        projetos integradores ou atividades extracurriculares vinculadas
        ao tema da pesquisa.

## Indicadores de Resultado Esperados {#indicadores-de-resultado-esperados .unnumbered}

Os seguintes indicadores serão utilizados para monitoramento da execução
e avaliação dos resultados do projeto, conforme diretrizes do CNPq:

-   Artigos publicados em periódicos qualificados e apresentações em
    eventos internacionais;

-   Formação de recursos humanos: alunos de graduação e pós-graduação
    envolvidos diretamente no projeto;

-   Aumento de coautorias com o parceiro internacional e missões
    técnicas realizadas;

-   Participação em semanas científicas, feiras de ciências e outras
    ações de divulgação científica para o público não especializado;

-   Liberação de um dataset CSI--térmico anotado, em acesso aberto, com
    potencial de reutilização por outras equipes de pesquisa;

# Cronograma de Execução

::: center
   **Período (mês)**  **Atividade Principal**                      **Produto Esperado**
  ------------------- -------------------------------------------- ----------------------------------
         0--3         Planejamento e revisão bibliográfica         Protocolo de coleta CSI--IR
         4--6         Desenvolvimento de ferramentas de captura    Protótipo CSI_View v1.0
         7--12        Fusão bayesiana e modelagem CNN multimodal   Relatório técnico e publicação 1
        13--18        Testes clínicos e validação                  Protótipo CSI_BPM/CSI_RPM
        19--24        Integração e disseminação dos resultados     Artigos e relatório final
:::

# Resultados Esperados

Os seguintes indicadores serão utilizados para monitoramento da execução
e avaliação dos resultados do projeto, conforme diretrizes do CNPq:

-   Artigos publicados em periódicos qualificados e apresentações em
    eventos internacionais;

-   Formação de recursos humanos: alunos de graduação e pós-graduação
    envolvidos diretamente no projeto;

-   Engajamento de novos doutores e doutorandos em pesquisas
    internacionais, promovendo novas lideranças científicas;

-   Aumento de coautorias com o parceiro internacional e missões
    técnicas realizadas;

-   Participação em semanas científicas, feiras de ciências e outras
    ações de divulgação científica para o público não especializado;

-   Liberação de um dataset CSI--térmico anotado, em acesso aberto, com
    potencial de reutilização por outras equipes de pesquisa;

# Equipe Envolvida

**Brasil:** Prof. Cledson Oliveira de Sousa (coordenador), Prof. Célio
Albuquerque, Prof. Ricardo Carrano, alunos de graduação e
pós-graduação.\
**Exterior:** Prof.: George Ghinea - Especialista em multisensoriamento - Brunel University of London 

# Orçamento e Fontes de Financiamento

O orçamento solicitado ao CNPq contempla exclusivamente itens
financiáveis conforme a Chamada nº 16/2025 -- Faixa 1, com ênfase em
mobilidade internacional e colaboração técnico-científica entre as
instituições parceiras. Estão previstas quatro missões técnicas ao
exterior (Reino Unido), com duração de sete dias cada, realizadas por
dois membros da equipe. Os objetivos de cada missão estão detalhados na
Tabela [1](#tab:missoes){reference-type="ref" reference="tab:missoes"}.
Enquanto a Tabela [2](#tab:orcamento){reference-type="ref"
reference="tab:orcamento"} apresenta o resumo financeiro das despesas
solicitadas, que se restringem a passagens, diárias e seguro-saúde
internacional.

**Tabela 1 – Missões internacionais previstas**

| Missão | Período          | Objetivo principal |
|:------:|:----------------:|--------------------|
| M1 |  Mês 3–4             | Estabelecimento de métodos de calibração cruzada dos sensores CSI–térmicos, com acompanhamento do parceiro internacional. |
| M2 | Mês 8–9              | Implementação conjunta de modelos multimodais e análise de desempenho cruzado. |
| M3 | Mês 14–15            | Validação em ambiente real e ajuste fino do protótipo para publicação conjunta. |
| M4 | Mês 20–21            | Finalização de artigos, preparação de submissões futuras e planejamento de continuidade. |
    

**Tabela 2 – Resumo do orçamento solicitado ao CNPq (Faixa 1)**

| Item | Qtd. | Valor unitário (R$) | Total (R$) |
|:--------------------------------|:----:|:----------------------:|:-------------:|
| Passagens aéreas internacionais | 8 | 8.000,00 | 64.000,00 |
| Diárias internacionais (7 dias/pessoa) | 56 | 1.200,00 | 67.200,00 |
| Seguro-saúde internacional | 8 | 500,00 | 4.000,00 |
| **Total estimado** | — | — | **135.200,00** |


Equipamentos (como câmeras térmicas, roteadores CSI e servidores GPU),
bolsas de doutorado sanduíche e de iniciação científica, bem como
infraestrutura física e suporte técnico, serão providos como
contrapartida institucional da Universidade Federal Fluminense e de
parcerias nacionais vigentes.

Embora esta proposta não envolva contrapartida financeira formal por
parte da instituição estrangeira, a Brunel University London
compromete-se com a cessão de espaço físico para atividades conjuntas,
liberação parcial de carga horária do pesquisador estrangeiro e acesso a
infraestrutura laboratorial e outros recursos científicos não
financeiros.

A consolidação desta cooperação bilateral visa não apenas alcançar os
objetivos científicos do projeto, mas também garantir sua continuidade e
ampliação institucional. A médio e longo prazo, a parceria pretende
fortalecer a atuação dos grupos proponentes em chamadas internacionais,
como o *Going Global Partnerships* (British Council), o *INTPART --
International Partnerships for Excellent Education and Research*
(Noruega) e o *Horizon Europe*. Esses desdobramentos ampliam o impacto
técnico-científico da colaboração e asseguram sua sustentabilidade.

Os principais impactos esperados incluem:

-   Reforço às políticas de internacionalização da UFF e aos programas
    de pós-graduação envolvidos (PPGEET e PPGC);

-   Contribuição direta aos Objetivos de Desenvolvimento Sustentável
    (ODS 3 -- Saúde e bem-estar, ODS 9 -- Indústria, inovação e
    infraestrutura, ODS 11 -- Cidades e comunidades sustentáveis, e ODS
    17 -- Parcerias e meios de implementação);

-   Continuidade da colaboração científica com grupos europeus mesmo
    após o encerramento formal do projeto, visando novas submissões
    conjuntas a editais internacionais.

# Conclusão

O presente projeto consolida e estende uma cooperação científica madura
entre a Universidade Federal Fluminense e a Brunel University London,
unindo competências complementares em sensoriamento sem fio, aprendizado
de máquina e fusão multimodal. A proposta apresenta forte potencial de
impacto científico e tecnológico, com resultados esperados de alta
relevância, desde o desenvolvimento de um *framework* de fusão
CSI-térmica até a disponibilização de um *dataset* público padronizado,
contribuindo para a ciência aberta e a internacionalização da pesquisa
brasileira.

A iniciativa está formalmente respaldada por carta de apoio da Brunel
University London, que confirma o compromisso institucional e o
interesse mútuo na execução e expansão desta parceria. Tal colaboração
reforça o papel da UFF como polo de excelência em sensoriamento
inteligente e consolida as bases para submissões futuras a chamadas
internacionais, ampliando o alcance e a sustentabilidade das ações
científicas aqui propostas.
