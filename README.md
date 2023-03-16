# Snippets Personalizados en VS Code
### Made By Facundo Sichi

Hola, mi nombre es Facundo Sichi, desarrollador FullStack en tecnologias Web. El proposito de este documento y repositorio es compartir con la comunidad el listado de Snippets personalizados que fui adicionando a lo largo de toda mi trayectoria codeando. Estos Snippets tienen como proposito ayudarte a **Programar de una manera mucho mas veloz** a traves de la insercion de codigo como funciones y componentes de Javascript y Typescript puros **(.js | .ts)** y su respectiva integracion con React **(.jsx | .tsx)**


## Instrucciones para incorporar Snippets en VS Code

A continuacion presentare el listado de pasos a seguir para poder utilizar estos snippets en su propio VS Code.

1. Con VS Code corriendo presionar 
    >- `CTRL + SHIFT + P` -> Shortcut de acceso rapido a configuracion 
    >- Escribir Snippets en la barra de busqueda y acceder a la opcion que dice:  *`Snippets:Configure User Snippets`*
    
    Caso contrario presionar 'Archivo | File' en la parte superior izquierda
    
    Luego dirigirse a preferencias y en las opciones del desplegable les saldra una opcion de los snippets. Mi VS Code esta en ingles y la opcion aparece como : 

    *`Configure User Snippets`*


2. Una vez alli, nos aparecera un listado de todos los lenguajes y entornos soportados por VS Code nativamente. Nosotros debemos buscar los mismos nombres que aparecen en los archivos de la carpeta snippets en el repositorio. Los cuales son: 
    
    - javascript.json
    - javascriptreact.json
    - typescript.json
    - typescriptreact.json


3. A continuacion, vamos a ir seleccionando 1 por 1 los distintos lenguajes del listado y vamos a copiar y pegar el contenido de los archivos individuales de cada repositorio en el correspondiente archivo con ese nombre en VS Code. 

    ***Repetir este paso con cada archivo***

4. Recuerda guardar los cambios en los propios archivos de Snippets VS Code para aplicar los cambios. 

5. Ya Esta!!. Con eso ya estan configurados e integrados los snippets en tu flujo de trabajo de VS Code. 
    
***Nota: En caso de no funcionar, reinicia la instancia de VS Code que tienes y abrelo nuevamente.***

## Como utilizar los Snippets

Para poder utilizar los Snippets, simplemente debes tener abierto un archivo con la correspondiente extension con los snippets previamente configurados, en nuestro caso recuerden: 

- javascript.json
- javascriptreact.json
- typescript.json
- typescriptreact.json

Dentro de los archivos de los Snippets, en cada uno existe una propiedad llamada

>- `"prefix"`

La cual indica en shortcut a escribir para integrar ese snippet. 

A continuacion comparto el Listado completo de Snippets disponibles

| Shortcut | Snippet | Extension Soportada
| -- | -- | -- |
| cl | Insertar Console Log | .js  / .ts / .jsx / .tsx |
| gft | Insertar Funcion basica | .js  / .ts / .jsx / .tsx | 
| a | Insertar Alert | .js  / .ts / .jsx / .tsx | 
| gfor | Generar Estructura for | .js  / .ts / .jsx / .tsx | 
| gforE | Generar Estructura forEach | .js  / .ts / .jsx / .tsx | 
| gD | Generar Variable de Document por ID (DOM) | .js  / .ts | 
| gf | Insertar arrow Function | .js  / .ts / .jsx / .tsx | 
| gef | Insertar arrow Function con Export y Return | .js  / .ts / .jsx / .tsx | 
| gAEL | Generar Prototipo de AddEventListener | .js  / .ts | 
| gUseDispatch | Insertar el hook de useDispatch (REDUX)| .js  / .ts / .jsx / .tsx | 
| gUseSelector | Insertar el hook de useSelector (REDUX) | .js  / .ts / .jsx / .tsx | 
| gUseSelector | Insertar el hook de useSelector (REDUX) | .js  / .ts / .jsx / .tsx | 
| stles | Insertar el Stylesheet de React Native |.tsx | 
| gRNC | Crear un Functional Component en React Native |.tsx | 
| gRNCS | Crear un Functional Component en React Native + Stylesheet |.tsx | 


