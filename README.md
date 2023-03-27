# MOVIE_SERVER

```mermaid
flowchart LR;
    A(MOVIE_SERVER) -- GORLLA MUX --> B(GET ALL);
    A ----> C(GET BY ID);
    A ----> D(CREATE);
    A ----> E(UPDATE);
    A ----> F(DELETE);
```