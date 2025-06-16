## Capítulo 7 - Integração com APIs de IA

### Exemplo com OpenAI API:

```java
HttpClient client = HttpClient.newHttpClient();
HttpRequest request = HttpRequest.newBuilder()
    .uri(URI.create("https://api.openai.com/v1/chat/completions"))
    .header("Authorization", "Bearer SUA_CHAVE")
    .POST(HttpRequest.BodyPublishers.ofString(payload))
    .build();
```

### Resposta JSON:

```json
{
  "choices": [
    {
      "message": {
        "content": "Claro, aqui está seu código Java com IA!"
      }
    }
  ]
}
```
