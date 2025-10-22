# 🧾 Actividad Git y GitHub

## 🧠 Principales comandos de Git

| Comando | Descripción |
|----------|--------------|
| `git init` | Inicializa un nuevo repositorio Git en la carpeta actual. |
| `git add .` | Agrega todos los archivos modificados al área de preparación. |
| `git commit -m "mensaje"` | Guarda los cambios con un mensaje descriptivo. |
| `git status` | Muestra el estado de los archivos. |
| `git log` | Muestra el historial de commits realizados. |
| `git branch` | Lista o crea nuevas ramas. |
| `git checkout nombre-rama` | Cambia a otra rama. |
| `git merge nombre-rama` | Combina una rama con la actual. |
| `git remote add origin URL` | Conecta tu repositorio local con GitHub. |
| `git push origin main` | Envía los cambios al repositorio remoto. |
| `git pull origin main` | Descarga los cambios del repositorio remoto. |

---

## 🪜 Proceso paso a paso para subir un proyecto a GitHub

1. **Inicializar el repositorio local**
   ```bash
   git init
   ```

2. **Agregar archivos al área de preparación**
   ```bash
   git add .
   ```

3. **Confirmar los cambios**
   ```bash
   git commit -m "Primer commit del proyecto"
   ```

4. **Conectar con GitHub**
   ```bash
   git remote add origin https://github.com/tuusuario/nombre-repo.git
   ```

5. **Enviar los cambios**
   ```bash
   git push -u origin main
   ```

6. **Verificar en GitHub**  
   Entra a tu perfil y revisa que los archivos aparezcan.

---

## 🖼️ Capturas de pantalla sugeridas

```
![Inicio del repositorio](./img/git-init.png)
![Commit realizado](./img/git-commit.png)
![Repositorio en GitHub](./img/github-upload.png)
```

---

## 📎 Entrega
🔗 [https://github.com/tuusuario/nombre-del-repo](https://github.com/tuusuario/nombre-del-repo)

---

## 💡 Tip final
- Usa **títulos**, **listas** y **tablas**.
- Escribe con tus propias palabras.
- Agrega capturas claras.
- ¡Haz que tu README se vea profesional!
