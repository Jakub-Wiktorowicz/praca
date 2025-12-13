```
flowchart LR
    Brainstorming[Brainstorming] --> NewProduct[New Product]
    Trends[Trends] --> NewProduct
    Research[Research] --> NewProduct

    NewProduct --> Prototyping{Prototyping}

    Prototyping -- Yes --> Design[Design]
    Design --> Implementation[Implementation]
    Implementation --> Testing[Testing]

    Prototyping -- No --> Review[Review]
    Review --> Refinement[Refinement]
    Refinement --> QuickDesign[Quick Design]
    QuickDesign --> Prototyping
