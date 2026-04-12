# Intro Python  
## Actividad 1  

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