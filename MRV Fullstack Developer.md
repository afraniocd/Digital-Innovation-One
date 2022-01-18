


# Bootcamp MRV Fullstack Developer

## Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

Linkedin: falvojr

Passo-a-passo:
1. Acessar o GitHub na web.
2. Criar um novo repositório.
3. Rodar o GitBash na pasta local.
4. Clonar o GitHub para a máquina local: git clone (colar o link do repositório disponível no GitHub)
5. Verificar status: git status
6. Inserir uma pasta ou arquivo novo na máquina local;
7. git status
8. Enviar arquivos para o GitHub: git add .
9. Verificar se foram adicionados: git status
10. Comitar: git commit -m “Comentário do commit, p.e., Descrição do versionamento”
11. Dar um push para enviar para a nuvem: git push origin main



## Introdução ao Git e ao GitHub (Otávio Reis)
- GIT: repositório online de armazenamento da versão (versionamento) de código; é open source;
- GitHub: é da Microsoft;
- Git é diferente de GitHub;
- Benefícios de aprender ambas tecnologias: 

Navegação via command line interface e instalação
Comandas básicos para um bom desempenho no terminal:
- GUI (graphic user interface) x CLI (command line interface);
- O GIT é por CLI;

dir: lista de diretórios e pastas
cd (change directory): navegar entre os diretórios;
cd..: retroceder um nível;
control l (clear screen): limpar a tela de comando;
tecla tab: função auto completar;
mkdir: criar um diretório ou pasta;
del: deleta arquivo
rmdir: deleta pasta

Realizando a instalação do Git:
- instalação no windows
- Linux
- MacOs (instalado): https://brew.sh/; https://git-scm.com/download/mac


Entendendo como o GIT funciona por baixo dos panos:

SHA: algoritmo de encriptação

O instrutor fez uma demonstração de encriptografia com o gitbash de um arquivo de texto mas não consegui pelo Mac.
Consegui obter uma SHA1 com o comando abaixo mas ainda não sei onde está este arquivo.

chave SHA1: fc31e91b26cf85a55e072476de7f263c89260eb1

Vou mudar para o Windows para continuar o curso. Deu certo!

Objetos Internos do GIT


- Blobs (bolha): contém metadados do Git. Não guarda o nome do arquivo. Contém a SHA1;
- Tree: armazena as blobs: contém também metadados; e guarda o nome do arquivo; contém seu próprio SHA1. Uma árvore pode apontar para outras árvores (tree)
- Commit: irá juntar tudo. Aponta para uma tree; para um parente; para um autor; para uma mensagem e timestamp (carimbo da data e hora que foi criado). Tb possui SHA1 próprio.
- Assim o Git é um sistema distribuído e seguro;



Chaves SSH e Tokens GITHUB
- Chave SSH: comunicação segura entre 2 máquinas; duas chaves, uma pública e outra privada.
- Tokens: token de acesso pessoal. Tem que ficar colocando usuário e senha diferentemente da SSH.


Iniciando o Git e criando um commit

ls -a: ver pastas ocultas;

- Markdown (md): forma mais humana de se escrever um arquivo html.


Passo a passo no ciclo de vida:
- GIT INIT: inicializa um repositório git na pasta em questão;
- Tracked ou Untracked: 

Staged: arquivos em preparação

Git add: move o arquivo direto para o staged.

Arquivos Unmodified: arquivo está no repositório e ainda não sofreu modificação.

É um Ciclo unmodified —> modified —> stage.



O qué os repositórios significam?
Ambientes: 2 tipos
- GitHub é o remote repository.

git status: ajuda a verificar os status dos arquivos
mv: mover
git add *: pega tudo dentro do diretório de trabalho e adiciona para o stage para comutar.

Próxima Aula será sobre Remote Repository: GitHub
Trabalhando com o GitHub
- Como empurrar uma pasta para o GitHub


Como os conflitos acontecem no GitHub e como resolvê-los
- Conflitos de versão, merge
- git pull
- git clone


## Aprenda o que são Estrutura de Dados e Algoritmos (prof. Bruno Campos Dias)
1. Introdução e objetivos: sem conteúdo.
2. O que é Estrutura de dados: Usou o portugol para exemplificar.
    1. Definição:
￼
￼

Algoritmo:

1. Vetores e Matrizes (Arrays):

- A primeira posição é o ZERO (0).

Matriz 4:3
- Temos 1 vetor de 3 posições e 1 vetor de 4 posições.

O que são registros:


## Listas, Pilhas e Filas:
PILHAS (STACK): EMPILHAMENTO

FILAS:

ESTRUTURAS DE DADOS: ÁRVORE, TABELA HASH e GRAFOS

ÁRVORE:

Na computação esta estrutura é representada de forma inversa.

TABELA HASH OU TABELA DE ESPALHAMENTO

GRAFOS


## Introdução ao Portugol:
1. Estrutura de Repetição:
    1. Executar mais de uma vez
2. Linguagens de Programação (Portugol):
    1. Pseudocódigos na prática
    2. Linguagem de programação (LP):
        1. Alto nível: se aproxima mais da nossa linguagem
        2. Baixo nível: próxima da máquina
        3. Compiladas: C#, C++, delphi
        4. Interpretadas: java script; php, phyton: roda geralmente no browse
    3. Portugal: mais básico.
3. Aprenda a utilizar desvios condicionais e boas práticas em programação:
    1. Estruturas de decisão (Portugol):
        1. se: 
        2. se-nao
    2. Comentários no código
    3. Desvio condicional - caso
4. Trabalhando com laços de repetição em Portugol
    1. Executar mais de uma vez um comando dentro de uma condição ou com um contador.
5. Aplicação prática com matrizes e vetores:
    1. Matriz: coleção de variáveis de mesmo tipo. acessíveis com um único nome e armazenados contiguamente na memória; por exemplo, ou é cadeia ou é inteiro.
    2. Índices: forma de realizar a individualização de cada variável de um vetor;
    3. Vetores: são matrizes de uma só dimensão; por exemplo, só colunas.
