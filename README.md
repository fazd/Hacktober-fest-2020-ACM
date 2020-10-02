# Organiza: ACM UNINORTE 2020

# Hacktober fest

Este repositorio está diseñado con fines educativos para explicar como realizar un pull request a los usuarios del grupo de ACM uninorte (2020)

## Paso 0

Se debe tener instalado git en el computador

- Para descargar git en el pc, debes descargar el siguiente programa [Git](https://git-scm.com/downloads)
- Instalar git y abrirlo en la carpeta donde guardarás el repositorio
- Tener una cuenta en [Github](htpps://www.github.com)

## Paso 1

Visitamos el repositorio al cual queremos contribuir
https://github.com/fazd/Hacktober-fest-2020-ACM

## Paso 2

realizamos un fork al repositorio presionando el botón de fork:
![alt text](guide-files/fork.PNG?raw=true 'Fork')

## Paso 3

Visitamos nuestro repositorio creado en nuestra cuenta:
https://github.com/yourUser/Hacktober-fest-2020-ACM

## Paso 4

Clonamos el repositorio:

```ssh
$ git clone https://github.com/yourUser/Hacktober-fest-2020-ACM`
$ cd Hacktober-fest-2020-ACM`
```

## Paso 5

Agregar una foto al folder de **avatars**

## Paso 6

Agregar en el archivo de **README.md**  
"- Tu nombre"

## Paso 7

En la tabla (Html) agregar tu nombre el siguiente codigo con tus datos

```ssh
    <td align="center">
      <img src="avatars/yourPicture" width="100px;" alt=""/><br/><sub><b>Your Name</b></sub></a><br/>
    </td>
```

## Paso 8

Creamos una nueva rama y agregamos los cambios al repositorio

```ssh
$ git checkout -b AddYourName_Contribution
$ git add -A
$ git commit -m "add Your name into readme files"
$ git push origin AddYourName_Contribution
```

## Paso 9

Verificamos que los cambios estén en el repositorio de github.

## Paso 10

Nos dirigimos al repositorio nuestro (https://github.com/yourUser/Hacktober-fest-2020-ACM) y allí nos vamos a la ventana de pull request.

## Paso 11

Presionamos el botón de Pull request y llenamos la información de la siguiente manera:

- base repository: fazd/Hacktober-fest-2020-ACM
- base: master
- head repository: yourUser/Hacktober-fest-2020-ACM
- base: La rama que acaban de crear

Presionas en crear pull request y escribes el mensaje explicando que hiciste

# Contribución

Muchas gracias por contribuir a este repositorio

- Fabio Zapata
- Daniel Soto

<table>
<tr>
    <td align="center"><img src="avatars/fabioZapata.jpg" width="100px;" alt=""/><br /><sub><b>Fabio Zapata</b></sub></a><br/></td>
    <td align="center"><img src="avatars/yo.jpg" width="100px;" alt=""/><br /><sub><b>Daniel Soto</b></sub></a><br/></td>
</tr>
  
</table>
