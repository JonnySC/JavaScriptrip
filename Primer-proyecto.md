Para crear un nuevo proyecto de Node.js, puedes seguir estos pasos:

1. Abre una terminal o línea de comandos y navega hasta la carpeta donde deseas crear tu proyecto.

2. Ejecuta el siguiente comando para crear un nuevo directorio para tu proyecto:

   ```bash
   mkdir nombre-del-proyecto
   ```

3. Accede al directorio de tu proyecto:

   ```bash
   cd nombre-del-proyecto
   ```

4. A continuación, inicializa tu proyecto Node.js ejecutando el siguiente comando:

   ```bash
   npm init
   ```

   Esto iniciará un asistente interactivo que te guiará para configurar tu proyecto. El asistente te hará varias preguntas sobre el nombre del proyecto, versión, descripción, punto de entrada del programa, autor, licencia, etc. Puedes presionar "Enter" para aceptar los valores predeterminados o ingresar tus propias respuestas.

5. Después de completar el asistente, se generará un archivo llamado "package.json" en el directorio de tu proyecto. Este archivo contiene la configuración y la lista de dependencias de tu proyecto.

6. Ahora puedes empezar a agregar archivos y escribir tu código dentro de la estructura de tu proyecto. El punto de entrada del programa se especifica en el archivo "package.json" bajo la propiedad "main".

7. Si deseas agregar dependencias a tu proyecto, puedes instalarlas utilizando el comando `npm install`. Por ejemplo, para instalar la dependencia "express", ejecuta:

   ```bash
   npm install express
   ```

   Esto descargará e instalará la última versión de "express" y agregará la dependencia al archivo "package.json".

8. Ahora estás listo para comenzar a desarrollar tu proyecto de Node.js. Puedes ejecutar tu código utilizando el comando `node nombre-del-archivo.js`, donde "nombre-del-archivo.js" es el nombre del archivo que contiene tu código de inicio.

Recuerda que estos son solo los pasos básicos para crear un nuevo proyecto de Node.js. Puedes personalizar y ampliar tu proyecto agregando más archivos, configuraciones y dependencias según tus necesidades.