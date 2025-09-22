# RiwiMusic
A C# system capable of managing concerts and their clients.

Justificación de la POO:
En este proyecto, aplicamos la Programación Orientada a Objetos (POO) para organizar y estructurar el código de una manera más lógica y modular. La POO se basa en cuatro pilares principales: encapsulamiento, herencia, polimorfismo y abstracción. Aunque no usamos todos, los conceptos clave aquí son la abstracción y el encapsulamiento.

Abstracción: Creamos clases como Admin, Concierto, Cliente, Tiket e HistorialCompra que representan entidades del mundo real. Estas clases no son solo variables; son "plantillas" o "modelos" que encapsulan tanto los datos (atributos) como las acciones (métodos) que se pueden realizar con ellos. Por ejemplo, la clase Concierto abstrae la idea de un concierto, incluyendo sus propiedades (como nombre, ciudad y fechaConcierto) y sus comportamientos (listarConciertos).

Encapsulamiento: Agrupamos los datos (atributos) y los métodos que operan sobre esos datos en una sola unidad: la clase. Por ejemplo, en la clase Cliente, los atributos como id, nombre, email, etc., están encapsulados con métodos como registrar() y editarCliente(). Esto protege los datos de ser manipulados directamente y asegura que solo se pueda acceder a ellos a través de los métodos definidos en la clase. Esto ayuda a mantener la integridad y la consistencia de la información.


DIAGRAMA DE CLASES:
<img width="1140" height="2652" alt="Espacio de trabajo sin título (1)" src="https://github.com/user-attachments/assets/f100c210-521a-417b-8195-be7d36c2bcae" />

DIAGRAMA DE CASOS DE USO:
<img width="857" height="580" alt="image" src="https://github.com/user-attachments/assets/ebe40a81-8c37-4774-a0cd-06487ced7ff2" />
<img width="1128" height="708" alt="Captura de pantalla 2025-09-21 234556" src="https://github.com/user-attachments/assets/759018c9-2bba-4b96-bea6-0b5d2781cce8" />


