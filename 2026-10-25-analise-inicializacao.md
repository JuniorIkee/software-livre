# Semana 9

De novo, o projeto voltou a apresentar problemas ao iniciar pelo Eclipse. Porém, felizmente após alguns reinicios, clean do projeto, atualização do Maven, etc ... consegui voltar a executar a aplicação.

Na semana tentei uma alteração em `QueryProcessor.java`, relacionada à limpeza do estado antes da execução do script. Quando o bug acontece, posso tentar rodar várias vezez com Alt + x (AX) que não corrige, mas basta uma vez executar com Control + Enter (CE) que as próximas chamadas voltam com a referência correta. A ideia então era aproximar o comportamento do AX ao do CA, colocando um reset() que existia apenas no CE, mas testando vi que essa mudança não corrigia o bug.

Na próxima semana vou continuar a debugar considerando a diferença entre os dois fluxos. A ideia de que uma execução com CE faz as consultas seguintes funcionarem ajudou a entender que devo procurar mais na inicialização que é feita de forma diferente e não necessariamente um metadado deixado para trás.
