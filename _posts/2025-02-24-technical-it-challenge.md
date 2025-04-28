---
layout: post
title: "Liderando la Puesta a Punto de BetLine: Un Desafío Técnico y de Gestión en Entornos Escalables"
categories: arquitectura-software, gestión-proyectos, backend, escalabilidad
tags: [nodejs, java, arquitectura, gestión, integración, postgres, jwt]
---

## Contexto del Proyecto  

El desafío en BetLine fue un **proyecto de puesta a punto con fecha de entrega inamovible**, lo que implicó un enfoque estratégico en **gestión, diseño de arquitectura y desarrollo** para cumplir con las expectativas sin comprometer la calidad.  

### **Equipo y Metodología**  
- **Equipo:** 6 desarrolladores fullstack.  
- **Plan de trabajo:**  
  - Sprints de 2 semanas.  
  - Primera semana: desarrollos no desplegables.  
  - Segunda semana: entrega con despliegue.

#### **Desafíos técnicos y soluciones**  

### **1. Escalabilidad y Multiprovincia**  
**Problema:** Los cambios en la estructura de datos impactaban la escalabilidad en múltiples provincias.  
**Solución:**  
- Se adelantó el esfuerzo de desarrollo para ampliar los tiempos de prueba.  
- Se creó una tabla de parametrización por provincia para condicionar los componentes a utilizar.  

### **2. Integración con Sistema de Medios Digitales**  
**Desafío:** Incorporación de MODO como medio de pago.  
**Solución:**  
- La integración resultó intuitiva, lo que facilitó su implementación.  

### **3. Navegación sin Login y Simplificación del Registro**  
**Problema:** Se requería habilitar navegación sin login solo en una provincia y simplificar el registro, reduciendo datos ingresados.  
**Solución:**  
- Se condicionaron endpoints sin afectar la fecha de entrega.  
- Se preparó una optimización futura con una tabla de configuración por provincia.  

### **4. Rediseño de Estilos por Provincia**  
**Solución:**  
- Uso de archivos `.js` con constantes de theming y variables dinámicas.  
- Documentación clara para futuras modificaciones.  

### **5. Solicitud de Retiro por Transferencia**  
**Desafío:** Incorporar una funcionalidad manual para operadores.  
**Solución:**  
- Implementación con JWT para autenticación del servicio.  
- Proceso manual para gestionar las transferencias con un administrador.  

### **6. Bonificaciones y Plan de Fidelización**  
**Solución:**  
- Se parametrizó la lógica con esquemas flexibles para definir distintos tipos de bonificaciones (registro, incentivo, retención, premios).  
- Diseño escalable por provincia.  

### **7. Reportes y Métricas de Negocio**  
**Solución:**  
- Desarrollo de reportes con **PostgreSQL**.  
- Consultas SQL reflejadas en un dashboard de operaciones.  

## **Conclusiones y Aprendizajes**  
Este proyecto no solo me permitió reforzar mis habilidades en **arquitectura de software y gestión de proyectos**, sino que también representó un **desafío en la toma de decisiones estratégicas** bajo condiciones de entrega rígidas.  
La planificación temprana de mitigación de riesgos, la modularidad en los cambios y la documentación clara fueron claves para lograr una entrega exitosa.  

---

📌 **¿Quieres saber más sobre mi experiencia en arquitectura de software y gestión de equipos técnicos? Conectemos en LinkedIn.**  
