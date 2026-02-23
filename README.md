# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
- Nombre del proceso: Clasificación de Tickets
- Contexto (empresa/servicio web/IT): Amazon
- Rol/es implicados: Clientes/Usuarios, Agentes de soportes y Supervisores.

## 2) ANTES (sin IA)
- Pasos (5–7):
  1. Un cliente envía un ticket a través de un formulario por la web o por la aplicación
  2. El sistema lo registra en la bandeja general sin clasificación
  3. Uno de los agentes de soporte revisan manualmente el tipo de ticket
  4. Un supervisor asigna manualmente el departamiento correspondiente
  5. El equipo revisa el tiquet y cominza la gestión
- Tiempo aproximado por caso: 1hora
- Problemas / cuellos de botella: se tarda demasiado en administrar cada caso individual

## 3) DESPUÉS (con IA)S
- ¿Qué automatiza la IA?
- Clasificación automática del tipo de ticket (envíos, devoluciones, pagos, incidencias técnicas, etc.).
- Asignación automática al departamento correspondiente.
- Respuestas automáticas iniciales para casos frecuentes (FAQ).
- ¿Qué queda para humanos?
- Resolución de casos complejos o no habituales.
- Supervisión de decisiones tomadas por la IA.
- Gestión de reclamaciones delicadas.
- Mejora continua del sistema
- Datos necesarios (tipos de datos, sin datos personales):
- Texto del ticket (descripción del problema).
- Categorías históricas de tickets.
- Etiquetas de prioridad.
- Historial de resolución (tipo de solución aplicada).
- Modelo/técnica (NLP, clasificación, recomendación, visión, etc.):
- Procesamiento de Lenguaje Natural (NLP).
- Modelos de clasificación supervisada.
- Sistemas de recomendación para asignación automática.
  
## 4) Optimización (mejora medible)
Define 3 métricas con valores antes/después:
- Tiempo: Antes tardando 1 hora y ahora tardando unos 15-20 minutos
- Coste: Antes unos costes elevados por mano de obra y ahora se reduce un 40% más o menos
- Calidad: Antes podia haber menos errores a la hora de clasificar el ticket pero ahora puede fallar más

## 5) Diagrama del flujo (ASCII o Mermaid)
(Pega aquí el diagrama)
Cliente envía ticket
        │
        ▼
Sistema recibe ticket
        │
        ▼
IA analiza texto (NLP)
        │
        ├── Clasifica tipo
        ├── Asigna prioridad
        └── Deriva al departamento correcto
                │
                ▼
        Agente revisa y gestiona
                │
                ▼
           Resolución final
## 6) Riesgos y mitigación
- Riesgo 1: Clasificación incorrecta del ticket
- Mitigación 1:Supervisión humana y reentrenamiento periódico del modelo con nuevos datos.
- Riesgo 2:Dependencia excesiva de la automatización.
- Mitigación 2:Mantener revisión humana en casos críticos y auditorías regulares del sistema.

## 7) Fuente oficial
- Enlace: https://www.amazon.com/customer-service
