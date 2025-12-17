# Funções DAX

## SUM

Calcular a somatória de uma coluna.

```
SUM(coluna)
```

## AVERAGE

Calcular a média de uma coluna.

```
AVERAGE(coluna)
```

## MAX

Extrai o valor máximo de uma coluna.

```
MAX(coluna)
```
## MIN

Extrai o valor mínimo de uma coluna.

```
MIN(coluna)
```

## Operações Aritméticas 

```
[colunaA] + [colunaB]
[colunaA] - [colunaB]
[colunaA] * [colunaB]
[colunaA] / [colunaB]
```

## COUNT

Contagem da quantidade de valores não-nulos em uma coluna.

```
COUNT(coluna)
```

## DISTINCTCOUNT

Contagem de valores distintos em uma coluna.

```
DISTINCTCOUNT(coluna)
```

## COUNTROWS

Contagem de linhas de uma tabela.

```
COUNTROWS('tabela')
```

## IF

Decisão.

```
IF(condição, valor se verdadeiro, valor se falso)
```

## Operadores Lógicos

### E

```
condiçãoA && condiçãoB
```

### OU

```
condiçãoA || condiçãoB
```

## CONCATENATE

Concatenação de valores em texto.

```
CONCATENATE(colunaA, colunaB)
```

## RELATED

Acessar valor em outra tabela.

```
RELATED(coluna em outra tabela)
```

## CALCULATE

Calcular uma fórmula utilizando filtros.

```
CALCULATE(fórmula, filtro1, filtro2, ..., filtroN)
```

## FILTER

Filtrar os valores de uma tabela para criar uma tabela nova.

```
FILTER('tabela', filtro)
```
