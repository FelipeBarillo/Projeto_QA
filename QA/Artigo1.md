# Tipos de testes: quais os principais e por que utilizá-los?

Se você iniciou há pouco tempo sua jornada no mundo do desenvolvimento, provavelmente em algum momento se deparou com os famosos testes de software, ou mesmo percebeu que dentre as exigências para vagas em muitas empresas estão presentes algumas tecnologias de testes. Existem diferentes tipos de testes e é isso que vamos discutir neste artigo!

Tornou-se padrão que empresas busquem testar seus produtos em diferentes etapas do desenvolvimento até a entrega ao usuário final, devido às vantagens que os testes nos trazem, possibilitando a identificação de erros e garantindo a confiabilidade no uso do software, que deve ser um produto com qualidade de funcionamento.

Então sabendo do quão importantes são os testes e de como as empresas hoje buscam utilizá-los em diversas etapas da criação do software, nos vem a pergunta: quais são os tipos de testes?

É comum sentir uma certa dificuldade em entender os tipos de testes. Até a data da escrita deste artigo, não temos uma definição exata de quais tipos de testes são de fato os principais. Mas podemos dizer que alguns deles são os mais utilizados.No geral, a escolha pela utilização de determinados tipos de testes depende do projeto, cultura da empresa e da equipe que os realizam.

## Testes unitários

Esses testes são feitos em um nível muito baixo (próximo ao código fonte) do projeto, por isso, geralmente quem os realiza são os programadores envolvidos no projeto.

Geralmente são realizados de forma isolada do restante do sistema, visto que tem por objetivo assegurar a qualidade das unidades de forma individual e não o sistema como um todo. Podemos entender como “unidade” as menores partes do nosso sistema, ou seja, métodos e funções das classes ou pacotes utilizados no projeto.

Esses testes têm como objetivo verificar as menores unidades isoladamente, garantindo que a lógica de cada uma delas está correta e que funciona conforme o esperado. Geralmente têm um baixo custo para automatização e podem ser executados rapidamente, inclusive por um servidor de integração contínua.

## Teste de Integração

Como vimos, os testes unitários buscam verificar se elementos individuais (unidades) do sistema estão corretos, mas isso não nos garante que a interação entre essas unidades ocorrerá da forma que planejamos. É nesse momento que utilizamos os testes de integração.

Geralmente eles são mais complexos para serem desenvolvidos e mais lentos ao ser executados, pois ao contrário dos testes unitários, nosso objetivo não será testar a lógica nas menores unidades do sistema, mas sim as funcionalidades inteiras, o conjunto funcionando em simultâneo e entregando o resultado esperado.

Por isso, o ideal é realizar testes de integração após a realização dos testes unitários, garantindo que as unidades estão corretas individualmente e também que funcionam em conjunto.

## Testes de ponta a ponta (E2E)

Como o próprio nome sugere, esses testes buscam verificar o comportamento do sistema como um todo, “de uma ponta à outra”.

Geralmente simulam a atividade que o usuário final teria, mas feita em um ambiente preparado para ser muito semelhante ao do ambiente de produção. Normalmente ele é o último teste antes de o projeto entrar em produção.

O ambiente no qual os testes são feitos precisa de situações que simulem o uso do produto desenvolvido no mundo real, como interagir com um banco de dados com informações reais, usar comunicações de rede, interagir com outros aplicativos, sistemas ou hardware, se necessário.

Os testes de ponta a ponta também buscam dar uma visão geral do funcionamento do sistema para tomadas de decisão e podem ser utilizados para verificar se ele atende a alguma norma específica, padrões legais ou regulamentações.

Demoram mais para ser escritos e executados, visto que englobam todo o projeto em questão. Além disso, por se tratar de um tipo de teste de alto nível, ele não se atêm aos mínimos detalhes da aplicação que está sendo testada… ou seja, geralmente não nos dá muitos detalhes a respeito dos erros encontrados, como os testes unitários por exemplo.

## Teste manual vs. automatizado

Agora que entendemos alguns dos principais tipos de testes, vêm algumas questões que são muito comuns. O que são testes automatizados? Quais as vantagens e quando devemos utilizá-los?

A maioria dos testes podem ser executados de duas formas: <b>manual ou automatizada</b>. <b>O teste manual</b>, como o próprio nome nos indica, é feito manualmente por um analista, desenvolvedor ou especialista em qualidade. Nessa situação, a pessoa responsável pelos testes irá executar cada passo necessário para que o teste seja realizado com sucesso, sempre atento para as condições que o teste precisa para ser realizado da forma correta.

<b>O teste manual</b> costuma ter baixo valor de investimento e também permite que a pessoa que os realiza experimente condições semelhantes às do ambiente de produção, já que pode definir os parâmetros do teste manualmente.

Em compensação, testes manuais são mais lentos e como dependem totalmente da interação humana, sempre existe uma alta possibilidade de um problema passar despercebido por quem testa.

Já os <b>O teste automatizados</b> nos trazem a praticidade de ter scripts, ferramentas como os mocks, citados neste artigo e técnicas que agilizam o processo. Eles nos ajudam a descobrir rapidamente se o sistema está com o desempenho esperado, e por serem automatizados, podem ser executados sem a necessidade de uma pessoa em todas as etapas de testes.

São mais confiáveis, já que são definidos por uma ferramenta ou scripts específicos; Assim o teste será executado automaticamente, sem interferência humana direta, diminuindo a possibilidade de erros passarem despercebidos.

Costumam ser mais caros, pois dependem de ferramentas específicas e o nível de automação que escolhemos influencia no tipo de ferramenta a ser utilizada, o que pode trazer mais custos. Além disso, existem problemas que apenas um testador humano poderá detectar, como os de usabilidade. Nesses casos não conseguimos utilizar a automatização de forma eficiente.

### Por fim, fica a dúvida: Usar testes automatizados ou manuais? Essa é uma daquelas perguntas que têm como resposta um: depende…

O mais comum é que os dois tipos sejam utilizados em simultâneo, pois como vimos, temos vantagens e desvantagens em ambos e existem tipos de testes que preferencialmente serão automatizados, enquanto outros tendem a permanecer manuais, pois se faz necessária uma interação humana real, ou ainda por apresentarem um custo muito elevado.

## Conclusão:

Como vimos, os testes nos trazem muitas vantagens, nos garantem um maior padrão de qualidade no desenvolvimento e asseguram que os requisitos do projeto serão atingidos.

Além disso, os tipos diferentes de testes complementam uns aos outros, fazendo com que todas as etapas da produção do software sejam realizadas com maior eficiência, reduzindo drasticamente a ocorrência de erros nos projetos.
