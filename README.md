# Monitor de APIs

Um monitor simples e leve de APIs.

Permite acompanhar em tempo real o status de múltiplas APIs, exibindo:

- Status (online/offline)
- Código de resposta
- Tempo de resposta (ms)
- Histórico das últimas requisições

---

## Funcionalidades

- Monitoramento automático
- Tempo de resposta das APIs
- Indicador visual de status
- Suporte a múltiplas APIs (abas)
- Tema claro/escuro

---

## ⚙️ Como funciona

As APIs são configuradas dentro de um array no próprio código:

```js
const apis = [
  {
    name: "API de idiomas",
    url: "https://linguaflow-studio-api.onrender.com/api/Auth/test",
    interval: 15000,
  },
];
```
