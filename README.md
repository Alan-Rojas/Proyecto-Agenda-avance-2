# Proyecto-Agenda-avance-2
Este es el avance2 de mi proyecto: un diagrama de UML. Aquí explico qué componentes son los que derivan de mi proyecto.
En este caso identifiqué tres clases: el cliente, los objetivos/tareas, y la agenda. 
En el caso del cliente me interesan dos atributos: su nombre (str) y su ocupación (str). Derivado de esto, puedo genrar dos métodos. 
Dichos métodos son imporarDatos():str y creaPerfil(): void. De esta manera, al importar los datos los puedo llamar en otra clase para usarlos. 
En la clase de objetivos, identifiqué varios atributos: tipoDeObjetivo: str #Primoridial, Importante, Secundario; rangoTiempo: str #cu´ndo empieza y termina; 
descripcionObj: str #Qué quiere alcanzar?; horarioRecordatorio: str #a qué hora te recuerdo el objetivo; verificadorHabito: str #con qué acción verifico que realizas el hábito; 
cliente: Cliente #Información del cliente. De estos atributos derivan los métodos: creaObjetivo(): arreglo[] #Que crea el objetivo con los datos recibidos para importarlo a la agenda. 
En la clase de Agenda, se tienen como atributos: objetivo: Objetivo #El objetivo y sus datos; cliente: Cliente #Datos del cliente; calendario: arreglo[] #Calendario para fechas.
De estos atributos surgen estos métodos: despliegaCalendario(): void #Da un visual del calendario con los onjetivos; recuerdaObjetivo(): void #Recuerda el objetivo al usuario; 
verificaHabito(): bool #Asegura que se cumpla el hábito que lleva al objetivo; concluyeObjetivo():void #Termina el objetivo y lo da por completado o fallido; statusObjetivo(): str 
#Muestra hasta la fecha cómo es el progreso del objetivo: muestra los datos. 


