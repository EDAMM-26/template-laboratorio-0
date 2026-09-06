# Práctica 0 – Configuración del Entorno – EDAMM 2026-27

> **Asignatura:** Entornos para Desarrollo de Aplicaciones Multimedia Multiplataforma  
> **Titulación:** Máster en Tecnologías Audiovisuales – ETSI de Telecomunicación – UPV

---

## ¿Qué tienes que hacer?

1. **Abre** el archivo `student.js` en VS Code.
2. **Rellena** las tres variables con tus datos reales:

```js
const STUDENT_NAME  = "Tu Nombre Apellido";
const STUDENT_EMAIL = "tuusuario@etsit.upv.es";
const GITHUB_USER   = "tu-usuario-github";
```

3. **Guarda** el archivo (`Ctrl+S`).
4. **Abre** `index.html` con Live Server o con el navegador integrado en VS Code y comprueba que aparecen tus datos y el mensaje verde de confirmación.
5. **Haz commit y push:**

```bash
git add student.js
git commit -m "Práctica 0: Configuración inicial del entorno de desarrollo EDAMM"
git push
```

6. **Verifica** en tu repositorio de GitHub que los cambios se han publicado correctamente.

---

## Estructura del repositorio

```
laboratorio-0-tu-usuario/
├── index.html    ← página web de verificación (no modificar)
├── student.js    ← aquí editas tus datos
├── style.css     ← estilos de la página web (no modificar)
└── README.md     ← estas instrucciones
```

---

## ¿Algo no funciona?

- Si los comandos `git` o `node` no se reconocen, **cierra y vuelve a abrir** la terminal.
- Si no puedes hacer push, necesitas un **Personal Access Token** de GitHub (Settings → Developer settings → Personal access tokens → Tokens classic → scope *repo*).
- Repasa el guión completo de la práctica o pregunta al profesor.
