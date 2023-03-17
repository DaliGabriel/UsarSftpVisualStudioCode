# UsarSftpVisualStudioCode
Breve tutorial a cerca de como utilizar esta extension en vs code


# Es importante recordar el directorio que se esta utilizando para trabajar con sftp


# Primero descargar la extensión desde el marketplace de visual studio code

<h1>Se abre la paleta de comandos</h1>

```
control + Mayús + P
```

<h1>Se escribe: </h1>

```
SFTP:CONFIG
```

# Presionar enter

<h1>Pegamos el siguiente json con los datos necesarios </h1>

```
{
    "name": "My Server",
    "host": "ftp.nombreDelServidor.com",
    "protocol": "ftp",
    "port": 21,
    "username": "userName",
    "password": "Password",
    "remotePath": "/",
    "uploadOnSave": true,
    "useTempFile": false,
    "openSsh": false
}
```
# Para poder editar los archivos utilizando la extension Sftp es necesario realizar la siguiente [Configuración](https://github.com/liximomo/vscode-sftp/wiki/Setting#downloadwhenopeninremoteexplorer). De lo contrario va a necesitar descargar todo el proyecto y otras movidas extrañas.
