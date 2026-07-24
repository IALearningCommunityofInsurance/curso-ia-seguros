# Cómo publicar este repositorio en GitHub

*Guía paso a paso. Tiempo estimado: 20 minutos.*

---

## Paso 1 — Crear cuenta en GitHub (si no la tienes)

1. Ve a [github.com](https://github.com)
2. Clic en **Sign up** (esquina superior derecha)
3. Elige un nombre de usuario — por ejemplo: `communityofinsurance` o `coi-cica`
4. Confirma el correo electrónico

---

## Paso 2 — Crear el repositorio

1. En GitHub, clic en el botón verde **New** (o en el **+** arriba a la derecha → New repository)
2. Configura así:
   - **Repository name:** `curso-ia-seguros`
   - **Description:** *Curso de formación: Inteligencia Artificial Aplicada al Sector Asegurador · COI / CICA*
   - **Visibility:** Public (para que los alumnos accedan sin cuenta) o Private (si quieres control de acceso)
   - **NO** marques "Add a README file" (ya tienes el tuyo)
3. Clic en **Create repository**

---

## Paso 3 — Subir los archivos

### Opción A — Sin instalar nada (recomendada para empezar)

1. En la página del repositorio recién creado, clic en **uploading an existing file**
2. Arrastra toda la carpeta `curso-ia-seguros` (o sus archivos)
3. En la parte inferior escribe un mensaje, por ejemplo: *"Versión inicial del curso"*
4. Clic en **Commit changes**

> **Nota:** GitHub no permite subir carpetas vacías. Las carpetas de módulos con solo un README.md se subirán bien.

### Opción B — Con GitHub Desktop (más cómodo para futuras actualizaciones)

1. Descarga [GitHub Desktop](https://desktop.github.com)
2. Abre la app → **File → Add local repository**
3. Selecciona la carpeta `curso-ia-seguros`
4. Clic en **Publish repository** y elige el repositorio que creaste en el paso 2

---

## Paso 4 — Activar GitHub Pages (la web pública)

1. En el repositorio, ve a **Settings** (pestaña superior)
2. En el menú lateral, clic en **Pages**
3. En **Source**, selecciona **Deploy from a branch**
4. En **Branch**, selecciona `main` y carpeta `/ (root)`
5. Clic en **Save**

En 1–2 minutos, tu curso estará disponible en:
```
https://[tu-usuario].github.io/curso-ia-seguros/
```

---

## Paso 5 — Compartir con alumnos y profesores

**URL para alumnos** (solo lectura):
```
https://[tu-usuario].github.io/curso-ia-seguros/
```

**URL del repositorio** (para el profesor, que puede editar):
```
https://github.com/[tu-usuario]/curso-ia-seguros
```

Para dar acceso de edición al profesor: Settings → Collaborators → Add people → introduce su correo de GitHub.

---

## Actualizar el contenido en el futuro

Cuando tengas nuevos materiales (teoria.md de un módulo, slides, etc.):

1. Ve al repositorio en GitHub
2. Navega hasta la carpeta correspondiente
3. Clic en **Add file → Upload files**
4. Sube el archivo y haz commit

La web de GitHub Pages se actualiza automáticamente en 1–2 minutos.

---

## ¿Necesitas ayuda?

Carlos Biurrun Murillo · carlos@communityofinsurance.es
