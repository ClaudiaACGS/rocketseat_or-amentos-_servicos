# rocketseat_or-amentos-_servicos

Neste desafio, iremos criar um projeto para gerar orçamentos simples com itens, quantidades e desconto, com status do ciclo de vendas.

Instruções
Estrutura, regras e requisitos do projeto

1. Estrutura inicial
Objetivo: Criar um novo projeto usando oque foi aprendido nos primeiros módulos, focando nos fundamentos e na navegação

2. Funcionalidades de orçamento
Objetivo: Criar funcionalidades para a gestão de orçamentos.

Funcionalidade para criar um novo orçamento, com informações como título, cliente, status e serviços inclusos.
É possível adicionar novos serviços a um orçamento, com quantidades diferentes. 
É possível filtrar orçamentos por status diferentes, e por ordenações diferentes.
É possível duplicar um orçamento, assim como o cálculo local de subtotal, desconto e total.
3. Modelo de cada orçamento
Objetivo: Cada orçamento deve ter o seguinte formato:

QuoteDoc: { id: Identificador único, client: Nome do cliente, title: Título do serviço, items: uma lista de itens o tipo está abaixo, discountPct: Valor do desconto, opcional, caso haja, status: Rascunho, Enviado, Aprovado ou Recusado, createdAt: Data de criação, updatedAt: Data quando foi atualizado pela última vez }
Item: { id: Identificador único, description: Descrição do serviço, qty: Quantidade de vezes que o serviço foi realizado, price: Preço do serviço }
4. Telas e componentes
Objetivo: Ter telas acessíveis e intuitivas para os usuários

Criar uma tela para mostrar os orçamentos e permitir filtragens.
Possibilitar que o usuário duplique, altere o status ou remova um orçamento após a confirmação.
5. Persistência dos dados
Objetivo: Permitir os dados no celular do usuário, de forma que possam ser acessados depois usando async storage.

Os orçamentos devem ser salvos no celular.
Os filtros selecionados devem ser salvos no celular. 
6. Interface (baseada no layout do Figma)
O layout deve ser feito com base no Figma do projeto. Após ele ser finalizado, se sinta livre para publica-lo e realizar alterações, mas para o desenvolvimento do desafio, se atenha ao que temos especificado no Figma.

7. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais ferramentas que utilizamos durante a formação até aqui.

Caso você tenha alguma dificuldade você pode ir no nosso 
fórum
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além 🚀

Exemplos de novas funcionalidades
Algumas opções válidas para novas funcionalidades seriam:

Temas de PDF
Logo customizados no PDF a depender do cliente ou prestador de serviço
Compartilhamento do orçamento em PDF ou mensagem
Histórico ilimitado
8. Entrega
Lembre-se que o intuito de um desafio é te impulsionar, por isso, dependendo do desafio, pode ser que você precise ir além do que foi discutido em sala de aula. Mas isso não é algo ruim: ter autonomia para buscar informações extras é uma habilidade muito valiosa e vai ser ótimo pra você treinar ela aqui com a gente!

E lembre-se: tenha calma! Enfrentar desafios faz parte do seu processo de aprendizado!

Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência?

É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

Feito com 💜 por Rocketseat 👋
