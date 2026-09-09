## Glosario Software

### 1. Node.js

- **Término:** Node.js  
- **Descripción:** Entorno de ejecución de código JavaScript que funciona fuera del navegador. Permite desarrollar aplicaciones del lado del servidor, APIs, herramientas de línea de comandos y aplicaciones web. Es multiplataforma y se utiliza junto con herramientas como npm para administrar paquetes.
- **Ejemplo:** Crear un servidor web sencillo con Node.js:

```javascript
const http = require("http");

const servidor = http.createServer((solicitud, respuesta) => {
  respuesta.writeHead(200, { "Content-Type": "text/plain" });
  respuesta.end("Hola desde Node.js");
});

servidor.listen(3000, () => {
  console.log("Servidor ejecutándose en el puerto 3000");
});
```

### 2. NVM

- **Término:** NVM — *Node Version Manager*  
- **Descripción:** Herramienta de línea de comandos que permite instalar, administrar y cambiar entre diferentes versiones de Node.js en un mismo equipo. Es útil cuando distintos proyectos requieren versiones específicas de Node.js.
- **Ejemplo:** Instalar y utilizar una versión determinada de Node.js:

```bash
nvm install 20
nvm use 20
node --version
```

`nvm install 20` instala Node.js versión 20, mientras que `nvm use 20` la activa para trabajar en el proyecto.

## Glosario Ser

### 1. Marca personal

- **Término:** Marca personal  
- **Descripción:** Es la percepción, reputación e imagen que una persona construye y comunica en los ámbitos personal, académico o profesional. Incluye sus conocimientos, habilidades, valores, forma de comunicarse y manera de diferenciarse de los demás.
- **Ejemplo de aplicación:** Un desarrollador puede construir su marca personal publicando proyectos en GitHub, compartiendo conocimientos sobre programación y participando en comunidades tecnológicas.

### 2. Huella

- **Término:** Huella  
- **Descripción:** Es la influencia, recuerdo o impacto que una persona deja en los demás mediante sus acciones, conocimientos, valores y relaciones. En el contexto digital, también puede referirse a la información y las actividades que una persona deja en Internet.
- **Ejemplo de aplicación:** Una persona deja una huella positiva cuando ayuda a sus compañeros, comparte conocimientos y desarrolla proyectos que benefician a su comunidad.

## Glosario Inglés

### 1. Assess

- **Término:** Assess  
- **Traducción:** Evaluar, valorar o analizar  
- **Descripción en inglés:** To examine or evaluate something carefully in order to understand its quality, importance, condition, or effectiveness.
- **Descripción en español:** Examinar o evaluar cuidadosamente algo para conocer su calidad, importancia, estado o efectividad.
- **Example in English:**  
  *The manager will assess the candidate’s technical skills during the interview.*

### 2. Dispelling interviewing myths

- **Término:** Dispelling interviewing myths  
- **Traducción:** Desmontando los mitos de las entrevistas  
- **Descripción en inglés:** The process of correcting false beliefs or common misunderstandings about job interviews.
- **Descripción en español:** Proceso de aclarar y corregir creencias falsas o ideas equivocadas que suelen existir sobre las entrevistas de trabajo.
- **Example in English:**  
  *The workshop focuses on dispelling interviewing myths and preparing candidates for real interview situations.*
