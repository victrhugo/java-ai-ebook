## Capítulo 5 - NLP com Java

### Técnicas comuns:

- Tokenização
- Stemming
- Análise de sentimento

### Usando OpenNLP:

```java
TokenizerModel model = new TokenizerModel(new FileInputStream("pt-token.bin"));
Tokenizer tokenizer = new TokenizerME(model);
String[] tokens = tokenizer.tokenize("ChatGPT é incrível!");
```

