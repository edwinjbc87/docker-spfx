# Imagen Docker para SharePoint Framework 1.17.2

## Detalles de la imagen
* Node: 16.20.0
* Yeoman: 4.3.1
* SharePoint Framework: 1.17.2
* Gulp-cli: 2.3.0
* Gulp: 4.0.2

## Como ejecutar
```
docker run -it --rm --name spfx-helloworld -v ${PWD}:/usr/app/spfx -p 5432:5432 -p 4321:4321 -p 35729:35729 edwinjbc87/spfx:1.7.1
```

## Errores conocidos
En caso de obtener un error al obtener las dependencias con NPM, utilizar en reemplazo Yarn: 
```
yo @microsoft/sharepoint --package-manager yarn
```

## Autores
* **Edwin Bonifacio** - *Trabajo inicial* - [edwinjbc87](https://github.com/edwinjbc87)
* Imagen basada en **waldekm/spfx** - [waldekmastykarz](https://github.com/waldekmastykarz)
