# Alerta Dengue — Proyecto base (estructura)

Este repositorio contiene **solo la estructura principal** (carpetas y archivos básicos) sin `.java`.

## Estructura
```
src/main/java/pe/autonoma/alerta/{domain,service/impl,persistence/csv,ui,util}
src/main/resources
src/test/java/pe/autonoma/alerta/{service,persistence,ui}
docs/
scripts/
pom.xml
```
> Se incluyen archivos `.gitkeep` para que Git registre las carpetas vacías.

## Requisitos
- JDK 21
- Apache NetBeans IDE 25 (o cualquier IDE con soporte Maven)
- Maven (NetBeans ya lo incluye)

## Abrir en NetBeans
1. **File → Open Project...** y selecciona esta carpeta.
2. Crea tus clases en los paquetes indicados (`pe.autonoma.alerta.*`).
3. Ejecuta con **Run** o desde consola: `mvn -q -DskipTests package`.
