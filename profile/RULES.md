# 🛡️ Guia de Acesso, Segurança e Boas Práticas — GetBrain 🧠

Este documento define as **regras internas de controle, segurança e boas práticas** que todos os colaboradores devem seguir ao utilizar os repositórios e ferramentas da empresa.

O objetivo é garantir **segurança, organização, rastreabilidade e conformidade** nos projetos de tecnologia.


# 🔐 1. Acesso aos Repositórios

## 1.1. Princípio do Menor Privilégio
Cada colaborador terá acesso **somente aos projetos** para os quais foi designado.

## 1.2. Solicitação de Acesso
1. Solicitar acesso ao gestor
2. Informar justificativa.
3. A solicitação será analisada pelo Tech Lead / CTO.

## 1.3. Suspensão / Revogação de Acesso
- Mudanças de função geram revisão de acessos.
- Ao sair da empresa, o acesso é removido **imediatamente**.


# 🔑 2. Gerenciamento de Credenciais

## 2.1. Proibido Compartilhar Credenciais
Cada colaborador é responsável **exclusivamente** por suas credenciais.

## 2.2. Autenticação em Dois Fatores (2FA)
É **obrigatório** ativar 2FA no GitHub e ferramentas internas.

## 2.3. Não Armazenar Chaves no Código
- Nunca subir `.env` para o repositório.
- Utilizar serviços como GitHub Secrets.

---

# 📁 3. Organização dos Projetos

## 3.1. Estrutura de Branches
- `main` — versão estável.
- `dev` — integração.
- `dev-{nome_dev}` - Branch pessoal de cada dev

## 3.2. Pull Requests
- Nenhum merge direto para `main`.
- Revisão obrigatória pelo gestor

## 3.3. Padrão de Commits
feat: adicionar funcionalidade
fix: corrigir bug
docs: atualizar documentação
chore: ajustes internos
refactor: refatorar sem alterar comportamento

# 🧪 4. Qualidade e Testes

## 4.1. Testes Automatizados
- Testes unitários e de integração sempre que possível.
- Cobertura recomendada: **mínimo 70%**.

## 4.2. CI/CD
Todo PR deve executar pipeline de:
- 

# 🛡️ 5. Segurança de Código

## 5.1. Dependências
Manter Dependabot ou ferramenta similar ativada.

## 5.2. Scans de Vulnerabilidade
Repositórios devem utilizar:
- GitHub Code Scanning
- Secret Scanning
- Dependência Scanning

## 5.3. Proibido versionar dados sensíveis
Incluindo, mas não limitado a:
- Tokens
- Chaves de API
- Dados de clientes
- Dumps de banco

# 🤝 6. Conduta e Boas Práticas

## 6.1. Comunicação
- Documentar mudanças relevantes.
- Descrever adequadamente PRs, issues e tickets.

## 6.2. Respeito aos Fluxos Internos
Seguir decisões técnicas, padrões e boas práticas acordadas pelo time.

## 6.3. Propriedade Intelectual
Todo código desenvolvido durante o trabalho é propriedade da empresa.

# 📘 7. Como Reportar Incidentes

Se identificar:
- Acesso indevido  
- Vulnerabilidade  
- Comportamento suspeito  
- Vazamento de credenciais  

Reportar **imediatamente** ao Tech Lead, gestor direto ou canal oficial de segurança.

# ✔️ Final

Este documento é **obrigatório** para todos os colaboradores.  
Qualquer alteração deve ser revisada e aprovada pela liderança técnica.
