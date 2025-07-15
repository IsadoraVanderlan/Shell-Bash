# Shell-Bash
Bash Shell Commands for Cloud

🗂️ **Comandos de Navegação e Manipulação de Arquivos
| Comando                 | O que faz                        |
| ----------------------- | -------------------------------- |
| `pwd`                   | Mostra o caminho da pasta atual. |
| `ls`                    | Lista os arquivos e pastas.      |
| `cd nome_da_pasta`      | Entra em uma pasta.              |
| `cd ..`                 | Volta uma pasta.                 |
| `cd /`                  | Vai para a raiz do sistema.      |
| `mkdir nome_da_pasta`   | Cria uma nova pasta.             |
| `touch nome_do_arquivo` | Cria um arquivo vazio.           |
| `rm nome_do_arquivo`    | Apaga um arquivo.                |
| `rm -r nome_da_pasta`   | Apaga uma pasta com tudo dentro. |
| `cp origem destino`     | Copia arquivo ou pasta.          |
| `mv origem destino`     | Move ou renomeia.                |


🛠️ Comandos de Visualização e Edição
| Comando                | O que faz                                  |
| ---------------------- | ------------------------------------------ |
| `cat arquivo`          | Mostra o conteúdo todo do arquivo.         |
| `head -n 10 arquivo`   | Mostra as 10 primeiras linhas.             |
| `tail -n 10 arquivo`   | Mostra as 10 últimas linhas.               |
| `nano arquivo`         | Abre o editor de texto básico.             |
| `less arquivo`         | Permite ler o arquivo página por página.   |
| `grep "texto" arquivo` | Procura por um texto dentro de um arquivo. |
| `wc -l arquivo`        | Conta quantas linhas tem.                  |


🧰 Comandos Úteis para Automação e Scripts
| Comando              | O que faz                                |
| -------------------- | ---------------------------------------- |
| `echo "texto"`       | Exibe um texto na tela.                  |
| `echo $VARIAVEL`     | Mostra o valor de uma variável.          |
| `export NOME=valor`  | Cria uma variável de ambiente.           |
| `chmod +x script.sh` | Dá permissão de execução para um script. |
| `./script.sh`        | Executa um script.                       |


🌐 Comandos de Rede (usados para testar conectividade com a AWS e outras redes)
| Comando                | O que faz                                    |
| ---------------------- | -------------------------------------------- |
| `ping google.com`      | Testa conexão com a internet.                |
| `curl url`             | Faz uma requisição HTTP e mostra a resposta. |
| `wget url`             | Baixa arquivos da internet.                  |
| `ifconfig` ou `ip a`   | Mostra as configurações da rede.             |
| `nslookup dominio.com` | Mostra o IP de um domínio.                   |


🔍 Comandos de Busca e Monitoramento
| Comando                | O que faz                                      |
| ---------------------- | ---------------------------------------------- |
| `find . -name "*.log"` | Busca arquivos por nome.                       |
| `ps aux`               | Mostra todos os processos ativos.              |
| `top`                  | Monitora o uso de CPU e memória em tempo real. |
| `df -h`                | Mostra o uso de espaço em disco.               |
| `du -sh pasta`         | Mostra o tamanho da pasta.                     |


🧹 Comandos para Limpeza e Diagnóstico
| Comando   | O que faz                                     |
| --------- | --------------------------------------------- |
| `clear`   | Limpa a tela do terminal.                     |
| `history` | Mostra os últimos comandos usados.            |
| `uptime`  | Mostra há quanto tempo o sistema está ligado. |
| `whoami`  | Mostra o nome do usuário atual.               |
