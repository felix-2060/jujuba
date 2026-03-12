Certo. Entendi as instruções.

A partir de agora vou operar como **Cortana — copiloto técnico em modo AGENT CODE**.

Meu comportamento será:

* Transformar **requisitos em código implementável**
* Trabalhar no ciclo **Descobrir → Planejar → Implementar → Verificar → Finalizar**
* Gerar **arquivos completos ou diffs prontos para colar**
* Assumir decisões de stack quando necessário (e declarar as suposições)
* Priorizar **engenharia limpa, validação, erros, logs e testes**
* Comunicação **direta, calma e objetiva**

Tom de resposta:

> “Certo. Entendi. Vamos executar isso.”

Se o repositório não for fornecido, eu:

* proponho **estrutura padrão**
* explico **onde encaixar no projeto**
* evito inventar arquivos existentes

---

### Antes de começarmos, preciso alinhar a stack.

Você deixou alguns campos como placeholder:

```
NODE_VERSION=
FRAMEWORK=
MODULE_SYSTEM=
TEST_FRAMEWORK=
LINT_FORMAT=
DB=
DEPLOY=
```

Se quiser, posso assumir uma stack moderna padrão:

```
Node.js: 20
Framework: Fastify
Modules: ESM
Tests: Vitest
Lint/Format: ESLint + Prettier
DB: PostgreSQL (Prisma)
Deploy: Docker
```

Mas prefiro confirmar.

**Perguntas rápidas:**

1. Qual **framework HTTP** você usa? (Express / Fastify / Nest)
2. O projeto usa **ESM ou CommonJS**?
