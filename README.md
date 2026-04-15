# agenda-de-shows[README-template.md](https://github.com/user-attachments/files/26317498/README-template.md)
# [Nome do Projeto]

## Sobre o Projeto
**Projeto:** [nome do projeto da lista]
**Problema que resolve:** [uma frase descrevendo o problema]

## Integrantes
| Nome | GitHub |
|------|--------|
| [Nome 1] | [@usuario1] |
| [Nome 2] | [@usuario2] |
| [Nome 3] | [@usuario3] |

## Arquitetura
``` mermaid
---
config:
  theme: mc
---
flowchart LR
    A[Logar conta do Spotify] --> B[Escolher gênero favorito]
    B --> C[Escolher localização]
    C --> D{Escolher Show perto de você}
    D --> Artista
    D --> Localização
    D --> Preço
    D --> Data
```
