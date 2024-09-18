### 1. Listas
- **Descripción**: Colecciones de elementos ordenados y mutables.
- **Ejemplo**:
  ```python
  frutas = ["manzana", "naranja", "plátano"]
  frutas.append("fresa")  # Agrega un elemento
  print(frutas)  # Output: ['manzana', 'naranja', 'plátano', 'fresa']
  ```

### 2. Tuplas
- **Descripción**: Colecciones de elementos ordenados e inmutables.
- **Ejemplo**:
  ```python
  coordenadas = (10, 20)
  print(coordenadas[0])  # Output: 10
  # coordenadas[0] = 15  # Esto causaría un error porque las tuplas son inmutables
  ```

### 3. Diccionarios
- **Descripción**: Colecciones de pares clave-valor, mutables y no ordenados.
- **Ejemplo**:
  ```python
  persona = {"nombre": "Juan", "edad": 30}
  print(persona["nombre"])  # Output: Juan
  persona["edad"] = 31  # Modifica el valor
  ```

### 4. Conjuntos
- **Descripción**: Colecciones de elementos únicos, no ordenados y mutables.
- **Ejemplo**:
  ```python
  numeros = {1, 2, 3, 2}
  print(numeros)  # Output: {1, 2, 3} (el duplicado se elimina)
  numeros.add(4)  # Agrega un elemento
  ```
