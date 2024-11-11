# Sistema de Registro de Ponto

## Descrição

O **Sistema de Registro de Ponto** é uma aplicação desenvolvida em Django para o registro e monitoramento de pontos dos colaboradores de uma empresa. O sistema permite que colaboradores efetuem o login, registrem seus pontos, acompanhem justificativas para atrasos e inconsistências, e permite que líderes gerenciem os pontos de seus subordinados.

## Funcionalidades Principais

- **Login Seguro**: Os colaboradores acessam o sistema com autenticação segura para registrar seus pontos.
- **Registro de Ponto com IP e Horário**: O sistema captura o IP da máquina do colaborador, além da data e horário do registro, identificando atrasos e solicitando justificativa quando necessário.
- **Configuração de Tipos de Ponto**: Permite a definição de diferentes tipos de pontos (ex: entrada, saída, intervalo) que podem ser atribuídos aos colaboradores.
- **Gestão de Justificativas**: Colaboradores justificam atrasos e inconsistências que são revisados por seus líderes.
- **Relatórios e Monitoramento**: Líderes podem acessar relatórios detalhados sobre os registros de ponto dos colaboradores, incluindo pontos inconsistentes e justificativas apresentadas.

## Estrutura do Projeto

- **app_ponto**: Aplicação principal com os modelos, formulários, visualizações e templates para o registro e gestão dos pontos.
- **Templates**: Contém as páginas de frontend, incluindo telas de registro de ponto, frequência, relatórios e visualizações para líderes e colaboradores.
- **projeto_ponto**: Configurações principais do projeto Django, como configurações de banco de dados, URLs e autenticação.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/sistema-ponto.git

Acesse o diretório do projeto:

cd sistema-ponto

Instale as dependências:

pip install -r requirements.txt

Execute as migrações do banco de dados:

python manage.py migrate

Inicie o servidor de desenvolvimento:

python manage.py runserver


Acesse o sistema pelo navegador no endereço http://127.0.0.1:8000/.
Realize o login com as credenciais fornecidas pelo administrador.
Use as funcionalidades de registro de ponto, visualização de frequência e relatórios conforme o seu perfil de acesso (colaborador ou líder).

Contribuição
Não aceitamos pulll requests 

