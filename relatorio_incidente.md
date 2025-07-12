# Relatório de Incidente – Malware via E-mail (Caso Fictício)

**Autor:** Blue Team XYZ  
**Data:** 10/07/2025  
**Versão:** 1.1

## Sumário Executivo
Um malware foi identificado após um funcionário abrir um anexo suspeito. A resposta rápida evitou movimentações laterais. Não houve exfiltração.

## Objetivo
Registrar e analisar o incidente de segurança ocorrido no dia 08/07/2025.

## Escopo
Apenas o host afetado, e-mails recebidos e logs do antivírus e firewall.

## Metodologia
Análise de logs, sandbox de malware, coleta de IOC e entrevistas com o usuário.

## Diagnóstico
- Anexo `.doc` com macro maliciosa.
- E-mail passou pelo filtro com score abaixo do limiar.
- Usuário sem treinamento recente.

## Recomendações
- Reforçar regras de spam.
- Desabilitar macros por padrão.
- Fazer campanha de conscientização.

## Plano de Ação (80/20)

| Ação                      | Impacto | Facilidade | Prioridade |
|---------------------------|---------|------------|------------|
| Desabilitar macros        | Alto    | Alta       | Alta       |
| Treinamento de phishing   | Médio   | Alta       | Alta       |

## Conclusão
Incidente foi contido. Reforço de filtros e educação reduzirá o risco futuro.

## Anexos
- Hash do malware
- Print do e-mail
- Log de antivírus
