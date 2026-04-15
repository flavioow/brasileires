# Commit 1 — Core v0.1

Este commit define o **núcleo inicial do brasileires (v0.1)**.

O objetivo é estabelecer um sistema mínimo:

* consistente
* previsível
* aplicável em larga escala

Este não é o estado final da língua, mas sim uma **base funcional** sobre a qual futuras decisões serão construídas.

---

## 🧠 Visão Geral

O brasileires v0.1 introduz:

* remoção de acentos
* eliminação de letras não funcionais (`h`, `q`, `k`, `w`, `y`)
* sistema fonético consistente
* representação explícita de nasalização
* simplificação gramatical inicial
* ajustes lexicais estratégicos

---

## 🔤 1. Ortografia Base

### 1.1 — Remoção de acentos

Todos os acentos são removidos, incluindo diferenciais.

```text
avó → avo
pôde → pode
têm → tem
```

---

### 1.2 — Remoção de letras não funcionais

As seguintes letras são removidas do sistema:

* `h`
* `q`
* `k`
* `w`
* `y`

```text
homem → omem
hoje → oje
aqui → aci
```

---

### 1.3 — Representação do som /k/

Todo som de /k/ passa a ser representado por `c`.

```text
que → ce
quilo → cilo
guerra → gerra
```

---

### 1.4 — Remoção do “ç”

```text
maçã → masan
ação → asaon
```

---

## 🔊 2. Sistema Fonético Consistente

### 2.1 — Sons fixos

| Som      | Representação |
| -------- | ------------- |
| /s/      | s             |
| /z/      | z             |
| /k/      | c             |
| /ʃ/ (sh) | x             |

---

### 2.2 — Conversões obrigatórias

```text
cidade → sidade
casa → caza
coisa → coiza
chave → xave
chuva → xuva
```

---

### 2.3 — “lh” → “li”

```text
filho → filio
trabalho → trabalio
```

---

### 2.4 — “nh” → “ni”

```text
banho → banio
minha → minia
```

---

## 🌫️ 3. Nasalização (sem acentos)

### 3.1 — Regra base

A nasalização é representada com **“n”**.

---

### 3.2 — Conversões principais

```text
não → naon
pão → paon
mãe → maen
amanhã → amanian
```

---

### 3.3 — Regra complementar

* Palavras comuns terminam com **“m”**
* O **“n” é reservado para nasalização**

```text
homem → omem
abdômen → abdomem
```

---

## 📚 4. Léxico

### 4.1 — Simplificações seguras

* Remoção de acentos diferenciais
* Fusão apenas quando não há colisão semântica relevante

```text
tem / têm → tem
vem / vêm → vem
```

---

### 4.2 — Substituições estratégicas

Casos de ambiguidade crítica podem ser resolvidos via substituição lexical:

```text
avô / avó → nono / nona
```

---

### 4.3 — Regra de colisão semântica

> Fusões lexicais só são permitidas quando não causam ambiguidade relevante.

---

## ⚙️ 5. Gramática

### 5.1 — Plural

Sempre formado com **“-s”**.

```text
caza → cazas
animal → animals
```

---

### 5.2 — Estrutura verbal

* Apenas **próclise** é permitida
* Mesóclise e ênclise são eliminadas

```text
dir-lhe-ei → eu vo diz pra ele
```

---

### 5.3 — “por que”

Sistema simplificado:

| Uso      | Forma  |
| -------- | ------ |
| pergunta | por ce |
| resposta | porce |

```text
Por que voce veio? → Por ce voce veio?
Eu vim porque quis → Eu vim porce quis
```

---

## 🧠 6. Regras Implícitas

Estas regras emergem da aplicação prática do sistema:

---

### 6.1 — Escrita segue o som

A grafia deve refletir o som percebido, não a forma original.

```text
cozinha → cozinia
```

---

### 6.2 — Fonética tem prioridade

A origem da palavra não influencia sua escrita no v0.1.

---

### 6.3 — Consistência acima de familiaridade

Regras devem ser aplicadas mesmo que causem estranheza inicial.

---

### 6.4 — Adaptação é esperada

Brasileires não deve ser lido como português.
A adaptação faz parte do processo.

---

## 🧪 Exemplo consolidado

```text
Eu perguntei por ce ele naon veio ontem. Ele dise ce teve um problema em caza e naon consegiu sair. Nos combinamos de nos ver amanian.
```

---

## 🧬 Conclusão

O v0.1 estabelece:

* um sistema sem acentos
* um sistema fonético consistente
* um conjunto mínimo de regras aplicáveis
* uma base estável para evolução futura

Este commit representa o ponto onde o brasileires deixa de ser apenas conceito
e passa a ser um **sistema utilizável**.
