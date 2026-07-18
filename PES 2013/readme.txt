==================================================
   PRO EVOLUTION SOCCER 2013 — COMO INSTALAR
==================================================

Siga os passos abaixo NA ORDEM pra o jogo funcionar
corretamente.

--------------------------------------------------
1) EXTRAIA O JOGO NO LOCAL CERTO
--------------------------------------------------
O arquivo baixado já vem com a pasta da Konami e o
restante das pastas do jogo prontas.

Extraia (ou mova) essa pasta pra:

    C:\Program Files (x86)\

Ao final, o caminho completo deve ficar parecido com:

    C:\Program Files (x86)\KONAMI\...

Não mude o nome das pastas nem extraia em outro lugar
(como Área de Trabalho ou Documentos) — o jogo depende
desse caminho específico pra funcionar.

--------------------------------------------------
2) APLIQUE O ARQUIVO .REG (AJUSTE DE REGISTRO)
--------------------------------------------------
Depois de colocar a pasta do jogo no lugar certo:

  a) Dê dois cliques no arquivo .reg incluso no download
  b) O Windows vai perguntar se você quer adicionar essas
     informações ao Registro — clique em "Sim"
  c) Se aparecer outro aviso de confirmação, clique em
     "Sim" de novo

Isso ajusta uma configuração do Registro do Windows que
o jogo precisa pra reconhecer a instalação corretamente.
Sem esse passo, o jogo não abre ou fecha sozinho.

ARQUIVOS ALTERADOS:
HKEY_LOCAL_MACHINE
└── SOFTWARE
    └── WOW6432Node
        └── KONAMI(ADICIONADO)
            └── PES2013(ADICIONADO)
                ├── code = "E5DW-NHA5-RR9T-DLMH-A6NP"(ADICIONADO)
                ├── installdir = "C:\Program Files (x86)\KONAMI\Pro Evolution Soccer 2013\"(ADICIONADO)
                └── version = "1.00.0000"(ADICIONADO)
NOTA:
O arquivo .reg não altera configurações importantes do sistema, apenas adiciona
arquivos para a leitura correta do jogo para não dar o erro "Pro Evolution Soccer 2013 não está instalado.".
O .reg foi testado no meu próprio computador e tive o mesmo erro sem o arquivo, ele é 100% legítimo mas necessário.
(Sempre analise e questione qualquer arquivo .reg, se instalado um malicioso pode danificar seu sistema.)

O arquivo .reg foi feito pra rodar em sistemas de 64 bits(x64), por enquanto o suporte ao 32 bits(x86) está inexistente e
logo logo tera a compatibilidade

--------------------------------------------------
3) JOGAR
--------------------------------------------------
Depois de extrair a pasta E aplicar o .reg, é só abrir o
executável do jogo normalmente.

--------------------------------------------------
PROBLEMAS COMUNS
--------------------------------------------------
- O jogo não abre → confirme se a pasta está exatamente
  em "C:\Program Files (x86)\" e se você já aplicou o
  arquivo .reg.

- O Windows bloqueou o .reg ou mostrou aviso do
  antivírus → isso é normal para arquivos de registro
  de jogos modificados/repacks. Se você baixou pelo link
  oficial deste site, pode confirmar e continuar.

- Erros de DLL ao abrir → pode ser necessário instalar o
  Visual C++ Redistributable e o DirectX (ambos gratuitos
  no site da Microsoft).

--------------------------------------------------
    ====== TechOfThings - 2026 ======
==================================================
