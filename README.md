# Ejemplo ESLint

Este proyecto es un ejemplo práctico de configuración y uso de ESLint para JavaScript.

## Requisitos previos

- Node.js (versión 14 o superior)
- npm (viene incluido con Node.js)

## Instalación

1. Clona o descarga este repositorio
2. Instala las dependencias:

```bash
npm install
```

## Dependencias instaladas

Este proyecto incluye las siguientes dependencias de desarrollo:

- **eslint** (^9.33.0) - Herramienta principal de linting
- **eslint-config-prettier** (^10.1.8) - Configuración para integrar con Prettier
- **eslint-plugin-prettier** (^5.5.4) - Plugin de Prettier para ESLint
- **prettier** (3.6.2) - Formateador de código

## Scripts disponibles

- `npm run lint` - Ejecuta ESLint en el archivo ejemplo.js
- `npm start` - Ejecuta el archivo ejemplo.js con Node.js

## Uso

Para verificar el código con ESLint:

```bash
npm run lint
```

Para ejecutar el código de ejemplo:

```bash
npm start
```

## Configuración

El archivo `eslint.config.mjs` contiene la configuración de ESLint con las siguientes reglas habilitadas:

- `no-unused-vars`: Advierte sobre variables no utilizadas
- `no-undef`: Error al usar variables no definidas
- `no-console`: Advierte sobre el uso de console
- `no-extra-semi`: Error por puntos y comas extra
- `eqeqeq`: Obliga a usar comparación estricta (=== en lugar de ==)
- `camelcase`: Advierte si no se usa camelCase
- `semi`: Obliga a usar punto y coma
- `quotes`: Obliga a usar comillas simples
- `indent`: Indentación de 2 espacios
- `comma-dangle`: Coma final solo en multilínea

## Archivo de ejemplo

El archivo `ejemplo.js` contiene ejemplos de código que demuestran cada una de las reglas de ESLint configuradas.