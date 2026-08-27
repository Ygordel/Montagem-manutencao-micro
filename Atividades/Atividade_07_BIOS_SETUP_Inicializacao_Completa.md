# ATIVIDADE 07 — BIOS/SETUP E PROCESSO DE INICIALIZAÇÃO

## Investigando o que acontece antes do sistema operacional

**Curso:** Montagem e Manutenção de Micro  
**Atividade:** 07  
**Modalidade:** Prática em sala de aula / laboratório  
**Organização:** Duplas  
**Duração sugerida:** 60 minutos  
**Equipamento:** PCs disponíveis no laboratório  
**Desmontagem:** Não será realizada  
**Alterações no SETUP:** Não serão realizadas

---

## 1. Apresentação

O computador não começa a executar o sistema operacional imediatamente após ser ligado.

Antes do carregamento do Windows, existe uma sequência de procedimentos responsáveis por verificar e preparar o equipamento para a inicialização.

Nesta atividade, os alunos irão conhecer, por meio de observação, o ambiente de configuração do computador e sua relação com o processo de inicialização.

A disciplina aborda o **SETUP, o POST, opções de configuração, dispositivos de inicialização, sequência de boot e procedimentos relacionados à inicialização do sistema**.

> **Importante:** a atividade será realizada de forma segura. O objetivo é observar e compreender. Nenhuma configuração deverá ser alterada ou salva sem autorização expressa do professor.

---

# 2. Objetivos

Ao finalizar a atividade, o aluno deverá ser capaz de:

- compreender a finalidade do BIOS/firmware;
- reconhecer o ambiente SETUP;
- compreender o conceito de POST;
- identificar informações apresentadas durante a inicialização;
- reconhecer opções relacionadas ao boot;
- compreender a importância da ordem de inicialização;
- observar informações de hardware disponíveis no SETUP;
- diferenciar BIOS/firmware, SETUP e sistema operacional;
- desenvolver uma postura segura diante de configurações de baixo nível.

---

# 3. Situação-problema

Imagine que um computador esteja apresentando a seguinte situação:

> **“O equipamento liga, mas não inicia o Windows como deveria.”**

O usuário informa que o problema começou depois que uma configuração foi modificada.

Como técnico, você precisa entender o processo de inicialização antes de tomar qualquer decisão.

---

# 4. Antes de começar — pense como técnico

O computador liga e apresenta informações na tela antes de carregar o Windows.

### O que você imagina que esteja acontecendo nesse momento?

__________________________________________________

__________________________________________________

### Por que o computador precisa realizar verificações antes de iniciar o sistema?

__________________________________________________

__________________________________________________

---

# 5. ETAPA 1 — Observando a inicialização

Reinicie o computador somente quando autorizado pelo professor.

Observe atentamente as primeiras telas.

Procure informações como:

- fabricante;
- modelo;
- mensagens de inicialização;
- teclas de acesso ao SETUP;
- teclas de acesso ao menu de boot;
- mensagens relacionadas a dispositivos.

### Registre:

**Fabricante:**  
____________________________________________

**Modelo:**  
____________________________________________

**Tecla indicada para SETUP:**  
____________________________________________

**Tecla indicada para menu de boot, se apresentada:**  
____________________________________________

**Mensagem que chamou atenção:**  
____________________________________________

---

# 6. ETAPA 2 — Compreendendo o POST

O POST é uma etapa realizada durante a inicialização para verificar condições básicas do equipamento antes do carregamento do sistema operacional.

### Pergunta

Por que essa verificação é importante?

__________________________________________________

__________________________________________________

### Cite duas informações ou sinais que podem aparecer durante a inicialização.

1. _____________________________________________
2. _____________________________________________

---

# 7. ETAPA 3 — Acessando o SETUP

Se autorizado pelo professor, utilize a tecla indicada durante a inicialização para acessar o SETUP.

> **Não altere nenhuma configuração.**

Observe a interface.

Registre os menus encontrados.

| Menu | Informação observada |
|---|---|
| | |
| | |
| | |
| | |
| | |

---

# 8. ETAPA 4 — Informações do equipamento

Procure informações relacionadas ao hardware.

Quando disponíveis, registre:

**Processador:**  
____________________________________________

**Memória:**  
____________________________________________

**Armazenamento:**  
____________________________________________

**Data/hora:**  
____________________________________________

**Modelo do equipamento/placa:**  
____________________________________________

---

# 9. ETAPA 5 — Investigando o boot

Localize uma opção relacionada à inicialização, quando disponível.

Pode aparecer com nomes diferentes conforme o fabricante, como opções de:

- Boot;
- Boot Order;
- Boot Priority;
- Boot Sequence;
- dispositivos de inicialização.

### Registre:

**Primeira opção de inicialização:**  
____________________________________________

**Segunda opção, se apresentada:**  
____________________________________________

**Terceira opção, se apresentada:**  
____________________________________________

---

# 10. ETAPA 6 — Entendendo a ordem de inicialização

Imagine que o computador esteja configurado para procurar primeiro um dispositivo que não possui um sistema inicializável.

### O que pode acontecer?

__________________________________________________

__________________________________________________

### Por que a ordem de boot é importante?

__________________________________________________

__________________________________________________

---

# 11. ETAPA 7 — SETUP x Windows

Complete:

| Ambiente | Finalidade |
|---|---|
| BIOS/firmware | |
| SETUP | |
| Windows | |

### Questão

Por que o SETUP não deve ser confundido com o sistema operacional?

__________________________________________________

__________________________________________________

---

# 12. ETAPA 8 — Situação-problema

O usuário informa:

> **“Meu computador não encontra o sistema operacional.”**

Você não sabe ainda qual é a causa.

### O que verificaria primeiro?

__________________________________________________

### Que informação do processo de inicialização seria importante observar?

__________________________________________________

### Que ferramenta ou ambiente poderia ajudar nessa investigação?

__________________________________________________

---

# 13. ETAPA 9 — Configuração alterada

Imagine que um técnico tenha alterado várias opções do SETUP ao mesmo tempo.

Depois disso, o computador passou a apresentar um comportamento diferente.

### Por que essa situação dificulta o diagnóstico?

__________________________________________________

__________________________________________________

### Qual seria uma atitude profissional?

__________________________________________________

__________________________________________________

---

# 14. ETAPA 10 — Raciocínio técnico

Analise:

```text
Computador liga
      ↓
Tela inicial aparece
      ↓
SETUP pode ser acessado
      ↓
Dispositivo de armazenamento é reconhecido
      ↓
Windows não inicia
```

### Em qual etapa você concentraria a investigação?

__________________________________________________

### Por quê?

__________________________________________________

__________________________________________________

---

# 15. ETAPA 11 — Estudo de caso

Leia:

> Um computador funcionava normalmente. Depois de uma alteração na configuração de inicialização, passou a tentar iniciar por um dispositivo diferente do armazenamento que contém o sistema.

### Responda:

**1. Qual configuração pode estar relacionada à situação?**

__________________________________________________

**2. O que você verificaria?**

__________________________________________________

**3. Que cuidado deve ser tomado antes de salvar uma alteração?**

__________________________________________________

**4. Por que é importante registrar a configuração anterior?**

__________________________________________________

---

# 16. ETAPA 12 — Diagnóstico sem alteração

Monte uma sequência segura de investigação.

```text
1. __________________________________________

2. __________________________________________

3. __________________________________________

4. __________________________________________

5. __________________________________________
```

### Explique por que a sequência é segura.

__________________________________________________

__________________________________________________

---

# 17. ETAPA 13 — Comparação com o Windows

Depois de sair do SETUP, acesse o Windows.

Compare uma informação de hardware encontrada no SETUP com a informação disponível no próprio Windows.

| Informação | SETUP | Windows |
|---|---|---|
| Processador | | |
| Memória | | |
| Armazenamento | | |

### Houve alguma diferença?

__________________________________________________

### Se houve, o que você faria antes de concluir que existe um problema?

__________________________________________________

---

# 18. Questão norteadora

> **Por que um técnico deve compreender o processo de inicialização antes de alterar configurações do SETUP?**

__________________________________________________

__________________________________________________

__________________________________________________

__________________________________________________

---

# 19. Questão desafio

Um colega afirma:

> **“Se o Windows não inicia, é só mudar a ordem de boot.”**

Você concorda?

(   ) Sim

(   ) Não

### Justifique.

__________________________________________________

__________________________________________________

### Que outras possibilidades poderiam ser investigadas?

__________________________________________________

__________________________________________________

---

# 20. Ficha técnica

```text
ANÁLISE DE INICIALIZAÇÃO

Equipamento:
____________________________________________

Fabricante:
____________________________________________

Modelo:
____________________________________________

Tecla de acesso ao SETUP:
____________________________________________

Informações de hardware:
____________________________________________

Ordem de boot observada:
____________________________________________

Problema analisado:
____________________________________________

Hipótese:
____________________________________________

Teste recomendado:
____________________________________________

Conclusão:
____________________________________________
```

---

# 21. Apresentação da dupla

Cada dupla terá até **3 minutos** para explicar:

1. o que observou durante a inicialização;
2. o que encontrou no SETUP;
3. como estava organizada a inicialização;
4. qual situação-problema analisou;
5. qual seria o primeiro teste;
6. quais cuidados devem ser tomados.

---

# 22. O que NÃO fazer

Nesta atividade:

- não alterar configurações;
- não alterar ordem de boot;
- não modificar senha;
- não alterar parâmetros do processador;
- não modificar configurações de armazenamento;
- não ativar ou desativar dispositivos;
- não salvar alterações sem autorização;
- não restaurar configurações por conta própria.

> **Conhecer uma configuração é diferente de alterá-la.**

---

# 23. Checklist

- [ ] Observamos a inicialização.
- [ ] Identificamos fabricante e modelo.
- [ ] Identificamos a tecla de acesso ao SETUP.
- [ ] Observamos o POST.
- [ ] Entramos no SETUP, quando autorizado.
- [ ] Identificamos menus.
- [ ] Localizamos informações de hardware.
- [ ] Observamos a ordem de boot.
- [ ] Comparamos SETUP e Windows.
- [ ] Resolvemos o estudo de caso.
- [ ] Elaboramos uma sequência de diagnóstico.
- [ ] Preenchemos a ficha técnica.
- [ ] Participamos da apresentação.

---

# 24. Entrega

A dupla deverá entregar:

- registros da inicialização;
- observações do POST;
- informações do SETUP;
- ordem de boot;
- comparação SETUP x Windows;
- estudo de caso;
- questão norteadora;
- questão desafio;
- ficha técnica;
- conclusão.

---

# 25. Avaliação — 10 pontos

| Critério | Valor |
|---|---:|
| Observação da inicialização | 1,5 |
| Compreensão do POST/SETUP | 2,0 |
| Análise do boot | 2,0 |
| Estudos de caso | 1,5 |
| Raciocínio técnico | 1,0 |
| Registro técnico | 1,0 |
| Participação/apresentação | 1,0 |
| **TOTAL** | **10,0** |

---

# 26. Para guardar

O processo de inicialização pode ser entendido de forma simplificada como:

```text
ENERGIA
   ↓
FIRMWARE
   ↓
POST
   ↓
IDENTIFICAÇÃO DOS DISPOSITIVOS
   ↓
SELEÇÃO DO DISPOSITIVO DE BOOT
   ↓
CARREGAMENTO DO SISTEMA
   ↓
WINDOWS
```

> **Antes de investigar o Windows, em determinados problemas é necessário compreender o que acontece antes dele iniciar.**

---

## Orientação ao professor

A atividade deve ser realizada nos PCs disponíveis no laboratório.

O acesso ao SETUP depende do fabricante e do modelo. As telas e opções podem ser diferentes entre os equipamentos.

Se o acesso ao SETUP não for permitido no laboratório, o professor poderá utilizar capturas de tela ou imagens previamente preparadas.

O foco da atividade é a compreensão do processo de inicialização e a leitura das informações disponíveis. Nenhuma alteração de configuração deve ser realizada sem autorização.

---

<p align="center">
<strong>CURSO DE MONTAGEM E MANUTENÇÃO DE MICRO</strong><br>
FAETEC • Professor Ygor Delfino
</p>
