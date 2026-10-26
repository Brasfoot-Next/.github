# Brasfoot 2027

O Brasfoot 2027 é a nova geração do clássico gerenciador de futebol que marcou época. O projeto preserva exatamente o que sempre fez o jogo ser viciante — partidas rápidas, simplicidade de navegação e a emoção de levar um time da quarta divisão ao topo do mundo —, mas expande a experiência com sistemas modernos de gestão e uma arquitetura aberta pensada para a comunidade.

---

## O Projeto

A ideia do Brasfoot 2027 nasceu da vontade de jogar o clássico em qualquer lugar, com visual limpo, mecânicas profundas e sem as limitações do passado. O motor de jogo foi refeito do zero com paridade matemática nas regras e fórmulas clássicas, enquanto novas camadas de administração trazem desafios reais para quem quer gerenciar um clube por décadas.

### O que muda na prática

* **Gestão de Clube Completa:** Categorias de base com evolução real de promessas, comissão técnica com impacto direto no elenco, negociação de patrocínios, expansão de estádio setor por setor e finanças detalhadas.
* **Competições e Calendário:** Calendário dinâmico com estaduais completos, copas nacionais, torneios continentais e o Super Mundial de Clubes com 32 equipes a cada quatro temporadas.
* **Mercado Realista:** Janelas de transferências abertas e fechadas, propostas de empréstimo com opção de compra e IA ativa negociando atletas entre si.
* **Jogue Onde Quiser:** Disponível como executável nativo para computador (Linux, Windows e macOS) e também diretamente pelo navegador.
* **Compatibilidade Histórica:** Seus saves antigos não se perdem. O jogo conta com um importador que lê arquivos `.s22` das versões clássicas e migra sua carreira para o formato atual.

---

## Estrutura da Organização

O ecossistema é dividido em dois repositórios complementares:

### [brasfoot-next](https://github.com/Brasfoot-Next/brasfoot-next)
O coração do jogo. É aqui que vive todo o código do aplicativo, incluindo:
* O simulador de partidas minuto a minuto e o resolvedor de táticas.
* A inteligência artificial dos clubes adversários e o ciclo de mercado.
* Toda a interface gráfica, menus e telas de escalação.
* Os sistemas administrativos de base, staff, estádio e finanças.
* O motor de internacionalização com textos traduzíveis em formato aberto.
* A ferramenta de linha de comando para empacotamento e validação de dados.

### [database](https://github.com/Brasfoot-Next/database)
O banco de dados oficial e aberto de futebol. Em vez de arquivos binários fechados, tudo aqui é texto legível (TOML e CSV) que qualquer pessoa consegue abrir no Excel ou Bloco de Notas:
* Mais de 1.200 clubes distribuídos por 132 países.
* Mais de 34.000 jogadores com idades, características e posições revisadas.
* Mais de 30 ligas nacionais configuradas e todos os 27 campeonatos estaduais do Brasil.
* Mais de 1.100 escudos e quase 3.000 camisas catalogadas.
* Coleção de troféus das principais competições do planeta.

---

## Como Tudo se Conecta

O jogo consome o repositório de dados de forma nativa. Ao abrir o Brasfoot 2027, a tela de Patches sincroniza o banco oficial automaticamente.

Se você quiser criar um patch com o elenco atualizado da sua cidade ou com uma nova liga internacional, não precisa alterar os arquivos do jogo: basta criar um repositório no GitHub com os arquivos que deseja modificar. O jogo empilha seu patch por cima do banco oficial pelo próprio link do repositório, mantendo o jogo sempre atualizado e customizável pela própria comunidade.
