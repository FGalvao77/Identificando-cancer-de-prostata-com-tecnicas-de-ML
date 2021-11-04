# Identificando câncer de próstata com técnicas de ML

**Câncer de próstata**

No Brasil, o câncer de próstata é o segundo mais comum entre os homens (atrás apenas do câncer de pele não-melanoma). Em valores absolutos e considerando ambos os sexos, é o segundo tipo mais comum. A taxa de incidência é maior nos países desenvolvidos em comparação aos países em desenvolvimento.

A próstata é uma glândula que só o homem possui e que se localiza na parte baixa do abdômen. Ela é um órgão pequeno, tem a forma de maçã e se situa logo abaixo da bexiga e à frente do reto (parte final do intestino grosso). A próstata envolve a porção inicial da uretra, tubo pelo qual a urina armazenada na bexiga é eliminada. A próstata produz parte do sêmen, líquido espesso que contém os espermatozoides, liberado durante o ato sexual.

Mais do que qualquer outro tipo, é considerado um câncer da terceira idade, já que cerca de 75% dos casos no mundo ocorrem a partir dos 65 anos. O aumento observado nas taxas de incidência no Brasil pode ser parcialmente justificado pela evolução dos métodos diagnósticos (exames), pela melhoria na qualidade dos sistemas de informação do país e pelo aumento na expectativa de vida.

Alguns desses tumores podem crescer de forma rápida, espalhando-se para outros órgãos e podendo levar à morte. A maioria, porém, cresce de forma tão lenta (leva cerca de 15 anos para atingir 1 cm³ ) que não chega a dar sinais durante a vida e nem a ameaçar a saúde do homem.

- Fonte: https://www.inca.gov.br/tipos-de-cancer/cancer-de-prostata


O nosso desafio é criar um modelo pra predizer o `câncer de próstata` através de alguns atributos.

E para esse desafio utilizaremos o classificador [multinomial Naïve Bayes](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html).

A base de dados utilizada foi extraída do [Kaggle](https://www.kaggle.com/sajidsaifi/prostate-cancer).
