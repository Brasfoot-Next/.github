<p align="center">
  <img src="profile/logo.png" width="160" alt="Brasfoot 2027" />
</p>

# Brasfoot 2027

O Brasfoot 2027 é a evolução do clássico gerenciador de futebol. O objetivo é manter a dinâmica viciante de sempre, com partidas rápidas e progressão direta de temporadas, trazendo recursos modernos de gestão e dados abertos para toda a comunidade.

## O Projeto

O projeto recria o jogo com paridade matemática nas fórmulas clássicas e adiciona sistemas que trazem desafios reais para quem quer comandar um clube a longo prazo.

### O que muda no jogo

* **Gestão de Clube Completa:** Categorias de base com evolução real de promessas, comissão técnica com impacto no elenco, negociação de patrocínios, ampliação de estádio setor por setor e finanças detalhadas.
* **Competições e Calendário:** Calendário com estaduais completos, copas nacionais, torneios continentais e o Super Mundial de Clubes com 32 equipes a cada quatro temporadas.
* **Mercado Realista:** Janelas de transferências abertas e fechadas, propostas de empréstimo com opção de compra e inteligência artificial ativa negociando atletas.
* **Disponibilidade:** Versão nativa para computador em Linux, Windows e macOS, além de rodar direto pelo navegador.
* **Compatibilidade Histórica:** Os saves clássicos continuam utilizáveis. O importador integrado lê arquivos com extensão s22 e converte sua carreira para a nova versão.

## Repositórios

O ecossistema é dividido em dois repositórios complementares:

### [brasfoot-next](https://github.com/Brasfoot-Next/brasfoot-next)
O aplicativo e motor do jogo. Contém todo o código da interface visual, simulação de partidas minuto a minuto, inteligência artificial de transferências, sistemas de gestão de clube e leitor de saves.

### [database](https://github.com/Brasfoot-Next/database)
O banco de dados oficial e aberto de futebol. Todos os dados são organizados em formatos simples de texto legíveis em planilhas ou editores comuns:
* Mais de 1200 clubes em 132 países.
* Mais de 34000 jogadores com atributos revisados.
* Ligas nacionais e todos os 27 campeonatos estaduais do Brasil.
* Mais de 1100 escudos e quase 3000 uniformes catalogados.
* Galeria de troféus das principais competições.

## Integração e Patches

O jogo consome este banco de dados de maneira nativa. Na inicialização, a tela de Patches sincroniza o conteúdo oficial automaticamente.

Qualquer pessoa pode criar seu próprio patch com novos elencos ou ligas customizadas. Basta criar um repositório no GitHub com os arquivos alterados e colar o link na tela de Patches do jogo. O sistema empilha as modificações por cima do banco oficial sem necessidade de instalar arquivos manualmente.
