# Aluno
* 216698: Gabriella Serrano Santana

# Análise do Artigo CandiDATA: um dataset para análise das eleições no Brasil

| campo | valor |
|------------|----------------------------------------|
| referência | VASCONCELOS, Felipe F.; TAVARES, João V. S.; RIBEIRO, Murilo U.; COUTINHO,  Fabio J.; CLARINDO, João Paulo. CandiDATA: um dataset para análise das eleições no Brasil. 2021. Artigo - Universidade Federal de Alagoas, Maceió, AL, 2021; Universidade de São Paulo, São Carlos, SP, 2021. |
| link       | [Artigo](https://drive.google.com/file/d/10hh-MLRk9omaGwdormsXwQa7O7XHXFhT/view) |
| dataset | [Repositório Público do Dataset](https://github.com/felipeVsc/CandiDATA) |
| formato | CSV |

## Resumo

O CandiData é um dataset disponível gratuitamente em formato aberto que tem como objetivo permitir a análise dos dados das eleições brasileiras dos anos de 1945 a 2020. Ele foi construído  com base nos dados disponibilizados pelo portal do TSE. Os dados fornecidos pelo TSE apresentavam problemas como a falta de padronização e consistência, então nesse novo dataset eles passaram pelos processos de padronização, limpeza e transformação. Além disso, foram acrescentados dados ausentes dos anos anteriores a 1996. Tais mudanças facilitaram a integração com bases externas e a consulta de dados de maneira correta.
Esse dados são de extrema importância, pois eles permitem analisar diversas características de eleições assim auxiliando em tomadas de decisões de governantes, gestores, pesquisadores e demais interessados.

## Perguntas de pesquisa/análises

Os dados disponibilizados pelo TSE são padronizados e consistentes a ponto de serem uma fontes confiável para análise da democracia do país e para se integrar com bases externas?

Qual é o grau de maturidade da democracia do país?

Qual é a porcentagem de eleitores que foram identificados por biometria (método que evita fraudes) nas últimas eleições?

Análise da participação feminina na política.

## Trabalhos relacionados

Camargo et al. (2016) tem como objetivo encontrar padrões nos perfis de candidatos a vereador em municípios do Rio Grande do Sul, a partir de dados do TSE referentes as eleições do ano de 2012. Os autores afirmam que os dados do TSE precisaram ser convertidos para arquivos do tipo Comma-Separated Values (CSV) e alterados para a padronização de atributos. Posteriormente, aplicaram técnicas de busca de dados para a identificação de padrões, utilizando o algoritmo J48. Os resultados apresentados apontam como fatores relevantes para a eleição no cargo de vereador: a carreira política; a idade; o grau de escolarização e o género do candidato.

Filho and Pappa (2015) desenvolveram uma ferramenta para a caracterização demográfica de usuários do Twitter. A partir da análise de mensagens postadas e de informações do perfil, são inferidos o género, a idade e a classe social do usuário. Para demonstrar o uso da ferramenta, os autores utilizaram dados de eleitores obtidos junto ao repositório do TSE, de modo a construir uma distribuição demográfica real para compará-la com a distribuição demográfica construída a partir dos dados de usuários do Twitter.

CEPESP (2020) desenvolveu a plataforma CepespData com o objetivo de facilitar o acesso integrado as bases de dados disponibilizadas pelo TSE em seu repositório. Os dados mantidos na plataforma podem ser obtidos diretamente no site da CepespData ou através de Application Programming Interfaces (APIs) que podem ser acessadas através de linguagens de programação como R e Python. O trabalho supera alguns problemas encontrados no repositório do TSE, entretanto, os dados são restritos ao período de 1998 a 2018.
