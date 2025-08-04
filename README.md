# Arreglamecainador

<img width="1396" height="570" alt="image" src="https://github.com/user-attachments/assets/8d72411d-eabe-4318-8178-2a771a294515" />


![Versión](https://img.shields.io/badge/versión-1.0.5-blue)  
![Estado](https://img.shields.io/badge/estado-en%20prototipo-yellow)  
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

> Breve descripción del proyecto: ¿qué hace, para quién está hecho y por qué es importante?
La solución que se propuso es la realización de una aplicación que permita el reconocimiento estructural de los puntos del cuerpo a través de la cámara del dispositivo móvil durante la realización física de la mecánica de tiro en el baloncesto, este reconocimiento permitirá que la app analice si la posición corporal de la persona es correcta a la hora de lanzar pero si no lo es la aplicación le dará tips y recomendaciones al usuario de como mejorar el movimiento mecánico del tiro en el baloncesto. Siguiendo las recomendaciones a través de la practica el usuario gradualmente mejorara su porcentaje de acierto en los tiros.
---

## 🎯 Objetivo del Proyecto

Explica brevemente el propósito general:

- La mala ejecución de la técnica al tirar puede generar malos porcentajes de acierto y posibilidad de lesión 
La mecánica de tiro en baloncesto se refiere al conjunto de movimientos y técnicas que un jugador utiliza para lanzar el balón hacia el aro de manera precisa y eficiente. Es un aspecto clave para tener un buen porcentaje de acierto.
Esto nos llevó a preguntarnos ¿De qué manera se puede corregir automáticamente la postura del brazo para que la mecánica de tiro sea más efectiva y de esa manera aumentar el porcentaje de acierto en tiros de los jugadores y evitar posibles lesiones? 

- -Disminución del porcentaje de acierto:
Falta de precisión: Si la técnica de tiro es incorrecta, el balón no seguirá la trayectoria adecuada, lo que reducirá las probabilidades de encestar.
Descontrol en la dirección: Un mal agarre o un mal movimiento de las manos puede llevar a tiros descontrolados, que se desvían hacia los lados o hacia arriba, dificultando la puntuación.
- Mayor esfuerzo físico:
Dependencia de la fuerza en lugar de la técnica: En lugar de usar las piernas y el movimiento fluido de los brazos, los jugadores con mala técnica tienden a depender demasiado de la fuerza de sus brazos, lo que puede hacer que se fatiguen más rápido.
Menos eficiencia: La mala técnica genera movimientos innecesarios, lo que obliga al jugador a usar más energía para realizar un tiro que podría ser más efectivo si se ejecuta correctamente.
- Lesiones:
Sobrecarga muscular: Si se utiliza una mala mecánica repetidamente, puede generar tensiones y sobrecargar músculos y articulaciones, especialmente en los hombros, muñecas y codos.
Problemas en las muñecas y codos: Un mal uso de la muñeca, como no darle el "flick" adecuado, puede llevar a lesiones en estas áreas, que son comunes en los tiradores con mala técnica.
- Inseguridad y frustración:
Falta de confianza: Si un jugador no tiene buenos resultados debido a una mala técnica de tiro, es probable que pierda confianza en su capacidad para encestar. Esto puede afectar su rendimiento en otras áreas del juego.
Frustración: La constante falta de éxito en los tiros puede causar frustración, lo que afecta la mentalidad del jugador y su rendimiento general en los partidos.
- Dificultad para mejorar:
Frenar el progreso: Una mala técnica de tiro puede limitar el desarrollo de un jugador. Aunque un jugador puede mejorar su tiro mediante esfuerzo y práctica, si la base técnica es incorrecta, el progreso puede ser mucho más lento.
Hábito de mala técnica: Si la mala técnica se convierte en un hábito, será mucho más difícil corregirla con el tiempo, y el jugador puede necesitar un cambio significativo en su enfoque para mejorar.
El impacto de este anteproyecto esta enfocado a un ámbito social para la comunidad de jugadores de baloncesto al ayudarlos en algo tan crucial como es la mecánica de tiro

-Proponemos una forma economica y sencilla de usar para practicar y mejorar la mecanica de tiro de los basketbolistas , sin la necesidad de maquinas super caras o de un entrenador personal, nosotros damos la oportunidad de mejorar mostrando tips y la forma de ejecucion de la mecanica de tiro y tambien permite al usuario entender con mayor facilidad en que se esta equivocando al tirar , mostrando especificamente la fase que tiene que mejorar y como puede hacer una mejor acción 

---

## 🧪 Prototipo

Primer prototipo
Una idea inicial de donde se intentaria realizar una lectura muscular para con esa lectura generar una serie de promedios estadisticos para corregir la fuerza ejercida en el brazo durante la mecanica de tiro, una idea rechazada debido a la complejidad de los calculos del sensor y la incomodidad del dispositivo en el usuario por lo que se descarto este prototipo y se inicio la construccion del modelo de IA

<img width="439" height="500" alt="image" src="https://github.com/user-attachments/assets/ae088fb3-5a34-455a-ad15-ff029bb74f62" />

 
Segundo prototipo
En esta etapa iniciamos la creacion de la aplicación en app inventor, un entorno de programacion diseñado para este tipo de actividades, en el avance del proyecto se tiene unas pantallas principales conectadas a partir de botones donde se puede navegar por la app, ademas de la inclusion y deteccion de la camara del celular en la pantalla “Practica” esto nos permitira conectar la aplicación con el modelo de uso Mediapipe para que se genere la captura de movimiento del cuerpo desde la camara del dispositivo y asi como paso siguiente crear los calculos de las lecturas de posicion para asi estipular las clases de cada una de las etapas de la mecanica del tiro y realizar las correcciones
 
<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/cb5d5aea-2994-4fae-8fce-4aad64aaeed2" />
<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/c68cba5d-caa3-4816-8882-ca15f2edc67b" />
<img width="465" height="362" alt="image" src="https://github.com/user-attachments/assets/8dd08701-d85e-4419-aadb-63586c7dcbb9" />



### 📸 Capturas

| Pantalla de Inicio | Vista de Usuario | Panel Admin |
|--------------------|------------------|-------------|
<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/12936332-d659-4790-b92c-45dcd2efa32f" />
<img width="439" height="500" alt="image" src="https://github.com/user-attachments/assets/190f88fc-e7a9-4bb5-a186-d94ae7fb01ff" />
<img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/55708510-6161-4066-8f00-fb198189378d" />
<img width="465" height="362" alt="image" src="https://github.com/user-attachments/assets/16ba8b9b-c1cc-44c4-8bb2-f621279d4b60" />
<img width="444" height="532" alt="image" src="https://github.com/user-attachments/assets/da045669-103b-4374-8fdc-5d746d241404" />
<img width="886" height="490" alt="image" src="https://github.com/user-attachments/assets/eb97c853-0642-44a1-ac5b-634ab9e28c4d" />
<img width="886" height="476" alt="image" src="https://github.com/user-attachments/assets/36b2394d-dc09-4ea5-96e0-e4befb1746c0" />



---

## 🧰 Tecnologías Utilizadas

Fase de planificación:
 Para el desarrollo del proyecto los recursos que necesitaremos serán pocos, pero esenciales, primeramente, necesitamos una placa de Arduino que contendrá toda la programación luego necesitaremos un sensor de señales EMC o electrodo que captan señales eléctricas a partir del movimiento muscular, un sensor bluetooth para conectar el Arduino al celular y por último el desarrollo de una aplicación en Android estudio con Java.
Fase de desarrollo:
 En esta fase vamos a implementar la creación de la aplicación en Android estudio que conectará el dispositivo móvil a una placa de Arduino que a su vez recibirá señales EMC de unos electrodos.
Fase de pruebas:
 Realización de pruebas con los electrodos y la aplicación viendo cuales son las zonas más eficientes de usar y tomar información de los músculos mientras se ejecuta la mecánica de tiro. 
Fase de entrega:
 Presentación de la manga conectada a la placa Arduino y una aplicación hecha en Android estudio 
Producto esperado
Una aplicación conectada a una manga que permitirá monitorear y corregir la mecánica de tiro en baloncesto para el usuario, está conectada por una placa Arduino, un conjunto de electrodos y un sensor bluetooth.


---

## ⚙️ Instalación

### Requisitos previos

- Tener un celular con camara  
- App instalada
- Navegador moderno
-Balon de baloncesto
  
### Pasos
