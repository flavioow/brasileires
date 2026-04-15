# PRINCIPLES

Este documento define os princípios operacionais do **brasileires**.
Enquanto o `README.md` apresenta o projeto, este arquivo responde a uma pergunta mais profunda:

> **Como decisões devem ser tomadas dentro do sistema?**

Ele estabelece critérios claros para evolução, resolução de problemas e manutenção da consistência linguística.

---

## 🧠 Filosofia Operacional

Brasileires trata linguagem como um sistema projetável.

Toda decisão deve ser:

* justificável
* reproduzível
* escalável

A linguagem não evolui por tradição ou costume, mas por **critérios explícitos de design**.

---

## 📜 Axiomas Detalhados

### 1. Consistência é prioridade absoluta

Uma regra consistente é preferível a uma regra “correta” historicamente.

> Se uma regra cria exceções frequentes, ela está errada.

---

### 2. Fonética é a base estrutural

A escrita deve representar o som percebido.

* grafia segue pronúncia
* etimologia é ignorada quando entra em conflito com consistência

---

### 3. Sistema > Casos isolados

Decisões não devem ser tomadas para resolver palavras específicas, mas sim padrões.

> Resolver um caso quebrando o sistema é proibido.

---

### 4. Ambiguidade controlada é aceitável

Nem toda ambiguidade precisa ser eliminada.

Critério:

* se o contexto resolve naturalmente → manter
* se gera confusão real → resolver

---

### 5. Simplicidade não é simplismo

Reduzir complexidade não significa empobrecer a linguagem.

> O objetivo é eficiência, não minimalismo extremo.

---

### 6. Trade-offs devem ser conscientes

Toda mudança deve declarar:

* o que melhora
* o que piora

Nenhuma decisão é “gratuita”.

---

## 🔄 Modelo de Override (Detalhado)

Brasileires funciona como um sistema de transformação sobre o português.

### Estrutura conceitual:

```text
entrada: português
processamento: aplicação de regras
saida: brasileires
```

---

### Características do modelo:

* não reescreve tudo do zero
* permite comparação direta
* facilita aprendizado incremental
* permite reversibilidade parcial

---

### Implicação prática:

> Sempre que possível, uma regra deve poder ser aplicada como transformação previsível.

---

## 🧩 Modelo de Resolução de Problemas

Quando uma inconsistência é identificada, o processo deve seguir uma ordem:

---

### 1. Tentar resolver dentro do próprio sistema

* ajustar regra existente
* remover exceção
* simplificar estrutura

---

### 2. Reestruturar a regra

Se o problema for recorrente:

* a regra está errada
* deve ser redesenhada

---

### 3. Substituição lexical (quando necessário)

Se o problema não puder ser resolvido estruturalmente:

> permite-se substituir palavras

Exemplo:

* `avô / avó` → `nono / nona`

---

## 🌍 Modelo de Empréstimo Linguístico

Quando o sistema não oferece solução interna adequada:

### Ordem de preferência:

1. Italiano
2. Espanhol
3. Francês

---

### Critérios para adoção:

* compatibilidade fonética com o brasileires
* baixa complexidade
* alinhamento com padrão latino
* ausência de conflito com regras existentes

---

### Importante:

> Empréstimo não é regra — é exceção controlada.

---

## 🧪 Modelo de Soluções Provisórias

Nem toda decisão precisa ser perfeita no início.

Brasileires aceita soluções provisórias quando:

* o problema ainda não está completamente compreendido
* múltiplas abordagens são possíveis
* a decisão final exige mais experimentação

---

### Regras para soluções provisórias:

* devem ser explicitamente marcadas
* devem ser simples
* não devem bloquear evolução futura

---

### Exemplo típico:

* sistema de nasalização ainda aberto a refinamento
* representação pode evoluir em versões futuras

---

## ⚖️ Hierarquia de Decisão

Quando houver conflito entre princípios:

1. Consistência
2. Fonética
3. Simplicidade
4. Legibilidade
5. Compatibilidade com português
6. Fidelidade histórica

---

## 🧠 Critério de Qualidade

Uma boa decisão em brasileires deve:

* reduzir exceções
* aumentar previsibilidade
* ser explicável em poucas regras
* escalar para múltiplas palavras

---

## 🧬 Evolução do Sistema

Brasileires é versionado.

Isso implica:

* mudanças podem ser quebradas (breaking changes)
* regras podem ser substituídas
* decisões não são permanentes

---

## 📌 Regra Final

Se houver dúvida sobre uma decisão:

> **Escolha sempre a opção que torna o sistema mais previsível, mesmo que menos familiar.**

---

Este documento define o comportamento do projeto em situações de clareza e de incerteza.

Ele existe para garantir que, mesmo em desacordo,
as decisões sigam a mesma lógica.
