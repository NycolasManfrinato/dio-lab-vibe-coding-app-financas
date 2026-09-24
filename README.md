# 💰 FinOrg — App de Organização de Finanças Pessoais (Vibe Coding)

> Desafio da DIO: App de Organização de Finanças Pessoais com Vibe Coding — fork do repositório-base (digitalinnovationone/dio-lab-vibe-coding-app-financas), resolvido guiando o GitHub Copilot Chat como parceiro criativo de IA.

## 📝 Meu prompt final (PRD)

```
# Contexto
Quero criar o conceito de um app de Organização de Finanças Pessoais chamado "FinOrg", que funcione como uma conversa com um assistente financeiro, e não como uma planilha ou formulário.

# Problema
A maioria das pessoas desiste de controlar as finanças porque os apps tradicionais pedem cadastro manual de cada gasto e telas cheias de campos. Quero trocar o "preenchimento de formulário" por uma conversa natural com um Agente Financeiro que organiza tudo sozinho.

# Público-Alvo
Jovens adultos e iniciantes no controle financeiro que já desistiram de outros apps por acharem o processo cansativo.

# Funcionalidades-Chave
1. Registrar gastos e receitas por linguagem natural, sem formulários.
2. Categorização automática das transações pela IA.
3. Metas de economia com acompanhamento de progresso.
4. Agente Financeiro com tom acolhedor que dá dicas personalizadas.
5. Relatório visual simples (saldo, entradas, saídas, gastos por categoria).

# Entregável da IA
Com base nisso, gere: (1) uma definição curta do tom de voz do Agente Financeiro, (2) o fluxo conceitual de telas do app simulando a interação por conversa, e (3) um plano de MVP resumido com as 5 funcionalidades, recursos necessários e uma forma simples de validar se o app ajuda o usuário a economizar. Tom educativo, linguagem acessível, em português.
```

Usei o **GitHub Copilot Chat** (web) para conversar com esse PRD. Tentei também o **Lovable**, mas ele exige criar conta antes de gerar qualquer resposta — então segui só com o Copilot (isso virou material pra reflexão lá embaixo).

## 🤖 O que a IA devolveu

**Tom de voz do Agente Financeiro:** acolhedor e sem julgamentos, claro e simples, conversacional (fala como parceiro, não como consultor formal), motivador mas realista, personalizado à renda/objetivos do usuário, e transparente sobre como chegou nas recomendações.

Exemplo dado pela IA: "Você gastou R$ 120 com delivery esta semana. Se quiser economizar, podemos definir um limite de R$ 80 na próxima — sem cortar completamente o que você gosta."

**Fluxo de telas principal:** Boas-vindas/cadastro → Configuração financeira (renda, despesas fixas, metas) → Tela de conversa (registro de gastos em linguagem natural) → Confirmação da transação → Resumo financeiro (saldo, gastos por categoria) → Metas → Dicas personalizadas.

**Plano de MVP (resumo):**

| Funcionalidade | Escopo inicial | Validação |
| --- | --- | --- |
| Registro por conversa | Registrar receitas/despesas em linguagem natural | Nº de transações registradas e taxa de correção |
| Categorização automática | Categorizar gastos (alimentação, transporte, moradia...) | Precisão das categorias e correções feitas |
| Resumo financeiro | Saldo, receitas, despesas, gastos por categoria | Testes de compreensão do resumo |
| Metas de economia | Criar meta, prazo, valor acumulado | Criação de metas e frequência de acompanhamento |
| Dicas e alertas | Avisar excesso de gastos, sugerir ações | Cliques, respostas e mudança de comportamento |

Validação geral sugerida pela IA: entrevistar de 10 a 15 pessoas que desistiram de apps financeiros tradicionais, prototipar o fluxo conversacional, lançar uma beta para 50-100 usuários e acompanhar retenção (7/30 dias), transações por usuário e taxa de criação de metas.

## 📱 Resumo do app

O **FinOrg** é o conceito de um assistente financeiro pessoal que troca formulários por conversa: em vez de preencher campos, o usuário simplesmente conta o que gastou (ex: "gastei R$ 45 no mercado") e a IA categoriza, atualiza o saldo e acompanha metas de economia sozinha. O foco é reduzir o atrito que faz as pessoas abandonarem apps financeiros tradicionais.

## 💭 Reflexão

**O que funcionou bem:** o GitHub Copilot Chat entendeu o PRD de primeira e devolveu exatamente os três blocos pedidos (tom de voz, fluxo de telas e plano de MVP), já bem estruturados. Escrever o PRD antes de pedir qualquer coisa fez diferença real — sem ele, a resposta provavelmente teria saído genérica.

**O que não funcionou como o esperado:** o plano gratuito do Copilot tem um limite de sessão curto — bati no limite depois de poucas mensagens numa primeira tentativa e precisei abrir um novo chat. O Lovable, a segunda ferramenta sugerida, exige criar conta antes de gerar qualquer coisa, então não consegui testar o fluxo de telas visual por lá.

**O que aprendi sobre conversar com IAs:** quanto mais estruturado o prompt (contexto, problema, público, funcionalidades, entregável esperado), mais direta e utilizável é a resposta. Também aprendi que vibe coding não é sobre acertar o prompt perfeito de primeira, e sim sobre iterar — dá pra pedir complementos específicos (ex: "detalha só a tela de metas") em vez de tentar extrair tudo de uma vez.

## 📸 Prints da conversa com o Copilot
<img width="1568" height="745" alt="copilot-prompt-tom-de-voz" src="https://github.com/user-attachments/assets/156cdd5c-f331-4fa9-8007-6513b0c6a5fb" />

<img width="1568" height="745" alt="copilot-fluxo-de-telas" src="https://github.com/user-attachments/assets/e06dccf7-68fe-47a7-a7a6-e79d552f0b5a" />

<img width="1568" height="745" alt="copilot-plano-mvp" src="https://github.com/user-attachments/assets/c73170c1-a4f7-4ca8-aa93-c6eb4af7c302" />



