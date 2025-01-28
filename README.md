
# Personal Information
- **Name:** Jose Daniel Muñoz martinez
- **Registration Number:** 2941584
- **Degree:** Software development engineering 
- **Semester:** 7th semester

# Subject Information
- **Subject Name:** web app design
- **Professor:** Mario Eduardo Rodríguez Palafox

# que es Markdown?
Markdown es un lenguaje de marcadores de texto plano de sintaxis de formato. su diseño le permite ser convertido a varios formatos de output, pero el uso principal es para convertirlo a HTML para paginas web. Usualmente se implementa para escribir documentación y notas por su facilidad de comprensión y escritura.

## opciones de etiquetado de Markdown.

Markdown provee varias maneras de formato y estructura de texto, por ejemplo, las mas usadas son los siguientes:

### encabezados
puedes crear encabezados usando los simbolos `#` . dependiendo de la cantidad de `#` simbolos que utilizes determina el nivel del encabezado.
```markdown
# encabezado 1
## encabezado 2
### encabezado 3
```
### Texto
```markdown
**Negrita**  
*Itálica*  
~~Tachado~~
```
**texto**  
*texto*  
~~texto~~

### Listas
- Lista desordenada
  - Sublista
    - Otro nivel

1. Lista ordenada
2. Segundo elemento

### Enlaces e Imágenes
```markdown
[Texto del enlace](https://example.com)
![Texto alternativo de la imagen](https://example.com/imagen.png)
```

### Tablas
```markdown
| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Valor 1      | Valor 2      |
```

### Código
```markdown
`Texto en línea`

```
Bloque de código
```
```

---

## Comandos de Git

A continuación, se enumeran los comandos comunes utilizados en Git para gestionar un repositorio:

### Verificar el estado del repositorio local
```bash
git status
```

### Agregar archivos al área de preparación
- Agregar un archivo específico:
  ```bash
  git add nombre-del-archivo
  ```
- Agregar todos los archivos:
  ```bash
  git add .
  ```

### Agregar comentarios al commit
```bash
git commit -m "Mensaje descriptivo del commit"
```

### Subir los cambios al repositorio remoto
```bash
git push origen rama
```

### Gestionar ramas
- Crear una rama:
  ```bash
  git branch nombre-de-la-rama
  ```
- Cambiar a una rama:
  ```bash
  git checkout nombre-de-la-rama
  ```
- Listar ramas:
  ```bash
  git branch
  ```
- Eliminar una rama:
  ```bash
  git branch -d nombre-de-la-rama
  ```

### Revertir un repositorio a un commit específico
```bash
git reset --hard ID-del-commit
```

---

Espero que esta guía sea útil para ti al trabajar con Markdown y Git.
