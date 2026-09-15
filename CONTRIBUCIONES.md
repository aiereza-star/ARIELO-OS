# 🤝 Guía de Contribuciones - Arielo OS

Gracias por tu interés en contribuir a **Arielo OS**. Esta guía te ayudará a entender cómo puedes participar en el proyecto.

---

## 🎯 Tipos de Contribuciones

### 1. 📝 Documentación

**Mejorar y expandir la documentación**

- Correcciones de errores tipográficos
- Clarificación de instrucciones
- Traducción a otros idiomas
- Nuevas guías y tutoriales
- Mejora de ejemplos
- Actualización de CHANGELOG

**Cómo contribuir:**
1. Edita o crea archivos .md
2. Sigue el formato actual
3. Prueba que los enlaces funcionan
4. Envía un Pull Request

**Ejemplo:** Mejora en la guía de instalación

```markdown
### Paso 1: Preparar el medio
- Descarga la ISO
- Verifica el checksum
- Crea un USB booteable
```

---

### 2. 🐛 Reportar Bugs

**Encontraste un problema?**

**Paso 1: Verifica que no esté reportado**
- Busca en [Issues](https://github.com/aiereza-star/ARIELO-OS/issues)
- Lee el CHANGELOG
- Consulta la documentación

**Paso 2: Abre un Issue**
- Click en "New Issue"
- Usa la plantilla proporcionada
- Completa toda la información

**Paso 3: Proporciona detalles**

```markdown
**Descripción del bug:**
Describe el problema claramente

**Pasos para reproducir:**
1. Haz esto
2. Luego esto
3. Y finalmente esto

**Resultado esperado:**
Qué debería pasar

**Resultado actual:**
Qué sucede realmente

**Sistema:**
- OS: [ej: Arielo OS AMD64 FULL]
- Versión: [ej: 1058]
- Plataforma: [ej: Laptop Dell]

**Logs/Capturas:**
[Adjunta si aplica]
```

---

### 3. 💡 Sugerencias de Mejora

**Tienes una idea para mejorar Arielo OS?**

**Abre un Issue con etiqueta "enhancement":**

```markdown
**Descripción:**
Explica tu idea en detalle

**Beneficio:**
¿Por qué sería útil?

**Implementación posible:**
Cómo crees que se podría hacer

**Alternativas:**
Otros enfoques posibles
```

---

### 4. 👨‍💻 Contribuir Código

**¿Quieres contribuir código?**

#### Paso 1: Fork del Repositorio

```bash
# En GitHub, click en "Fork" en la esquina superior derecha
```

#### Paso 2: Clonar tu Fork

```bash
git clone https://github.com/TU-USUARIO/ARIELO-OS.git
cd ARIELO-OS
```

#### Paso 3: Crear una Rama

```bash
# Para features
git checkout -b feature/descripcion-corta

# Para bugfixes
git checkout -b bugfix/descripcion-corta

# Para documentación
git checkout -b docs/descripcion-corta

# Ejemplos:
git checkout -b feature/mejorar-interfaz
git checkout -b bugfix/error-instalacion
git checkout -b docs/guia-avanzada
```

#### Paso 4: Realizar Cambios

```bash
# Edita los archivos necesarios
# Haz commits frecuentes con mensajes claros

git add archivo-modificado.md
git commit -m "Descripción clara del cambio"
```

#### Paso 5: Push a tu Fork

```bash
git push origin feature/descripcion-corta
```

#### Paso 6: Crear Pull Request

1. Ve a tu fork en GitHub
2. Click en "New Pull Request"
3. Selecciona la rama que creaste
4. Completa la descripción:

```markdown
## Descripción
Explica qué cambios haces y por qué

## Tipo de cambio
- [ ] Bug fix (corrección sin cambio de funcionalidad)
- [ ] Feature (nueva funcionalidad)
- [ ] Documentation (cambios en docs)
- [ ] Improvement (mejora existente)

## Cambios
- Cambio 1
- Cambio 2
- Cambio 3

## Testing
Describe cómo probaste los cambios

## Checklist
- [ ] Mi código sigue el estilo del proyecto
- [ ] He actualizado la documentación
- [ ] He añadido tests si aplica
- [ ] No hay warnings o errores nuevos
```

#### Paso 7: Responder Feedback

- Los mantenedores revisarán tu PR
- Responde a los comentarios
- Haz cambios si es necesario
- Tu PR será mergeado cuando esté listo ✅

---

### 5. 🧪 Testing

**Prueba nuevas versiones**

- Instala versiones beta
- Reporta problemas encontrados
- Prueba en diferentes hardware
- Verifica funcionalidades

**Cómo reportar:**
- Abre un Issue con etiqueta "testing"
- Describe el hardware usado
- Detalla qué probaste
- Proporciona resultados

---

### 6. 🌍 Traducción

**Ayuda a traducir Arielo OS**

- Documentación a otros idiomas
- Interfaz del sistema
- Mensajes de aplicaciones
- Guías y tutoriales

**Idiomas prioritarios:**
- Inglés (en)
- Español (es) ✓ (completado)
- Francés (fr) - Buscando traductores
- Portugués (pt) - Buscando traductores
- Otros idiomas - Bienvenidos

**Cómo contribuir:**
1. Contacta: aiereza@yahoo.com
2. Indica el idioma
3. Trabaja en los archivos
4. Envía un Pull Request

---

### 7. 💬 Ayudar a Otros Usuarios

**Comparte tu conocimiento**

- Responde preguntas en Issues
- Ayuda en Discussions (próximamente)
- Comparte tutoriales
- Proporciona ejemplos
- Documenta soluciones

---

## 📋 Normas de Contribución

### Código

1. **Estilo consistente**
   - Sigue el estilo existente del proyecto
   - Indentación: 4 espacios o tabs
   - Línea máxima: 80-100 caracteres

2. **Comentarios**
   - Comenta código complejo
   - Explica el "por qué", no solo el "qué"
   - Utiliza comentarios en inglés

3. **Commits**
   ```bash
   # Bueno
   git commit -m "Fix: corrección de error en instalación"
   git commit -m "Feature: agregar soporte para x86"
   git commit -m "Docs: mejorar guía de instalación"
   
   # Evitar
   git commit -m "fixes"
   git commit -m "asdfd"
   git commit -m "cambios varios"
   ```

### Documentación

1. **Formato Markdown**
   - Usar sintaxis estándar
   - Incluir títulos claros (H1, H2, H3)
   - Usar listas y tablas cuando sea apropiado
   - Incluir ejemplos de código

2. **Claridad**
   - Escribe para lectores no técnicos cuando sea posible
   - Evita jerga innecesaria
   - Proporciona ejemplos
   - Explica términos técnicos

3. **Enlaces**
   - Verifica que todos los enlaces funcionen
   - Usa enlaces relativos dentro del proyecto
   - Actualiza referencias cuando cambien rutas

### Issues y Pull Requests

1. **Títulos claros**
   ```
   ✅ "Error: No se puede instalar en Raspberry Pi"
   ❌ "No funciona"
   
   ✅ "Feature: Agregar soporte para tema oscuro"
   ❌ "Mejoras"
   ```

2. **Descripción detallada**
   - Explica el problema/cambio
   - Proporciona contexto
   - Adjunta capturas si es relevante
   - Menciona versiones

3. **Etiquetas**
   - `bug` - Reporte de error
   - `enhancement` - Mejora o feature
   - `documentation` - Cambios en docs
   - `testing` - Reportes de testing
   - `help wanted` - Busca ayuda
   - `good first issue` - Para nuevos contribuidores

---

## ✅ Checklist para Contribuidores

Antes de enviar tu contribución:

- [ ] He leído esta guía de contribuciones
- [ ] He verificado que no haya un Issue/PR similar
- [ ] He probado mis cambios localmente
- [ ] He actualizado la documentación si es necesario
- [ ] He seguido el estilo del proyecto
- [ ] He incluido un mensaje de commit claro
- [ ] Mi PR tiene una descripción detallada
- [ ] He reviado mis propios cambios antes de enviar

---

## 🎓 Primeros Pasos para Nuevos Contribuidores

**Si es tu primera vez contribuyendo:**

1. Empieza con Issues etiquetados `good first issue`
2. Lee la documentación existente
3. Realiza una contribución pequeña
4. Aprende del feedback
5. Contribuye cambios más grandes

**Sugerencias para primeras contribuciones:**
- Correcciones de typos
- Mejorar ejemplos
- Actualizar links rotos
- Expandir FAQs
- Mejorar claridad de docs

---

## 💰 Reconocimiento

Todos los contribuidores serán:

1. **Mencionados en:**
   - CONTRIBUTORS.md (en desarrollo)
   - Página web oficial
   - Release notes

2. **Reconocidos por:**
   - GitHub (automáticamente en el repositorio)
   - Redes sociales
   - Comunidad

3. **Beneficiarios de:**
   - Acceso prioritario a features
   - Participación en decisiones
   - Crédito en documentación

---

## 🐛 Proceso de Revisión

### Para Issues

1. **Reporte** - Se crea el issue
2. **Confirmación** - Verificamos si es válido
3. **Clasificación** - Asignamos etiqueta y prioridad
4. **Asignación** - Si es posible, asignamos a alguien
5. **Resolución** - Trabajamos en una solución
6. **Cierre** - Cerramos cuando se resuelve

### Para Pull Requests

1. **Envío** - Creas el PR
2. **Revisión** - Revisamos los cambios
3. **Feedback** - Damos comentarios si es necesario
4. **Cambios** - Realizas ajustes si es necesario
5. **Aprobación** - Cuando está listo, lo aprobamos
6. **Merge** - Incorporamos los cambios al proyecto

**Tiempo promedio de revisión:** 1-2 semanas

---

## 🚫 Código de Conducta

Todos los contribuidores aceptan:

✅ **Ser respetuoso** - Con todos los participantes
✅ **Ser constructivo** - Crítica amable y útil
✅ **Ser inclusivo** - Sin discriminación
✅ **Ser paciente** - Las respuestas toman tiempo
✅ **Ser honesto** - Transparencia en problemas
✅ **Ser responsable** - Asumir errores propios

❌ **Prohibido:**
- Lenguaje ofensivo o abusivo
- Discriminación de cualquier tipo
- Spam o auto-promoción
- Conflictos personales
- Contenido inapropiado

**Consecuencias del incumplimiento:**
- Advertencia
- Suspensión temporal
- Bloqueo permanente

---

## 🤔 Preguntas Frecuentes

### P: ¿Debo crear un Issue antes de un PR?
**R:** Para cambios pequeños (typos, docs), no. Para cambios significativos (features, big changes), sí. Así evitamos trabajo duplicado.

### P: ¿Cuánto tiempo toma que mi PR sea revisado?
**R:** Usualmente 3-7 días. Cambios simples más rápido, cambios complejos más lento.

### P: ¿Qué si no me gusta el feedback?
**R:** Podemos discutir. Si no llegamos a acuerdo, respetamos la decisión de los mantenedores.

### P: ¿Puedo contribuir si soy principiante?
**R:** ¡Por supuesto! Los principiantes son bienvenidos. Busca issues con "good first issue".

### P: ¿Necesito permiso para crear un fork?
**R:** No. GitHub te permite fork de cualquier repositorio público.

---

## 📞 Contacto

**¿Preguntas sobre cómo contribuir?**

- 📧 Email: aiereza@yahoo.com
- 🐙 GitHub Issues: Abre una pregunta
- 💬 Discussions: (próximamente)
- 🌐 Web: arielo-os.com

---

## 🎉 ¡Gracias!

Gracias por considerar contribuir a Arielo OS. Tu ayuda hace que este proyecto sea mejor para todos.

**¡Esperamos tu contribución!** 🚀

---

**Última actualización:** Septiembre 2026

**Versión:** 1.0