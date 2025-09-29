# 🚀 Rocket Filmes - Planilha de Avaliação 🎬
Este projeto consiste em uma planilha de avaliação interativa, desenvolvida em um único arquivo HTML, para facilitar a apuração de notas em um evento de produção de curtas-metragens para o ministério de adolescentes Rocket.

A ferramenta foi criada para ser simples, intuitiva e funcionar offline, permitindo que os jurados insiram suas notas e o resultado seja calculado automaticamente em tempo real!

✨ Funcionalidades
Planilha Interativa: Interface amigável para inserção de notas.

Abas Dinâmicas: Abas personalizadas com o nome de cada jurado.

Cálculo Automático: A pontuação total de cada equipe é atualizada instantaneamente a cada nota inserida.

Apuração em Tempo Real: Uma aba de "Resultado Final" consolida as notas e destaca a equipe vencedora.

Totalmente Offline: Após carregado, o arquivo não necessita de conexão com a internet.

Responsivo: Funciona perfeitamente em computadores, tablets e celulares.

Zero Dependências: Não requer instalação de softwares ou servidores. Basta abrir o arquivo .html em qualquer navegador.

🛠️ Como Utilizar
Baixe o arquivo: Faça o download do arquivo avaliacao_rocket_filmes.html.

Abra no Navegador: Abra o arquivo em qualquer navegador de internet moderno (Google Chrome, Firefox, Safari, Edge, etc.).

Preencha as Notas:

Clique na aba com o nome de cada jurado.

Insira as notas para cada critério e para cada equipe.

Visualize o Resultado:

Clique na aba "🏆 Resultado Final" para ver a soma de todas as notas e descobrir a equipe campeã.

🔧 Como Personalizar
A planilha foi construída para ser facilmente adaptável. Para modificar os jurados, critérios ou número de equipes, basta editar o arquivo avaliacao_rocket_filmes.html e alterar as constantes no início da tag <script>:

<script>
    // Altere os nomes e a quantidade de jurados aqui
    const JURADOS = ["Nicolas", "Livia", "Adyel", "Natalia", "Niccoly", "Bianca", "Caio"];

    // Altere o número de equipes
    const NUM_EQUIPES = 3;

    // Adicione ou remova critérios de avaliação
    const CRITERIOS = [
        "Mensagem transmitida",
        "Todos do grupo aparecerem*", // O asterisco (*) indica que a nota é 0 ou 10
        "Criatividade",
        "Nome e capa do filme",
        "Trilha sonora",
        "Conexão da equipe",
        "Edição do vídeo"
    ];

    // ... o resto do código ...
</script>

💻 Tecnologias Utilizadas
HTML5

Tailwind CSS (via CDN para estilização rápida)

JavaScript (Vanilla) (para toda a interatividade e cálculos)

Desenvolvido com ❤️ para o Ministério Rocket.
