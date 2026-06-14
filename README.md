# Projeto PortfolioHUB

Este projeto consiste na implantação do PortfolioHUB, uma plataforma para gerenciar e exibir portfólios digitais. O processo de configuração foi realizado com o suporte do Google Gemini para a aplicação das melhores práticas de gerenciamento e segurança.

---

## 1. Planejamento da Implantação
O planejamento foi estruturado para garantir a criação do ambiente de forma organizada. Utilizei o Google Gemini como guia técnico para orientar as etapas de deploy e para a definição das configurações de proteção do repositório.

## 2. Configuração Inicial e Integração com GitHub
* Criado o repositório dedicado chamado portfolio-hub no GitHub para o controle de versão do código.
* O site foi publicado e colocado no ar utilizando o serviço do GitHub Pages.
* A estrutura inicial foi desenvolvida em HTML básico, servindo como base para futuras integrações com APIs.

## 3. Gestão de Usuários e Segurança
Seguindo as recomendações de segurança passadas pela IA, apliquei as seguintes configurações no repositório:
* Branch Protection: Ativei regras de proteção na branch main para impedir que alterações sejam feitas diretamente nela sem uma revisão por Pull Request. Isso evita a perda de código ou modificações acidentais no site em produção.
* GitHub Secrets: Configurei o armazenamento seguro de variáveis de ambiente inserindo a chave MINHA_CHAVE_SECRETA no painel de segredos do GitHub. Dessa forma, dados sensíveis e senhas não ficam expostos no código-fonte.

## 4. Compartilhamento e Controle de Acesso
O repositório está configurado para permitir o controle de versão completo por meio do Git. O ambiente também está pronto para o trabalho colaborativo, permitindo o gerenciamento de permissões e o controle de acesso de novos membros através das configurações de colaboradores do GitHub.

---
Projeto desenvolvido como atividade de Entrega Final com o suporte do Google Gemini.
