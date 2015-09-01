# Utils
Utilerias Para desarrollos



|  Navigational Shortcuts | Uses  |  
|---|---|
| Ctrl+L |  Go to line number. |
| Ctrl+I | Indent the highlighted text.  |
|Ctrl+Q | Goto last modified editor position  |
|Ctrl+K | Go to next occurrence of the selected text  |
|Ctrl+Shift+K |  Go to previous occurrence of the selected text |
|Ctrl+F6 | Navigate between open Editors (or, files in an editor)  |
|Ctrl+F7 | Navigate between open Views  |
|Ctrl+F8 | Navigate between open Perspectives  |
|Ctrl+Shift+P |  Navigating to Matching braces |
|F12 | Jump to the open Editor  |
|Ctrl+Shift+W | List all files open in an editor  |
|Alt+left arrow | Back (last editing position)  |
|Alt+right arrow  |  Forward (next editing position) |



|  Coding AssistantsCoding Assistants |  Uses |  
|---|---|
|Ctrl+Space|Brings up coding/context assistant.Make required selection and press enter or, double click.After selection, Javadoc will appear in hover Help.|
|Ctrl+Shift+M|Add import|
|Ctrl+Shift+O|Organize Imports|
|Ctrl+B|Executes an incremental build of a project in the navigation view
|Ctrl+E|Goes to the next error.|
|Alt+Shift+M|Extract Method|
|Alt+Shift+R|Rename method/variable|
|Ctrl+Shift+F|Format Code|
|Ctrl+Shift+E|Delete till end-of-line|



|Search Shortcuts|Uses|
|---|---|
|F3|Open Declaration of Selected Element|
|F4|Open hierarchy|
|Ctrl+F|Find/replace|
|Ctrl+H|Brings up Java search with the selected item in the search table.|
|Ctrl+Shift+T Or Ctrl+Shift+H|Type Browser:- Search a class/interface by typing it’s name(wildcards: ‘*’ and ‘?’ can also be used) “Ctrl+Shift+H” brings up Hierarchical Browser… works much the same as Type Browser!|
|Ctrl+Shift+G|Search References in workspace|
|Ctrl+O|Search data-members or methods in the Class (works similar to Ctrl+Shift+T ,i.e, type search… but the scope is only the current Class file open in the editor)|
|Ctrl+Shift+U|Search occurrences (of selected methodName or dataMember) within the same Class file.|

 Atajos de teclado. Dichos atajos los voy a dividir en dos casos puntuales iníciales que son los que todas los desarrolladores en dicho entorno mínimamente deberían saber, y los expertos que creo a mi entender que estará de más aclarar a quien están orientados no? Jajaja  :P.


|Atajo|Descripción|
|---|---|
|CTRL + E|    Acceso a los ficheros que ya están abiertos |
|CTRL + O|    Acceso a los atributos y métodos de esa clase|
|CTRL + O (2 veces)|    Igual que el anterior pero añadiendo los atributos y métodos de las clases padre|
|CTRL + L|    Acceso a la línea indicada|
|CTRL + K|    Rastrea la variable seleccionada|
|CTRL + F|    Buscar / Reemplazar una palabra|
|CTRL + D|    Eliminar la fila|
|CTRL + SUPR|    Eliminar la siguiente palabra|
|CTRL + RETRO|    Eliminar la anterior palabra|
|CTRL + MAY + SUPR|    Eliminar hasta el final|
|CTRL + Q|    Volver a la anterior pestaña de edición|
|CTRL + 3|    Cargador de vistas|
|CTRL + MAY + F|    Formatea el texto según lo configurado|
|CTRL + MAY + S|    Guarda todos los documentos abiertos|
|CTRL + MAY + O|    Organizador de imports (añadiéndolos si faltan)|
|CTRL + MAY + T|    Buscador de tipos en el workspace|
|CTRL + MAY + R|    Acceso a la búsqueda de recursos|
|CTRL + 7|    Comenta el texto seleccionado    |

Atajos Expertos

|Acción|    Descripción|
|---|---|
|Cambiar el texto a mayuscula|    Seleccionar el texto a pasar a mayúscula y pulsar CTRL + SHIFT + X|
|Cambiar el texto a minúscula|    Seleccionar el texto a pasar a mayúscula y pulsar CTRL + SHIFT + Y|
|Buscar todas las clases en el que método está siendo utilizado.|    Selecionamos el método y presionamos CTRL + SHIFT + G|
|Crear rápido una clase, interface ,etc.|    Presionamos la teclas CTRL + N|
|Ver las propiedades de una clase o proyecto.|    Primero se debe seleccionar y luego presionar ALT + ENTER|
|F3  Sobre el método  o la clase entramos donde se encuentra implementado.
|CTRL+ SHIFT + FLECHA ABAJO:| Posiciona el cursor en el método o propiedad siguiente al que estamos actualmente.|
|CTRL+ SHIFT + FLECHA ARRIBA:| Posiciona el cursor en el método o propiedad anterior al que estamos actualmente.|


Plugins Para Eclipse Kepler
```xml
<?xml version="1.0" encoding="UTF-8"?>
<bookmarks>
   <site url="http://update.atlassian.com/atlassian-eclipse-plugin/e3.6" selected="true" name="Atlassian Jira conector"/>
   <site url="http://update.eclemma.org" selected="true" name="Cobertura"/>
   <site url="http://dl.google.com/eclipse/inst/codepro/latest/3.5" selected="true" name="CodePro Google"/>
   <site url="http://eclipse-color-theme.github.com/update" selected="true" name="com.github.eclipsecolortheme.updatesite"/>
   <site url="http://ecobertura.johoop.de/update" selected="true" name="ecobertura"/>
   <site url="http://download.jboss.org/jbosstools/updates/stable/kepler/" selected="true" name="JBoss Tools 4.1 - Core - Stable Release Update Site"/>
   <site url="http://download.jboss.org/jbosstools/targetplatforms/jbosstoolstarget/kepler/" selected="true" name="JBoss Tools Target Platform - Kepler"/>
   <site url="http://download.eclipse.org/releases/kepler" selected="true" name="Kepler"/>
   <site url="http://archive.eclipse.org/mylyn/drops/3.8.0/v20120612-0600" selected="true" name="Mylyn for Eclipse 3.6, 3.7 and 3.8"/>
   <site url="http://download.eclipse.org/mylyn/releases/kepler" selected="true" name="Mylyn for Eclipse Kepler"/>
   <site url="http://download.oracle.com/otn_software/oepe/kepler" selected="true" name="Oracle Eclipse Pack for Eclipse"/>
   <site url="http://download.eclipse.org/tools/gef/updates/releases" selected="true" name="org.eclipse.gef.repository"/>
   <site url="http://www.soapui.org/eclipse/update" selected="true" name="SOAPUI"/>
   <site url="http://download.eclipse.org/technology/subversive/2.0/update-site/" selected="true" name="Subversive Site"/>
   <site url="http://download.eclipse.org/eclipse/updates/4.3" selected="true" name="The Eclipse Project Updates"/>
   <site url="http://download.eclipse.org/webtools/repository/kepler" selected="true" name="The Eclipse Web Tools Platform (WTP) software repository"/>
   <site url="http://community.polarion.com/projects/subversive/download/eclipse/4.0/update-site/" selected="true" name="Update Site"/>
</bookmarks>
```
