## Capítulo 6 - Visão Computacional com Java

### OpenCV com Java:

- Detecção de rosto
- Processamento de imagens

```java
System.loadLibrary(Core.NATIVE_LIBRARY_NAME);
Mat image = Imgcodecs.imread("foto.jpg");
Imgproc.cvtColor(image, image, Imgproc.COLOR_BGR2GRAY);
```

