# Proyecto a dockerizar. Workshop Docker 101 Nerdearla 2020.

## Enunciado

Este repositorio tiene una aplicación React, pero no te asustes, no hace falta que sepas React para poder hacer esta actividad.

La idea de esta actividad es que puedas crear el archivo Dockerfile necesario para poder dockerizar el proyecto. Como dije, no es necesario saber React pero te voy a tirar un par de pistas sobre cosas que si vas a necesitar:

- La imagen de la que podes partir es node:10.15-alpine. Es un poco vieja pero sirve para este ejercicio
- El proyecto en React requiere algunas dependencias, el comando para poder instalarlas es `npm install --silent`
- React tiene dos posibles builds, desarrollo y producción. Si queres generar el de producción, el comando que necesitas es `npm run build`
- Generalmente el puerto que se utiliza es el 3000
- El comando para levantar la aplicación es `npm start`

## Plataforma

Si pudiste instalar Docker en tu computadora sentite libre de correrlo ahí, pero como a veces pueden surgir incovenientes que no logres solucionar en la duración de un workshop, te recomendamos que lo hagas con "Play with Docker", podés acceder de forma gratuita en: https://labs.play-with-docker.com/

Clickea en la barra lateral izquierda la opción "Add new instance" y arrastrá el código de este repositorio a la terminal que se te crea para subirlo automaticamente.

## Dudas, consultas, feedback.

Si tenés cualquier tipo de duda, consulta o queres pasar feedback sobre la actividad o el workshop en general, podes contactarme directamente en mi twitter @JuaniGallo, tengo los MDs abiertos.
