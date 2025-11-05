# Por que e o que é possível testar?

Assim que iniciamos nosso trabalho como desenvolvedor ou desenvolvedora, é comum pensarmos que quando criamos um software ele está finalizado assim que escrevemos a última linha de código. Neste momento não nos atentamos a uma etapa muito importante do processo de desenvolvimento, <b>o teste</b>. Em resumo, o teste é a etapa em que verificamos as falhas (os famosos bugs) que nossa aplicação pode ter.

Testes são tão importantes que temos um profissional especializado para essas situações. Aqui introduzimos um termo muito comum, o <b>Quality Assurance (QA)</b>. A tradução para ele seria algo como “garantia de qualidade” se referindo ao profissional ou área que irá garantir que um produto ou serviço está sendo oferecido da melhor forma o possível.

Definir testes em poucas linhas é complicado porque podemos abordar diversos tipos para diferentes aplicações; como mobile, frontend, backend, segurança dentre outras. [Neste artigo](https://github.com/FelipeBarillo/Projeto_QA/blob/main/QA/Artigo1.md)</br> você encontrará uma explicação ainda mais completa sobre as mais comuns.

Queremos convencê-lo do porquê de testar, além de apresentar o que é possível testar. Será que eu preciso testar mesmo o que eu não vejo?

## Mas vamos lá, por que testar?

Vamos pensar em exemplos práticos.

- Supondo que você trabalhasse no setor financeiro de uma empresa, você acabaria lidando com pagamentos e possivelmente uma quantidade razoável de dinheiro. O ideal é que possíveis senhas e dados pessoais de clientes ou funcionários estivessem bastante seguros, certo?

Imagine se esses dados ficassem expostos para hackers ou outros agentes de ameaças. Teríamos um grande problema. Portanto, precisamos testar nosso sistema para evitar que isso aconteça, avaliando as vulnerabilidades da nossa aplicação.

Geralmente testes não são gratuitos e demandam tempo, mas ter esses dados expostos poderia nos prejudicar ainda mais, seja financeiramente ou até diminuindo a credibilidade da nossa empresa. Até problemas que nos expusessem menos poderiam ser prejudiciais

- Imagine que a página de login de uma plataforma de streaming estivesse com um bug bem na hora que você quisesse assistir a sua série favorita. Você teria uma experiência ruim e talvez não recomendasse aquela plataforma. A credibilidade do produto diminuiria cada vez mais, caso o problema continuasse.

Vimos exemplos de diferentes áreas. Então é possível testar tudo? Vale a pena fazer testes no frontend? E no backend?

### Pirâmide de testes

Antes de analisar área por área, vamos pensar juntos na teoria e na lógica do uso de testes. Para isso temos a pirâmide de testes. Ela foi idealizada por Mike Cohn em seu livro “Succeeding with agile”. A ideia é ser uma metáfora relacionando a complexidade, o tempo, entre outros fatores para auxiliar na jornada de testes. Veja a pirâmide abaixo:


