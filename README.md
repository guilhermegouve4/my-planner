# Semana do Guilherme - Terminal Edition

## Visão Geral
Este projeto é uma **página web minimalista** e estilizada para simular um terminal de computador, exibindo a rotina semanal de Guilherme. Inspirado na estética _hacker_ e em interfaces de linha de comando, ele oferece uma maneira visualmente interessante de acompanhar uma agenda. A agenda é apresentada em uma tabela, com horários fixos e atividades pré-definidas para cada dia útil da semana. 

## Características Principais
* **Design Terminal-like**: Uma interface com fonte monoespaçada, cores vibrantes em verde neon sobre fundo escuro, e efeitos visuais como _flicker_ e _glitch_ para simular um terminal antigo.
* **Cronograma Semanal**: Uma tabela clara e responsiva exibe a rotina de segunda a sexta-feira, com horários e atividades específicas.
* **Destaque da Tarefa Atual**: O sistema identifica o dia e horário atuais para destacar a tarefa em andamento. Isso é feito com um _radar-pulse_ e um efeito de _text-glitch_, tornando a atividade atual imediatamente visível.
* **Atividades Protegidas**: Algumas atividades, como o "Passeio Marx" (uma provável referência ao pet do Guilherme), são destacadas com um aviso de "Sistema Crítico", indicando sua importância.
* **Atividades Especiais**: As tarefas têm estilos visuais diferenciados para indicar diferentes tipos de atividades:
    * **Atividade `Python`**: Destacada em um tom de verde mais claro.
    * **Atividade `sem telas`**: Destacada em um tom de laranja, incentivando o tempo _offline_.
    * **`Pausa`**: Identificada com um emoji e um estilo mais discreto.
* **Dinâmico e Interativo**: A página atualiza automaticamente a data e o destaque da tarefa a cada minuto.

## Tecnologias Utilizadas
* **HTML**: A estrutura principal da página e o conteúdo da agenda.
* **CSS**: Responsável por toda a estilização, incluindo a paleta de cores, as fontes, a aparência de terminal, os efeitos de animação (`@keyframes`) e a responsividade para diferentes tamanhos de tela.
* **JavaScript**: Adiciona a funcionalidade dinâmica, como:
    * Atualizar a data atual na barra superior.
    * Identificar a tarefa do horário atual e aplicar as classes CSS de destaque.
    * Simular um efeito de digitação na seção de _prompt_ inicial.
    * Gerenciar a atualização da data e do destaque a cada 60 segundos.

## Como Usar
Simplesmente abra o arquivo `index.html` em qualquer navegador web moderno.

Não há necessidade de _backend_ ou de servidor, pois todo o código é executado no lado do cliente. Você pode hospedar a página em um serviço de hospedagem estática, como **GitHub Pages**, ou simplesmente abri-la localmente.