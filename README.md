# HabitFlow básico

Uma versão simples, em uma única página e com três arquivos de código:

- `index.html`: os textos, o formulário e a lista.
- `style.css`: as cores, os espaçamentos e a adaptação para celular.
- `script.js`: as funções e o salvamento no navegador.

## O que você pode fazer

- Adicionar hábitos com nome, categoria, frequência e meta.
- Editar e excluir hábitos.
- Marcar e desmarcar a conclusão de um hábito.
- Consultar registros anteriores pelo campo de data, que abre o calendário do navegador.
- Filtrar hábitos pendentes e concluídos.
- Ver barras com porcentagens do dia selecionado, da semana atual e do mês atual.
- Acompanhar a sequência atual de realizações.
- Alternar entre tema claro e escuro.

O site começa vazio. Cadastre seu primeiro hábito para experimentar.

Se deixar a página aberta de um dia para o outro, recarregue-a para atualizar a data de hoje.

## Como os registros funcionam

A meta é um texto, como “Beber 8 copos de água”. Marcar o hábito significa que você cumpriu essa meta naquele dia. Não há contador separado de copos, páginas ou minutos.

A frequência pode ser todos os dias, segunda a sexta ou sábado e domingo. O campo de data mostra os hábitos a partir da data de criação. Atividades fora da programação aparecem com a caixa de conclusão desabilitada, mas podem ser editadas ou excluídas. Não é possível marcar datas futuras.

As sequências contam realizações em dias programados. Dias de folga não interrompem a sequência. Um hábito ainda pendente hoje mantém a sequência anterior enquanto o dia não termina.

Se você editar a frequência, a lista e os cálculos do histórico passam a usar a frequência atual. As datas já marcadas continuam guardadas no hábito. Excluir um hábito remove também seus registros.

Os dados ficam no **localStorage** do navegador. Não há conta, servidor ou sincronização. Limpar os dados do navegador pode apagar seus hábitos. Para manter um endereço de armazenamento consistente durante o desenvolvimento, você pode usar o Live Server.