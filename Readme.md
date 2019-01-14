# Images para SharePoint Framework 1.7.1

## Detalles de la imagen
- Node: 8.12.0
- Yeoman: 2.0.5
- SharePoint Framework: 1.7.1
- Nano

## Como ejecutar

```
docker run -it --rm --name spfx-helloworld -v ${PWD}:/usr/app/spfx -p 5432:5432 -p 4321:4321 -p 35729:35729 edwinjbc87/spfx:1.7.1
```

## Adicionales
Utilizar Yarna en vez de npm en caso de obtener un error al obtener las dependencias con npm: 

```
yo @microsoft/sharepoint --package-manager yarn
```