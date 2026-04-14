# Arquitetura (alto nível) — Plataforma e Dados

[Voltar ao README](../README.md)

O material descreve uma inovação digital com três pilares:
- **Integração Gov.BR** (login único e gestão de acesso) para maior segurança de autenticação.
- **Plataforma digital** para controle de credenciamentos, informações operacionais e cadastro de propostas.
- **Inteligência Artificial** para apoiar a formulação de propostas (clareza, estrutura e capacidade de síntese), com validação humana.

## Componentes recomendados (para replicação)
- **Identidade e acesso**: login único (ideal) ou alternativa local com trilha de auditoria.
- **Credenciamento**: registro de participação, oficina, território, perfil (quando aplicável).
- **Propostas**: captura de insumos, versão estruturada, status (rascunho/validada/priorizada).
- **Priorização**: mecanismo de votação (QR Code) e regras de pontuação.
- **Publicação/observatório**: página pública com propostas eleitas e lista completa para consulta e auditoria social.
- **Dashboards**: métricas operacionais e estratégicas (participação, propostas, votos, jornada).

## Dados mínimos (campos)
Veja o template em `03-Plataforma_Digital_e_Dados/Modelo_de_Dados_e_Padroes.csv` (pode ser usado mesmo sem plataforma).

---

### Navegação
- [README](../README.md)
- Anterior: [RACI e Papéis](../02-Metodologia_e_Fluxos/RACI_e_Papeis.md)
- Próximo: [Políticas de Segurança e Auditoria](./Politicas_de_Seguranca_e_Auditoria.md)
