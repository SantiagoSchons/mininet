mininet-debian
Mininet 2.3.0 – Instalação compatível com Debian 12 (modo CLI)
Este repositório contém uma versão levemente modificada do Mininet 2.3.0, com pequenas alterações nos arquivos Makefile e install.sh para corrigir problemas de instalação e compatibilidade ao rodar em ambientes mais recentes.

🔍 Observações importantes:

Testado exclusivamente no Debian 12.

Funciona apenas no modo CLI (interface de linha de comando) — a interface gráfica (GUI) não funciona com essa configuração.

A base original do projeto foi mantida, com foco apenas na correção de erros para viabilizar o uso básico.

Principais mudanças:

Ajustes no Makefile para corrigir erros de compilação.

Modificações no install.sh para tratar dependências ausentes ou versões incompatíveis.

Nota: Caso esteja utilizando outra distribuição ou precise da GUI, esta versão não é recomendada.
