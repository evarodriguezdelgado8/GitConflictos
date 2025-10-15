## Experiencias y aprendizajes - Fernando
1. Creando mi propia rama
Lo primero que hice fue crearme mi rama `FernandoC` para trabajar sin molestar a nadie. Usé `git checkout -b FernandoC` y luego la subí con `git push -u origin FernandoC`. 
Así cada uno puede trabajar en lo suyo sin pisar el trabajo de los demás. Bastante útil la verdad.
## 2. Haciendo commits
Creé un par de archivos (`fernando.txt` y `codigo_fernando.py`) y fui haciendo varios commits. Lo básico: `git add` para preparar los archivos y `git commit -m "mensaje"` para guardarlos.
Lo que aprendí es que es mejor hacer commits pequeños y con mensajes claros. Si luego algo falla, es más fácil encontrar dónde.
## 3. primer conflicto (y cómo lo resolví)
Aquí vino lo interesante. Tanto mi compañero como yo modificamos el archivo `experiencia.md` desde distintas ramas. Cuando intenté hacer merge, 
El archivo se llenó de estos marcadores:
```
<<<<<<< HEAD
(mis cambios)
=======
(cambios del compañero)
>>>>>>> main
```
Lo que hice fue abrir el archivo, borrar esos marcadores y juntar ambos cambios a mano. Luego `git add`, `git commit` y `git push`. Problema resuelto.
## 4. Trabajo en equipo
La clave fue ir haciendo `git pull` de vez en cuando para no quedarnos desactualizados.
Lo importante: hablarse con el equipo. Si los dos vamos a tocar el mismo archivo, mejor avisar para no liarnos después con conflictos.

### 5. Comandos que más usé
- `git checkout -b <rama>` → Crear rama nueva
- `git add <archivo>` → Preparar cambios
- `git commit -m "mensaje"` → Guardar cambios
- `git push` → Subir al repositorio
- `git pull` → Bajar cambios de otros
- `git merge <rama>` → Fusionar ramas
- `git status` → Ver qué está pasando

Eva:
He creado una rama nueva con el nombre eva2, me he metido en ella y he creado un readme de nombre tareas-eva.md en el que he escrito para probar las tareas de mi dia.
Despues he cambiado de rama otra vez a la main y he hecho merge para juntarlas.
Despues hemos generado un conflicto modificando el archivo desde distintas ramas para generar conflicto y lo hemos solucionado dejandolo de nuevo como estaba antes.
Al pricipio ha sido un pco frustrante porque no sabiamos como resolver los problemas que teniamos, pero finalmente hemos podido resolverlos.

Hola fernando


Paco:
Hemos creado diferentes ramas,trabajado en ellas creando diferentes archivos,y creando conflictos al fusionar las ramas.
Algunos se han solucionado y otros han sido mas dificiles y no he podido terminarlos.
Tengo que practicar mas este aspecto de Git.

