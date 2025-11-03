# Codelabs

## Aspectos interesantes

### Greeting Card

El primer Codelab que realicé fue uno llamado Greeting Card. Fue simple, pero fue interesante en muchos aspectos al ser el primer vistazo al uso de Android Studio y al diseño a realizar. Resultó curioso la forma de declarar temas, pareciendo que en realidad es bastante sencillo de realizar.

```
@Preview(showBackground = true)
@Composable
fun GreetingPreview() {
    GreetinCardTheme {
        Greeting("María")
    }
}
```

Pensaba que habría que hacer más cambio que solo eso para poder cambiar tal vez la palabra o el contenido de lo que salía. Lo mismo pasaba con el color ded fondo, solo fue añadir un poco de texto, no hizo falta declarar gran cosa. Por otro lado, se hizo cómodo ver el uso de @Composable. Además, estaba el uso del @Preview, para poder ver un ejemplo del diseño sin ejecutar, no sabía exactamente como era al inicio, incluso pensaba que lo que se moestraba era la propia ejecución, que se hacía tanto fuera del móvil emulado como en el mismo.

### Dice Roller

En el segundo Codelab realizado se señala como interesante la forma de introducir las imágenes, puesto que se desconocía esa forma de hacerlo. Cabe añadir que ciertamente era curioso la forma en la que se consigue que aparezca un número aleatorio. Generar el número es sencillo, pero que eso se conecte directamente con la imagen del dado correspondiente. No solo eso, sino que se tiene cuidado de que los números de los lados sean correctos. Son ejercicios simples, pero para una persona que apenas a usado Android Studio, mientras varias cosas.
