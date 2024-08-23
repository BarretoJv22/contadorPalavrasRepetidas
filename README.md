# contadorPalavrasRepetidas

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Análise de Palavras Repetidas</title>
</head>
<body>
    <h1>Análise de Palavras Repetidas</h1>
    <p>Este é um programa em JavaScript que analisa arquivos de texto (.txt) e gera um novo arquivo .txt contendo as palavras repetidas encontradas nos parágrafos do arquivo original. O usuário pode especificar o caminho de saída para o arquivo resultante através do terminal.</p>

    <h2>Funcionalidades</h2>
    <ul>
        <li>Lê arquivos .txt fornecidos pelo usuário através do terminal.</li>
        <li>Identifica e lista palavras repetidas em parágrafos do arquivo de entrada.</li>
        <li>Gera um arquivo .txt contendo o resultado e o salva em um diretório especificado pelo usuário.</li>
    </ul>

    <h2>Pré-requisitos</h2>
    <p>Antes de começar, certifique-se de ter o seguinte instalado em sua máquina:</p>
    <ul>
        <li>Node.js</li>
        <li>NPM (Node Package Manager)</li>
    </ul>

    <h2>Instalação</h2>
    <p>Siga os passos abaixo para instalar o programa:</p>
    <pre><code>
# Clone este repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Navegue até o diretório do projeto
cd seu-repositorio

# Instale as dependências
npm install
    </code></pre>

    <h2>Como Usar</h2>
    <p>Para usar o programa, execute o comando abaixo no terminal:</p>
    <pre><code>
node index.js caminho/do/arquivo/entrada.txt caminho/para/saida
    </code></pre>
    <p>Substitua <code>caminho/do/arquivo/entrada.txt</code> pelo caminho do arquivo de entrada e <code>caminho/para/saida</code> pelo diretório onde deseja salvar o arquivo de saída.</p>

    <h3>Exemplo</h3>
    <pre><code>
node index.js ./meus_arquivos/texto.txt ./meus_resultados/
    </code></pre>
</body>
</html>
