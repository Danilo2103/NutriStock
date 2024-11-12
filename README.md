# 🥗 NutriStock - Sistema de Gestão de Estoque Nutricional

<p align="center">
  <img src="/static/images/logo/logo_transparente.png" alt="NutriStock Logo" width="200"/>
</p>

## 📑 Índice
- [Sobre](#-sobre)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Requisitos](#-requisitos)
- [Instalação](#-instalação)
- [Download do Projeto](#-download-do-projeto)
- [Configuração do Banco de Dados](#️-configuração-do-banco-de-dados)
- [Execução da API e do Frontend](#-execução-da-api-e-do-frontend)
- [Contribuição](#-contribuição)
- [FAQ](#-faq)
- [Licença](#-licença)
- [Contato](#-contato)

## 📋 Sobre

NutriStock é um sistema de gestão de estoque desenvolvido especificamente para profissionais da área de nutrição. O sistema permite o controle eficiente de produtos alimentícios, monitoramento de validade, gestão de inventário e geração de relatórios detalhados.

## ⭐ Funcionalidades

### Principais
- Cadastro e gestão de produtos
- Controle de estoque
- Monitoramento de validade
- Gestão de fornecedores
- Relatórios personalizados
- Dashboard interativo

### Recursos Adicionais
- Sistema de alertas
- Backup automático
- Controle de acesso por níveis
- Histórico de movimentações
- Exportação de dados

## 🛠 Tecnologias

- Python
- Flask
- SQLite/SQLAlchemy
- HTML5/CSS3
- JavaScript
- Bootstrap 5
- TailwindCSS

## 💻 Requisitos

Certifique-se de ter o Python, pip e o git instalados em seu sistema.

## 📦 Instalação

### Dependências

```bash
pip install -r requirements.txt
```

## 📥 Download do Projeto

Primeiro, com o git instalado, você pode clonar o projeto com o seguinte comando:

```bash
git clone https://github.com/Danilo2103/NutriStock.git
```

## 🗒️ Configuração do Banco de Dados
Navegue até a pasta api e execute os seguintes comandos:

```bash
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
```

## 🚀 Execução da API e do Frontend
1. Com o banco de dados configurado, execute a API:

```bash
cd api
python app.py
```

2. Com a API em execução, abra um novo terminal, navegue até a pasta raiz e execute o frontend:

```bash
python app.py
```

## 👥 Contribuição

### Fork o projeto

Crie sua Feature Branch (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add some AmazingFeature')
Push para a Branch (git push origin feature/AmazingFeature)
Abra um Pull Request
Diretrizes de Contribuição
Siga o estilo de código PEP 8
Adicione testes para novas funcionalidades
Atualize a documentação conforme necessário
Mantenha o código limpo e bem documentado

## ❓ FAQ
P: Como redefinir minha senha? R: Acesse a página de login e clique em "Esqueci minha senha".

P: O sistema funciona offline? R: Não, é necessário conexão com internet.

## 📜 Licença
Este projeto está licenciado sob a Licença da Uninassau - consulte o arquivo [LICENSE](LICENSE.md) para obter detalhes.

## 📞 Contato
NutriStock - @twitter.com/@nutristock - contact@nutristock.com

## 👨‍💻 Repositório
- GitHub: [NutriStock](https://github.com/Danilo2103/NutriStock)

# Desenvolvido com ❤️ por Equipe do NutriStock <span><img src="/static/images/logo/logo_transparente.png" alt="NutriStock Logo" width="30"/></span>
