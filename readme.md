# Resumo de Sistemas Operativos
## Diogo Chança

---

### Índice

- Dados

- Informação

- Conhecimento

- Sistemas de informação

- Tecnologias de Informação

- Processo

- POO

- UML

---

#### Dados

É uma forma de representar a informação que pode ser utilizada como um meio de comunicação. Também pode ser um conjunto de factos não processados representando eventos que ocorrem na organização ou no ambiente físico antes de serem organizados de forma a serem compreendidos.

Exemplo: dados de um cliente como: nome, idade, morada, telefone, etc.

---

#### Informação

São dados moldados de forma a possuir um significado e utilidade para o ser humano. Também é conhecimento formalizado dos estados de um sistema que pode ser transmitido de um modo reproduzivel.

Exemplo: Notícias.

---

#### Conhecimento

É a transformação da informação que é criada por alguém e que partilha publicamente e/ou em privado.

Exemplo: criação de jornais científicos.

---


#### Sistemas de informação

É um conjunto integrado de recursos humanos e tecnológicos, cujo objetivo é satisfazer as necessidades de informação de uma organização e os respectivos processos de negócio.
Basicamente, um sistema de informação é uma manipulação de informação através da tecnologia, onde envolve: adicionar, alterar e remover dados.

![Sistema](img/sistema.png)

---

##### Tipos de sistemas de informação

- Operacionais: tratam as transações de rotina como, facturação, controlo de encomendas e stock, contabilidade e contas correntes.

- Conhecimento: permite gerir o conhecimento nas organizações, dando suporte à criação, captura, armazenamento e eliminação da informação.

- Tácticos: analisa a informação para dar suporte ao processo de tomada de decisão a curto prazo. Inclui os sistemas de informação que permitem por exemplo, a análise de vendas, controlo de orçamentos e gestão do inventário.

- Estratégicos: abordam o planeamento a médio e longo prazo, tais como previsões de vendas, receitas, custos, planeamento da produção e previsões de encomendas.

- TPS (Sistema de Processamento de Transações - Transaction Processing System): recolhe e mantém informação sobre transações e controla as atividades da organização.

- MIS (Sistema de Informação de Gestão - Management Information System): converte a informação das transações e informação em decisões e gestão da organização.

- DSS (Sistema de apoio à decisão - Decision Support System): suporta os utilizadores na tomada de decisão não estruturáveis, tendo como Outputs informação, modelos e ferramentas para analisar a informação.

- ESS (Sistema de informação para executivos - Executive Suport System): fornece aos gestores de uma forma interativa e fléxivel o acesso à informação geral para a gestão da organização.

- KWS (Sistemas Periciais - Knowledge Work System): suporta os profissionais do desenho, diagnóstico e avaliação de situações complexas que requerem conhecimento especializado em áreas bem definidas.

- OS (Sistema de Escritório - Office System): mantém as tarefas de comunicação e processamento de informação em ambiente de escritório.

---

##### Gestão de Sistemas de Informação 

- Gestão do Recurso Informação e de todos os recursos envolvidos no planeamento, desenvolvimento, exploração e manutenção do SI.

- Atividade de gerir SI como sendo a junção das atividades de planear SI e de desenvolver SI.

- Gestão do recurso informação, gestão de recursos humanos, gestão de recursos computacionais e gestão de projetos para o Desenvolvimento de SI.

![Sistema](img/info.png)

#### ***Amaral em 1994***

---

##### Planeamento de sistemas de informação

- Definir a intervenção e conjugar correctamente as interacções entre as pessoas, o processo aplicado, as características do produto e o projecto que orienta as actividades a desenvolve;

- Articular pessoas, processo produto e projeto (4Ps).

- Porquê *(Why)* é que o sistema vai ser desenvolvido;

- O que *(What)* vai / deve ser feito;

- Quando *(When)* é que vai ser feito;

- Quem *(Who)* é o responsável;

- Onde *(Where)* é que as responsabilidades estão localizadas;

- Como *(How)* é que vai ser feito;

- Quanto vai custar *(How much)* em termos de recursos.

![Sistema](img/piramide.png)

---

#### Tecnologias de Informação

- Conjunto de equipamentos e suportes lógicos (hardware e software) que permitem executar tarefas como recolher, tratar e expor dados.

- Também se pode utilizar o termo TIC (Tecnologias de Informação e Comunicação) para demonstrar a união de TI's com as telecomunicações.

---

#### Processo

- Termo usado para descrever uma ação, sendo constituido por um nome e um verbo, cuja ordem é indiferente. 
Exemplo: "Encomendar produto" ou "Produto vendido".

- O resultado é contável, ou seja, permite saber quantas vezes foi feito esse processo. Exemplo: saber quantos backups foram feitos num mês. É essencial para a organização deve-se focar no objeto em si e não quem tá o a fazer nem como;

---

##### Regras
1. Evitar nomes de processos inconsistentes. Exemplo: “Gerir Reparações”. Se inverter-se a verbalização do nome no exemplo anterior, o resultado será “Reparações Geridas”. Se estão ambas no plural, não se pode por uma palavra no singular, senão fica sem sentido.

2. Evitar verbos como: gerir; manter; administrar; monitorizar; tratar, entre outros. Não ajuda a ver o resultado do processo. No entanto, pode-se usar verbos como: contar; avaliar; imprimir; anexar; retornar; ordenar; priorizar e fornecer, que já ajudam a ver o resultado.

---

##### Boas práticas

- É iniciado por um evento despoletador, algo que acontece para iniciar um processo;

- O processo é essencialmente verbo ação (resulta o output) + nome (no singular) ou ao contrário;

- Compreende um corpo de trabalho, que pode ser caraterizado como um conjunto de atividades ou uma sequência definida de etapas e decisões;

- O resultado é discreto e contável, se for utilizado um verbo vago esses critérios não se verificam e é o que o cliente do processo pretende.

---

##### Processo de desenvolvimento de software

- Providenciar orientação na sequência de realização das atividades envolvidas e critérios para monitorizar e avaliar os modelos e atividades do projeto;

- Especificar os modelos descritivos do sistema que devem ser desenvolvidos;

- Dirigir as tarefas dos participantes e da equipa como um todo.

---

Alguns exemplos:

|Processo sugerido|O que lhe chamamos|Porque não é processo?|
|:--------:|:------:|:-----------:|
|Customer Relationship Management|Área de processo|Não entrega um único, resultado específico; um conjunto de processos de negócio com um objetivo global
|Obter novo cliente|Processo de negócio|Entrega um resultado específico e encontra todos os outros critérios nesta seção. Como processo de negócio end-to-end|
|Avaliar a situação financeiro ou configurar o cliente|Subprocesso|Muito pequeno – entrega resultados específicos, mas são resultados intermédios num processo negócio end-to-end|
|Calcular o limite de crédito do cliente, limitar ou criar a conta do cliente|Atividade, etapa, tarefa… (sem termo específico)|Muito pequeno – parte de umsubprocesso. Provavelmente descrito num procedimento, caso de uso ou serviço|
|Determinar limite de crédito do cliente ou definir o tipo de conta do cliente |Atividade, etapa, tarefa … (sem termo específico)|Muito, muito pequeno – uma etapa ou instrução, provavelmente uma linha num procedimento ou passo num caso de uso|
|Processo de vendas interno|Função|Não entrega um único resultado, uma unidade organizacional que participa em vários processos de negócio|
|“Processo CRM no Oracle” |Sistema|Não entrega um resultado, um sistema que suporta vários processos de negócio|
|“Nosso processo ebusiness”|Tecnológico|Não entrega um resultado específico, tecnologia empregue em vários processos de negócio|

---

#### POO

POO- Programação Orientada a Objetos: linguagens de programação que permitem criar classes e manipular objetos com código. Exemplos: Java, C, C#, Python, entre outras.

- Encapsulamento: liga os dados e funções. Mantém ambos seguros de interferência externa e má utilização e pode ocultar dados, de modo a ficar privado.

- Herança: permite ligar as classes numa hierarquia através do tipo. 

- Polimorfismo: permite que referências de tipos de classes mais abstratas representem o comportamento das classes concretas que referenciam. Caracteriza-se quando duas ou mais classes diferentes têm métodos de mesmo nome, de forma que uma função possa utilizar um objeto de qualquer uma das classes polimórficas, sem necessidade de tratar de forma diferenciada conforme a classe do objeto. O termo significa "muitas formas".

- Abstração: utilizada para a definição de entidades do mundo real, sendo onde são criadas as classes. Essas entidades são consideradas tudo que é real, tendo como consideração as suas características e ações.

- Objeto: é qualquer coisa a qual pudermos dar um nome. Em programação, é uma instância (ou seja, um exemplar) de uma classe. É capaz de armazenar estados através de seus atributos e reagir a mensagens enviadas a ele, assim como se relacionar e enviar mensagens a outros objetos.

- Classes: estrutura que abstrai um conjunto de objetos com características similares. Define o comportamento de seus objetos através de métodos e os estados possíveis destes objetos com atributos.

---

##### Regras de como declarar um objeto

1. Tem de ser definido como as operações que o objeto pode efetuar.

2. Ter verbos de ação como Gravar ou Alterar.

3. Ter uma Identidade que permita identificar um objeto como único.

4. Partilhar as mesmas propriedades, como por exemplo: nome, morada, contacto, etc.

5. Poder-se adicionar, alterar ou remover dados.

6. Definir o tipo (Integer, Float, Long, Double, String, Date ou Boolean) com os ":".

---

##### Não são objetos ou classes se:

- Tiverem apenas um atributo e/ou apenas um objeto;

- Sem serviços aplicáveis, ou que não produzem um resultado visível para o problema em análise;

- Não sejam relevantes para a solução do problema;

- Correspondem a atributos de outros objetos (processo de abstração de classes);

- Identifica entidades e conceitos;

- Descreva atributos (propriedades);

- Operações (comportamentos);

---

#### UML

Significa Unified Modelling Language e permite especificar, visualizar, construir e documentar artefactos de um sistema de software. Pode ser considerado uma metodologia suportada numa orientação por objetos que resolve as limitações das abordagens anteriores e classifica e subdivide o mundo em diferentes objetos com base nas diferenças e semelhanças existentes ao nível das caraterísticas e comportamento dos objetos, de modo a resolver o problema em questão.

---

##### Antecedentes

1. Grady Booch desenvolveu a linguagem ADA e técnicas Orientadas a Objectos para a linguagem;

2. Jim Rumbaugh propôs o Object Modelling Technique (OMT) para análise e sistemas de informação;

3. Ivar Jacobson cria Object Oriented Software Engineering (OOSE) que utilizava um modelo conhecido como casos de uso para a compreensão do sistema;

4. Jim Rambaugh alia-se a Grady Booch na Rational e criam o Unified Method;

5. Ivar Jacobson adere à Rational e integram os casos de uso no UML;

6. Em 1996 saí a 1ª versão do UML;

7. Em 1997 o UML torna-se num standard da OMG(Object Management Group).

---

##### Modelação com UML

- Diagrama de casos de uso: constituem um elemento fundamental no UML. Captura o contexto do sistema na perspectiva do utilizador. É um sistema em termos de interação que os utilizadores têm com o mesmo. É constituido poe atores e casos de uso.

1. Ator: é uma pessoa, que está em interação com o sistema, subsistema ou classe. 

2. Caso de Uso: unidade coerente de uma funcionalidade visível do exterior fornecida por um elemento do sistema, que expressa uma sequência de mensagens trocadas por um elemento do sistema com um ou mais atores. Representa os requisistos do sistema e permite que o utilizador compreenda o sistema.

3. Relação Include: utiliza a funcionalidade de outro caso de uso e pode ser aproveitado no contexto de outro. Relaciona dois casos e uso com o procedimento "incluído no outro" incondicionalmente, ou seja vai acontecer sempre.

4. Relação Extend: reflete um comportamento opcional necessário para outro caso de uso. Terá seu procedimento "ACRESCIDO" de outro caso de uso e Representa outro caso de uso que ocorre uma situação especial.

5. Relação Generalização: relação entre um caso geral e um caso específico. A relação do ator geral é herdada pelo ator especifico e terá uma relação com um "caso" que não se considera no geral. A generalização também pode ser realizada nos atores.

6. Relação Regras gerais: utilizar o include quando o caso de uso pode ser utilizado em duas ou mais situações e utilizar o extend quando se pretende efetuar uma variação do comportamento normal de uma forma mais controlado. Utilizar a generalização quando se pretende efetuar uma variação do comportamento normal.

7. Descrição casos de uso: tem um conjunto de passos a descrever o cenário principal. Pode ter pré condiçõs, pós condições e casos alternativos. A descrição dos casos de uso pode ser realizada utilizando texto livre ou descrição estruturada.

---

###### Exemplo de caso de uso: 
Exercício 1 – Casos de Uso – Bolsa de Emprego

1. Atores
- Administrador: O administrador representa a pessoa ou entidade responsável pela gestão do sistema desenvolvido, que é responsável pela validação dos registos dos empregadores e dos candidatos, fazendo a atribuição de um login e de uma password, sendo também o responsável pela remoção dos anúncios com validade expirada;

- Empregador: O empregador representa a pessoa que disponibiliza anúncios de oferta de emprego, aos candidatos à procura de emprego;

- Candidato: O candidato representa o utilizador que procura anúncios que satisfaçam os seus interesses.

2. Casos de Uso
- Colocar anúncios de oferta de emprego: Corresponde a uma ação realizada por um empregador, que depois de autenticado poderá preencher um formulário correspondente a um anúncio de oferta de emprego.

- Pesquisar candidatos: Este caso de uso consiste na pesquisa, por parte dos empregadores, de candidatos registados na Bolsa de Emprego, de acordo com diferentes critérios.

- Alterar dados de registo: Os candidatos e os empregadores, depois de registados na Bolsa de Emprego, poderão alterar os seus dados de identificação, como por exemplo, contacto, email, morada, etc. Os candidatos poderão fazer alteração do seu Curriculum Vitae.

- Fazer registo: Este caso de uso corresponde à introdução dos dados que permitam identificar os diferentes utilizadores do sistema, empresa ou candidato. Para o caso de candidatos, o registo deverá incluir um formulário com dados relativos ao seu Curriculum Vitae.

- Candidatura a anúncio: Como o próprio nome do caso de uso sugere, a candidatura a anúncio refere-se à acção por parte dos candidados a emprego, de envio de um mail com os seus dados (dados pessoais, CV, referências, etc...) para o empregador.

- Validar Registo: Este é um caso de uso do administrador da Bolsa de Emprego, que depois de efetuado um registo de candidato ou de empregador, deverá verificar os dados introduzidos, e em caso de validação deverá enviar um login e uma password que lhes permita o acesso à aplicação.

- Consultar anúncios: Os candidatos registados na Bolsa de Emprego poderão consultar os diferentes anúncios disponíveis, de acordo com diferentes critérios pré-definidos, como, funções a desempenhar, local de trabalho, habilitações, etc...

- Autenticação: Como visível na figura 1, quase todos os casos de uso definidos implicam a autenticação dos utilizadores do sistema, empregadores ou candidatos, ou seja, a introdução do login e da respetiva password, que receberam aquando do registo.

- Remover anúncios: Este caso de uso é da responsabilidade do administrador do sistema, consistindo na remoção, automática (requisito não mínimo) ou não, dos anúncios presentes no sítio com validade expirada(valor a especificar).

- Notificar: Embora este caso de uso tenha sido especificado como requisito nãomínimo, pretende representar a notificação que deverá ser efetuada pelo administrador do sistema, aos candidatos, caso seja introduzido algum anúncio da sua área de interesse, e aos empregadores, caso algum candidato introduza um curriculum compatível com à área dos empregadores registados. De notar, que tal como referido em requisitos não-mínimos, esta notificação poderá ser efetuada automaticamente, sem intervenção direta do administrador do sistema.

![diagrama](img/caso.png)

---

- Diagrama de classes: tem descrição formal da estrutura de objetos num sistema, descreve a identidade dos objetos, relações com outros objetos, atributos e as operações. Os elementos que compõem um diagrama de classes são: classes de objetos, relações de associação e generalização multiplicidade.
Tem uma perspetiva estática para suportar os requisitos funcionais identificados nos diagramas casos de uso.

![diagrama](img/classe.jpg)

---
- Diagramas de Sequência: representam um conjunto de mensagens organizadas numa sequência temporal. Este tipo de diagramas têm duas dimensões:
Vertical, que representa o tempo e Horizontal, que representa os objectos participantes numa sequência de eventos necessários para atingir o objectivo.

![diagrama](img/ds.jpg)

---
- Diagramas de Colaboração: representam interacções organizadas espacialmente de uma forma distinta dos diagramas de sequência. Mostra as relações entre os objectos que desempenham papéis diferentes realizadas em torno dos objectos e das suas ligações com os restantes.

![diagrama](img/colab.png)

---
- Diagramas de estado: permitem modelar o comportamento interno de um determinado objecto, subsistema ou sistema global, representando a sequência de estados de um determinado objecto. Representam os estados possíveis de um objeto e as transições entre estados. Os eventos que fazem desencadear as transições e as operações que são executados dentro de um estado ou transição.

![diagrama](img/estado.png)

---
- Diagramas de componentes: representam as dependências entre os componentes de software, ilustrando as dependências entre os vários componentes.

![diagrama](img/comp.png)

---
- Diagramas de instalação: demonstram a configuração dos elementos de processamento e dos componentes de software, processos e objectos neles suportados.

![diagrama](img/inst.jpg)

---
- Diagrama de atividade: permite representar atividades no sistema.

![diagrama](img/atividade.png)

---
- Diagrama de implementação: mostra elementos de software implementados por quais elementos de hardware, ilustra o processamento do tempo de execução do hardware e dá uma perspetiva de uma visão da topologia do sistema do hardware.

![diagrama](img/impl.png)

---
- Diagrama de domínio: permite dividir o sistema em subsistemas.

![diagrama](img/modelo.jpg)

---
