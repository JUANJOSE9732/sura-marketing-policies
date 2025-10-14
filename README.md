# SURA Marketing Automation - Políticas de Privacidad

Este repositorio contiene los documentos de políticas legales para la aplicación SURA Marketing Automation integrada con Facebook/Meta.

## 📄 Documentos Incluidos

1. **privacy-policy.html** - Política de Privacidad completa conforme a RGPD
2. **terms-of-service.html** - Términos y Condiciones de Servicio
3. **data-deletion.html** - Instrucciones de Eliminación de Datos de Usuario

## 🚀 Despliegue en GitHub Pages (5 minutos)

Sigue estos pasos para alojar estos documentos en GitHub Pages gratuitamente:

### Paso 1: Crear Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión (o crea una cuenta gratis)
2. Haz clic en el botón **"New"** (Nuevo) o **"+"** en la esquina superior derecha
3. Selecciona **"New repository"** (Nuevo repositorio)
4. Configura el repositorio:
   - **Repository name:** `sura-marketing-policies` (o el nombre que prefieras)
   - **Description:** "Documentos legales para SURA Marketing Automation"
   - Selecciona **Public** (Público) - necesario para GitHub Pages gratuito
   - **NO** marques "Initialize this repository with a README" ya que crearemos los archivos localmente
5. Haz clic en **"Create repository"**

### Paso 2: Subir los Archivos al Repositorio

Tienes dos opciones:

#### Opción A: Usando Git (Recomendado)

1. Abre tu terminal o línea de comandos
2. Navega a la carpeta donde están los archivos:
   ```bash
   cd C:\Users\jjmpo\sura-marketing-policies
   ```

3. Inicializa un repositorio Git local:
   ```bash
   git init
   ```

4. Agrega todos los archivos:
   ```bash
   git add .
   ```

5. Crea el primer commit:
   ```bash
   git commit -m "Initial commit: Add privacy policy, terms of service, and data deletion documents"
   ```

6. Conecta con el repositorio remoto (reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub):
   ```bash
   git remote add origin https://github.com/TU_USUARIO/sura-marketing-policies.git
   ```

7. Sube los archivos a GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

#### Opción B: Subida Manual (Más Simple)

1. Ve a tu repositorio recién creado en GitHub
2. Haz clic en **"uploading an existing file"** o **"Add file" → "Upload files"**
3. Arrastra y suelta los 3 archivos HTML y este README.md
4. Haz clic en **"Commit changes"**

### Paso 3: Activar GitHub Pages

1. En tu repositorio de GitHub, haz clic en **"Settings"** (Configuración)
2. En el menú lateral izquierdo, busca y haz clic en **"Pages"**
3. En la sección **"Source"** (Fuente):
   - Selecciona **"Deploy from a branch"**
   - En **"Branch"**, selecciona **"main"** y la carpeta **"/ (root)"**
4. Haz clic en **"Save"** (Guardar)
5. Espera 1-2 minutos mientras GitHub despliega tu sitio
6. Actualiza la página y verás un mensaje verde con tu URL:
   ```
   Your site is live at https://TU_USUARIO.github.io/sura-marketing-policies/
   ```

### Paso 4: Verificar las URLs

Tus documentos estarán disponibles en las siguientes URLs (reemplaza `TU_USUARIO`):

- **Política de Privacidad:**
  ```
  https://TU_USUARIO.github.io/sura-marketing-policies/privacy-policy.html
  ```

- **Términos de Servicio:**
  ```
  https://TU_USUARIO.github.io/sura-marketing-policies/terms-of-service.html
  ```

- **Eliminación de Datos:**
  ```
  https://TU_USUARIO.github.io/sura-marketing-policies/data-deletion.html
  ```

## 📝 Usar las URLs en Meta/Facebook

Una vez que tengas las URLs funcionando:

1. Copia las URLs generadas arriba
2. Ve al Panel de Apps de Meta/Facebook
3. Pega las URLs en los campos correspondientes:
   - **URL de la política de privacidad:** URL de `privacy-policy.html`
   - **URL de Condiciones del servicio:** URL de `terms-of-service.html`
   - **URL de instrucciones para la eliminación de datos:** URL de `data-deletion.html`

## ⚠️ Importante: Personalización

Antes de usar en producción con SURA, debes:

1. **Revisar y actualizar** la información de contacto en todos los documentos
2. **Consultar con el departamento legal** de SURA para aprobación
3. **Actualizar el correo electrónico** `jimoposada@gmail.com` con el correo corporativo oficial
4. **Agregar información corporativa** específica de SURA (dirección, datos fiscales, etc.)
5. **Revisar las secciones de pagos y facturación** según el modelo de negocio real

## 🔄 Actualizar los Documentos

Si necesitas hacer cambios en el futuro:

1. Edita los archivos HTML localmente
2. Sube los cambios a GitHub:
   ```bash
   git add .
   git commit -m "Update policies"
   git push
   ```
3. GitHub Pages se actualizará automáticamente en 1-2 minutos

## 📧 Contacto

Para preguntas sobre estos documentos: jimoposada@gmail.com

## 📜 Licencia

Estos documentos son plantillas legales. Se recomienda consultar con un abogado antes de usar en producción.

---

**Nota:** Estos documentos están diseñados para cumplir con RGPD y requisitos de Meta/Facebook, pero deben ser revisados por profesionales legales antes de uso en producción.
