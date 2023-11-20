# Revelando a relação entre integração contínua e revisão de código: Um estudo com 10 projetos de código fechado

## Resumo

As empresas adotaram a integração contínua (IC) e a revisão de código (RC) como práticas essenciais para monitorar e
melhorar continuamente a qualidade das alterações de software. Uma das principais motivações é o fato de que essas
práticas permitem a detecção e a resolução antecipadas de problemas de software e geraram resultados promissores em
projetos de código aberto e fechado. No entanto, há pouca compreensão da relação entre os aspectos de IC e RC em
projetos de código fechado. Por exemplo, não sabemos que influência as práticas de IC têm sobre a RC e vice-versa e como
as más práticas de IC podem prejudicar o processo de RC em projetos de código fechado. Portanto, neste estudo, nosso
objetivo é investigar se existe uma relação entre IC e RC em relação a (1) correlações existentes entre IC e RC, (2)
percepção das equipes de desenvolvimento acerca da relação entre IC e RC, (3) problemas causados por más práticas de IC
na RC e (4) benefícios e desafios gerados pela IC na RC. Para isso, coletamos e analisamos 32 métricas relacionadas aos
aspectos de IC e RC de 10 projetos de código fechado. Além disso, investigamos as percepções dos revisores de código
sobre as correlações existentes entre IC e RC, os benefícios e desafios do uso de IC e RC em projetos de software e o
impacto das más práticas de IC na RC. Os resultados revelam correlações entre métricas de IC e RC, indicando práticas da
IC que influenciam diretamente a RC. Foram identificadas 23 correlações fortes entre métricas nas matrizes individuais e
gerais, como o tempo de execução da IC impactando métricas da RC, como tempo de revisão e participação. Análises sugerem
que o tempo da IC pode afetar significativamente o da RC. Percepções das equipes mostraram concordância moderada sobre o
aumento do tempo total de revisão em relação ao tempo de execução da IC e mais pipelines executados. Más práticas na IC
podem impactar negativamente a RC, como divergências em branches, falta de testes em feature branches, passos manuais na
pipeline e scripts de build longos, aumentando o trabalho dos revisores. Algumas más práticas foram mencionadas poucas
vezes, indicando variação na frequência ou impacto. Destacaram-se benefícios da IC na RC, como detecção precoce de
problemas e bugs, distribuição eficiente de atualizações e redução de tarefas repetitivas. Desafios incluem garantir
qualidade do código e resolver conflitos durante a RC, mesmo com a implementação da IC.

## Artefatos

| Artefato                                  | Descrição                                                |
|-------------------------------------------|----------------------------------------------------------|
| [Mining tool](artefatos/mining-tool.zip)  | Ferramenta utilizada para coletar as métricas de IC e RC |
| [Correlações](artefatos/correlations.ods) | Dados gerais das correlações encontradas                 |
| [Dados gerais](artefatos/general)         | Arquivos das métricas para todos os projetos             |
| [Dados do projeto 22](artefatos/22)       | Arquivos das métricas para todos o projeto 22            |
| [Dados do projeto 26](artefatos/26)       | Arquivos das métricas para todos o projeto 26            |
| [Dados do projeto 36](artefatos/36)       | Arquivos das métricas para todos o projeto 36            |
| [Dados do projeto 39](artefatos/39)       | Arquivos das métricas para todos o projeto 39            |
| [Dados do projeto 41](artefatos/41)       | Arquivos das métricas para todos o projeto 41            |
| [Dados do projeto 54](artefatos/54)       | Arquivos das métricas para todos o projeto 54            |
| [Dados do projeto 55](artefatos/55)       | Arquivos das métricas para todos o projeto 55            |
| [Dados do projeto 56](artefatos/56)       | Arquivos das métricas para todos o projeto 56            |
| [Dados do projeto 78](artefatos/78)       | Arquivos das métricas para todos o projeto 78            |
| [Dados do projeto 133](artefatos/133)     | Arquivos das métricas para todos o projeto 133           |