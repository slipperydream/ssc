# ssc
SCC world
A pointcrawl campaign world seeded with DCC RPG adventures.

```mermaid
graph TD;
    B[Bitterweed Barrow] --- E
    B --- P[Portnelle]
    B --- D[Dorcaster]
    B --- W[Wetherby]
    B --- DDP>Dead Dragon Peak]
    W --- TTM
    subgraph E[Valley of Eng]
    E1[Eng] --- E2((Ivy Woods))
    end
    subgraph TTM[Trooltooth Mountains]
    H[Hirot] --- R[Riverside]
    H --- Ph[Philbin]
    end
    E --- P
    P --- D
    W --- B
    P --- TI[Tolomak Islands]
    TTM --- Pu[Punjar]
