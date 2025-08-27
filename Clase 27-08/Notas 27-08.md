## Repaso

### Formato y Configuración de Números

#### Conceptos Fundamentales
- **Formato**: Es la forma de representar un número siguiendo una serie de reglas y convenciones específicas
- **Configuración**: Se refiere a la base de representación de un número y cómo se estructuran sus dígitos

#### Sistemas de Numeración

##### 1. Sistema Decimal (Base 10)
- **Base**: 10
- **Dígitos**: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- **Ejemplo**: 1234₁₀ = 1×10³ + 2×10² + 3×10¹ + 4×10⁰
- **Punto decimal**: Para números fraccionarios (ej: 123.45)

##### 2. Sistema Binario (Base 2)
- **Base**: 2
- **Dígitos**: 0, 1
- **Ejemplo**: 1101₂ = 1×2³ + 1×2² + 0×2¹ + 1×2⁰ = 13₁₀
- **Punto binario**: Para fracciones (ej: 101.11₂ = 5.75₁₀)

##### 3. Sistema Hexadecimal (Base 16)
- **Base**: 16
- **Dígitos**: 0-9, A, B, C, D, E, F (donde A=10, B=11, C=12, D=13, E=14, F=15)
- **Ejemplo**: 2AF₁₆ = 2×16² + 10×16¹ + 15×16⁰ = 687₁₀
- **Uso común**: Representación compacta de datos binarios

##### 4. Sistema Octal (Base 8)
- **Base**: 8
- **Dígitos**: 0, 1, 2, 3, 4, 5, 6, 7
- **Ejemplo**: 754₈ = 7×8² + 5×8¹ + 4×8⁰ = 492₁₀

#### Números de Punto Fijo

##### Definición
Los números de punto fijo tienen una posición fija del punto decimal/binario, determinada por el formato elegido.

##### Características
- **Parte entera**: Número fijo de bits para la parte entera
- **Parte fraccionaria**: Número fijo de bits para la parte decimal
- **Formato común**: Qm.n (donde m = bits enteros, n = bits fraccionarios)

##### Ejemplo de Punto Fijo Binario
- Formato Q4.4 (8 bits total):
   - 4 bits para parte entera
   - 4 bits para parte fraccionaria

- Número: 0101.1010₂ = 5 + 0.5 + 0.125 = 5.625₁₀

#### Conversiones Entre Sistemas

##### Decimal a Binario
1. **Parte entera**: División sucesiva por 2
2. **Parte fraccionaria**: Multiplicación sucesiva por 2

##### Decimal a Hexadecimal
1. **Parte entera**: División sucesiva por 16
2. **Parte fraccionaria**: Multiplicación sucesiva por 16

##### Binario a Hexadecimal
- Agrupar de 4 bits desde el punto hacia afuera
- Cada grupo de 4 bits = 1 dígito hexadecimal

#### Representación en Computadoras

##### Enteros
- **Sin signo**: Representación directa en binario
- **Con signo**: 
  - Signo-magnitud
  - Complemento a 1
  - Complemento a 2 (más común)

##### Punto Flotante (IEEE 754)
- **Signo**: 1 bit
- **Exponente**: 8 bits (float) / 11 bits (double)
- **Mantisa**: 23 bits (float) / 52 bits (double)

#### Ventajas y Desventajas

##### Punto Fijo
- ✅ **Ventajas**: Operaciones rápidas, predecible
- 🚫 **Desventajas**: Rango limitado, precisión fija

##### Punto Flotante
- ✅ **Ventajas**: Amplio rango, precisión variable
- 🚫 **Desventajas**: Operaciones más lentas, errores de redondeo

#### Ejemplos Prácticos

![alt text](image.png)

##### Conversión 25.375₁₀:
- **Binario**: 11001.011₂
- **Hexadecimal**: 19.6₁₆
- **Octal**: 31.3₈

##### En formato Q8.8:
25.375₁₀ → 00011001.01100000₂ <br>

#### Ejemplo de Empaquetado
![alt text](image-1.png)

#### Otro ejemplo de formato y configuración
![alt text](image-2.png)

# CLASE
