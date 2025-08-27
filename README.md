```mermaid
graph TD
    A[População de Pacientes Elegíveis] --> B{Randomização};
    B --> C[Grupo Intervenção <br> (Recebe o novo tratamento)];
    B --> D[Grupo Controle <br> (Recebe o comparador)];
    C --> E{Acompanhamento e Medição do Desfecho};
    D --> E;
    E --> F[Análise Comparativa dos Resultados];
```
