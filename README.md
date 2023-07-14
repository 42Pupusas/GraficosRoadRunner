# Comision de Graficos

Este repositorio servira como lista de recompensas para la creacion de diferentes graficas e imagenes necesarias para la pagina de [RoadRunner](roadrunner.lat) y los perfiles sociales asociados. El objetivo es crear un espacio para colaboracion abierto y organizado.

## Proceso Colaborativo

Este documento se mantendra actualizado con los ultimos documentos requeridos, y la recompensa ofrecida por su creacion.

Para aplicar a la recompensa, un colaborador creara una rama del repositorio con su nombre, y agregara una vista previa del documento a la carpeta `previas`.

Una vez aprobada la vista previa, la recompensa se entrega y los documentos finales se agregan a la carpeta `entregas`.

Un `merge commit` agregara los archivos a la rama principal, y en el mensaje del `commit` se agregara el `tx_hash` del pago de la recompensa.

### Como colaborar

La entrega de archivos y documentos se realizara por medio de [Git](https://git-scm.com/). Asegurate de instalar las herramientas de CLI para tu sistema antes de continuar con estos pasos.

Crea tu repositorio local y una rama con tu nombre:

```bash
git clone https://github.com/42Pupusas/GraficosRoadRunner.git
cd GraficosRoadRunner
git checkout -b <tu_nombre>
```

Agrega tus archivos a la carpeta indicada, ya sea `previas` o `entregas`. Ahora agrega tus cambios al repositorio remoto:

```bash
git add .
git commit -m "Titulo_Del_Documento: Agrega cualquier nota necesaria aqui"
git push origin <tu_nombre>
```

Asegurate de mantener tu rama principal actualizada!

```bash
git checkout mera
git pull
```

## Documentos Requeridos

Esta lista se actualizara cada vez que se agregue o complete un requerimiento. Recuerda usar el mismo titulo de documento de esta lista en tu mensaje de `commit`.

Todos los documentos deberan mantener el estilo, fuentes, y colores de la pagina, a menos que se establezca lo contrario.  

### Mejoras Logo Principal (150000 sats)

Criterio abierto, mantener los conceptos principales (correcaminos, rayo, carro). Entrega final debe incluir:

- Set con fondos solidos
- Set con fondo transparente y solo objetos

### Botones Pagina Principal (100000 sats)

Set de botones para la pagina principal de funciones (4 total). Botones deberian contener texto + imagen que facilmente identifiquen su funcion. Entrega final debe contener botones en ingles y español

### Botones Funcionalidad General (50000 sats)

Set de botones de fucnionalidad. 3 en total. Botones para volver a pagina principal, refrescar el viaje y cancelar accion. Sin texto.

### Diseños Mocks Paginas (50000 sats)

Set de bocetos de ideas para mejorar la interfaz de cada pagina. Entrega final debe contener un boceto por pagina.

## Criterio de Aceptacion

Este espacio colaborativo no es democratico. Me reservo el derecho de criterio y la decision final, pero una vez aceptado un requerimiento, el pago se realizara de forma publica y transparente.
