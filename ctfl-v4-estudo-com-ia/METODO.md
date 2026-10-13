# O método

## 1. Classifique os erros por tipo, e não só por assunto

No meu primeiro simulado, quase nenhum erro foi por não conhecer o conteúdo. Eles caíam em quatro tipos:

| Tipo de erro | Exemplo | Antídoto |
|---|---|---|
| **Leitura** | Não perceber "NÃO", "todas", "sempre", "normalmente" | Perguntar: *"alguma palavra restringe, exagera ou inverte a frase?"* |
| **Classificação** | Confundir categorias vizinhas (sistema x aceite, confirmação x regressão, entrada x saída) | Perguntar: *"em que **subcategoria** do syllabus isso se encaixa?"* |
| **Cálculo e contagem** | Contar itens repetidos, esquecer um limite, pular o estado inicial | Rascunho em tabela, um item por linha, e só contar no final |
| **Sequência** | Trocar a ordem de etapas (processo de revisão, priorização) | Começar pela associação de que tem mais certeza e eliminar alternativas |

Saber o **tipo** do erro diz **como** estudar. Saber só o **assunto** diz apenas **o que** estudar.

## 2. A regra do muro (análise de valor limite)

Cada fronteira entre duas faixas é um **muro**.

```
   R$15        R$30          R$60
 1 2 3 4 5 ▌ 6 7 ... 19 20 ▌ 21 22 23 ...
         ↑   ↑          ↑    ↑
```

- **2 valores:** os valores encostados em cada muro, dos dois lados (5 e 6, 20 e 21), mais os extremos definidos pelo enunciado (o 1).
- **3 valores:** além dos encostados, **um passo para dentro** de cada faixa, em **todas** as faixas.
- Vizinho **fora do domínio** nunca entra.

## 3. As regras do caderno

**Análise de valor limite (4.2.2)**
1. Faça a tabela **partição | mín | máx**. Toda faixa tem limites, inclusive as inválidas.
2. **2 valores:** só os valores encostados nos muros (com inteiros, são os próprios limites).
3. **3 valores:** cada limite + 1 passo para dentro da faixa **dele**, em **todas** as faixas.
4. Extremos definidos pelo enunciado entram. Vizinho fora do domínio nunca entra.

**Tabela de decisão (4.2.3)**

5. Classifique cada caso verificando **todas** as condições. Atenção a "acima de" x "a partir de".
6. Denominador = colunas **viáveis** da tabela dada. Tabela completa = 2ⁿ; tire as inviáveis.

**Transição de estado (4.2.4)**

7. O **estado inicial conta** como visitado.
8. Cada critério tem seu denominador: **estados** | **transições válidas** | **estados × eventos** (todas as transições).
9. Conte transições **distintas**. A sequência mais longa costuma repetir.

**Gerenciamento (capítulo 5)**

10. **Três pontos:** E = (a + 4m + b) ÷ 6 e DP = (b − a) ÷ 6.
11. **Proporção:** médias → proporção → multiplicar. Nunca copie um projeto só.
12. **Priorização:** o pré-requisito **herda** a prioridade de quem ele destrava; entre os liberados, vence a maior prioridade.

**Para toda questão de cálculo**

13. Rascunho em tabela, um item por linha, e só contar no final.
14. Porcentagem: 100% ÷ total = quanto vale cada item.

## 4. Na hora da prova

- Leia cada questão até o fim procurando **"NÃO", "todas", "sempre", "principalmente"**.
- Faça as fáceis primeiro; marque as que travarem e volte no final.
- Questões fáceis valem o mesmo ponto: leia com a mesma calma.
