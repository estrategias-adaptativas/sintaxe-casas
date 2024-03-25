---
title: "Caracterização das tipologias de casas tradicionais luso-brasileiras por meio da integração visual[^1]"
authors:
  - "Pedro P. Palazzo"
  - "Eduarda Toscano de Carvalho"
bibliography: _data/biblio.yaml
csl: _data/elsevier-harvard.csl
reference-section-title: "Referências"
lang: pt-BR
figureTitle: "Figura"
abstract: | # 200 palavras
  ***Resumo.***
  Este trabalho analisa as diferenças morfológicas na arquitetura
  tradicional urbana luso-brasileira entre as tipologias de casas
  correntes e de casas senhoriais, no período que vai da metade do
  século XVIII até o início do século XX. O recorte privilegia o
  universo mais uniforme e conservador dos estados do Rio de Janeiro,
  Goiás (incluindo Tocantins) e Minas Gerais. O estudo identifica
  características estruturantes de cada uma das duas séries
  morfológicas. Enquanto a maioria dos estudos anteriores se concentra
  na análise de grafos para avaliar as conexões topológicas entre
  ambientes individuais, esta pesquisa adota a análise de integração
  visual, que enfatiza os centros morfológicos dos espaços. Os
  resultados evidenciam como a análise de integração visual confirma a
  congruência entre a composição espacial das casas correntes e
  senhoriais e os atributos da vida social próprios a cada uma dessas
  tipologias. Tais atributos são a localização do convívio familiar nos
  fundos da casa corrente e, em contraste, a primazia dos espaços de
  recepção e representação na parte dianteira das casas senhoriais.

  ***Palavras-chave.***
  Arquitetura domética, Intervisibilidade, Tipologia, Brasil,
  Séculos XVIII e XIX.

keywords: ["Arquitetura doméstica", "Profundidade visual", "Tipologia", "Brasil", "Séculos XVIII e XIX"]
thanks: >
  Esta pesquisa foi fomentada com uma bolsa de iniciação científica do
  Conselho Nacional para o Desenvolvimento Científico e Tecnológico
  (CNPq) no período 2021-2022.
---

<!--8.000 palavras-->

# Characterizing traditional Brazilian house typologies by means of intervisibility analysis # {-}

:::::::::::::::::::::::::::::::::::::::::::::: {custom-style="Abstract"}
***Abstract.*** This paper analyzes the morphological differences in
traditional urban architecture in Brazil between the typologies of
rowhouses and urban or suburban mansions, from the mid-eighteenth to the
early twentieth century. It focuses on the relatively uniform and
conservative context of the states of Rio de Janeiro, Goiás (including
Tocantins), and Minas Gerais. This study highlights defining
characteristics of each of the two typological series. While most
previous studies have looked at tree graph analysis to assess the
topological connections between individual spaces, this research turns
to intervisibility analysis, evidencing the morphological centers of
compositions. The results highlight how visual integration analysis
confirms the overlap between the spatial composition of both rowhouses
and mansions and the attributes of social life specific to each of these
typologies. These attributes include the location of the family room in
the rear of rowhouses and, in contrast, the primacy of ceremonial spaces
in the front of mansions.

***Keywords:*** Domestic architecture, visual depth,
typology, Brazil, 18th and 19th centuries
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

# Introdução #

O universo das casas correntes tradicionais no Brasil é reconhecidamente
marcado pela uniformidade tipológica, dominada pelo paradigma da « casa
de morada » composta por células de pequenas dimensões, com distribuição
longitudinal por meio de um corredor. Esse universo coexiste e se
hibridiza com a tipologia da casa senhorial urbana
([@fig:real-fazenda]), menos popular na historiografia do que a sua
congênere rural. A análise de integração visual de um conjunto de casas
urbanas do século XVIII até o início do XX no estado do Rio de Janeiro,
Goiás (incluindo Tocantins) e Minas Gerais permite observar as variações
morfológicas entre essas duas tipologias.

![Casas correntes dos séculos XVIII, XIX e XX na cidade de Goiás. Foto do autor, 2007](media/br-go-goias-ladeira_chafariz-070101-pp-0224-full.jpg){#fig:casario}

Por volta da metade do século XVIII, a cultura construtiva em Portugal e
no seu império ultramarino realiza um processo simultâneo de
consolidação das suas tradições de origem medieval e de renovação,
identificada por @pinto:2016regulacao, nas suas práticas tecnológicas e
nos seus paradigmas normativos. Tal movimento resulta a partir de então
numa relativa estabilidade de uma tradição luso-brasileira, sobretudo no
âmbito da edilícia de base urbana ([@fig:casario]). Ultrapassando a
Independência, essa tradição persiste em ambas as margens do Atlântico
ao menos até a difusão de ideologias sanitaristas e da cultura doméstica
burguesa no contexto republicano do início do século XX, e mais além em
regiões isoladas como o interior do estado de Goiás.

![Real fazenda, Goiás, meados do século XVIII: exemplar de casa senhorial urbana. Foto do autor, 2007](media/br-go-goias-real_fazenda-070101-pp-0216-full.jpg){#fig:real-fazenda}

O presente artigo analisa a morfologia do andar nobre de moradas urbanas no recorte
cronológico dessa tradição luso-brasileira, confrontando entre si as
configurações de casas correntes e moradas senhoriais. O instrumental
usado para tal comparação é a análise de visibilidade
(intervisibilidade) pertencente à caixa de ferramentas da sintaxe
espacial e produzida pelo programa de código aberto depthmapX criado por
@varoudis:2020depthmapx. A aplicação da sintaxe espacial na arquitetura
doméstica tradicional no Brasil é um campo em expansão, baseado em
grande parte na análise de grafos justificados, indicando a profundidade
de conexões topológicas entre ambientes unitários. Essa estratégia foi
aplicada inicialmente por @trigueiro:2012sobrados e continua a ser amplamente
adotada, por exemplo, por @umbelino:2016casa e @oliveira:2021escravidao,
onde permite identificar os padrões de circulação em árvore dentro das
casas. Na investigação de Trigueiro, a profundidade topológica permitiu
evidenciar diferenças na organização espacial entre tipos de plantas
visualmente semelhantes.

Em contraste, a integração visual enfatiza o chamado centro
morfológico dos espaços, aqueles mais visíveis e acessíveis a partir de
todo o restante da edificação, representados no gráfico em cores
quentes ([@fig:intervisibilidade]). Exemplos do método da integração
visual podem ser encontrados também no estudo de @umbelino:2016casa,
assim como no de Santana, Garcia e Gurgel [-@santana:2022nada10].
Este último, em particular,
demonstra como a integração visual permite realçar semelhanças na
hierarquia espacial de casas à primeira vista muito díspares.
Aprofundando as explorações preliminares de tais trabalhos, esta
comunicação apresenta a análise de integração visual comparada de várias
edificações privadas urbanas no Brasil, datadas de meados do século
XVIII até o início do século XX.

![Gráfico de intervisibilidade da casa do patrimônio de Paraty, 1750. Desenho da autora](media/br-rj-paraty-1750-escritorio_tecnico_do_iphan-casa_do_patrimonio_em_paraty-half.png){#fig:intervisibilidade}


# Contexto histórico--tipológico #

## Casas correntes ##

A tipologia da arquitetura doméstica urbana portuguesa divergiu da
matriz mediterrânea com o reparcelamento das casas-pátio antigas em
casas correntes durante a Idade Média. Usando a terminologia cunhada por
@westfall:1991building, o tipo portante em grande parte dos tecidos
urbanos ibéricos deixou de ser a *regia* e passou a ser a *domus.*
Adotando a conceituação de @caniggia:1997analisi, a tipologia
mediterrânea das casas-pátio --- e especialmente o tipo islamizado dos
quarteirões profundos acessíveis por meio de adarves --- foi reduzida a
um substrato do parcelamento do solo. Sobre este substrato islamizado, a
reforma administrativa e a reorganização demográfica dos reinos cristãos
impuseram, como mostrado por @navarro:2001urbanismo, um reparcelamento
desses quarteirões em lotes de casas correntes, estreitos e profundos,
modulados pelo substrato das casas-pátio preexistentes. Esse tipo de
lote é convencionalmente designado em Portugal como « lote gótico ».

:::::::::::::::::::::::::::::::::::::::::::::::::: {#fig:building-types}
![domus](media/building-types-domus.png){#fig:building-types-domus}
![regia](media/building-types-regia.png){#fig:building-types-regia}

Diagramas ideais dos tipos edilícios segundo C. William Westfall, 1991.
Desenho do autor
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Não obstante as implicações historicamente discutíveis de tal
nomenclatura apontadas por @trindade:2013urbanismo, tanto a alusão aos
godos quanto a morfologia desse paradigma urbanístico remetem à sua
origem nos reinos germânicos do Noroeste da Europa --- Inglaterra, onde
foi extensamente analisado por @conzen:2022alnwick, França e, mais a
propósito da primeira dinastia portuguesa, Borgonha. O que importa notar
é que, contrariamente à diversidade irredutível e aborígene das
tradições rurais portuguesas identificadas pelo inquérito à *Arquitetura popular em Portugal*
[-@arquitectura:1961], a tipologia das casas correntes tardomedievais na
península Ibérica decorre de um processo intencionalmente uniformizador
e xenofílico. A uniformidade da série tipológica das casas correntes
europeias é demonstrada no catálogo de plantas de habitações « para
todas as qualidades de homens », desenhado por @serlio:1547sesto para um
público francês, mas igualmente representativo das casas
luso-brasileiras.

No entanto, as casas correntes luso-brasileiras não são apenas uma
adaptação de modelos vindos do norte. Uma vez adotada em Portugal, essa
série tipológica se materializa por meio de dimensões modulares
caracteristicamente locais. Essas dimensões se baseiam em células
espaciais de pequenas dimensões (3,5 a 5,5 metros) conformando o que
@costa:2015moradas [13] denomina « moradas de casas ». A derivação do
processo tipológico da casa corrente dá-se então pelo desdobramento,
primeiro em profundidade e depois em largura, desse aglomerado de
células.

## Casas senhoriais ##

Ao mesmo tempo que se consolida a tipologia da casa corrente
luso-brasileira na Idade Moderna, as classes altas introduzem nos
tecidos urbanos uma série tipológica de moradas de origem rural,
conhecidas em Portugal como « casas nobres » e no Brasil como « casas
senhoriais » ou « solares » (este último termo reservado, em Portugal,
para moradas rurais). Ao contrário das moradas de casas que dão origem
às casas correntes, formadas essencialmente por células de pequenas
dimensões, a tipologia aristocrática se estrutura em torno de um ou mais
salões de grandes dimensões.

Para além dos salões, a característica mais saliente da série tipológica
das casas senhoriais consiste na relação interior--exterior, com clara
distinção entre espaço aberto público e espaço aberto privado, como
elemento estruturante da composição. Tal relação é amiúde materializada
por meio de um pátio, seja ele inteiramente encerrado na construção ou
delimitado por três alas edificadas em forma de U e aberto para o
quintal --- nunca um pátio dianteiro à maneira francesa. Com isso, a
casa senhorial se vincula ao tipo ideal da *regia*, sendo irredutível
tipologicamente à série da casa corrente, uma vez que esta é instância
da *domus* [@westfall:1991building].

O pátio da casa senhorial, porém, não tem semelhança morfológica com o
das casas mediterrâneas antigas e islamizadas. Isto porque o pátio
vernacular mediterrâneo é, entre outros atributos, um elemento da
*promenade architecturale* na casa, conduzindo até o salão principal da
morada. O pátio senhorial, ao contrário, se vincula ao tipo do *palazzo*
medieval e renascentista. Neste tipo, o percurso social e público se
situa *entre* a rua e o pátio, e não *através* do pátio.

Por isso mesmo, há exemplares que se podem classificar como casas
senhoriais, mesmo sendo totalmente desprovidos de pátio. Nesses casos, é
o partido volumétrico mais largo do que profundo o que marca,
inequivocamente, a oposição entre espaço aberto dianteiro e espaço
aberto de fundos enquanto cerne da caracterização morfológica dessa
série. Nesse caso, a morada se conforma, por assim dizer, como se toda
ela fosse o bloco dianteiro de um *palazzo* com pátio do qual foram
eliminadas as alas laterais e a de fundos.

## Periodização e regionalização ##

A história da morada urbana luso-brasileira tem, atualmente, uma
narrativa consolidada a partir de décadas de estudos generalistas, desde
os primeiros ensaios interpretativos por @freyre:1951sobrados até as
sínteses canônicas por @lemos:1996historia e @reis:1969lote no terceiro
quartel do século XX. Esta narrativa toma como ponto de partida a
correspondência direta entre o sistema escravista e a configuração
espacial da casa corrente luso-brasileira, tida como dependente da
servidão doméstica para os mínimos confortos [@reis:1983quadro, 29].

Essa narrativa ressalta, por exemplo, o contraste entre a renovação
estética das fachadas sob o classicismo imperial do século XIX
[nomenclatura proposta por @sousa:1994arquitetura, 25] e a persistência
de distribuições tradicionais até o final da monarquia. Segundo
@maestri:2001sobrado, o conservadorismo das plantas de casas
correntes evidencia uma relativa uniformidade do modelo escravista
urbano no espaço e no tempo. Caberia então à República, na esteira da
abolição da escravatura e da introdução do discurso sanitarista,
promover mudanças significativas na distribuição espacial da moradia,
muitas vezes, como mostrou @lemos:1999republica, por meio de imposições
normativas.

Pesquisas mais especializadas têm relativizado esse panorama de
uniformidade e especificidade da morada urbana de dois modos. Primeiro,
elas mostram crescentes semelhanças morfológicas entre a casa corrente
urbana e a morada rural ao longo do século XIX, como na documentação
realizada por @martins:1978partido no interior de São Paulo. Segundo,
chamam atenção para a tipologia da morada senhorial, objeto de
aprofundados estudos neste século por grupos de pesquisa
luso-brasileiros como aquele coordenado por Malta e Mendonça
[-@malta:2013casas].

A tipologia da habitação de origem portuguesa no Brasil não forma uma
árvore genealógica autônoma a partir de um tipo matriz comum. Mais bem,
como afirma @weimer:2005arquitetura, é uma teia na qual se entrecruzam,
desde o início da colonização, várias tradições regionais já
amadurecidas em Portugal continental e hibridizadas nas ilhas
atlânticas. Essa teia desenvolve, por sua vez, já no território da
América portuguesa, ulteriores diferenciações e sínteses regionais e
contextuais, alimentadas tanto por dinâmicas internas à cultura edilícia
colonial quanto por injeções periódicas e localizadas de contingentes de
artífices e usuários recém-chegados da península Ibérica e dos Açores.

Certo é, nesse panorama, que a formação do habitat vernáculo
luso-brasileiro não tem a forma nem do caldeirão unitário e
homogeneizado proposto pela mitologia do Estado Novo nem, inversamente,
de uma constelação de tradições que se movessem sempre no sentido de uma
maior diferenciação regional, tal como atestado pelos autores do
Inquérito em Portugal continental.

## Tipologia doméstica no Brasil ##

A história da morada luso-brasileira se caracteriza por duas
negativas fundamentais já postuladas por @waisman:1993interior para
o conjunto da arquitetura latinoamericana: por um lado, a
impossibilidade de se estabelecer uma periodização consistente baseada
em critérios formais e, por outro, a inexistência de processos
tipológicos formando simples genealogias processuais. Na ausência desses
marcadores de uma convencional história linear, a edilícia de base no
Brasil pode ser definida por uma nuvem de características predominantes.
Estas são em grande medida herdadas de variadas matrizes portuguesas,
desdobradas e recombinadas ao sabor das possibilidades e necessidades de
diferentes contextos urbanos ou rurais, classes sociais, recursos e
saberes disponíveis. Algumas dessas características dentre as mais
frequentemente mencionadas na literatura são:

1. Setorização espacial derivada do propósito social da domus ou morada
   arquetípica formulado por @westfall:1991building, qual seja, a
   distinção entre uma zona mais acessível à frente e uma zona mais
   reclusa aos fundos da casa. Na casa brasileira, como sintetiza
   @lemos:1996historia, essa distinção se resolve na precedência da zona
   « íntima » sobre a zona « social », associada à natureza patriarcal
   da sociedade colonial descrita por @freyre:1951sobrados.

2. Distinção ancestral entre tipos distributivos rurais e urbanos, com
   primazia do rural sobre o urbano tanto na genealogia da derivação
   tipológica quanto, como observa @reis:1983quadro, na preferência
   cotidiana pela morada rural sobre o pouso na cidade. Todavia, nos
   séculos XVIII e XIX observa-se intensa contaminação cruzada desses
   tipos, com a presença de plantas rurais solarengas  na cidade e de
   partidos de casas correntes urbanas (com corredores longitudinais) em
   moradas rurais, como observou @martins:1978partido.

3. Cozinha segregada da distribuição principal da morada, quando não da
   sua própria volumetria. Esse aspecto é por vezes apontado como
   indício de uma suposta influência indígena sobre a edilícia
   luso-brasileira. No entanto, a cozinha segregada é atestada já no
   vernáculo açoriano por @duarte:2020traditional. Neste, sinaliza a
   precedência da segurança contra incêndio sobre o aproveitamento do
   calor do fogo, pouco importante nos climas amenos do mundo atlântico
   português. Destaca-se também nesse universo atlântico a raridade de
   chaminés, com a extração de fumo obtida mais frequentemente através
   da telha vã.

Há outra característica morfológica transmitida da morada rural minhota
para o Brasil através dos Açores, esta ainda não sistematizada na
literatura. Trata-se do processo tipológico de « urbanização » da
habitação por meio da transformação do estábulo ao rés do chão em porão
alto e finalmente em pavimento térreo completo ([@fig:ribeiras]). Embora
o primeiro passo desse processo seja raro no Brasil, livre da
necessidade de captar o calor do gado para aquecer a habitação, as
variantes com porão alto e sobrado completo estão presentes. Toda esta
série tipológica apresenta a escada de acesso à habitação
preferencialmente exterior ou imediatamente acessível pela entrada
principal.

![Processo tipológico de casas nas Ribeiras de Santa Cruz, ilha do Pico, Açores. Desenho do autor. Da esquerda para a direita: morada rural sobre estábulo, morada em piso sobre porão alto, e sobrado com rés-do-chão e andar nobre](media/pt-pico-ribeira-scruz-processo.tif){#fig:ribeiras}

Apenas no final do século XIX é que se pôde ver a marca inconfundível de
transformações diacrônicas operadas pela renovação dos modos de morar e
dos comportamentos domésticos. A principal terá sido a adição longitudinal de
uma zona de « serviço » às já existentes zonas « social » e « íntima »
[@lemos:1976cozinhas]. Já a introdução do afastamento lateral no lote
urbano, por esta mesma época, provocou uma compactação e reorganização da
circulação interior da morada, com reposicionamento das zonas
« íntima » e « social » [@lemos:1999casa; @lemos:1989alvenaria].

# Recorte e metodologia #

## Nomenclatura ##

A nomenclatura habitual dos tipos edilícios de base no Brasil não
recobre todas as manifestações da morada tradicional e, pior ainda, não
tem consistência descritiva. Designações sócio-históricas, como a de
« casa bandeirista », coexistem com outras vagamente descritivas da
morfologia das plantas, tais como « casa de morada » --- a qual designa
qualquer casa corrente dotada de corredor longitudinal --- e suas
variações, « meia-morada » ou « morada-inteira ». Estas duas últimas
diferem quanto ao número de células em largura --- uma ou duas --- e,
consequentemente, à posição lateral ou central do corredor.

Em Portugal o vocabulário é igualmente equívoco e por vezes incompatível
com a nomenclatura brasileira. O termo « morada de casas » designa,
sobretudo no Alentejo [@costa:2015moradas], uma tipologia doméstica
urbana formada por células de pequenas dimensões sem distinção quanto à
composição dessas células ou à natureza do parcelamento do solo. Mais
consistente é a distinção, dentro da série tipológica da casa corrente,
entre « habitação de frente estreita » contando com uma única célula em
largura, e « habitação de frente larga » contando com duas ou mais
células em largura. A habitação de frente estreita na nomenclatura
portuguesa corresponde à « casa de porta e janela » na nomenclatura
brasileira, e a habitação de frente larga recobre o espectro das casas
de morada na nomenclatura brasileira.

Outra inconsistência de nomenclatura entre Portugal e Brasil se refere à
terminologia do « solar ». Em Portugal este nome designa somente uma
« casa nobre » (habitação palaciana) rural, uma vez que a sua etimologia
deriva de « solo », ou seja, de uma herdade aristocrática. Já no Brasil
as « casas senhoriais » (termo equivalente à casa nobre em Portugal)
urbanas ou suburbanas também recebem, ocasionalmente e sem critérios
claros, a designação de solar.

Ademais, essa nomenclatura é pouco relevante para se retroceder às
matrizes tipológicas da casa luso-brasileira em Portugal continental ou
nas ilhas atlânticas. Desde o Inquérito que a classificação hegemônica
da arquitetura tradicional portuguesa opera por tipos regionais, em
autores como Oliveira e Galhano [=@oliveira:1992arquitectura], @moutinho:1995arquitectura e
@mascarenhas:2015arquitectura. No entanto, trata-se de uma nomenclatura
em grande medida estabilizada na bibliografia brasileira e da qual não
será possível divergir significativamente.

Além disso, como já apontado acima, o principal interesse deste trabalho
está na trajetória dos tipos urbanos de casas correntes e das casas
senhoriais que se aproximam ao contexto urbano. A tipologia da casa
corrente em Portugal tem, por sua vez, uma origem unitária como indicado
pela nomenclatura do « lote gótico ».


## Recorte de estudo ##

O enquadramento tipológico se limitou, conforme a premissa desta
investigação, às casas correntes urbanas e às casas senhoriais, estas
tanto no contexto de tecidos urbanos consolidados quanto em implantações
de caráter suburbano, suficientemente próximas aos núcleos urbanos para
que representassem um modo de vida citadino. O recorte não leva em conta
o uso atual ou pretérito dessas edificações, uma vez que o termo
« casa » ou « morada » é empregado aqui como indicador tipológico e não
funcional.

Este trabalho reuniu, portanto, 94 plantas de casas urbanas ou quintas
suburbanas datadas de meados do século XVIII ao início do século XX já
publicadas na literatura ou disponíveis em acervos digitalizados. Nesse
universo, predominam os exemplares de casas correntes, tanto térreas
quanto sobrados, sobre as casas senhoriais, por serem aquelas mais
difundidas nos tecidos urbanos. O conjunto de dados empregados nesta
análise --- as plantas de todas as 94 casas estudadas e seus respetivos
gráficos de visibilidade --- está depositado em <https://osf.io/gy47h/>.

A tipologia das casas correntes e senhoriais é pautada pela relação
entre um « conceito de casa » --- terminologia proposta por
@muratori:1959studiIX --- predominante, respectivo a cada uma das duas
séries tipológicas citadas, e as variações e adaptações ao sítio e às
necessidades específicas de cada caso. Nessa relação, verifica-se a
maior estabilidade configuracional no que constitui o « andar nobre »
das edificações: o nível único das casas térreas, ou o pavimento sobre
porão ou sobre rés-do-chão comercial nas casas sobrelevadas ou
assobradadas. Reciprocamente, os porões ou pavimentos inferiores dos
sobrados apresentam grande variabilidade formal, compreendendo desde
porões hipóstilos sem subdivisão espacial até pavimentos que chegam
quase a replicar a distribuição de ambientes do andar nobre.

O conjunto da amostra se concentra no antigo territórios goiano
(incluindo o atual Tocantins), mineiro e fluminense. Trata-se de uma
opção metodológica para contornar o contexto paulista, já amplamente
estudado na literatura por autores como Lemos [-@lemos:1999casa;
-@lemos:1989alvenaria], bem como para privilegiar o aspecto mais
conservador da tradição luso-brasileira frente aos casos inovadores e
idiossincráticos das principais cidades do Nordeste, explorados por
Oliveira e Galhano [-@oliveira:1986casas] e @silva:1986arquitetura.

A variação diacrônica das séries tipológicas foi observada sempre que
possível, mas não se constitui num aspecto predominante neste estudo.
Pelo contrário, a relativa estabilidade da tradição doméstica
luso-brasileira de meados do século XVIII até o início do XX é uma das
premissas do recorte deste trabalho. Devido a essa estabilidade e à
carência de fontes documentais, grande parte das casas correntes
estudadas não podem ser datadas com qualquer grau de confiança.
Reciprocamente, as casas senhoriais apresentam datações mais precisas,
remontando em sua maioria ao período entre o final do século XVIII e o
terceiro quartel do século XIX.


## Procedimentos metodológicos ##

As plantas das casas incluídas no recorte deste trabalho foram
redesenhadas especificamente para uso no programa depthmapX, levando em
conta apenas a distribuição de espaços interiores e pátios. O objetivo
da análise foi averiguar o posicionamento do centro morfológico --- a
zona de maior integração visual na planta, representada como uma mancha
de cores mais quentes --- e sua relação com diferentes tipos de casas
correntes e senhoriais.

A análise da amostra considerou apenas o andar nobre das moradas, quando
se tratava de edificações com mais de um pavimento. Como observado mais
acima, o processo tipológico das moradas sobre porão alto ou
assobradadas deriva da morada rural sobre estábulo. Nesse processo, o
acesso ao andar nobre por escadaria exterior ou porta principal dando
acesso direto à escada é a regra. Portanto, embora seja quase sempre
possível a circulação interna entre pavimentos, o andar nobre constitui
efetivamente uma configuração espacial autônoma e escassamente
influenciada pela sua ligação com o nível térreo ou porão. A expressão
tipológica da composição é representada, assim, de modo suficientemente
completo por aquela configuração do andar nobre, ao passo que o porão ou
pavimento térreo apresentam, na amostra analisada, variações
independentes da configuração do andar nobre. Além disso, eventuais
pavimentos acima do andar nobre e sótãos raramente ocorrem na amostra, e
mais raramente ainda foram documentados na bibliografia disponível.

Por fim, cabe ressaltar que o propósito da análise foi o de identificar
a ocorrência de padrões morfológicos recorrentes, não a sua frequência e
nem configurações excepcionais. Isto porque o viés bibliográfico da
seleção não garante representatividade para eventuais distribuições
estatísticas. Além disso, na amostra ocorreram algumas configurações
*sui generis* condicionadas seja por restrições na implantação das
casas, seja como resultado de sucessivas alterações ou amálgamas de
edificações originalmente separadas. Tais casos singulares não
constituem, por si mesmos, tipos morfológicos uma vez que não pertencem
nem a séries de variações sincrônicas, e nem, até onde foi possível
identificar, a processos diacrônicos mais amplos. Portanto, fogem ao
escopo deste trabalho e não são apresentados nos resultados.


# Resultados e discussão #

## Descrição das variantes sincrônicas ##

A definição histórica das séries tipológicas da casa corrente e da casa
senhorial luso-brasileiras, conforme já exposto mais acima, é bastante
clara na sua distinção. Os tipos da casa corrente se originam da
produção de lotes estreitos e profundos. Isso resulta numa configuração
que remete ao tipo ideal da *domus* caracterizado por um gradiente de
privacidade da frente para os fundos da casa. Esse processo tipológico
se desdobra em frentes mais largas para formar casas articuladas por
meio de um corredor longitudinal lateral ou, nos casos mais expansivos,
central. Trata-se, portanto, de uma série com extremos conceituais bem
definidos, desde a habitação mínima com uma « casa » (célula espacial)
de frente e outra de fundos até a « morada de casas » (Portugal) ou
« casa de morada » (Brasil) expansiva com uma ou duas fileiras de salas
e alcovas de cada lado de um corredor central.

Em casos extremos de
expansão do núcleo elementar da casa corrente, o conjunto inteiro da
casa de morada se duplica com a introdução de um segundo corredor
longitudinal com seu sistema de salas e alcovas ([@fig:cora]).

![Casa corrente duplicada: casa de Cora Coralina, Goiás, 1782. Desenho da autora](media/br-go-vila_boa-1782-guia_dos_bens_imoveis_tombados_em_goias-casa_de_cora_coralina_v02.png){#fig:cora}

No contexto das povoações brasileiras estabelecidas no período colonial,
em geral menos densas do que os centros urbanos consolidados em
Portugal, as casas de morada apresentam quase sempre, conforme descrito
por @algranti:1997familias, uma grande sala situada na extremidade de
fundos do corredor e com acesso direto ou vista para o quintal. Essa
sala é conhecida como « varanda » embora nem sempre tenha tido a
configuração semiaberta que essa palavra denota hoje em dia. Nas fontes
escritas do século XIX, especialmente nos relatos de viajantes como
@debret:1839voyage3, a varanda é identificada como o centro do convívio
doméstico. Nisso ela se opõe à sala de visitas situada na frente da
casa, e usada, como o nome indica, para encontros mais formais com
pessoas externas ao convívio familiar [@lemos:1996historia].

Quanto às casas senhoriais, não é possível falar propriamente num
*processo* tipológico com extremos conceitualmente fixos. Pelo
contrário, verifica-se uma grande diversidade de configurações que se
não pode ordenar numa sequência de desdobramentos lógicos
[@lemos:1996historia]. O ponto comum, porém, à tipologia de casas
senhoriais parece ser as enfiadas transversais de salões de dimensões
maiores do que as células das casas correntes. Além disso, em muitos
exemplares de casas senhoriais a profundidade do corpo edificado
resolve-se com um aparente empréstimo à série tipológica das casas
correntes. Nesses casos, um corredor longitudinal ladeado por diversas
alcovas (nem sempre acessíveis pelo próprio corredor) media a separação
entre salões de frente e de fundos.


## Duas classes tipológicas ##

A partir da descrição das composições de casas correntes e senhoriais,
parece haver uma zona cinzenta entre essas duas séries tipológicas. De
um lado, o crescimento da casa de morada resulta num desdobramento da
composição --- e consequentemente do centro integrador --- para os lados.
Do outro lado, certas casas senhoriais
hibridizam-se com elementos da distribuição espacial da casa corrente. É
diante dessas zonas cinzentas que a análise de integração visual permite
esclarecer características estruturantes de tais composições.

Os gráficos de profundidade visual
gerados pelo programa depthmapX [@gil:2015space10] sobre plantas de
casas evidenciam, de fato, duas séries tipológicas distintas que
confirmam a diferença morfológica essencial entre as casas correntes e
as senhoriais. Essa diferença reflete um matiz mais complexo de relações
entre privacidade e publicidade da vida social entre as elites do Brasil
escravista.

![Gráfico de intervisibilidade de uma casa corrente com centro morfológico no acesso à varanda: casa enxaimel, Pilar de Goiás, século XVIII. Desenho da autora](media/br-go-pilar_de_goias-plantas_residenciais-_casa_enxaimel-half.png){#fig:enxaimel}

Nas plantas representativas da tipologia de casas correntes, o centro
morfológico da composição está invariavelmente na « varanda » ou no
portal entre o corredor e a varanda, reforçando a identificação desta
última com o centro social da convivência doméstica ([@fig:enxaimel]). O
vetor morfologicamente « quente » em volta desse ponto central
desenvolve-se sobretudo ao longo do eixo longitudinal formado pelo
corredor.

Reciprocamente, nas casas senhoriais, o vetor morfologicamente mais
quente situa-se no mais das vezes junto à frente da casa e tem uma direção
transversal. Os pontos de maior integração visual situam-se então junto
aos portais de alguns desses salões dispostos contra a fachada da casa
([@fig:koeler]).

![Gráfico de intervisibilidade de uma casa senhorial com centro morfológico na enfiada transversal dianteira: chácara dos herdeiros de Constantino Dias Pinheiro, Rio de Janeiro. Arquiteto Júlio Frederico Koeler, meados do século XIX. Desenho da autora](media/br-rj-rio_de_janeiro-xix-koeler_julio_frederico-pavimento_da_casas_da_1_chacara_dos_herdeiros_de_constantino_dias_pinheiro.png){#fig:koeler}

Mesmo naquelas plantas em que parece haver aproximação entre as duas
séries tipológicas da casa corrente e da casa senhorial, o gráfico de
integração visual não reflete a ambiguidade aparente à primeira vista.
Em todos os casos analisados de aparente hibridismo tipológico, apenas
uma das duas configurações é dominante: seja a da casa corrente, com o
centro morfológico na varanda e eixo integrador longitudinal, seja a da
casa senhorial, com eixo integrador transversal junto à fachada.

No corpo de exemplos estudados nesta investigação, os casos de gráficos
de visibilidade híbridos, onde as características tipológicas da casa
corrente e da casa senhorial se sobrepõem, são extremamente raros.
Apenas em alguns exemplares de casas senhoriais muito alongadas
longitudinalmente ou dotados de pátio totalmente encerrado, há também um
vetor de integração visual longitudinal --- não necessariamente
associado a composições importadas das casas correntes, porém. A casa da
Princesa, em Pilar de Goiás, é o único exemplar do universo analisado
que apresenta dois centros morfológicos de importância comparável. O
primeiro, na parte dianteira, configura uma enfiada transversal de
salões segundo a tipologia das casas senhoriais; o segundo, aos fundos,
enfatiza a importância da varanda no convívio íntimo ([@fig:princesa]).

![Híbrido de casa corrente e senhorial: casa da Princesa, Pilar de Goiás, c. 1750. Desenho da autora](media/br-go-pilar-1750c-casa_da_princesa-casa_do_patrimonio_em_pilar_de_goias.png){#fig:princesa}


## Implicações para o estudo da arquitetura doméstica luso-brasileira ##

A nitidez com que o método da integração visual permite distinguir entre
as séries tipológicas da casa corrente e da casa senhorial é um
resultado que redireciona a leitura convencional da cidade de origem
colonial e imperial no Brasil. Em vez de separar os tipos edilícios por
variações regionais ou pela quantidade de ambientes, é possível
diferenciar as séries tipológicas pelo posicionamento do núcleo
integrador e pela direção do vetor linear de maior integração.

O resultado da análise de integração visual vem, na verdade, confirmar
por meio da morfologia espacial as dinâmicas da vida doméstica que a
história social já apontavam, nomeadamente a primazia da varanda no
convívio familiar urbano e, no caso específico da arquitetura senhorial,
a primazia dos espaços de recepção e representação. Com isso, permite
fortalecer o vínculo até então tênue e pouco rigoroso entre forma
arquitetônica e dinâmicas socioculturais.

Mais ainda, essa ferramenta da sintaxe espacial esclarece, nos casos
morfológicos limítrofes, a vinculação de certas edificações
preferencialmente à tipologia da casa corrente ou da casa senhorial. Tal
assistência é pertinente se levarmos em conta justamente a sua
capacidade de fortalecer o diálogo crítico entre os modos de
sociabilidade e a sua materialização na forma construída.


# Conclusão #

Durante todo o período estudado, constatou-se a constância do centro
morfológico das casas correntes e dos solares. Salões e varandas
voltadas para o quintal, as áreas de passagem, como corredores, assim
como pátios internos, como as áreas mais quentes, ou seja, mais
acessíveis. As áreas mais frias, ou seja, menos acessíveis, se
mantiveram nas áreas de puxados e laterais das casas. Mesmo que os
anexos e áreas de serviços sejam os pontos menos acessíveis nas casas,
percebeu-se que se localizavam relativamente próximos às áreas centrais.
Foi confirmada a primazia da zona íntima nas casas de morada ou do salão
nos tipos solarengos, onde centro quente nas residências permaneceu
constante entre os séculos XVIII e XX.

As casas brasileiras sofreram diversas adaptações ao longo do período
estudado, como a especialização das atividades nos cômodos e a
introdução de novos sistemas construtivos. Todavia, a transformação mais
significativa é a introdução das moradas ecléticas, partido
caracterizado pelo afastamento do volume principal das habitações em
relação aos limites do lote e o acesso feito pela lateral das casas.

Assim, a continuação de um trabalho sistemático de investigação da
tipologia doméstica tradicional no Brasil deve expandir o escopo de
análise para a arquitetura eclética, mas também para séries tipológicas
vernaculares ainda não exploradas: nomeadamente as moradas dos
imigrantes de diversas nacionalidades e outras casas rurais de pequeno
porte. Ademais, os casos singulares que não se enquadram em nenhuma
série tipológica podem, também, ser confrontados com essas séries e
analisados quanto às implicações da sua configuração para a vida social.

[^1]: Esta pesquisa foi fomentada com uma bolsa de iniciação científica
    do Conselho Nacional para o Desenvolvimento Científico e Tecnológico
    (CNPq) no período 2021-2022.
