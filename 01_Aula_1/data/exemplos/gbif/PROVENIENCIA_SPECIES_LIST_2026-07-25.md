# Proveniência das Species lists — Aula 1

Consulta auditada em 25 de julho de 2026.

## Filtros comuns

- `OCCURRENCE_STATUS = PRESENT`
- `TAXON_KEY = P` — Plantae; o predicado registra o checklist COL XR
  `7ddf754f-d193-4cc9-b351-99906754a03b`
- `GADM_GID = BRA.13.546_2, BRA.13.46_2, BRA.13.344_2`
- `BASIS_OF_RECORD = PRESERVED_SPECIMEN`
- formato `SPECIES_LIST`

## Solicitação GBIF Backbone

- Download: [0008869-260721160103020](https://www.gbif.org/occurrence/download/0008869-260721160103020)
- DOI: [10.15468/dl.bu5m5b](https://doi.org/10.15468/dl.bu5m5b)
- `request.checklistKey = d7dddbf4-2cf0-4f39-9b2a-bb099caae36c`
- Arquivo preservado: `species_list_gbif/0008869-260721160103020.zip`

## Solicitação Catalogue of Life Extended Release

- Download: [0008956-260721160103020](https://www.gbif.org/occurrence/download/0008956-260721160103020)
- DOI: [10.15468/dl.5yjx2e](https://doi.org/10.15468/dl.5yjx2e)
- `request.checklistKey = 7ddf754f-d193-4cc9-b351-99906754a03b`
- Arquivo preservado: `species_list_col/0008956-260721160103020.zip`

## Resultado observado

- cada ZIP contém somente um CSV tabulado, sem `metadata.txt`;
- cada CSV possui 700 linhas e 22 colunas;
- `numberOfOccurrences` soma 1423 em cada arquivo;
- os conjuntos integrais de linhas são iguais; somente a ordem original difere;
- há 95
  linhas com `scientificName` diferente de `acceptedScientificName` dentro de cada lista;
- ambos os arquivos usam predominantemente identificadores alfanuméricos.

## Interpretação

A API comprova que backbones diferentes foram solicitados, mas os CSVs exportados não
materializam tratamentos diferentes. O resultado não prova equivalência entre o GBIF
Backbone legado e o COL XR. Ele documenta o comportamento observado do exportador
Species list durante a transição taxonômica do GBIF.
