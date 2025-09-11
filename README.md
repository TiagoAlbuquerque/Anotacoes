```mermaid
graph TD
    A[PCR Pediátrica: Iniciar RCP de Alta Qualidade] --> B{Analisar Ritmo};
    B --> C[Ritmo Chocável <br> (FV/TVSP)];
    B --> D[Ritmo Não Chocável <br> (Assistolia/AESP)];

    C --> C1[Choque 2 J/kg];
    C1 --> C2[RCP por 2 min];
    C2 --> C3{Ritmo persiste?};
    C3 -- Sim --> C4[Choque 4 J/kg];
    C4 --> C5[RCP por 2 min <br> + Administrar Epinefrina];
    C5 --> C6{Ritmo persiste?};
    C6 -- Sim --> C7[Choque 4-10 J/kg];
    C7 --> C8[RCP por 2 min <br> + Administrar Amiodarona];
    C8 --> C3;

    D --> D1[RCP por 2 min];
    D1 --> D2[Administrar Epinefrina <br> (assim que houver acesso)];
    D2 --> D3[Repetir RCP por 2 min];
    D3 --> D4{Analisar Ritmo};
    D4 -- Não Chocável --> D3;
    D4 -- Chocável --> C;

    C6 -- Não --> E[ROSC? Cuidados Pós-PCR];
    C3 -- Não --> E;
    D4 -- Pulso Presente --> E;
```
