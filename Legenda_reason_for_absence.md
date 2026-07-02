# Legenda da variável Reason for absence

Este arquivo documenta a legenda da variável Reason for absence do dataset **Absenteeism at work**.

A variável Reason for absence representa o motivo da ausência. Segundo a documentação original da base, os códigos de 1 a 21 correspondem a categorias do **International Code of Diseases (ICD/CID)**. Além disso, há 7 categorias adicionais sem CID, representadas pelos códigos de 22 a 28.

O código 0 aparece no arquivo de dados, mas não possui descrição explícita na documentação original. Por isso, neste MVP, ele será tratado como **não informado / sem classificação**.

## Legenda dos códigos

| Código | Descrição |
|---|---|
| 0 | Não informado / sem classificação |
| 1 | Doenças infecciosas e parasitárias |
| 2 | Neoplasias |
| 3 | Doenças do sangue e órgãos hematopoéticos e alguns transtornos envolvendo o mecanismo imunológico |
| 4 | Doenças endócrinas, nutricionais e metabólicas |
| 5 | Transtornos mentais e comportamentais |
| 6 | Doenças do sistema nervoso |
| 7 | Doenças dos olhos e anexos |
| 8 | Doenças do ouvido e da apófise mastoide |
| 9 | Doenças do aparelho circulatório |
| 10 | Doenças do aparelho respiratório |
| 11 | Doenças do aparelho digestivo |
| 12 | Doenças da pele e do tecido subcutâneo |
| 13 | Doenças do sistema osteomuscular e do tecido conjuntivo |
| 14 | Doenças do aparelho geniturinário |
| 15 | Gravidez, parto e puerpério |
| 16 | Afecções originadas no período perinatal |
| 17 | Malformações congênitas, deformidades e anomalias cromossômicas |
| 18 | Sintomas, sinais e achados clínicos e laboratoriais anormais, não classificados em outra parte |
| 19 | Lesões, envenenamentos e algumas outras consequências de causas externas |
| 20 | Causas externas de morbidade e mortalidade |
| 21 | Fatores que influenciam o estado de saúde e contato com serviços de saúde |
| 22 | Acompanhamento de paciente |
| 23 | Consulta médica |
| 24 | Doação de sangue |
| 25 | Exame laboratorial |
| 26 | Ausência injustificada |
| 27 | Fisioterapia |
| 28 | Consulta odontológica |

## Observação sobre uso no MVP

No notebook, a variável Reason for absence será utilizada como variável categórica. A legenda acima serve para interpretação humana e documentação dos códigos, mas o modelo de Machine Learning utiliza os códigos como categorias, sem incorporar diretamente as descrições textuais.

## Fonte

Documentação original baixada junto ao dataset **Absenteeism at work**, disponível no UCI Machine Learning Repository.
