# BackEnd-NodeJS
# Product Management CLI - FakeStore API

Aplicación de consola en **Node.js** para gestionar productos mediante la API de FakeStore

## ⚙️ Configuración
* **Entrada:** `index.js`
* **Módulos:** `"type": "module"` habilitado
* **Script:** `"start": "node index.js"` en `package.json`

## ⌨️ Comandos (CLI)

| Acción | Comando |
| :--- | :--- |
| **Listar todos** | `npm start GET products` |
| **Buscar por ID** | `npm start GET products/<id>` |
| **Crear nuevo** | `npm start POST products <title> <price> <category>` |
| **Eliminar** | `npm start DELETE products/<id>` |

## 🛠️ Tecnologías Aplicadas
* **Captura de datos:** `process.argv`.
* **Peticiones:** API `fetch` asíncrona.
* **Lógica:** Destructuring, Spread Operator y métodos de Arrays.