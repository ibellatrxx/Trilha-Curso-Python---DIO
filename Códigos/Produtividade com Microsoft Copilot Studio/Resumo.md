# 📚 Resumo sobre Microsoft Copilot Studio

## 🧠 O que é o Copilot Studio?

O **Copilot Studio** é uma ferramenta da **Microsoft Power Platform** que permite criar **copilotos personalizados (chatbots inteligentes)** com base em IA generativa. Ele é a evolução do antigo **Power Virtual Agents** e se integra diretamente com ferramentas como o **Microsoft Teams, Outlook** e outros serviços do **Microsoft 365**.

Com ele, é possível:
- Criar conversas inteligentes e automatizadas.
- Integrar com APIs, fluxos do Power Automate e outros serviços.
- Usar modelos do **AI Builder**.
- Publicar bots em canais como Microsoft Teams, sites e mais.

---

## 🔌 Integrações possíveis

O Copilot Studio pode ser integrado com:
- **Power Automate** – para automatizar processos.
- **AI Builder** – para aplicar modelos de IA personalizados.
- **Microsoft 365** – para interagir com dados e serviços da suíte (como emails, calendários, etc.).
- **Conectores personalizados** – para integrar APIs e sistemas próprios da empresa.

---

## 🧩 Soluções na Power Platform

As **Soluções** são pacotes onde você pode organizar todos os recursos criados:
- Aplicativos
- Fluxos
- Copilotos
- Tabelas do Dataverse
- Conectores

Elas facilitam o gerenciamento, versionamento e migração entre ambientes (ex: Dev → Teste → Produção).

---

## 🌍 Ambientes na Power Platform

Os **ambientes** são espaços isolados onde você pode criar, testar e publicar suas aplicações/copilotos. Cada ambiente tem sua própria base de dados no **Dataverse**.

### Tipos de Ambientes:
- **Production**: ambiente principal, usado por usuários finais.
- **Sandbox**: usado para testes e desenvolvimento com segurança.
- **Developer**: ambiente individual para aprendizado e criação pessoal.
  
> ❌ "Ambiente de Teste" não é um tipo oficial.

### Regiões válidas incluem:
- América do Sul  
- Alemanha  
- Estados Unidos  
> ❌ Chile (não é uma região individualmente válida)

---

## 👤 Gerenciamento de Usuários

Você pode adicionar usuários indo em:  
**Ambiente → Configurações → Usuários ou Equipes**

Permissões e acessos são controlados por funções de segurança.

---

## 🗂️ Armazenamento no Dataverse

- Por padrão, cada ambiente consome **1GB** de espaço no **Dataverse**, mesmo sem dados inseridos.

---

## ⚠️ Boas Práticas

- **Evite editar ambientes em horários de pico** de uso.
- Organize recursos dentro de soluções para melhor controle.
- Use ambientes separados para desenvolvimento, testes e produção.


