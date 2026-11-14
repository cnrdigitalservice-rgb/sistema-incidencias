
# SISTEMA DE INCIDENCIAS

## 1. Descripción del proyecto

El proyecto consiste en desarrollar un sistema básico
para validar incidencias informáticas mediante JavaScript.

Se utiliza GitHub Actions para implementar un proceso
de integración continua que ejecuta automáticamente
pruebas cada vez que se realizan cambios en el repositorio.

## 2. Integrantes

- Integrante 1: Copaticona Nolasco, Ronald
- Integrante 2: Quirita Llasa Juan Carlos
- Integrante 2: Tenorio Cartagena, José Miguel

- Curso: Herramientas de Desarrollo

## 3. Tecnologías utilizadas

- GitHub
- GitHub Actions
- JavaScript
- Node.js 22

## 4. Estructura del proyecto

- README.md
- package.json
- incidencias.js
- test.js
- .github/workflows/ci.yml

## 5. Pruebas automatizadas

1. Acepta una incidencia válida.
2. Rechaza prioridad desconocida.
3. Rechaza descripción vacía.

## 6. Procedimiento realizado

1. Creación del repositorio en GitHub.
2. Incorporación del compañero como colaborador.
3. Desarrollo del módulo de validación.
4. Implementación de tres pruebas automatizadas.
5. Configuración de GitHub Actions.
6. Ejecución inicial exitosa.
7. Simulación de un error controlado.
8. Identificación de la prueba fallida.
9. Corrección del código.
10. Verificación de las tres pruebas exitosas.

## 7. Preguntas de reflexión

### ¿Qué evento activa el workflow?

Los eventos push y pull_request activan
automáticamente el workflow.

### ¿Qué verifica la prueba automatizada?

Verifica que las incidencias tengan código,
descripción y prioridad permitida.

### ¿Qué diferencia existe entre un commit
y una ejecución de Actions?

Un commit registra los cambios realizados
en el repositorio. Una ejecución de Actions
verifica automáticamente esos cambios.

### ¿Qué ventaja ofrece detectar un error antes
de integrar más cambios?

Permite identificar y corregir errores
oportunamente, evitando que afecten otras
funcionalidades del sistema.

## 8. Enlaces del proyecto

Repositorio:
https://github.com/cnrdigitalservice-rgb/sistema-incidencias


Ejecuciones GitHub Actions:
https://github.com/cnrdigitalservice-rgb/sistema-incidencias/actions

## 9. Conclusión

La práctica permitió implementar un proceso de
integración continua utilizando GitHub Actions.
Se desarrollaron tres pruebas automatizadas para
validar las incidencias informáticas. Asimismo,
se simuló un error intencional que fue detectado
automáticamente por GitHub Actions. Posteriormente,
se corrigió el código y se verificó que todas las
pruebas fueran exitosas. Esta experiencia permitió
comprender la importancia de la integración continua
para mejorar la calidad del software.

