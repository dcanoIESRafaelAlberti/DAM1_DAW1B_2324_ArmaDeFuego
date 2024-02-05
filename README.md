## Prueba de POO 02 - Armas de Fuego

### Descripción:

1. Implementar una clase ArmaDeFuego con sus métodos y propiedades:

2. Propiedades (ninguna de las propiedades podrá accederse desde fuera de esta clase)

   - nombre: String
   - municion: Int
   - municionARestar: Int
   - tipoDeMunicion: String (9mm, 7.62mm, 60mm, RPG, ...)
   - danio: Int
   - radio: String (puede tomar valores '["Pequeño", "Intermedio", "Amplio"]')

3. Metodos

   - dispara: resta munición (utiliza correctamente a municionARestar) y muestra un mensaje dónde indiques que arma de fuego se ha disparado y la munición restante. 
   - recarga: aumenta la munición y muestra un mensaje con el dónde indiques que arma de fuego se ha recargado y la munición actual después de dicha recarga. 
   - mostrarInfo: debe implementarse en las clases derivadas de ésta y mostrará el contenido o estado e la instancia, es decir, todas sus propiedades.

***NOTA***: Se pretende que la clase ArmaDeFuego refleje la intención del programador de que sirva como una superclase para tipos más específicos de armas y prevenir 
su instanciación directa, manteniendo así la coherencia y la claridad en la jerarquía de clases del programa.

### El ejercicio constará de dos partes:

***Parte 1: Implementa las sub-armas.***

- Pistola: Resta munición * 1
- Rifle: Resta munición * 2
- Bazooka: Resta munición * 3

1. Crea una instancia de cada arma desde el programa principal.
2. Crea un mapa en el que registrar aletoriamente 6 disparos sobre el armas. 
3. Recorre el mapa... dispara y muestra su información cada vez que dispares.

*** Parte 2: Modifica el programa para contemplar que otros objetos puedan Disparar. *** 

1. Genera aleatoriamente disparos, en este caso 9, para las armas de fuego y para tres clases más (Casa, Coche y Bocadillo).
2. La clase Casa dispara confetti.
3. La clase Coche dispara ráfagas de luz larga.
4. La clase Bocadillo dispara olor a jamón.

### Recursos

  - Apuntes sobre principios de la programación orientada a objetos.
  - Documentación oficial de Kotlin sobre herencia, clases y métodos.

### Evaluación y calificación
  
  RA y CE evaluados: RA4, CE b-k
