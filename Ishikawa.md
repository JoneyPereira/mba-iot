## Diagrama de Ishikawa em Mermaid

```mermaid
graph TB
    P[Bug em produção que derrubou o sistema] --> M1[Métodos]
    P --> M2[Máquinas/Infraestrutura]
    P --> M3[Pessoas]
    P --> M4[Materiais/Código]
    P --> M5[Ambiente]
    P --> M6[Medições/Testes]

    M1 --> M1a[Deploy feito manualmente]
    M1 --> M1b[Sem checklist de revisão de código]
    
    M2 --> M2a[Servidor com versão antiga do Java]
    M2 --> M2b[Ambiente de staging não replica o de produção]
    
    M3 --> M3a[Desenvolvedor júnior sem supervisão]
    M3 --> M3b[Equipe sobrecarregada]
    
    M4 --> M4a[Função mal testada no backend]
    M4 --> M4b[Uso de lib desatualizada]
    
    M5 --> M5a[Alta carga de usuários não prevista]
    
    M6 --> M6a[Testes automatizados estavam desativados]
    M6 --> M6b[Falta de testes de carga e estresse]
```

## Diagrama de Ishikawa
                            Bug em produção
                                   ↑
           ┌────────────┬────────────┬────────────┬────────────┐
           │            │            │            │            │
       MÉTODOS       MÁQUINAS     PESSOAS     MATERIAIS    MEDIÇÕES
     - Procedimento   - Máquina     - Falta      - Matéria    - Instrumento
       errado           mal         de treino      prima         descalibrado
                        regulada                  vencida
