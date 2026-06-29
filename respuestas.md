Parte 1: Clonación vs. Archivo ZIPSi te bajás el archivo comprimido (ZIP), te estás llevando solo el código suelto de ese momento preciso. Nada de historial, nada de ramas y cero conexión con el repositorio original. Si el dueño del proyecto actualiza algo, marchaste y tenés que volver a descargar todo. En cambio, al usar el comando de clonar, te traés el proyecto completo con todo Git andando. Te quedan los commits guardados, podés navegar entre ramas y, como seguís conectado a GitHub, actualizar tu versión o subir cambios. 

 Parte 2: README.mdEl README es como la portada y el manual de supervivencia de un repositorio. Es el primer documento que vas a leer para entender de qué trata el software y con qué herramientas se armó. Pero su función más importante en el día a día es explicarte cómo hacer funcionar todo en tu propia computadora: te suele detallar los comandos exactos para instalar dependencias o levantar el entorno de desarrollo. Básicamente, evita que te tranques antes de empezar a programar. 
 
  Parte 3: Estado y seguimientoCuando corremos el comando para ver el estado, Git nos avisa que encontró la carpeta nueva de Estudiantes y nos la marca en rojo como untracked (sin seguimiento). Esto pasa porque el sistema reconoce que metimos archivos nuevos en el proyecto, pero como nosotros todavía no le dimos la orden, los está ignorando en su registro de cambios. Para que eso cambie y queden en el área de preparación listos para guardar, tenemos que pasarlos primero por un git add. 
  
   Parte 4: La función de un CommitPodemos pensar en un commit como un punto de guardado obligatorio en el historial de nuestro proyecto. Es una captura exacta de cómo estaban nuestros archivos en ese instante. Al hacer un commit estamos cerrando una etapa y asegurándola en la base de datos de nuestra compu. Lo mejor es que guarda un montón de contexto: quién lo hizo, a qué hora, y un mensaje que explica qué modificamos. Esto es un salvavidas, porque si más adelante rompés el código, podés mirar el historial y volver hacia atrás a esta versión estable. Son como copias de seguridad.  
   
   Parte 5: El uso de ramasArmar ramas secundarias es clave para no hacer un desastre en el proyecto. La rama principal (main) tiene que tener sí o sí el código que sabemos que funciona. Si nos ponemos a tocar directamente ahí, podemos tirar abajo todo el programa. Al crearnos una rama nuestra, abrimos un espacio de pruebas seguro. Ahí podemos desarrollar cosas y equivocarnos tranquilos. 
   
    Parte 6: Relación y explicación: hello.sh y .gitignoreEl comando de estado no nos muestra el archivo hello.sh por culpa del .gitignore. Si entramos a mirar ese archivo, vemos que está configurado a propósito para bloquear cualquier cosa que termine en .sh. El .gitignore sirve para eso: le avisa a Git qué cosas locales tiene que ignorar siempre. Se usa un montón para no subir carpetas pesadas con instalaciones locales, archivos temporales de Windows o documentos que tengan claves privadas. 
    
     Parte 7: Pull RequestCuando ya termine de programar algo en mi rama y quiero adjuntarlo a la rama principal, uso el Pull Request. Es una forma estructurada de decirle al resto del equipo que ya terminé con mi parte y quiero integrarla al código principal. Es una solicitud formal. 
     
      Parte 8: Reflexión final
      
      1. ¿Qué fue lo más sencillo de la tarea?
Lo que me resultó más fluido fue la configuración de las cuentas iniciales, hacer el repositorio y la instalación básica de Git en la computadora. 

 2. ¿Qué fue lo más difícil?
Sin dudas, pelearme con las diferentes terminales de Windows. Por estar usando PowerShell, comandos que deberían correr bien me tiraban errores de sintaxis o parámetros ambiguos, y hasta me saltó un error del entorno WSL al querer ejecutar un script. Darme cuenta de cómo interactuaban las consolas y cómo configurar las rutas de los repositorios me llevó bastante tiempo. 

 3. ¿Qué ventajas observa en el uso de Git y GitHub para proyectos de software?
Git y GitHub son muy útiles porque permiten guardar el historial de los cambios realizados en un proyecto y volver a una versión anterior si hay algún error. Además, facilitan el trabajo en equipo, ya que varias personas pueden colaborar en el mismo proyecto sin sobrescribir el trabajo de los demás. Me parece que son herramientas muy importantes para organizar mejor el desarrollo de software.

  4. ¿Considera útil el uso de ramas? Justifique su respuesta.
Sí, considero que el uso de ramas es muy útil porque permite trabajar en nuevas funciones o hacer cambios sin afectar la versión principal del proyecto. De esa forma, si algo sale mal, no se rompe el trabajo que ya estaba funcionando. Además, también facilita probar ideas y luego unir los cambios cuando ya están listos. 