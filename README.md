# 🧩 Proyecto: **ParkEDS – Documentación Final Software II**

## 📖 Descripción General
Este repositorio contiene la **documentación técnica y arquitectónica** del sistema **ParkEDS**, desarrollada como parte del curso de *Software II (Moderno)*.  
ParkEDS es un sistema diseñado para la **gestión inteligente de parqueaderos**, aplicando principios de arquitectura de software, modelado UML y documentación formal.

---

## 👩‍💻 Autores
- **Estefanía Otálvaro Quintero**  
- **María Salomé Gonzales Blandón**  
- **Juan Daniel Rodríguez Giraldo**

📅 **Fecha:** Noviembre de 2025  
📄 **Versión:** 1.0  

---

## 🧱 Diagramas UML Incluidos
| Tipo de Diagrama | Descripción | Archivo |
|------------------|-------------|----------|
| **Paquetes** | Estructura modular del sistema ParkEDS. | `DocumentacionDiagramaPaquetes.xlsx` |
| **Componentes** | Interacción entre los módulos y servicios del sistema. | `PlantillaDocumentaciónDiagramaComponentes.xlsx` |
| **Secuencia** | Flujo de eventos y comunicación entre componentes. | `PlantillaDocumentaciónDiagramaSecuenciaParkEDS.xlsx` |
| **MER** | Modelo Entidad-Relación para la base de datos. | Incluido en el documento principal. |
| **Diagrama de Clases** | Define las relaciones entre objetos y atributos del sistema. | Incluido en el documento principal. |
| **Diagrama de Estados** | Muestra los cambios de estado en los procesos del sistema. | Incluido en el documento principal. |

---

## 🧩 Modelo 4+1 de Arquitectura del Sistema ParkEDS

El sistema se documenta siguiendo la metodología **4+1**, la cual estructura la arquitectura del software en cinco vistas complementarias:

### 🧠 Vista Lógica
Define la **estructura modular del sistema**, sus entidades y relaciones principales.  
Se representa mediante el **Diagrama de Paquetes**, que muestra la organización funcional del software.

### 🧰 Vista de Desarrollo
Describe la **arquitectura interna y los componentes**, así como su implementación.  
Está representada en el **Diagrama de Componentes** y refleja la separación por capas del sistema.

### 🔄 Vista de Procesos
Expone la **interacción entre los componentes**, los flujos de ejecución y la comunicación entre módulos.  
Se apoya en el **Diagrama de Secuencia** y sus plantillas asociadas.

### 🖥️ Vista Física
Representa la **distribución del sistema en la infraestructura** (servidores, red y base de datos).  
En esta vista se modela cómo los componentes se despliegan en entornos locales o en la nube.

### 🧩 Vista de Escenarios (+1)
Integra las vistas anteriores a través de **casos de uso representativos**, como:
- Ingreso y salida de vehículos  
- Generación de reportes  
- Administración de sedes  

---

## ⚙️ Arquitectura General
ParkEDS se basa en una arquitectura modular que separa las capas del sistema:

```
Presentación → Lógica de Negocio → Persistencia → Base de Datos
```

Cada módulo mantiene independencia y cohesión interna, permitiendo escalabilidad y mantenibilidad a largo plazo.

---

## 🧠 Herramientas y Tecnologías Utilizadas
- **Lenguaje:** Java 21  
- **Framework:** Spring Boot 3.7  
- **Base de Datos:** PostgreSQL  
- **Modelado:** UML (StarUML, Draw.io, PlantUML)  
- **Entorno de Desarrollo:** IntelliJ IDEA / Visual Studio Code  

---

## 📚 Objetivo del Proyecto
El propósito de **ParkEDS** es crear una plataforma que facilite la administración de parqueaderos, automatizando procesos de ingreso, cobro y monitoreo de espacios, además de ofrecer trazabilidad y seguridad en los datos.

---

## 🧾 Documento Original
El documento completo con todos los diagramas y explicaciones está disponible en:
- 📄 [`Documentacion_Final_Software_2_Moderno_parkEDS.docx`](Documentacion_Final_Software_2_Moderno_parkEDS.docx)

---

## 🏫 Información Académica
**Universidad:** Universidad Catolica de Oriente 
**Programa:** Ingeniería en Sistemas  
**Materia:** Software II 
**Docente:** Wider Farid Sanchez Garzon


---




