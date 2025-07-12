# Documentação Técnica – Topologia de Rede da Empresa XYZ

**Autor:** Equipe de Segurança da Informação  
**Data:** 12/07/2025  
**Versão:** 1.0

## Sumário Executivo
Foi realizada a documentação da rede da matriz e filiais da empresa XYZ, visando melhor gestão de ativos e segmentação. Identificamos oportunidades de segmentação e melhorias na autenticação VPN.

## Objetivo
Documentar a infraestrutura de rede atual da empresa XYZ, incluindo matriz e duas filiais.

## Escopo
Infraestrutura de rede física e lógica das unidades da empresa, incluindo VPNs, VLANs e ativos principais.

## Metodologia
Foram utilizados: entrevistas com TI, `nmap`, coleta de arquivos de configuração de roteadores/switches e análise dos mapas existentes.

## Diagrama de Rede
(incluir imagem draw.io ou ASCII)

## Diagnóstico (Achados)
1. Falta de segmentação adequada entre setores.
2. VPN com autenticação apenas por senha.
3. Switches legados sem firmware atualizado.

## Recomendações
- Implementar VLANs para setores críticos.
- Habilitar MFA na VPN.
- Atualizar firmwares dos switches de borda.

## Plano de Ação (80/20)

| Ação                     | Impacto | Facilidade | Prioridade |
|--------------------------|---------|------------|------------|
| Implantar VLANs          | Alto    | Média      | Alta       |
| Habilitar MFA na VPN     | Alto    | Alta       | Alta       |
| Atualizar firmware       | Médio   | Baixa      | Média      |

## Conclusão
A topologia atual atende ao básico, mas carece de controles segmentados e boas práticas de segurança.

## Anexos
- Mapas de rede
- Saídas do Nmap
- Prints de configurações
