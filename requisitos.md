# Requisitos de Dados

## 1. Objetivo

Definir os requisitos para preparar a base de legislação trabalhista.

## 2. Escopo

Esta etapa abrange a importação, auditoria, exploração, limpeza,
estruturação e divisão dos textos em chunks.

## 3. Requisitos funcionais

| ID | Requisito |
|---|---|
| RF-D01 | Importar os arquivos do repositório de legislação e registrar sua origem e versão. |
| RF-D02 | Inventariar os arquivos, identificando formato, tamanho e integridade por hash. |
| RF-D03 | Identificar arquivos vazios, duplicações, falhas de leitura e possíveis problemas de extração ou codificação. |
| RF-D04 | Registrar fontes, normas e informações temporais disponíveis, sinalizando o que não foi verificado. |
| RF-D05 | Produzir estatísticas e visualizações sobre a composição, a estrutura e a qualidade do corpus. |
| RF-D06 | Limpar os textos preservando o conteúdo jurídico, a hierarquia dos dispositivos e as notas de alteração, revogação e veto. |
| RF-D07 | Estruturar os documentos com identificadores únicos e metadados que permitam localizar sua origem. |
| RF-D08 | Gerar chunks vinculados aos documentos e dispositivos originais, preservando o contexto necessário à interpretação. |
| RF-D09 | Exportar os dados preparados e os relatórios de qualidade para as próximas etapas do projeto. |

## 4. Requisitos de qualidade

| ID | Requisito |
|---|---|
| RQ-D01 | Preservar os arquivos originais separados dos dados transformados. |
| RQ-D02 | Registrar versões dos dados, código, dependências e parâmetros utilizados no processamento. |
| RQ-D03 | Permitir a reprodução das transformações por meio de código e instruções documentadas. |
| RQ-D04 | Validar campos obrigatórios, identificadores únicos, texto não vazio e referências de origem antes da indexação. |
| RQ-D05 | Registrar falhas e pendências sem descartar ou corrigir conteúdo silenciosamente. |
| RQ-D06 | Manter credenciais e dados pessoais fora do repositório público e dos relatórios compartilhados. |

## 5. Condição de conclusão

A preparação será considerada concluída quando a base estruturada
e os chunks estiverem disponíveis, as validações forem executadas
e as limitações e pendências estiverem documentadas.

A presença de uma norma ou de uma data no texto não comprova,
por si só, a completude ou a vigência do conteúdo.
