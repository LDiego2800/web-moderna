# La Web Moderna 

## Autor

* Luis Mezarina
* 201 Fundamentos
* Luis.mezarina2800@gmail.com
* 20 de Noviembre del 2024

## Sobre el proyecto

En “La Web Moderna” podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.


## Eslintrc

**env** Define los entornos en los que el código será ejecutado. Esto ayuda a ESLint a conocer qué variables globales estarán disponibles.

**browser: true** Indica que el entorno es un navegador, habilitando variables globales como window, document, etc.

**es2021: true** Indica que se está utilizando JavaScript moderno, compatible con ES2021.

**"extends": ["eslint:recommended"],** 
**extends** Define configuraciones base que el archivo hereda.
**eslint:recommended** Activa un conjunto básico de reglas recomendadas por ESLint para evitar errores comunes.

**"parserOptions": { "ecmaVersion": "latest", "sourceType": "module" },** 
**parserOptions** Configura el parser de ESLint para interpretar el código.
**ecmaVersion: "latest":**  Indica que se utilizará la versión más reciente de ECMAScript (JavaScript) disponible.
**sourceType: "module":** Especifica que el código utiliza módulos de JavaScript (import/export).

**"rules": { ... }** 
**rules:** Define las reglas personalizadas para ESLint. Cada regla tiene un nivel de severidad y opciones adicionales.

**Reglas específicas:**
**"indent": ["error", 2],** 
* Configura la indentación del código.
* "error": Genera un error si no se cumple la regla.
* 2: Exige que se usen 2 espacios para la indentación.

**"linebreak-style": ["error", "unix"],** 
* Fuerza un estilo de salto de línea específico.
* "unix": Usa saltos de línea estilo UNIX (\n).

**"quotes": ["error", "single"],** Obliga a usar comillas simples (') en lugar de dobles (").

**"semi": ["error", "always"],** Obliga a terminar cada instrucción con un punto y coma (;).

**"no-unused-vars": "warn",** Genera una advertencia si hay variables declaradas que no se utilizan.

**"no-console": "warn"** Genera una advertencia si se utilizan declaraciones de console como console.log.



## Despliegue

[Link de Github](https://github.com/LDiego2800/web-moderna) 
