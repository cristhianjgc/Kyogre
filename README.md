# README.md

## Proyecto Angular

### Instalación y Configuración

#### **1. Instalación de Node.js y Angular CLI**
Si no tienes Node.js instalado, descárgalo desde [nodejs.org](https://nodejs.org/) e instala la versión **LTS**.

Luego, instala Angular CLI globalmente con:
```bash
npm install -g @angular/cli
```
Verifica la instalación con:
```bash
ng version
```

#### **2. Crear un Nuevo Proyecto Angular**
Si deseas crear un nuevo proyecto desde cero:
```bash
ng new nombre-del-proyecto
cd nombre-del-proyecto
npm install
```

#### **3. Instalar un Proyecto Existente**
Si ya tienes un proyecto y necesitas instalarlo:
```bash
cd nombre-del-proyecto
npm install
ng serve
```
Esto iniciará el servidor en **http://localhost:4200/**.

---
## **Actualización de Node.js y Angular**

#### **1. Actualizar Node.js**
##### **Windows (usando el instalador oficial)**
- Descarga la última versión desde [nodejs.org](https://nodejs.org/).
- Instala y verifica con:
  ```bash
  node -v
  ```

##### **macOS (Homebrew)**
```bash
brew update
brew upgrade node
```

##### **Linux (nvm)**
Si usas `nvm`, actualiza con:
```bash
nvm install node
nvm alias default node
```

#### **2. Actualizar Angular**
Para actualizar Angular CLI globalmente:
```bash
npm install -g @angular/cli@latest
```

Para actualizar Angular dentro del proyecto:
```bash
ng update @angular/core @angular/cli
```

Si necesitas actualizar todas las dependencias de Angular:
```bash
ng update
```

---
## **Hacer una copia del Proyecto**

Si necesitas clonar este proyecto en otro entorno:
```bash
git clone https://github.com/usuario/nombre-del-repositorio.git
cd nombre-del-repositorio
npm install
ng serve
```

Si deseas crear una copia manual del código:
1. Copia la carpeta del proyecto.
2. En la nueva ubicación, elimina la carpeta `node_modules`.
3. Ejecuta `npm install` para reinstalar las dependencias.

---
### **Notas Finales**
- Usa `ng serve --open` para abrir el proyecto automáticamente en el navegador.
- Si usas `git`, recuerda actualizar con `git pull origin main` antes de comenzar.
- Para producción, usa `ng build --prod`.

Si tienes dudas, consulta la documentación oficial de Angular en [angular.dev](https://angular.dev/).

