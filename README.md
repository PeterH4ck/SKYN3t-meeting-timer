# ⏰ Contador Empresarial - Reuniones | SKYN3T

![SKYN3T Timer](https://img.shields.io/badge/SKYN3T-Timer-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/version-2.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/license-Free-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/status-Active-success?style=for-the-badge)

## 🎯 Descripción

**Contador Empresarial - Reuniones** es una herramienta profesional diseñada por el equipo de [SKYN3T.cl](https://skyn3t.cl) para facilitar la gestión visual del tiempo en salas de reuniones y espacios corporativos. Esta solución permite mantener un seguimiento preciso de fechas importantes, entregas de proyectos y eventos críticos mediante un sistema de cuenta regresiva inteligente y altamente visual.

## 🌐 Acceso

**¡Completamente GRATUITO!** Accede ahora en: **[https://skyn3t.cl/timer](https://skyn3t.cl/timer)**

---

## ✨ Características Principales

### 🎨 **Diseño Profesional**
- Interfaz neumórfica moderna y elegante
- Diseño responsive adaptable a cualquier pantalla
- Dos versiones disponibles (Classic y Retro)
- Modo oscuro/claro con transiciones suaves

### ⏱️ **Sistema de Cuenta Regresiva Inteligente**
- **Desaparición Progresiva**: Las unidades de tiempo desaparecen automáticamente cuando llegan a 0
- **Visualización Dinámica**: El tamaño de los bloques se adapta según la cantidad de unidades activas
- **Precisión Total**: Cuenta regresiva en Meses, Semanas, Días, Horas, Minutos y Segundos

### 🔔 **Alertas y Notificaciones**
- Alerta especial **"IT'S TODAY!"** cuando es el día del evento
- Mensaje de **"EVENTO COMPLETADO"** al llegar a cero
- Notificaciones visuales destacadas

### ⚙️ **Configuración Flexible**
- Nombre personalizable del proyecto/evento
- Fecha y hora específicas
- Logo corporativo personalizado (opcional)
- Imagen de fondo personalizable
- Persistencia automática de configuración (localStorage)

### 🔄 **Gestión de Eventos**
- Botón de reset rápido (🔄) siempre visible en el header
- Modal de configuración intuitivo
- Actualización instantánea de parámetros

---

## 📋 Casos de Uso Empresariales

### 🏢 **Salas de Reuniones**
Mantén visible el tiempo restante para:
- Presentaciones importantes a clientes
- Juntas de directorio
- Revisiones de proyecto con stakeholders
- Conferencias y webinars

### 📦 **Entregas de Proyectos**
Seguimiento visual para:
- Fechas límite de desarrollo (sprints)
- Entregas a clientes
- Lanzamientos de productos
- Implementaciones en producción

### 📅 **Eventos Corporativos**
Cuenta regresiva para:
- Aniversarios de la empresa
- Eventos de networking
- Ferias y exposiciones
- Capacitaciones programadas

### 🎯 **Hitos Estratégicos**
Control de tiempo para:
- Presentación de propuestas
- Cierres fiscales/contables
- Auditorías programadas
- Renovaciones de contratos

---

## 🚀 Funcionalidades por Versión

### **Timer.php - Versión Classic**
```
✅ Diseño neumórfico suave
✅ Bloques de tiempo cuadrados
✅ Transiciones elegantes
✅ Ideal para: Ambientes corporativos tradicionales
```

### **Timer_v2.php - Versión Retro**
```
✅ Efecto flip retro (split-flap display)
✅ Animaciones mecánicas realistas
✅ Estética vintage industrial
✅ Ideal para: Espacios creativos, startups, tech companies
```

---

## 💡 Comportamiento Inteligente

### **Ejemplo de Desaparición Progresiva**

Cuando configuras un evento para dentro de **2 horas**:

```
⏰ 02:00:00 → Muestra: 2 HORAS | 0 MINUTOS | 0 SEGUNDOS
⏰ 01:30:00 → Muestra: 1 HORA | 30 MINUTOS | 15 SEGUNDOS
⏰ 00:59:59 → Muestra: 59 MINUTOS | 59 SEGUNDOS ⚡ (Horas desaparecen)
⏰ 00:30:00 → Muestra: 30 MINUTOS | 0 SEGUNDOS
⏰ 00:01:00 → Muestra: 1 MINUTO | 0 SEGUNDOS
⏰ 00:00:59 → Muestra: 59 SEGUNDOS ⚡ (Minutos desaparecen - Bloque grande)
⏰ 00:00:05 → Muestra: 5 SEGUNDOS (Máxima visibilidad)
⏰ 00:00:00 → 🎉 ¡EVENTO COMPLETADO! 🎉
```

### **Lógica de Visualización**

| Tiempo Restante | Unidades Visibles |
|-----------------|-------------------|
| > 1 mes | Meses, Semanas, Días, Horas, Minutos, Segundos |
| < 1 mes, > 1 semana | Semanas, Días, Horas, Minutos, Segundos |
| < 1 semana, > 1 día | Días, Horas, Minutos, Segundos |
| < 1 día, > 1 hora | Horas, Minutos, Segundos |
| < 1 hora, > 1 minuto | Minutos, Segundos |
| < 1 minuto | **Solo Segundos** (Bloque Gigante) |

---

## 🎯 Ventajas Competitivas

### ✅ **Sin Instalación**
- Acceso directo vía navegador web
- Sin necesidad de descargas o plugins
- Compatible con todos los dispositivos

### ✅ **Cero Configuración Técnica**
- Interfaz intuitiva
- Configuración en 3 clicks
- Sin conocimientos técnicos requeridos

### ✅ **Persistencia Automática**
- Se guarda automáticamente
- No pierdes tu configuración al refrescar
- Recuperación instantánea

### ✅ **Totalmente Gratuito**
- Sin límites de uso
- Sin publicidad
- Sin registro requerido

---

## 🖥️ Requisitos Técnicos

### **Navegadores Compatibles**
- ✅ Google Chrome (v90+)
- ✅ Mozilla Firefox (v88+)
- ✅ Microsoft Edge (v90+)
- ✅ Safari (v14+)
- ✅ Opera (v75+)

### **Dispositivos Soportados**
- 💻 Desktop (Windows, macOS, Linux)
- 📱 Tablets (iPad, Android)
- 📺 Smart TVs con navegador
- 🖥️ Pantallas de salas de reuniones

### **Resoluciones Óptimas**
- Mínimo: 1280x720 (HD)
- Recomendado: 1920x1080 (Full HD)
- Ideal: 3840x2160 (4K)

---

## 🎨 Personalización

### **Opciones Disponibles**

1. **Nombre del Evento**
   - Texto personalizable
   - Formato libre
   - Ejemplos: "Entrega Q4", "Lanzamiento Producto X"

2. **Logo Corporativo**
   - URL de imagen personalizada
   - Formatos: PNG, JPG, SVG
   - Tamaño recomendado: 200x200px

3. **Fondo Personalizado**
   - Imagen de fondo corporativa
   - URL personalizable
   - Efectos de opacidad ajustables

4. **Fecha y Hora Objetivo**
   - Selector de fecha intuitivo
   - Hora exacta (HH:MM)
   - Zona horaria automática

---

## 📱 Modos de Visualización

### **Modo Presentación (Pantalla Completa)**
- F11 para pantalla completa
- Perfecto para proyectores
- Sin distracciones visuales

### **Modo Ventana**
- Integrable en dashboards
- Segunda pantalla dedicada
- Monitoreo continuo

---

## 🔧 Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript Vanilla
- **Diseño**: Neumorphism Design, Material Design
- **Almacenamiento**: LocalStorage API
- **Animaciones**: CSS Transitions & Keyframes
- **Responsive**: Flexbox & CSS Grid

---

## 🏆 Desarrollado por SKYN3T

**SKYN3T.cl** es un equipo especializado en desarrollo de soluciones tecnológicas innovadoras para empresas. Nos enfocamos en crear herramientas que mejoren la productividad y eficiencia organizacional.

### 🌐 Enlaces
- **Website**: [https://skyn3t.cl](https://skyn3t.cl)
- **Timer Tool**: [https://skyn3t.cl/timer](https://skyn3t.cl/timer)

---

## 📞 Soporte y Contacto

¿Necesitas ayuda o tienes sugerencias? Contáctanos:

- 🌐 Sitio web: [skyn3t.cl](https://skyn3t.cl)
- 📧 Formulario de contacto disponible en el sitio
- 💬 Feedback bienvenido para mejoras continuas

---

## 📄 Licencia

**Uso Gratuito** - Esta herramienta está disponible de forma gratuita para uso personal y comercial.

---

## 🎉 Características Destacadas en GIF

### **Transición Inteligente**
```
[Meses → Semanas → Días → Horas → Minutos → Segundos]
          ↓ Desaparece progresivamente ↓
```

### **Alerta Visual**
```
🚨 IT'S TODAY! 🚨
(Aparece cuando es el día del evento)
```

### **Evento Completado**
```
✅ ¡EVENTO COMPLETADO! ✅
(Reset disponible para nuevo evento)
```

---

## 🚀 ¡Comienza Ahora!

1. **Accede**: [https://skyn3t.cl/timer](https://skyn3t.cl/timer)
2. **Configura**: Click en ⚙️ → Ingresa datos del evento
3. **Guarda**: Click en "Guardar Configuración"
4. **¡Listo!**: Tu cuenta regresiva está activa

---

<div align="center">

### ⭐ **Desarrollado con ❤️ por SKYN3T.cl** ⭐

**[Pruébalo Ahora](https://skyn3t.cl/timer)** | **[Visita SKYN3T](https://skyn3t.cl)**

---

*Mejorando la productividad empresarial, un timer a la vez* ⏰

</div>
