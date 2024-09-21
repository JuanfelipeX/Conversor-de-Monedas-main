<p align="center">
  <img src="https://github.com/DavidVF7/Conversor-de-Monedas/assets/103916971/645bfae6-38cf-4f90-add7-8f9b3929cb5a" alt="Logo Conversor de Monedas">
</p>

# Conversor de Monedas 💵💱💶

Este proyecto fue creado como parte del Challenge "Conversor de Monedas" propuesto por **Alura Latam** en colaboración con **Oracle** dentro del programa ONE, como parte de la formación en Back-End.

## Descripción 📝

El Conversor de Monedas es una aplicación en **Java** que te permite convertir diferentes divisas en tiempo real utilizando una API de tasas de cambio. El programa realiza solicitudes a la API, interpreta la respuesta en formato JSON, selecciona las monedas deseadas y presenta los resultados de manera clara. Además, guarda un historial de conversiones, registrando la fecha y hora de cada consulta, permitiendo a los usuarios revisar su actividad anterior.

## Tecnologías Utilizadas 💻

- **Lenguaje de Programación:** Java
- **API de Tasas de Cambio:** Se utilizó una API para obtener las tasas de conversión actualizadas.
- **Biblioteca:** **Gson** fue empleada para convertir el JSON de la API en objetos Java manipulables.
- **Control de Versiones:** **Git/GitHub** fueron usados para el control de versiones del código.
- **IDE:** El desarrollo se realizó en **IntelliJ IDEA**, que permitió la escritura, depuración y ejecución del código.

## Estructura de Clases y Funcionalidades 🧩

### `Calculos.java`

Esta clase se encarga de gestionar la lógica de las conversiones de divisas, almacenando valores, realizando cálculos y generando respuestas al usuario.

### `ConsultaConversion.java`

Clase encargada de realizar las solicitudes a la API externa para obtener los tipos de cambio entre diferentes monedas.

### `GeneradorDeArchivos.java`

Su función principal es registrar el historial de conversiones en un archivo de texto.

### `Principal.java`

Es el punto de entrada principal del programa, donde se gestiona la interacción con el usuario a través de la consola. Ofrece un menú con opciones y controla el flujo de las conversiones.

## Instrucciones de Uso 🚀

1. Clona este repositorio en tu computadora local.
2. Abre el proyecto en **IntelliJ IDEA** o en tu IDE favorito.
3. Ejecuta la clase `Principal.java` para iniciar el programa.
4. Sigue las indicaciones en pantalla para realizar tus conversiones de divisas.

¡Empieza a convertir monedas de manera rápida y sencilla!

## Video de Demostración 🎥

Si quieres ver cómo funciona el proyecto, puedes consultar el siguiente enlace:

[Ver Demostración](https://youtu.be/a42KEl1l0kY)

---

Desarrollado con 💻 por **Juan Felipe Jimenez Pacheco**
