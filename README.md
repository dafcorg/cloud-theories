# 📂 Cloud Computing Theories & Code Snippets

Este repositorio contiene pequeños códigos aplicables a teorías de Cloud Computing. Cada implementación está orientada a toquetear algunos principios clave en la gestión de recursos en la nube. 

## 📌 Proyecto 1: Escalamiento Cloud con Demanda Probabilística

### 📖 Descripción
Este proyecto implementa un algoritmo de abastecimiento de inventarios con demanda probabilística basado en una distribución normal, aplicado al escalamiento en la nube. El objetivo es optimizar la asignación de recursos para manejar variaciones en la demanda de manera eficiente, minimizando costos y asegurando disponibilidad.

### 🛠️ Tecnologías y Herramientas
- Lenguaje: Python
- Bibliotecas: NumPy, Matplotlib
- Conceptos: Distribución normal, Escalamiento cloud, Gestión de inventarios

### 📜 Implementación
El código implementa un modelo en el que:
- La demanda sigue una distribución normal definida.
- Se calcula un nivel óptimo de aprovisionamiento para garantizar un cierto nivel de servicio teniendo una latencia de 5 seg para el lanzamiento de una nueva máquina.
- Se simula el impacto de diferentes niveles de aprovisionamiento en la disponibilidad del servicio cloud.

### 📂 Estructura del Proyecto
```
📦 cloud-theories
 ┣ 📂 inventory_scaling
 ┃ ┣ 📜 Abastecimiento_de_la_Nube.py  # Código fuente
 ┃ ┣ 📜 README.md             # ejecución
 ┣ 📜 README.md               # Información general del repositorio
```

### 📊 Resultados
El código generará gráficos y estadísticas que muestran cómo el escalamiento basado en demanda probabilística puede mejorar la eficiencia de los recursos cloud.

### 📌 Próximos Pasos
- Implementación de otros modelos de distribución para analizar su impacto en el escalamiento.
- Integración con herramientas de monitoreo en la nube.

### 📄 Licencia
Este proyecto está bajo la licencia MIT - ver el archivo [LICENSE] para más detalles.

---
📧 ¿Tienes sugerencias o mejoras? No dudes en contribuir o abrir un issue. ¡Toda ayuda es bienvenida! 😊
