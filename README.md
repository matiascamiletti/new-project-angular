# Nuevo proyecto en Angular
Pasos para la creación de un proyecto en Angular.

1. Instalar AngularCLI, si todavia no lo tienes instalado:
```bash
npm install -g @angular/cli
```
2. Crear nueva aplicación:
```bash
ng new name-of-project
```
3. Ejecutar proyecto para poder verlo en el navegador y realizar las pruebas:
```bash
cd name-of-project
ng serve --open
```

# Como crear un nuevo componente:
1. Ejecutar siguiente comando:
```bash
ng generate component name-of-component
```

# Como crear un nuevo servicio:
1. Ejecutar siguiente comando:
```bash
ng generate service name-of-service
```
2. Agregar servicio al modulo: app.modules.ts:
```ts
providers: [
    YourServiceService,
    /* . . . */
  ],
```

# Como usar Routing:
```bash
ng generate module app-routing --flat --module=app
```

# Compilar proyecto:
1. Ejecutar siguiente comando:
```bash
ng build --prod
```

# Recursos disponibles:
1. Plataforma para generar documentación de un proyecto Angular facilmente: https://compodoc.github.io/compodoc/