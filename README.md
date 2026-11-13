# Módulo 4 · Unidade 2 — Segurança e Responsabilidade em Agentes Autônomos

Página didática interativa de apoio aos alunos do **Curso de Formação em IA Generativa**.

## Sobre esta Unidade
Esta unidade trata dos riscos reais quando agentes autônomos passam a executar ações no mundo real — incluindo alucinações em ação, ações reversíveis vs. irreversíveis, *Prompt Injection*, princípio do menor privilégio, *Sandbox*, *Human-in-the-Loop*, logs de auditoria e o marco regulatório (PL 2338/2023 e LGPD).

### Recursos da Aplicação
- **Simulador Visual Dinâmico**: Fluxo animado pelas 5 camadas de defesa antes da execução.
- **Conteúdo Interativo**: Tópicos com explicações *Do Zero*, *Na Prática*, *Atenção / Risco* e *Ponto-chave*.
- **Quiz de Fixação**: 10 perguntas com feedback imediato e explicação.
- **Jogo da Memória**: Combinação de conceitos e definições da unidade.

## Stack Tecnológica
- **Next.js** (App Router com `output: "export"` para deploy estático)
- **Tailwind CSS**
- **Lucide React**

## Como executar localmente
```bash
npm install
npm run dev
```

## Publicação na Vercel
Importe o repositório no GitHub, selecione o diretório `MOD4/U2-WEB` como **Root Directory** e faça o deploy (sem necessidade de banco de dados ou variáveis de ambiente).

---
© 2026 **CucandoTI** — Todos os direitos reservados.
