# Instalación del README profesional de Mateo 🐻

## ¿Qué contiene este paquete?

```
Mateosalazar543/
├── README.md                 ← contenido visible en tu perfil de GitHub
├── .nojekyll                 ← publica la web estática sin procesarla con Jekyll
├── GUIA_DE_INSTALACION.md   ← instrucciones (no es necesario subirla)
├── assets/
│   ├── freddy.png           ← tu imagen original, en formato PNG
│   └── freddy-honk.wav      ← sonido tipo bocina recreado, NO es el audio original de FNaF
└── freddy/
    └── index.html          ← página interactiva con el botón de Freddy
```

## Método fácil: navegador GitHub

1. Abre https://github.com/new
2. En **Repository name** escribe exactamente `Mateosalazar543` (mismo nombre que tu usuario, sin espacios). Si ya existe, entra en ese repositorio y continúa.
3. Selecciona **Public** y crea el repositorio. Si GitHub ofrece agregar README desde el inicio, puedes desmarcarlo para subir el nuestro.
4. En el repositorio, pulsa **Add file → Upload files**. Extrae este ZIP primero y **arrastra `README.md`, `.nojekyll`, la carpeta `assets` y la carpeta `freddy` con su contenido**, conservando las rutas. Si el navegador no conserva carpetas, utiliza Git Bash (método siguiente).
5. Haz clic en **Commit changes**.
6. En el repo ve a **Settings → Pages → Build and deployment**. En **Source** selecciona **Deploy from a branch**; elige la rama `main` y la carpeta `/(root)`, después **Save**.
7. Espera a que GitHub Pages publique la web (en ocasiones puede tardar varios minutos). La URL esperada es:
   `https://mateosalazar543.github.io/Mateosalazar543/freddy/`
8. Abre tu perfil de GitHub, y tu README aparecerá encima de los repositorios destacados. Haz clic en Freddy y, en la nueva página, pulsa Freddy otra vez para escuchar el sonido.

## Método recomendado: Git Bash (Windows)

Abre Git Bash en la carpeta **que contiene** los archivos extraídos:

```bash
# Si aún no existe el repositorio remoto, créalo primero en GitHub.
# Este comando clona el repositorio, reemplaza USERNAME si alguna vez cambias de nombre.
git clone https://github.com/Mateosalazar543/Mateosalazar543.git

# Copia estos archivos al directorio clonado:
# README.md, .nojekyll, assets/ y freddy/
# En el Explorador de Windows puedes arrastrarlos a la carpeta Mateosalazar543.

cd Mateosalazar543
git add README.md .nojekyll assets/ freddy/
git commit -m "docs(profile): add interactive Freddy easter egg and developer README"
git push origin main
```

Si el repositorio ya tenía cambios, clónalo primero y copia los archivos encima del clone. No hagas `git init` en un repo clonado.

**Aviso:** los comandos de Git Bash presuponen que los archivos ya fueron copiados físicamente dentro de la carpeta clonada. El comentario no realiza automáticamente la copia.

## Cómo usar el audio original de Freddy

El archivo incluido (`assets/freddy-honk.wav`) es una **recreación de bocina corta**, no el efecto original del videojuego. Si tienes un MP3 del sonido exacto y cuentas con permiso para publicarlo:

1. Agrégalo como `assets/freddy-honk.mp3`.
2. En `freddy/index.html`, cambia la línea:
   `<audio id="honk" src="../assets/freddy-honk.wav" preload="auto"></audio>`
   por:
   `<audio id="honk" src="../assets/freddy-honk.mp3" preload="auto"></audio>`.
3. Sube ambos cambios al repositorio.

## Limitación de GitHub

GitHub **no ejecuta JavaScript dentro de los archivos README.md**; no es posible que el PNG reproduzca audio directamente en la página de perfil. Por eso el PNG lleva a una web de GitHub Pages, donde la persona vuelve a pulsar Freddy. Esto también respeta las políticas del navegador que impiden reproducir audio automáticamente sin interacción.

## Personalización

- En `README.md`, actualiza la biografía y las tecnologías según tu progreso.
- En `freddy/index.html` puedes cambiar los textos, colores, conteo de boops y sonido.
- Si cambias tu nombre de usuario o el nombre del repositorio, actualiza los enlaces absolutos incluidos en ambos archivos.
