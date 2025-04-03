# Comparação entre Oracle Database 18c e 19c

## Introdução
O Oracle Database 18c e 19c fazem parte da família Oracle 12c, mas cada versão traz melhorias significativas. Enquanto o 18c foi mais uma versão de transição, o 19c se consolidou como a versão de suporte a longo prazo (Long-Term Support - LTS). Abaixo está uma comparação detalhada entre ambas, incluindo suas vantagens e desvantagens.

---
## Comparação Geral
| Característica           | Oracle 18c | Oracle 19c |
|-------------------------|------------|------------|
| **Tipo de Suporte**     | Suporte de curto prazo (Innovation Release) | Suporte de longo prazo (Long-Term Release) |
| **Automação**           | Introdução da automação de algumas tarefas de DBA | Melhorias no Automatic Indexing e Data Guard |
| **Gerenciamento de Indexação** | Indexação manual e sem otimizações automáticas | Introdução do *Automatic Indexing*, melhorando a performance |
| **Suporte a JSON**      | Suporte a JSON, mas com algumas limitações | JSON nativo para melhor manipulação e desempenho |
| **Data Guard**          | Básico, sem grandes otimizações | Melhor recuperação e failover automático mais eficiente |
| **Quarentena de Consultas** | Não disponível | SQL Quarantine para isolar queries problemáticas |
| **Hybrid Partitioned Tables** | Não disponível | Introdução do conceito de partições híbridas |
| **Segurança**           | Melhorias na criptografia e autenticação | *Gradual Database Password Rollover* para transição suave de senhas |
| **Banco de Dados In-Memory** | Necessita licença para uso | Versão *Base Level* gratuita até 16GB |

---
## Principais Melhorias no Oracle 19c
1. **Automatic Indexing**: Redução do esforço manual para otimização de índices.
2. **Melhor suporte a JSON**: Melhor performance no armazenamento e manipulação de dados JSON.
3. **Quarentena de Queries**: Identificação automática de consultas problemáticas e isolamento.
4. **Hybrid Partitioned Tables**: Combinação de partições internas e externas.
5. **Suporte a Longo Prazo**: Oracle 19c é uma versão LTS, o que significa mais estabilidade e atualizações por mais tempo.
6. **Otimização do Data Guard**: Redução do tempo de failover e melhora na replicação.
7. **Segurança aprimorada**: Mudanças graduais de senha para minimizar impactos.

---
## Principais Falhas e Desafios
### Oracle 18c
- **Curta duração de suporte**: Atualizações descontinuadas rapidamente.
- **Otimização manual de índices**: Sem *Automatic Indexing*, era necessário ajustes manuais frequentes.
- **Menor eficiência no Data Guard**: Failover e replicação menos otimizados.
- **Problemas de performance em JSON**: Manipulação menos eficiente.

### Oracle 19c
- **Consome mais recursos**: Algumas novas funcionalidades exigem maior poder computacional.
- **Mudanças estruturais exigem ajustes**: A introdução do *Automatic Indexing* pode impactar bancos muito otimizados manualmente.
- **Migração pode ser trabalhosa**: Dependendo da arquitetura do 18c, a atualização pode exigir ajustes cuidadosos.

---
## Conclusão
Se você busca estabilidade e suporte prolongado, a migração para o Oracle 19c é altamente recomendada. Ele oferece automação, melhor desempenho, maior segurança e suporte a longo prazo. No entanto, para empresas que não podem lidar com mudanças estruturais imediatas, a migração pode exigir planejamento e ajustes adicionais.

### Links úteis:
- [GitHub: Claudio Augusto Pereira](https://github.com/claudioaugusto1969)
- [LinkedIn: Claudio Augusto Pereira](https://www.linkedin.com/in/claudio-augusto-513216190/)

