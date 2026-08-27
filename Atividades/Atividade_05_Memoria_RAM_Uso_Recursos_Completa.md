# ATIVIDADE 05 — MEMÓRIA RAM E USO DE RECURSOS

## Investigando a memória e o comportamento do computador

**Curso:** Montagem e Manutenção de Micro  
**Atividade:** 05  
**Modalidade:** Prática em sala de aula / laboratório  
**Organização:** Duplas  
**Duração sugerida:** 60 minutos  
**Equipamento:** PCs disponíveis no laboratório  
**Desmontagem:** Não será realizada

---

## 1. Apresentação

A memória RAM é um dos elementos fundamentais para o funcionamento do computador. Durante a utilização do sistema, programas e processos utilizam a memória para realizar suas atividades.

Nesta atividade, o aluno irá investigar a memória RAM diretamente no computador do laboratório, utilizando as ferramentas disponíveis no Windows.

O objetivo não é apenas descobrir quantos gigabytes estão instalados. A proposta é observar **como a memória é utilizada**, relacionar esse comportamento aos programas em execução e desenvolver uma forma organizada de investigação.

O conteúdo da disciplina aborda processadores e memórias, incluindo tipos e especificações de memória RAM, slots, dual channel e processadores com múltiplos núcleos. Nesta atividade, esses conhecimentos serão trabalhados pela observação do computador em funcionamento.

> **Importante:** não será realizada desmontagem. Não serão removidos módulos de memória e nenhuma alteração física será feita no equipamento.

---

# 2. Objetivos

Ao finalizar a atividade, o aluno deverá ser capaz de:

- identificar a quantidade de memória RAM instalada;
- localizar informações de memória no Windows;
- observar o consumo de memória;
- relacionar memória e programas em execução;
- comparar diferentes situações de utilização;
- identificar processos que consomem memória;
- compreender a diferença entre RAM e armazenamento;
- levantar hipóteses relacionadas à lentidão;
- registrar informações para um diagnóstico técnico;
- interpretar resultados sem concluir prematuramente que existe defeito.

---

# 3. Situação-problema

Um usuário procura uma assistência técnica e informa:

> **“Meu computador funciona normalmente quando ligo, mas fica lento depois que começo a abrir vários programas.”**

O usuário não sabe informar a quantidade de memória instalada.

Você recebeu o computador para uma primeira análise.

### Sua missão

Investigar o comportamento da memória RAM **sem desmontar o computador**.

---

# 4. Antes de começar — levantamento de hipóteses

Antes de abrir qualquer ferramenta, responda:

### O que pode provocar lentidão quando vários programas estão abertos?

Liste pelo menos três possibilidades.

1. ______________________________________________
2. ______________________________________________
3. ______________________________________________

### Qual informação você gostaria de verificar primeiro?

__________________________________________________

### Por quê?

__________________________________________________

__________________________________________________

---

# 5. ETAPA 1 — Identificando a memória instalada

Abra o **Gerenciador de Tarefas**:

```text
Ctrl + Shift + Esc
```

Acesse:

**Desempenho → Memória**

Registre:

**Memória total instalada:**  
____________________________________________

**Memória em uso:**  
____________________________________________

**Memória disponível:**  
____________________________________________

**Velocidade apresentada:**  
____________________________________________

**Slots em uso, se apresentado:**  
____________________________________________

**Forma/fator informado, se disponível:**  
____________________________________________

---

# 6. ETAPA 2 — Investigando o comportamento da memória

Observe a memória durante aproximadamente um minuto sem abrir novos programas.

Registre:

**Valor inicial aproximado:** ______________________

**Valor final aproximado:** ________________________

**O comportamento permaneceu estável?**

(   ) Sim  
(   ) Não  
(   ) Variou bastante

### Explique

__________________________________________________

__________________________________________________

---

# 7. ETAPA 3 — Teste controlado

Agora vamos observar o comportamento da memória em diferentes situações.

Primeiro, feche os programas que não estão sendo utilizados.

Registre o valor.

Depois abra um programa autorizado pelo professor.

Registre novamente.

Repita o procedimento com dois programas e depois com vários programas, sem utilizar aplicativos que possam prejudicar o computador.

| Situação | Memória utilizada | Memória disponível | Observação |
|---|---:|---:|---|
| Sem programas adicionais | | | |
| 1 programa | | | |
| 2 programas | | | |
| Vários programas | | | |

---

# 8. ETAPA 4 — Análise do resultado

Compare os valores encontrados.

### A utilização da memória aumentou conforme os programas foram abertos?

(   ) Sim  
(   ) Não  
(   ) Variou

### Qual foi a maior utilização observada?

__________________________________________________

### Em qual situação ocorreu?

__________________________________________________

### O computador apresentou mudança perceptível de comportamento?

(   ) Sim  
(   ) Não

Explique.

__________________________________________________

__________________________________________________

---

# 9. ETAPA 5 — Investigando os processos

Volte para:

**Gerenciador de Tarefas → Processos**

Clique na coluna **Memória** para organizar os processos pelo consumo.

Identifique os três processos que mais utilizam memória.

| Posição | Processo | Utilização observada |
|---:|---|---:|
| 1º | | |
| 2º | | |
| 3º | | |

### Questão

O processo que utiliza mais memória é necessariamente um problema?

(   ) Sim  
(   ) Não

Justifique.

__________________________________________________

__________________________________________________

---

# 10. ETAPA 6 — Comparando processos

Escolha dois processos diferentes.

### Processo 1

**Nome:** ______________________________________

**Uso de memória:** ______________________________

### Processo 2

**Nome:** ______________________________________

**Uso de memória:** ______________________________

### Qual apresentou maior utilização?

__________________________________________________

### Essa diferença significa necessariamente que existe defeito?

__________________________________________________

---

# 11. ETAPA 7 — Memória RAM x armazenamento

Complete a tabela.

| Característica | Memória RAM | Armazenamento |
|---|---|---|
| Função principal | | |
| Utilização durante a execução | | |
| Dados permanecem após desligar? | | |
| Exemplo | | |

---

# 12. Questões de compreensão

### 1. Para que serve a memória RAM?

__________________________________________________

__________________________________________________

### 2. O que acontece com os dados mantidos na RAM quando o computador é desligado?

__________________________________________________

### 3. Por que o espaço livre do SSD/HD não é a mesma coisa que memória RAM disponível?

__________________________________________________

__________________________________________________

---

# 13. ETAPA 8 — Investigando a inicialização

Acesse:

**Gerenciador de Tarefas → Aplicativos de Inicialização**

Observe os programas configurados para iniciar junto com o Windows.

Registre pelo menos quatro.

| Aplicativo | Status | Impacto apresentado, se houver |
|---|---|---|
| | | |
| | | |
| | | |
| | | |

### Questão

Como muitos aplicativos iniciados automaticamente podem influenciar o comportamento do computador?

__________________________________________________

__________________________________________________

---

# 14. ETAPA 9 — Cenário de comparação

Analise os dois computadores hipotéticos.

### Computador A

```text
RAM: 4 GB
Uso de memória: 92%
Poucos programas respondem rapidamente.
```

### Computador B

```text
RAM: 8 GB
Uso de memória: 45%
Vários programas estão abertos.
```

### Perguntas

Qual computador apresenta maior pressão sobre a memória?

__________________________________________________

Que informação adicional você gostaria de conhecer antes de concluir o diagnóstico?

__________________________________________________

---

# 15. ETAPA 10 — Desafio técnico

Considere:

```text
CPU:       25%
Memória:   93%
Disco:     20%
```

### 1. Qual recurso chama mais atenção?

__________________________________________________

### 2. Qual hipótese poderia ser levantada?

__________________________________________________

### 3. Qual informação você verificaria em seguida?

__________________________________________________

### 4. Que teste poderia ser realizado?

__________________________________________________

### 5. O resultado sozinho permite afirmar que a memória está com defeito?

(   ) Sim  
(   ) Não

Justifique.

__________________________________________________

---

# 16. ETAPA 11 — Situação de diagnóstico

O usuário informa:

> **“Meu computador começa rápido, mas depois que abro o navegador, editor de texto, planilha e outros programas, ele fica cada vez mais lento.”**

Elabore um plano de investigação.

### Primeiro passo

__________________________________________________

### Segundo passo

__________________________________________________

### Terceiro passo

__________________________________________________

### Quarto passo

__________________________________________________

### Quinto passo

__________________________________________________

---

# 17. ETAPA 12 — Registro das evidências

Preencha:

| Evidência | Resultado | Importância |
|---|---|---|
| Memória instalada | | |
| Memória utilizada | | |
| Processos | | |
| Inicialização | | |
| Comportamento do PC | | |

---

# 18. ETAPA 13 — Relatório técnico

```text
RELATÓRIO — MEMÓRIA RAM

Equipamento:
____________________________________________

Memória instalada:
____________________________________________

Memória utilizada:
____________________________________________

Maior utilização observada:
____________________________________________

Processo que mais utilizou memória:
____________________________________________

Comportamento do computador:
____________________________________________

Hipótese inicial:
____________________________________________

Testes realizados:
____________________________________________

Resultados:
____________________________________________

Diagnóstico provável:
____________________________________________

Próximo procedimento:
____________________________________________
```

---

# 19. Questão norteadora

> **Um computador com pouca memória RAM necessariamente apresenta defeito?**

Responda considerando a diferença entre **limitação de recursos**, **comportamento do sistema** e **defeito físico**.

__________________________________________________

__________________________________________________

__________________________________________________

__________________________________________________

---

# 20. Questão desafio

Um computador possui 8 GB de RAM.

Durante uma determinada atividade, o Gerenciador de Tarefas apresenta:

```text
Memória: 88%
CPU:     22%
Disco:   18%
```

O usuário afirma:

> **“A memória está alta, então preciso trocar a RAM.”**

Como técnico, você concordaria imediatamente?

(   ) Sim  
(   ) Não

### Justifique sua resposta.

__________________________________________________

__________________________________________________

__________________________________________________

### Qual seria sua próxima ação?

__________________________________________________

---

# 21. Comparação entre duplas

Compare os resultados com outra dupla.

| Item | Nossa máquina | Outra máquina |
|---|---:|---:|
| RAM instalada | | |
| RAM utilizada | | |
| Maior utilização | | |
| Processo principal | | |

### O que foi diferente?

__________________________________________________

### Qual pode ser a razão dessa diferença?

__________________________________________________

__________________________________________________

---

# 22. Produção em sala

Cada dupla terá até **3 minutos** para apresentar:

1. quantidade de RAM;
2. comportamento observado;
3. processo que mais utilizou memória;
4. hipótese levantada;
5. teste realizado;
6. conclusão.

---

# 23. O que NÃO fazer

Nesta atividade:

- não abrir o gabinete;
- não remover módulos de RAM;
- não alterar configurações do sistema;
- não finalizar processos sem autorização;
- não instalar programas para “testar” a memória;
- não alterar configurações de inicialização;
- não afirmar que existe defeito sem evidências.

---

# 24. Checklist da dupla

- [ ] Identificamos a quantidade de RAM.
- [ ] Registramos a memória disponível.
- [ ] Observamos o comportamento da memória.
- [ ] Realizamos o teste controlado.
- [ ] Identificamos os processos que mais utilizaram memória.
- [ ] Investigamos aplicativos de inicialização.
- [ ] Comparamos computadores.
- [ ] Analisamos as situações-problema.
- [ ] Elaboramos hipóteses.
- [ ] Registramos as evidências.
- [ ] Elaboramos o relatório.
- [ ] Participamos da apresentação.

---

# 25. Entrega

A dupla deverá entregar:

- levantamento da memória;
- tabela do teste controlado;
- análise dos processos;
- investigação dos aplicativos de inicialização;
- questões de compreensão;
- desafios de diagnóstico;
- questão norteadora;
- questão desafio;
- comparação entre computadores;
- relatório técnico;
- conclusão.

---

# 26. Avaliação — 10 pontos

| Critério | Valor |
|---|---:|
| Levantamento da memória | 1,5 |
| Execução e registro dos testes | 2,0 |
| Análise dos processos | 1,5 |
| Interpretação dos resultados | 1,5 |
| Questões e desafios | 1,5 |
| Relatório técnico | 1,0 |
| Participação/apresentação | 1,0 |
| **TOTAL** | **10,0** |

---

# 27. Para guardar

A quantidade de memória instalada é apenas uma das informações utilizadas em um diagnóstico.

Uma análise profissional deve considerar:

```text
MEMÓRIA INSTALADA
       ↓
MEMÓRIA EM USO
       ↓
PROCESSOS
       ↓
COMPORTAMENTO DO SISTEMA
       ↓
TESTES
       ↓
EVIDÊNCIAS
       ↓
DIAGNÓSTICO
```

> **Memória utilizada não é sinônimo de memória com defeito.**

---

## Orientação ao professor

A atividade foi elaborada para ser realizada nos computadores disponíveis no laboratório, sem necessidade de módulos de memória, placas ou computadores desmontados.

O professor pode utilizar os resultados encontrados pelos próprios alunos para promover uma comparação entre máquinas.

O teste controlado deve ser feito com programas já disponíveis no laboratório e de forma segura. A finalidade é observar a alteração no uso da memória, e não provocar travamentos.

É importante estimular o aluno a diferenciar uma **utilização elevada** de um **defeito de hardware**. Os dados observados devem servir como evidências para a investigação.

---

<p align="center">
<strong>CURSO DE MONTAGEM E MANUTENÇÃO DE MICRO</strong><br>
FAETEC • Professor Ygor Delfino
</p>
