## Herramienta Python-UML: https://jluiskarteaga.github.io/PYTHON_PLANTUML/

🎯 Objetivo: Generar PlantUML desde código PYTHON
Herramienta web para introducir a estudiantes de primer ciclo de ingeniería de software al **UML y patrones de diseño**, convirtiendo código Python en diagramas de clases automáticamente. <br>

| Aspecto                     | Valor Didáctico                                                         |
| --------------------------- | ----------------------------------------------------------------------- |
| **Visualización inmediata** | Conecta código con representación gráfica UML                           |
| **6 relaciones UML**        | Herencia, realización, composición, agregación, asociación, dependencia |
| **4 patrones GOF**          | Singleton, Factory Method, Observer, Strategy (fase de conocimiento)    |
| **Doble formato**           | Comentarios educativos + notas post-it visibles                         |
| **Sin ruido**               | Filtra clases del sistema (ABC, object, etc.)                           |
| **Interfaz limpia**         | Drag & drop, opciones configurables, exportable                         |

### 📚 Aplicación Pedagógica
| Escenario                   | Uso                                              |
| --------------------------- | ------------------------------------------------ |
| **Laboratorio**             | Estudiante escribe Python → ve su diseño UML     |
| **Revisión de código**      | Identifica relaciones implícitas no documentadas |
| **Introducción a patrones** | Descubre posibles patrones sin buscarlos         |
| **Documentación**           | Genera diagramas para reportes técnicos          |

### ⚠️ Limitaciones (intencionales)
| Limitación               | Justificación                                        |
| ------------------------ | ---------------------------------------------------- |
| Detección conservadora   | Evita falsos positivos que confundan a principiantes |
| Solo 4 patrones          | Suficiente para "fase de conocimiento", no saturar   |
| No edición visual        | Enfoca en código fuente como fuente de verdad        |
| Sin validación semántica | Solo estructura, no corrige diseño                   |

###🎓 Recomendación de Uso
**Para docentes:**
- Ejemplos progresivos: clases simples → herencia → composición → patrones
- Comparar: código Python vs. diagrama UML generado
- Discutir: "¿Por qué la herramienta detectó este patrón?"
  
**Para estudiantes:**
- Primero: dibujar UML a mano
- Luego: verificar con la herramienta
- Finalmente: reflexionar sobre diferencias

