# 📦 Hello World

##  ⚙️  Ejecución
### Compilar proyecto
```bash
$ javac Main.java
```


### Ejecutar proyecto
```bash
$ java Main
```

##  📁  Estructuras
### 🔹 Comentarios
### 1.1. Clase

#### 1.1.1. Estructura
```java
/**
* [Class <NOMBRE_CLASE>]
* [<IDEA_PRINCIPAL>]
* <DESCRIPCION>
*
* @author  <NOMBRE_AUTOR>
* @version 1.0
* @since   yyyy-mm-dd
*/
public class Main {

}
```
#### 1.1.2. Ejemplo
```java
/**
* [Class Main]
* [Representa la clase principal de la aplicación.]
* En esta clase tendrá una única función que será ejecuta inicialmente.
*
* @author  Oscar Ortiz
* @version 1.0
* @since   2025-05-23
*/
  public class Main {

}
```
### 1.2. Método

#### 1.2.1. Estructura
```java
/**
 * [<BREVE DESCRIPCIÓN DE LO QUE HACE EL MÉTODO>].
 * <DESCRIPCIÓN OPCIONAL MÁS DETALLADA, INCLUYENDO CONSIDERACIONES ESPECIALES O CONTEXTO DE USO>.
 *
 * @param <NOMRE_PARAMETRO> <DESCRIPCIÓN DEL PARAMETRO>
 * @return <DESCRIPCIÓN DEL RETORNO DEL METODO>
 * @throws <DESCRIPCIÓN DE LA EXCEPCIÓN>
 */
public boolean myFunction(boolean param) {
    return param;
}
```

#### 1.2.2. Ejemplo
```java
/**
 * [Divide dos números enteros.]
 * Este método realiza una división y puede lanzar una excepción si el divisor es cero.
 *
 * @param numerador El número que será dividido
 * @param denominador El número por el cual se divide
 * @return El resultado de la división como un número decimal
 * @throws ArithmeticException Si el denominador es cero
 */
public double dividir(int numerador, int denominador) {
    if (denominador == 0) {
        throw new ArithmeticException("No se puede dividir entre cero.");
    }
    return (double) numerador / denominador;
}
```