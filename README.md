# Cursor Rules

Este repositório contém um conjunto de regras e configurações personalizadas para uso com IDEs que utilizam agentes de IA, como o Cursor. Estas regras foram desenvolvidas para padronizar e otimizar o desenvolvimento de software, garantindo boas práticas de programação e manutenção de código.

## 📋 Regras Disponíveis

### 1. Segurança (`security.mdc`)
- Proteção de chaves API e dados sensíveis
- Validação de entrada de dados
- Autenticação e autorização
- Proteção contra ataques comuns
- Políticas de senha
- Backup e recuperação de dados
- Análise de dependências
- Certificados HTTPS e comunicação segura

### 2. Documentação (`documentation.mdc`)
- Documentação de projeto
- Documentação de código (docstrings)
- Documentação de mudanças
- Templates para README, arquitetura e API

### 3. Melhores Práticas FastAPI (`fastapi-best-practices.mdc`)
- Princípios de desenvolvimento de APIs escaláveis
- Tratamento de erros e validação
- Otimização de performance
- Convenções de código
- Dependências recomendadas

### 4. Formatação de Código (`code-format.mdc`)
- Limite de 79 caracteres por linha
- Regras de espaçamento
- Configuração do linter Ruff
- Padrões de formatação automática
- Exemplos de código bem formatado

### 5. Preferências de Código (`coding-preferences.mdc`)
- Soluções simples e diretas
- Evitar duplicação de código
- Consideração de ambientes (dev, test, prod)
- Limpeza e organização do código
- Limites de tamanho de arquivo
- Uso apropriado de dados mock

### 6. Preferências de Workflow (`workflow-preferences.mdc`)
- Foco em áreas relevantes
- Testes abrangentes
- Manutenção de padrões existentes
- Análise de impacto de mudanças

### 7. Geração de Testes Python (`python-testing-generator.mdc`)
- Geração de testes unitários
- Padrões de teste intuitivos
- Cobertura de casos de uso

### 8. Padrões de Commit (`commit.mdc`)
- Mensagens de commit convencionais
- Referência a issues
- Documentação de mudanças

## 🚀 Como Usar

1. Clone este repositório
2. Copie as regras desejadas para seu diretório `.cursor/rules/`
3. Configure seu IDE para utilizar estas regras

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem regras adicionais ou melhorias para as existentes, por favor:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-regra`)
3. Commit suas mudanças (`git commit -m 'feat: adiciona nova regra'`)
4. Push para a branch (`git push origin feature/nova-regra`)
5. Abra um Pull Request
