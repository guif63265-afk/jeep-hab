# Jeep Hab — sistema de geração de chaves

Página estática baseada no arquivo enviado, com geração de chaves via Firebase Realtime Database.

## Execução local

```bash
python3 -m http.server 8080
```

Depois, abra `http://localhost:8080`.

## Observações

- O frontend usa a configuração Firebase já presente no arquivo original.
- As regras de segurança do Realtime Database não são alteradas por este projeto.
- Antes de uso público em produção, configure regras Firebase restritivas e uma camada de backend para impedir abuso e controlar a emissão de chaves.
