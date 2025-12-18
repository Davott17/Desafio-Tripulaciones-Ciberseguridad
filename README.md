# 📂 Proyecto de Seguridad y Auditoría

Este repositorio reúne la documentación generada durante el análisis de seguridad, auditorías técnicas y diseño de infraestructura de una aplicación corporativa que integra un **chatbot basado en IA**, una **API backend** y una **base de datos con información sensible**.  

El objetivo es centralizar todos los informes y guías en un único espacio, facilitando la consulta, el versionado y la colaboración entre equipos de desarrollo, seguridad y operaciones.

---

## 📑 Contenido del repositorio

- **1. Informe Threat Modeling.pdf**  
  Modelado de amenazas inicial (bloqueado en este repositorio).  

- **2. Hardening.pdf**  
  Guía de medidas de hardening en Node.js, JavaScript, Render y Lambda.  

- **3. Diseño de infraestructura .docx.pdf**  
  Arquitectura segura y escalable, con propuesta de despliegue mixto (Render + AWS).  

- **4. Gestión de datos.docx.pdf**  
  Estrategia de protección y backup de datos sensibles (users, employees, customers, products, sales).  

- **5. Informe Owasp.pdf**  
  Aplicación del OWASP Top 10 (2024) y análisis de amenazas.  

- **6. Análisis de código estático.docx.pdf**  
  Resultados de SonarQube: vulnerabilidades, hotspots de seguridad y recomendaciones.  

- **7. Informe de Pentest.pdf**  
  Resultados del test de penetración sobre chatbot, backend y base de datos.  

- **desafio_reporte_nessus.pdf**  
  Reporte técnico de escaneo Nessus sobre hosts y servicios expuestos.  

- **desafio_report_dirbuster.txt**  
  Enumeración de directorios y ficheros accesibles en el frontend.  

---

## 🎯 Objetivos del repositorio

- Centralizar la documentación de seguridad y auditoría.  
- Facilitar la trazabilidad de hallazgos y recomendaciones.  
- Servir como referencia para equipos técnicos y de gestión.  
- Mantener un historial claro de evaluaciones y mejoras aplicadas.  

---

## 🛡️ Áreas cubiertas

- **Pentesting y explotación controlada**  
- **Análisis de vulnerabilidades (Nessus, OWASP ZAP, DirBuster, SpiderFoot)**  
- **Hardening de entornos Node.js, Render y AWS Lambda**  
- **Gestión y protección de datos sensibles (PostgreSQL en Render)**  
- **Diseño de infraestructura segura y escalable**  
- **Modelado de amenazas y aplicación del OWASP Top 10**  
- **Análisis estático de código con SonarQube**  

---

## 🚀 Uso recomendado

1. Revisar primero el **Informe de Pentest** y el **Informe OWASP** para entender los riesgos principales.  
2. Consultar el **Diseño de infraestructura** y la **Guía de Hardening** para aplicar medidas correctivas.  
3. Validar la protección de datos con el documento de **Gestión de datos**.  
4. Usar los reportes técnicos (**Nessus**, **DirBuster**) como evidencia y soporte para auditorías.  
5. Mantener este repositorio actualizado con nuevas versiones de informes y recomendaciones.  

---

## 📌 Notas

- Este repositorio está orientado a **uso académico y corporativo**.  
- No contiene código fuente de la aplicación, únicamente documentación técnica.  
- Los informes pueden incluir información sensible; se recomienda acceso restringido según roles.
- Se complementa con los siguientes respositorios de nuestros compañeros:
   - Data: https://github.com/LunaPerezT/Archivo-Desaf-o-DATA-SCIENCE
   - Full-Stack: https://github.com/carlgomezro-spec/desafio-tripulaciones

---

## 👥 Autores y colaboradores

Equipo de Ciberseguridad y Desarrollo:  
- Ignacio Muñoz González  
- Daniel Barón Iglesias  
- David Prieto González-Hidalgo    
- Jon Ormaechea Caro  
- Alejandro Alcázar Lucas  
- Alberto Seco Fuente  

---

## ⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub
