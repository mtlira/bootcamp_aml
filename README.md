# Teste de qualificação AML - Respostas

Submissão das respostas do teste de qualificação para o processo seletivo do Bootcamp da AML em 2022.

## Candidato: Matheus Ribeiro Lira

#### Dados utilizados para os itens K a O: Movimentações do CGPF de Outubro de 2021.

### A – Com suas palavras explique o que é lavagem de dinheiro.

A lavagem de dinheiro consiste na prática de atribuir uma falsa origem legal a quantias de dinheiro que foram obtidas por atividades ilegais e criminosas como roubo, corrupção, tráfico de drogas, entre outros, com o objetivo de esconder tais atividades dos olhos da Receita Federal.

### B – O que é Cartão de Pagamento do Governo Federal (CPGF), e qual a sua finalidade.

Segundo o Portal da Transparência da Controladoria Geral da União (CGU), o Cartão de Pagamento do Governo Federal (CPGF) é um meio de pagamento utilizado pelo Governo Federal que se assemelha ao cartão de crédito, mas com regras mais específicas para a sua utilização. O CPGF é utilizado para pagamentos de despesas próprias consideradas como suprimento de fundos, que são um adiantamento concedido aos servidores para pagamento de despesas tidas como excepcionais. O CGPF, portanto, fornece um meio de pagamento mais ágil e simples que fornece, ao mesmo tempo, mais modernidade e controle na gestão de recursos

Referência: https://www.portaltransparencia.gov.br/pagina-interna/603242-cartao-de-pagamento-do-governo-federal

### C – Quem pode utilizar o CPGF?

Segundo a cartilha sobre o CPGF da CGU, o CPGF pode ser utilizado por servidores públicos  ou ocupantes de cargo em comissão em efetivo exercício no órgão, que satisfaçam as seguintes condições:

a) não ser responsável por dois suprimentos de fundos em fase de aplicação e/ou de prestação de contas;

b) não tenha a seu cargo a guarda do material a adquirir, salvo quando não houver na repartição outro servidor que reúna condições de receber o Suprimento de Fundos; 

c) não ser responsável por Suprimento de Fundos que, esgotado o prazo, esteja pendente de prestação de contas; 

d) não ter sido declarado em alcance, assim entendido aquele que tenha cometido apropriação indevida, extravio, desvio ou falta verificada na prestação de contas, de dinheiro ou valores confiados à sua guarda; 

e) não tenha tido prestação de contas da aplicação de suprimento fundos com despesas impugnadas pelo Ordenador de Despesas ou que esteja em processo de Tomada de Contas Especial; 

f) não se confunda com a pessoa do Ordenador de Despesas;

g) não seja o próprio demandante da aquisição/contratação de serviço, exceto em viagem a serviço.

Referência: https://www.gov.br/cgu/pt-br/centrais-de-conteudo/publicacoes/orientacoes-aos-gestores/arquivos/suprimento-de-fundos-e-cartao-de-pagamento.pdf

### D – Qual a URL onde é possível fazer o download dos arquivos do CPGF?
A consulta sobre os dados do CPGF é feita no portal de transparência da CGU, por onde é possível verificar os dados de gastos em determinado período. O link específico para fazer download dos arquivos do CPGF é:
 http://www.portaldatransparencia.gov.br/download-de-dados/cpgf

### E – Qual a URL da paǵina com a descrição dos campos (ou dicionário de dados) da CPGF?
https://www.portaldatransparencia.gov.br/pagina-interna/603393-dicionario-de-dados-cpgf

### F – É possível identificar o nome e o documento do portador do CPGF, em todas as movimentações ou há movimentações onde não é possível identificar o portador?

Há movimentações de cunho sigiloso, nas quais não é possível identificar o portador pelo seu documento, nem pelo seu nome. 

### G – É possível identificar o Órgão do portador do CPGF?

Após uma inspeção no arquivo .csv de prestação de contas de Outubro de 2021, pode-se dizer que é possível identificar o Órgão do portador do CPGF em todas as movimentações, pois mesmo as sigilosas puderam ter seus Órgãos identificados.

### H - Qual o nome do Órgão cujo código é 20402?

Por uma simples pesquisa no arquivo .csv de Outubro de 2021 (ctrl + F), verifica-se que o nome do Órgão cujo código é 20402 é Agência Espacial Brasileira.

### I - É possível identificar o Nome e Documento (CNPJ) dos favorecidos pela utilização do CPGF?

É possível identificar o Nome e Documento dos favorecidos somente para as movimentações não-sigilosas.

### J – É possível identificar a data e o valor das movimentações financeiras do CPGF, em todas as movimentações? Ou há movimentações onde não é possível identificar as datas e ou valores?

Após inspeção no arquivo .csv de Outubro de 2021, pode-se dizer que a data só é visível em movimentações não-sigilosas. Já o valor pode ser visto para todas as movimentações, incluindo as sigilosas.

### K (código) – Qual a soma total das movimentações utilizando o CPGF?

Resposta: A soma total das transações é de R$5.619.007,95.

### L (código) – Qual a soma das movimentações sigilosas ?

Resposta: A soma das transações de cunho sigiloso é de R$3.108.731,15.

### M (código) – Qual o Órgão que mais realizou movimentações sigilosas no período e qual o valor (somado)?

Resposta: O órgão que mais realizou movimentações sigilosas foi a Presidência da República, com o total de R$1.699.751,04.

### N (código) – Qual o nome do portador que mais realizou saques no período? Qual a soma dos saques realizada por ele? Qual o nome do Órgão desse portador?

Resposta: Portanto, o portador que mais realizou saques foi Rafael Ferreira Costa, com 25 saques no mês de outubro de 2021.

O órgão ao qual o portador Rafael Ferreira Costa pertence é o Instituto Chico Mendes de Conservação da Biodiversidade.

### O (código) – Qual o nome do favorecido que mais recebeu compras realizadas utilizando o CPGF?

O favorecido que mais recebeu compras utilizando o CGPF foi o Mercadopago.com Representações Ltda, com 121 compras no total.

### P - Descreva qual a abordagem utilizada para desenvolver o código para os ítens de K a O.

A solução dos itens K a O foi obtida utilizando-se a linguagem Python com a biblioteca Pandas. A planilha de movimentações financeiras do CGPF de outubro de 2021 foi carregada como dataframe e, utilizando-se os métodos do Pandas, os resultados foram obtidos. Os códigos escritos para a obtenção das respostas dos itens K a O estão disponíveis no arquivo solucoes.ipynb.
