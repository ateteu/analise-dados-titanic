# Análise de Dados do Titanic

Projeto de análise exploratória de dados (EDA) utilizando o dataset clássico do Titanic.

## Objetivo

Explorar e entender os dados dos passageiros, identificando padrões e fatores que influenciaram a sobrevivência.

## Dataset

O dataset contém informações sobre passageiros do Titanic:

- Identificador
- Nome
- Idade
- Sexo
- Classe
- Número de parentes próximos e cônjuges a bordo (SibSp)
- Número de parentes (pais) e filhos a bordo (Parch)
- Tarifa paga
- Cabine
- Identificador do tiquete
- Porto de embarque
- Se sobreviveram ou não ao desastre

Fonte: https://github.com/datasciencedojo/datasets

## Pipeline

O projeto segue as seguintes etapas:

1. Carregamento dos dados
2. Inspeção inicial do dataset
3. Tratamento de valores nulos
4. Análise exploratória
5. Visualização dos dados

## Principais análises

Durante a exploração, foram analisados:

- Distribuição de idade dos passageiros
- Proporção de sobreviventes
- Impacto do sexo e idade na sobrevivência
- Influência da classe social na sobrevivência
- Dentre outros

## Insights

- Pela investigação inicial, notou-se que o dataset já se encontrava relativamente bem tratado: não havia valores absurdos ou muitos campos faltantes. Porém, a coluna `Cabin` não apresentava dados suficientes e foi ignorada na análise
- A maioria dos passageiros embarcou no porto de Southampton (Inglaterra)
- A faixa etária dos passageiros se concentrava principalmente entre 20 a 40 anos
- Há famílias a bordo do Titanic, mas grande parte dos passageiros (~ 60%) estava desacompanhada
- Uma parcela significativa dos passageiros a bordo embarcou na 3a classe (cerca de 55%), o que reflete na predominância de passagens abaixo de $100
- No desastre, mulheres tiveram uma taxa de sobrevivência significativamente maior que homens, em todas as faixas etárias
- Passageiros de classes mais altas tiveram maior chance de sobrevivência
- Idosos (60+ anos) tiveram a maior taxa de mortalidade (acima de 70%)
- Crianças (especificamente bebês) também apresentaram taxa de sobrevivência mais elevada

## Conclusão

Com base nesses insights, é possível inferir que houve um claro protocolo de priorização de mulheres e crianças durante o desastre, o que resultou em maiores taxas de sobrevivência nesses grupos.

Além disso, observa-se um padrão de desigualdade socioeconômica: poucos passageiros das classes mais altas, que pagaram tarifas mais elevadas, apresentaram maior taxa de sobrevivência; enquanto passageiros da 3ª classe, com tarifas mais baixas, foram mais afetados.

De forma geral, este projeto contribuiu para consolidar habilidades em manipulação de dados, análise exploratória e visualização utilizando Pandas, NumPy e MatPlotLib.
