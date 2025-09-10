# Semana do Guilherme - Terminal Edition

## Vis�o Geral
Este projeto � uma **p�gina web minimalista** e estilizada para simular um terminal de computador, exibindo a rotina semanal de Guilherme. Inspirado na est�tica _hacker_ e em interfaces de linha de comando, ele oferece uma maneira visualmente interessante de acompanhar uma agenda. A agenda � apresentada em uma tabela, com hor�rios fixos e atividades pr�-definidas para cada dia �til da semana. 

## Caracter�sticas Principais
* **Design Terminal-like**: Uma interface com fonte monoespa�ada, cores vibrantes em verde neon sobre fundo escuro, e efeitos visuais como _flicker_ e _glitch_ para simular um terminal antigo.
* **Cronograma Semanal**: Uma tabela clara e responsiva exibe a rotina de segunda a sexta-feira, com hor�rios e atividades espec�ficas.
* **Destaque da Tarefa Atual**: O sistema identifica o dia e hor�rio atuais para destacar a tarefa em andamento. Isso � feito com um _radar-pulse_ e um efeito de _text-glitch_, tornando a atividade atual imediatamente vis�vel.
* **Atividades Protegidas**: Algumas atividades, como o "Passeio Marx" (uma prov�vel refer�ncia ao pet do Guilherme), s�o destacadas com um aviso de "Sistema Cr�tico", indicando sua import�ncia.
* **Atividades Especiais**: As tarefas t�m estilos visuais diferenciados para indicar diferentes tipos de atividades:
    * **Atividade `Python`**: Destacada em um tom de verde mais claro.
    * **Atividade `sem telas`**: Destacada em um tom de laranja, incentivando o tempo _offline_.
    * **`Pausa`**: Identificada com um emoji e um estilo mais discreto.
* **Din�mico e Interativo**: A p�gina atualiza automaticamente a data e o destaque da tarefa a cada minuto.

## Tecnologias Utilizadas
* **HTML**: A estrutura principal da p�gina e o conte�do da agenda.
* **CSS**: Respons�vel por toda a estiliza��o, incluindo a paleta de cores, as fontes, a apar�ncia de terminal, os efeitos de anima��o (`@keyframes`) e a responsividade para diferentes tamanhos de tela.
* **JavaScript**: Adiciona a funcionalidade din�mica, como:
    * Atualizar a data atual na barra superior.
    * Identificar a tarefa do hor�rio atual e aplicar as classes CSS de destaque.
    * Simular um efeito de digita��o na se��o de _prompt_ inicial.
    * Gerenciar a atualiza��o da data e do destaque a cada 60 segundos.

## Como Usar
Simplesmente abra o arquivo `index.html` em qualquer navegador web moderno.

N�o h� necessidade de _backend_ ou de servidor, pois todo o c�digo � executado no lado do cliente. Voc� pode hospedar a p�gina em um servi�o de hospedagem est�tica, como **GitHub Pages**, ou simplesmente abri-la localmente.