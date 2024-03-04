# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas
<img src="img/persona1.jpeg" width="180px"> 
<p>Nome: Luciana Andreia Daiane Pires</p>
<p>Idade: 33</p>
<p>Quais tecnologias usar: Facebook | Instagram | Tinder | TikTok | Youtube</p>
<p>Ocupação: Formada em Arquitetura, trabalha como projetista em uma construtora que atende todo o território nacional</p>
<p>Quem os influencia: Canal Ciência todo dia | professor ferretto</p>
<p>Onde busca informação: Youtube | Tiktok</p>
<p>hobby: Gosta de fazer cursos online nas horas vagas.</p>
Sobre: 
A Luciana é uma mulher de 33 anos que tem uma menina de 16 que quer tirar boas notas na escola, mas a filha nunca consegue decorar o conteúdo quando o professor está passando, porque muitos colegas dela ficam falando na hora da aula quando o professor está ensinando.
<p>

<p>Principais informações sobre a persona</p>
<ul>
 <li>Nascimento: 02/03/1991;</li>
 <li>E-mail: luciana_pires@ibest.com.br;</li>
 <li>Endereço: Rua Barlavento</li>
</ul>

----------------------------------------------------------------------------------------------------
<img src="img/persona2.jpeg" width="180px"> 
<p>Nome: Hadassa Fernanda Débora Dias</p>
<p>Idade: 59</p>
<p>Quais tecnologias usar: WhatsApp | X | LinkedIn </p>
<p>Ocupação: Pedagogia</p>
<p>Quem os influencia:  | professor Andre | professor Carlos</p>
<p>Onde busca informação: X | Google</p>
<p>hobby: Adora dar aulas para jovens..</p>
Sobre: 
A Hadassa é uma mulher de 59 anos aposentada que adora dar aulas para jovens e ensina tudo que aprendeu em toda sua vida. 
<p>

<p>Principais informações sobre a persona</p>
<ul>
 <li>Nascimento: 02/03/1965;</li>
 <li>E-mail: hadassa_dias@deze7.com.br;</li>
 <li>Endereço: Rua I</li>
</ul>


----------------------------------------------------------------------------------------------------
<img src="img/persona3.jpeg" width="180px"> 
<p>Nome: Flávia Priscila Monteiro</p>
<p>Idade: 45</p>
<p>Quais tecnologias usar: Instagram | WhatsApp | Kwai | LinkedIn | Youtube </p>
<p>Ocupação: Advogada</p>
<p>Quem os influencia:  | Canal Psicologia | Jornal do Brasil</p>
<p>Onde busca informação: Youtube | Jornal do brasil</p>
<p>hobby: Adora ler livros de filósofos antigos.</p>
Sobre: 
Flávia é uma mulher de 45 anos, mãe de dois meninos, advogada que adora ler livros de filosofias antigas para ficar com a mente afiada na audiência.  Ela nunca tem tempo para os filhos. Diante disso, os filhos são muito mal na escola, sempre tirando notas baixas. 
<p>

<p>Principais informações sobre a persona</p>
<ul>
 <li>Nascimento: 01/03/1979;</li>
 <li>E-mail: flavia-monteiro81@focusdm.com.br;</li>
 <li>Endereço: Rua São Felipe</li>
</ul>



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:



|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|      Luciana       | Desejo uma aplicação que eu possa  | Isso me ajudaria a encontrar um        |
|                    | filtrar os cursos por suas         |    curso especifico para minha         |
|                    | especificações.                    |    filha assistir sem se destrair.     |
|                    |                                    |                                        |



|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|      Hadassa       |Quero uma plataforma intuitiva e de | Isso me ajudaria para eu dar aulas na  |
|                    |fácil entendimento para poder dar   | plataforma de forma prática e eficaz,  |
|                    |aulas para jovens.                  |já que eu sou aposentada e não tenho    |
|                    |                                    | muita experiẽncia com informatica.     |          |                    |                                    |                                        |



|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|     Flávia         | Desejo uma aplicação com           |  Isso ajudaria meus filhos para poder  |
|                    |  Cores visuais atraentes           | Estudar sem se distrair                |
|                    |  para as mentes dos jovens         |                                        |
|                    |  poder focar no conteúdo.          |                                        |
                                                         





## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
