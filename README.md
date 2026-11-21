# Cruzadinha de Arquitetura Computacional

Jogo de palavras cruzadas desenvolvido para a disciplina de **Arquitetura Computacional**, da **São Paulo Tech School (SPTech)**. O objetivo é revisar conceitos estudados em aula por meio de pistas sobre processadores, memórias e barramentos.

## Como jogar

1. Leia as pistas divididas em **Horizontais** e **Verticais**.
2. Clique em uma pista ou em uma casa do tabuleiro para selecionar a palavra.
3. Digite uma letra por casa. O cursor avança automaticamente para a próxima casa da palavra selecionada.
4. Clique em **Conferir** para identificar as palavras corretas e incorretas e visualizar o contador de acertos.
5. Clique em **Reiniciar** para limpar o tabuleiro e começar novamente.

As respostas são digitadas **sem espaços e sem acentos**. A numeração pode se repetir quando duas palavras começam na mesma casa.

## Palavras e pistas

O tabuleiro utiliza **12 palavras** da lista fornecida na atividade.

### Horizontais

| Nº | Palavra | Pista |
|---|---|---|
| 4 | DMA | Recurso que transfere dados entre dispositivos e memória sem ocupar o processador a cada byte. |
| 5 | REGISTRADORES | Pequenas memórias internas que armazenam valores temporários durante a execução das instruções. |
| 7 | RAM | Memória volátil usada para armazenar programas em execução e suas variáveis. |
| 8 | CACHE | Memória rápida que guarda cópias de dados recentemente utilizados pelo processador. |
| 10 | ULA | Parte do processador que realiza cálculos e operações lógicas. |
| 11 | CPU | Componente responsável por buscar e executar as instruções de um programa. |

### Verticais

| Nº | Palavra | Pista |
|---|---|---|
| 1 | ADDRESSBUS | Conjunto de linhas que identifica a posição de memória desejada pelo processador. |
| 2 | EEPROM | Memória não volátil que preserva configurações e permite regravações no microcontrolador. |
| 3 | FLASH | Tecnologia de armazenamento regravável que mantém programas mesmo sem energia. |
| 6 | DATABUS | Conjunto de linhas que transporta valores e instruções entre os componentes. |
| 7 | ROM | Memória não volátil tradicionalmente destinada a informações de inicialização do equipamento. |
| 9 | UC | Parte do processador que interpreta as instruções e coordena as operações. |

## Tecnologias utilizadas

- **HTML:** estrutura da página, pistas e controles.
- **CSS:** aparência do tabuleiro, casas e botões.
- **JavaScript:** montagem do tabuleiro, navegação entre casas, conferência e reinício.

O projeto utiliza HTML, CSS e JavaScript puros, sem frameworks. Na versão atual, o CSS e o JavaScript estão incluídos no arquivo `index.html`.

## Executar localmente

Abra o arquivo `index.html` em um navegador. Não é necessário instalar dependências.
