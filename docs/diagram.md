```mermaid
flowchart LR
    %% Aktor
    U[Użytkownik]

    %% Granica systemu
    subgraph SYS[Prosty system zarządzania zadaniami]
        A[Dodaj zadanie]
        B[Edytuj zadanie]
        C[Usuń zadanie]
        D[Przeglądaj zadania]
        E[Filtruj zadania]
        F[Sortuj zadania]
    end

    %% Relacje aktora do przypadków użycia
    U --> A
    U --> B
    U --> C
    U --> D
    U --> E
    U --> F
