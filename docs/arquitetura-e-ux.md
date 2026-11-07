# Arquitetura e UX

A Tech Polis é uma experiência estática isolada da aplicação do mapa. A entrada no mapa leva a `/tech-polis/`, e “Voltar à Bomba Land” retorna à raiz. O isolamento preserva os estados e a navegação da cidade e permite testar a experiência separadamente.

Na Tech Polis, o ambiente ativo determina o cenário, a legenda e os hotspots. Os painéis abrem o conteúdo sem navegar para outra página. O Tarot mantém no navegador o estado da tiragem e o reinicia ao embaralhar; a interação não depende de um backend. O Spotify é um destino externo.

As composições para desktop e telas menores usam enquadramentos próprios onde necessário. Em telas menores, os painéis entram no fluxo vertical para preservar a leitura e o alcance dos controles. A ficha de créditos é expansível. O retorno de foco ao fechar o painel musical foi verificado nos smoke tests.

A capa de Tech Polis II é compartilhada com o Record Wall. O título acessível e o link do álbum vêm da identificação editorial, independentemente do texto impresso na capa.
