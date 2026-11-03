# Semana 7

Nesta semana, fiquei alterando partes do código para tentar entender como era o funcionamento de geração dos ícones de encaminhamento para o registro da tabela estrangeira.

Porém, chegou um momento que a aplicação parou de rodar, mesmo eu voltando as alterações. A primeiro momento ela carregava infinitamente quando colocara para rodar, depois de tentar atualizar as dependências passou a dar um erro estranho que nem com auxilio da IA consegui corrigir.

No final das contas, precisei excluir o projeto e começar a configuração do zero novamente.

Aproveitei durante a configuração do ambiente para usar usar o Eclipse 2026-09 no lugar do Eclipse 2025-06 e também comecei a rodar o projeto com o Java 21. Vi pelo pom da dbeaver-common que estas eram as configurações certas do projeto. Acabou que com essa alteração tive que rever as configurações da IDE e as dependências antes de voltar a trabalhar no código.

Essa correção acabou que demandou bastante tempo, pois cada build levava vários minitos e tive que fazer vários até desistir do projeto anterior e durante a configuração do novo.

Com o ambiente refeito, espero na próxima semana voltar a investigar o bug e tentar alterar o código sem quebrar a aplicação.
