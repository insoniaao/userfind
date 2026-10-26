USER FINDER PRO MAX

Uma ferramenta de pesquisa de perfis públicos em múltiplas plataformas.

Desenvolvido por INSONIA.

Sobre

O USER FINDER PRO MAX é um projeto em Python executável no Termux e em ambientes compatíveis com Python 3. Ele consulta URLs públicas de perfis e organiza os resultados em relatórios locais.

Plataformas

- Instagram
- TikTok
- YouTube
- Facebook
- Pinterest
- Snapchat

Recursos

- Pesquisa individual e em lote de usernames
- Seleção de plataformas
- Geração de variações de usernames
- Histórico local com SQLite
- Exportação de relatórios em TXT, JSON e CSV
- Abertura de perfis no navegador
- Interface de terminal com cores

Requisitos

- Python 3
- Conexão com a internet

Não são necessárias bibliotecas externas para a versão atual.

Instalação no Termux

pkg update
pkg install python git -y
git clone https://github.com/insoniaao/userfind
cd USER-FINDER
python -m py_compile finder.py
python finder.py



Limitações

Os resultados são baseados em respostas HTTP. Uma página acessível não confirma necessariamente a existência de uma conta, e erros ou bloqueios podem tornar a consulta inconclusiva.

A ferramenta não acessa contas privadas, não tenta obter senhas e não contorna mecanismos de autenticação ou proteção.

Uso responsável

Utilize o projeto para pesquisas legítimas sobre informações públicas. Respeite a privacidade das pessoas, os termos de uso das plataformas e a legislação aplicável.

Desenvolvedor

INSONIA

Projeto educacional e experimental.