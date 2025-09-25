# 📘 Trabajo Práctico III – Ingeniería de Software III  

**Universidad Católica de Córdoba – Facultad de Ingeniería**  
**Cátedra:** Ingeniería de Software III  
**Docentes:** Schwindt, Ariel – Bono, Fernando  
**Integrantes:** Cuozzo, Sofía – Hernández, Simón  

---

## 🚀 Acceder al proyecto de Azure DevOps  

1. Ir a 👉 [https://dev.azure.com](https://dev.azure.com).  
2. Iniciar sesión con tu cuenta de Microsoft.  
3. Organización: **soficuozzo / hernandezsimon2122**  
4. Proyecto: **ProyectoTP3-Cuozzo-Hernandez**  

---

## 💻 Clonar y trabajar con el repositorio  

### Clonar el repositorio
```bash
# Clonar el repositorio desde GitHub
git clone https://github.com/soficuozzo/TP3-IngeSoftware3-Cuozzo-Hernandez.git
cd TP3-IngeSoftware3-Cuozzo-Hernandez
Crear una nueva rama de feature
bash
Copiar código
# Crear y cambiarse a una rama de feature
git checkout -b feature/us1-inscripcion
Hacer cambios y subirlos
bash
Copiar código
# Agregar los cambios
git add .

# Commit con mensaje
git commit -m "Implementación US1 - Inscripción"

# Subir cambios al remoto
git push origin feature/us1-inscripcion
Crear Pull Request en Azure DevOps
Ingresar al proyecto en Azure DevOps → Repos → Pull Requests.

Crear un PR desde la rama feature/... hacia main.

Vincular el PR con el Work Item (User Story o Bug) correspondiente.

Completar el merge (se elimina la rama automáticamente).
