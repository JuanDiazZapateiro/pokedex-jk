# Subida de Proyecto a Azure (Static Web App)

## 1. Creación del recurso
- Ingresé al portal de Azure.
- Creé un recurso de tipo **Static Web App**.
- Llené los campos requeridos (nombre, región, plan, etc.).

## 2. Integración con GitHub
- Vinculé mi cuenta de GitHub desde Azure.
- Seleccioné el repositorio:
  **pokedex-jk**
- Configuré la rama y las opciones de despliegue.

## 3. Despliegue automático
- Azure generó un workflow automáticamente.
- Se ejecutó el proceso de build y deploy del proyecto.

## 4. Problemas encontrados

### Error 1: Imágenes no cargaban
- Al principio, la aplicación se desplegó pero las imágenes no se mostraban.
- Posible causa: rutas incorrectas o diferencias entre rutas locales y producción.
- Solución: corregir las rutas (usar rutas relativas o verificar nombres de carpetas).

### Error 2: Problema con "Security Headers"
- Aparecía un error relacionado con **Security Headers**.
- Esto suele ocurrir por configuraciones de seguridad del navegador o del servidor.
- Posible solución: revisar configuración de headers o archivos de configuración del proyecto.

## 5. Resultado
- Finalmente, la aplicación quedó desplegada correctamente en Azure.