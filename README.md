# Shell-Bash
Bash Shell Commands for Cloud

<br>

🧠**Atalhos de teclado no terminal nano (editor de texto no terminal) (Bash)**
| Atalho            | O que faz                                            |
| ----------------- | ---------------------------------------------------- |
| Ir para o início da linha         | `Ctrl + A`                                 |
| Ir para o fim da linha            | `Ctrl + E`                                 |
| Apagar caractere (como backspace) | `Backspace`                                |
| Apagar linha inteira              | ❌ (não tem atalho direto nativo)           |
| Apagar palavra anterior           | ❌ (sem atalho por padrão)                  |
| Sair do `nano`                    | `Ctrl + X`                                 |
| Salvar (gravar) o arquivo         | `Ctrl + O`, depois `Enter`                 |
| Cancelar sem salvar               | `Ctrl + X`, depois `N`                     |
| Cortar linhas superiores inteira              | `Ctrl + K` *(funciona!)*                   |
| Colar linha                       | `Ctrl + U` *(se você usou o Ctrl+K antes)* |



<br>

🛠️**Sumario**
| Comando | Significado literal (em inglês) | Tradução / Função                             |
| ------- | ------------------------------- | --------------------------------------------- |
| `mkdir` | **make directory**              | criar diretório (pasta)                       |
| `ls`    | **list**                        | listar arquivos e pastas                      |
| `cd`    | **change directory**            | mudar de diretório (entrar em pasta)          |
| `pwd`   | **print working directory**     | mostrar o caminho da pasta atual              |
| `rm`    | **remove**                      | remover (deletar) arquivo                     |
| `rmdir` | **remove directory**            | remover diretório (pasta)                     |
| `cp`    | **copy**                        | copiar arquivo ou pasta                       |
| `mv`    | **move**                        | mover ou renomear arquivo/pasta               |
| `touch` | (não é abreviação)              | cria um novo arquivo vazio (ou atualiza data) |
| `cat`   | **concatenate**                 | juntar e mostrar o conteúdo de arquivos       |
| `nano`  | nome do editor de texto         | editor simples de arquivos no terminal        |
| `clear` | **clear screen**                | limpar a tela                                 |
| `exit`  | **exit**                        | sair do terminal ou sessão                    |

<br>

🗂️ **Comandos de Navegação e Manipulação de Arquivos**
| Comando                 | O que faz                        |
| ----------------------- | -------------------------------- |
| `pwd`                   | Mostra o caminho da pasta atual. |
| `ls`                    | Lista os arquivos e pastas.      |
| `ls -la`                    | Lista os arquivos e pastas completo.      |
| `ls`                    | Lista os arquivos e pastas.      |
| `cd nome_da_pasta`      | Entra em uma pasta.              |
| `cd `                 | Volta uma pasta.                 |
| `cd /`                  | Vai para a raiz do sistema.      |
| `mkdir nome_da_pasta`   | Cria uma nova pasta.             |
| `touch nome_do_arquivo` | Cria um arquivo vazio.           |
| `rm nome_do_arquivo`    | Apaga um arquivo.                |
| `rm -r nome_da_pasta`   | Apaga uma pasta com tudo dentro. |
| `cp nome_origem nome_destino`     | Copia arquivo.          |
| `cp nome_origem nome_destino`  | Copia pasta.          |
| `mv ~/caminho_origem/caminho_origem ~/nome_destino/`     | Move de pasta.                |
| `mv nome_antigo novo_nome`     | Renomeia.                |
| `wget -P ju https://site.com/arquivo.txt`     | colocar arquivo direto da web dentro da pasta               |


<br>

🛠️ **Comandos de Visualização e Edição**
| Comando                | O que faz                                  |
| ---------------------- | ------------------------------------------ |
| `cat arquivo`          | Mostra o conteúdo todo do arquivo.         |
| `head -n 10 arquivo`   | Mostra as 10 primeiras linhas.             |
| `tail -n 10 arquivo`   | Mostra as 10 últimas linhas.               |
| `nano arquivo`         | Abre o editor de texto básico.             |
| `less arquivo`         | Permite ler o arquivo página por página.   |
| `grep "texto" arquivo` | Procura por um texto dentro de um arquivo. |
| `wc -l arquivo`        | Conta quantas linhas tem.                  |

<br>


🧰 **Comandos Úteis para Automação e Scripts**
| Comando              | O que faz                                |
| -------------------- | ---------------------------------------- |
| `echo "texto"`       | Exibe um texto na tela.                  |
| `echo $VARIAVEL`     | Mostra o valor de uma variável.          |
| `export NOME=valor`  | Cria uma variável de ambiente.           |
| `nome_variavel= "conteudo variavel"`  | cria dentro do arquivo a variavel.           |
| `chmod +x script.sh` | Dá permissão de execução para um script. |
| `./script.sh`        | Executa um script.                       |


<br>

🌐 **Comandos de Rede (usados para testar conectividade com a AWS e outras redes)**
| Comando                | O que faz                                    |
| ---------------------- | -------------------------------------------- |
| `ping google.com`      | Testa conexão com a internet.                |
| `curl url`             | Faz uma requisição HTTP e mostra a resposta. |
| `wget url`             | Baixa arquivos da internet.                  |
| `ifconfig` ou `ip a`   | Mostra as configurações da rede.             |
| `nslookup dominio.com` | Mostra o IP de um domínio.                   |


<br>

🔍 **Comandos de Busca e Monitoramento**
| Comando                | O que faz                                      |
| ---------------------- | ---------------------------------------------- |
| `find . -name "*.log"` | Busca arquivos por nome.                       |
| `ps aux`               | Mostra todos os processos ativos.              |
| `top`                  | Monitora o uso de CPU e memória em tempo real. |
| `df -h`                | Mostra o uso de espaço em disco.               |
| `du -sh pasta`         | Mostra o tamanho da pasta.                     |


<br>

🧹 **Comandos para Limpeza e Diagnóstico**
| Comando   | O que faz                                     |
| --------- | --------------------------------------------- |
| `clear`   | Limpa a tela do terminal.                     |
| `history` | Mostra os últimos comandos usados.            |
| `uptime`  | Mostra há quanto tempo o sistema está ligado. |
| `whoami`  | Mostra o nome do usuário atual.               |

<br>

🧹 **Para AWS**=
Instale o nano: sudo yum install nano
| Comando   | O que faz                                     |
| --------- | --------------------------------------------- |
| `nano nome_script.sh`   | Cria um arquivo .sh - enter para abrir o arquivo - contrl x para salvar - y para sair.                     |
| `ls "|" grep palavra_procurada` | Mostra todos arquivos que contenham essa palavra.            |
| `sudo su`  | Para rodar tudo como rute. |
| `exit`  | Para voltar ao usuário comum.               |
