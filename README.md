# Estruturas de Dados Dinâmicas em C 💻

Este repositório apresenta implementações robustas de estruturas de dados para a resolução de problemas específicos, desenvolvidas com foco em alocação dinâmica de memória e lógica algorítmica.

## 🛠️ Projetos Integrados

### 1. Agenda de Contatos (Lista Circular Duplamente Encadeada)
Uma implementação avançada de lista onde cada nó possui ponteiros para o sucessor e o antecessor, e o último nó conecta-se ao primeiro.
* **Diferencial Técnico:** Permite navegação bidirecional e circular, ideal para sistemas que exigem percursos contínuos.
* **Operações:** Inserção ordenada, busca otimizada, remoção com liberação de memória (`free`) e exibição circular.

### 2. Calculadora de Notação Polonesa Reversa - RPN (Pilha)
Desenvolvimento de uma calculadora que utiliza a lógica de pós-fixação, eliminando a necessidade de parênteses para definir a precedência de operadores.
* **Estrutura de Dados:** Baseada em uma **Pilha (Stack)** dinâmica.
* **Funcionamento:** 1. Operandos são empilhados.
    2. Operadores desempilham os valores, realizam o cálculo e empilham o resultado.
* **Complexidade:** Operações de empilhar (push) e desempilhar (pop) em $O(1)$.

---

## 🔬 Contexto de Modelagem
A escolha dessas estruturas reflete a busca por eficiência computacional. Na **Modelagem Computacional**, a gestão eficiente de memória e o uso de pilhas para processamento de expressões são fundamentais para o desempenho de simuladores e interpretadores de alto nível.

## 🚀 Como Compilar e Rodar
Certifique-se de ter o GCC instalado:

```bash
# Para a Agenda
gcc agenda_circular.c -o agenda
./agenda

# Para a Calculadora RPN
gcc calculadora_rpn.c -o calculadora
./calculadora
