# Nutav_concurso_3
Proyecto fullstack de turismo

¿POR QUÉ?

NUTAV nace como respuesta a la necesidad de los guías oficiales de ofrecer sus servicios sin depender de una empresa intermediaria que retenga una parte considerable de sus ingresos y de una necesidad de parte de los turistas que buscan una experiencia más personalizada en sus viajes con guías turísticos que se acomoden a sus gustos. 

¿PARA QUÉ?

Nuestra plataforma permitirá a  los guías dar a conocer sus habilidades y experiencia, conectándolos directamente con los usuarios interesados en sus servicios.

¿PARA QUIÉN?

NUTAV está diseñado tanto para los guías oficiales que desean promocionar sus servicios de manera individual como para los usuarios que buscan encontrar el guía perfecto que se ajuste a sus necesidades, permitiéndoles vivir la experiencia de sus sueños de manera más personalizada.

TEMÁTICA
Turismo

CEO’S
JULIAN ACERO USUGA,  
DANIELA ROJAS TABORDA,
MIGUEL ÁNGEL TORO,
DEIBY CARDONA LOPEZ,
JHON FABER NORENA PINERES


LINK TRELLO:

https://trello.com/b/msBCIeDu/nutav

DIAGRAMA ARQUITECTURA
![Diagrama_Arquitectura](https://github.com/jusuga2001/Nutav_concurso_3/blob/main/diagramaArquitectura.jpeg)

DIAGRAMA BASE DE DATOS
![Diagrama_Base_Datos](https://github.com/jusuga2001/Nutav_concurso_3/blob/main/MODELO%20DATABASE%20OFICIAL.png)

-Un guia puede tener muchos tours, pero un tour solo puede tener un guia.
-Un guia puede tener muchas reservas de sus tours, pero una reserva solo puede tener un guia.
-Un cliente puede tener muchas reservas, pero una reserva solo puede tener un cliente.
-Una reserva solo puede tener un tour, pero un tour puede tener muchas reservas.
-Un tour puede tener mucha media(fotos, videos), pero una media solo puede pertenecer a un tour.
-Un tour solo pertenece a una categoria(enum), y una categoria tiene muchos tours.
-Un tour solo puede tener un idioma(enum), y un idioma puede tener muchos tours.

