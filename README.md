<h1 align="center">Construye aplicaciones web</h1>

<h2 align="center">Práctica Evaluatoria Parcial 3</h2>

<h2 align="center">Integrantes</h2>

<div style="margin-left: 40px; margin-right: 40px; text-align: center;">
<ul style="list-style-position: inside;">
  <li>Aparicio Hernandez Joselin</li>
  <li>Huerta Cortes Melanie Johanna</li>
  <li>Mejía Cruz Heidy Clarisa</li>
  <li>Rodriguez Rodriguez Fatima</li>
  <li>Salazar Acosta Layla Jayri</li>
</ul>
</div>

<h2 align="center">5 AMPG</h2>

<h2 align="center">Índice</h2>

<div style="margin-left: 40px; margin-right: 40px;">
1. Introducción  
2. Explicación de los comandos  
3. Diagrama  
4. Explicación de los archivos  
5. Código de los archivos  
6. Ejecución final de lo que va del proyecto  
7. Conclusión  
</div>

---

<h2 align="center">Introducción</h2>

<div style="margin-left: 40px; margin-right: 40px;">
En este semestre seguimos utilizando la herramienta Django que sirve para desarrollar aplicaciones porque ofrece rapidez, seguridad, escalabilidad y una gran comunidad de soporte. Es un framework de alto nivel que simplifica tareas comunes y permite construir proyectos muy grandes con menos esfuerzo.  
Django utiliza la arquitectura MVC (Modelo-Vista-Controlador), un patrón de diseño que separa una aplicación en tres componentes principales para mejorar la organización, mantenimiento y escalabilidad del código.  
El modelo maneja la lógica de negocios y la base de datos, la vista se encarga de la interfaz que observa el usuario y el controlador interpreta las acciones y actualiza el modelo o la vista según se requiera.
</div>

---

<h2 align="center">Explicación de Comandos</h2>

<div style="margin-left: 40px; margin-right: 40px;">
1. **cd Documents** → Entra a la carpeta Documentos desde la terminal.  
2. **md "tu nombre"** → Crea una nueva carpeta con el nombre indicado.  
3. **cd "tu nombre"** → Entra a la carpeta creada.  
4. **md Proyectos** → Crea una carpeta llamada Proyectos.  
5. **cd Proyectos** → Entra a la carpeta Proyectos.  
6. **md dj_marketplace** → Crea una carpeta llamada dj_marketplace.  
7. **cd dj_marketplace** → Entra a la carpeta dj_marketplace.  
8. **python -m venv venv** → Crea un entorno virtual.  
9. **venv\Scripts\activate** → Activa el entorno virtual.  
10. **pip install django** → Instala Django.  
11. **django-admin startproject marketplace_main** → Crea un proyecto Django.  
12. **cd marketplace_main** → Entra al proyecto.  
13. **python manage.py runserver** → Inicia el servidor local.  
14. **ctrl + c + c** → Detiene el servidor.  
15. **code .** → Abre el proyecto en VS Code.  
16. **pip install Pillow** → Instala la librería Pillow.  
17. **python manage.py migrate** → Aplica migraciones en la base de datos.  
18. **python manage.py createsuperuser** → Crea un usuario administrador.  
19. **python manage.py runserver** → Vuelve a iniciar el servidor.  
20. **python manage.py makemigrations** → Crea archivos de migración.  
21. **python manage.py startapp store** → Crea una aplicación llamada store.  
22. **python manage.py changepassword** → Cambia la contraseña de un usuario.  
</div>

---

<h2 align="center">Diagrama</h2>

<div style="margin-left: 40px; margin-right: 40px;">
Django usa la arquitectura MVT, muy parecida al patrón MVC:  
1. **Model** → Define cómo se estructuran y almacenan los datos.  
2. **View** → Contiene la lógica del negocio.  
3. **Template** → Se encarga de la presentación visual.  
</div>

---

<h2 align="center">Explicación de Archivos</h2>

<div style="margin-left: 40px; margin-right: 40px;">
- **settings.py** → Configuración principal del proyecto.  
- **urls.py** → Conecta las rutas con las vistas.  
- **models.py** → Define los modelos y tablas de la base de datos.  
- **views.py** → Contiene la lógica de las páginas.  
- **templates/store** → Carpeta para las plantillas HTML de la aplicación.  
</div>

---

<h2 align="center">Código de Archivos</h2>

<div style="margin-left: 40px; margin-right: 40px;">
- **models.py**: Define categorías y artículos con sus atributos.  
- **views.py**: Gestiona páginas principales, detalles de productos y registro de usuarios.  
- **templates**: Plantillas para autenticación y formularios.  
- **settings.py**: Configuración de aplicaciones, middlewares y templates.  
- **urls.py**: Rutas para login, registro, logout y detalles de ítems.  
- **forms.py**: Formularios para login, registro y creación de productos.  
</div>

---

<h2 align="center">Presentación Final</h2>

<div style="margin-left: 40px; margin-right: 40px;">
El proyecto tipo marketplace quedó funcional, con secciones esenciales como registro de usuarios, creación de productos, página de contacto y detalles individuales de artículos.  
La implementación en Django permitió desarrollar de manera eficiente, manteniendo separación de responsabilidades y un código organizado.  
</div>

---

<h2 align="center">Conclusión</h2>

<div style="margin-left: 40px; margin-right: 40px;">
La práctica consolidó conocimientos en desarrollo web backend con Django y las mejores prácticas de la línea de comandos.  
Se logró entregar una solución operativa de marketplace, reforzando la importancia de la arquitectura MVT y el uso de herramientas modernas para proyectos escalables.  
</div>
