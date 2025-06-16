## Capítulo 4 - Machine Learning com Java

### Tipos de aprendizado:

- Supervisionado
- Não supervisionado

### Exemplo com Smile:

```java
int[][] data = { {1, 0}, {0, 1}, {1, 1} };
int[] labels = {1, 0, 1};
SoftClassifier<int[]> knn = KNN.learn(data, labels, 2);
int prediction = knn.predict(new int[]{0, 0});
```

