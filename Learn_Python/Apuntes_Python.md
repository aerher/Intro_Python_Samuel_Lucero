# Intro Python  
## Actividad 1  


**Curso Python = https://www.youtube.com/@ProCodeTutoriales**
Ver notas claras sobre Variables  
``` Python
# Declaración de variables (Atributos de una entidad)
nombre_usuario = "Juan Pérez" # String (Texto)
edad = 20 # Integer (Entero)
promedio = 8.5 # Float (Decimal)
es_estudiante = True # Boolean (Lógico)
print(f"Usuario: {nombre_usuario}, Edad: {edad}, Estado: {es_estudiante}")

```

## Condicionales con if  

```
if edad >= 18:
 mensaje = "Usuario mayor de edad: Acceso total al SI."
else:
 mensaje = "Usuario menor de edad: Acceso restringido."
print(mensaje)

```


## Listar (Procedimientos de Datos )

```
# Lista de componentes de un SI
componentes_si = ["Hardware", "Software", "Datos", "Redes", "Personas", "Procesos"]
print("Componentes a auditar:")
for item in componentes_si:
 print(f"- {item}")
  
```

## para exportar a un csv  
para exportar a un archivo csv desde python  
se toca importar la biblioteca csv  

``` python
import csv  
with open('people.csv') as f:
    reader = csv.reader(f)
    for row in reader :
        print("Ap Paterno : {0}, Ap Materno : {1}, Nombre : {2}, Ciudad : {3}".format(row[0], row[1], row[2], row[3]))
```

en esta linea, cuando ponemos a f podemos poner el simbolo o signo que en nuestro csv este guardando por ejemplo si esta separado por un simbolo o caracter se utilizara el **delimiter = "( Simbolo o Caracter)"**
``` python
reader = csv.reader(f delimiter = "$")
```