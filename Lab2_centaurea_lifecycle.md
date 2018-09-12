```mermaid
graph TB
subgraph population
A(seed)--# of survivors-->B(jeuvenile)
B--# of survivors-->C(vegatative)
C--# of survivors-->D(flowering)
D-->D
C-->C
A-->A
D-->B
B-->D

end

A-->E(death)
B-->F(death)
C-->G(death)

style A fill:#44ffbf, stroke:#333
style B fill:#44ffbf, stroke:#333
style C fill:#44ffbf, stroke:#333
style D fill:#44ffbf, stroke:#333


style E fill:#b6ff90, stroke:#333
style F fill:#b6ff90, stroke:#333
style G fill:#b6ff90, stroke:#333



```

Flow chart of potential outcomes at each stage of the centaurea life cycle.