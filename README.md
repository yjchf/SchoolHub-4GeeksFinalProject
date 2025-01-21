# 🏢 **SchoolHub**

SchoolHub es una plataforma diseñada para facilitar la logística operativa de una escuela. Permite a los administradores gestionar estudiantes, grados, materias y profesores. Además, ofrece herramientas específicas para profesores y representantes para optimizar la experiencia educativa.

---

## ✨ **Características Principales**

- **Administradores**:  
  - Agregar estudiantes, crear grados, materias y asignar profesores.  

- **Profesores**:  
  - Panel exclusivo para gestionar evaluaciones, calificar y hacer un seguimiento del rendimiento de los estudiantes.  

- **Representantes**:  
  - Panel informativo que permite ver el desarrollo académico de sus representados, tanto general como por materia.  

---

## 🛠️ **Tecnologías Utilizadas**

El proyecto fue desarrollado con las siguientes tecnologías:  

**Backend:**  
- Python  
- Flask  
- SQLAlchemy  
- Marshmallow  
- Bcrypt  
- JWT Tokens  

**Frontend:**  
- JavaScript  
- React  
- Bootstrap  
- CSS  

**Librerías Adicionales:**  
- SweetAlert  
- React-Calendar  
- React-Datepicker  

---

## 🚀 **Cómo Instalar y Usar el Proyecto**

### 1. Clonar el Repositorio:  
```bash
git clone https://github.com/tu-usuario/schoolhub.git
cd schoolhub
```

### 2. Configurar el Entorno Virtual:  
```bash
pipenv install
pipenv shell
```

### 3. Configurar Variables de Entorno:  
Crea un archivo `.env` con las siguientes variables:  
```
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=tu_clave_secreta
DATABASE_URL=postgres://username:password@localhost:5432/schoolhub
```

**Opciones de Configuración de Base de Datos:**  
Dependiendo del motor de base de datos que utilices, el valor de `DATABASE_URL` debe seguir uno de estos formatos:  

| Motor     | DATABASE_URL                                        |
|-----------|-----------------------------------------------------|
| SQLite    | sqlite:////test.db                                  |
| MySQL     | mysql://username:password@localhost:port/example    |
| PostgreSQL| postgres://username:password@localhost:5432/example |

### 4. Ejecutar las Migraciones:  
```bash
pipenv run migrate
pipenv run upgrade
```

### 5. Iniciar el Servidor:  
```bash
pipenv run start
```

### 6. Configurar el Frontend:  
Desde la carpeta del frontend, ejecuta:  
```bash
npm install
npm start
```

---

## 📚 **Contribuciones**

¡Las contribuciones son bienvenidas! Si deseas colaborar:  

1. Haz un fork del repositorio.  
2. Crea una rama para tu contribución: `git checkout -b mi-contribucion`.  
3. Haz un pull request con los cambios realizados.  

---

## 📜 **Licencia**

Este proyecto está bajo la licencia MIT.  

---

## 📧 **Contacto**

Si tienes preguntas o sugerencias, no dudes en contactarme:  
- **Nombre:** Yuneido Chacín  
- **Correo Electrónico:** tu_email@example.com  
- **GitHub:** [TuPerfil](https://github.com/tu-usuario)  
