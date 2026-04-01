# Proyecto EV01 - GitFlow y DevOps básico


## 📌 Descripción
Este repositorio demuestra el uso de control de versiones con Git, trabajo colaborativo y automatización básica siguiendo el modelo GitFlow.

---

## 🧩 Convenciones de commits

Se utilizan mensajes claros y estructurados:

- feat: para nuevas funcionalidades
- fix: para correcciones de errores

Ejemplos:
- feat: agrega fecha al README
- fix: corrige formato de fecha

---

## 🌿 Naming de ramas

Se utiliza el siguiente esquema:

- main → rama de producción
- develop → integración
- feature/<nombre> → nuevas funcionalidades
- hotfix/<nombre> → correcciones urgentes

Ejemplos:
- feature/fecha-1
- feature/fecha-2
- hotfix/fix-fecha

---

## 🔀 Flujo de merges

Se sigue el modelo GitFlow:

- Las ramas feature se crean desde develop
- Las feature se integran a develop mediante Pull Request
- Las ramas hotfix se crean desde main
- Los hotfix se integran a main mediante Pull Request

---

## 👀 Estrategias de revisión

Se utiliza Pull Request para integrar cambios:

- Cada feature requiere un PR hacia develop
- Cada hotfix requiere un PR hacia main
- Antes del merge se revisan los cambios
- Se valida que el código funcione correctamente

---

## 🚀 Resultado

El repositorio contiene:

- Ramas main y develop
- Al menos 2 features
- Al menos 1 hotfix
- Pull Requests realizados
- Flujo GitFlow aplicado correctamente

cambio main fix

