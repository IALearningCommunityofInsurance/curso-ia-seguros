# Glosario de IA aplicada al sector asegurador

*Community of Insurance (COI) / CICA · Versión 1.0 · 2026*

Este glosario recoge los términos de inteligencia artificial más relevantes para el profesional del seguro, con definiciones orientadas a la práctica del sector, no al ámbito técnico puro.

---

## A

**Alucinación (hallucination)**
Fenómeno por el que un modelo de lenguaje genera información falsa con apariencia de veracidad. En el contexto asegurador, representa uno de los riesgos más críticos para chatbots de atención al cliente: el modelo puede afirmar que una cobertura existe cuando la póliza la excluye expresamente. Véase el *Caso Air Canada* (Módulo 04).

**Aprendizaje automático (machine learning, ML)**
Rama de la IA en la que los sistemas aprenden a partir de datos sin ser programados explícitamente para cada tarea. En seguros, se aplica a tarificación, detección de fraude, scoring de siniestros y predicción de churn.

**Aprendizaje profundo (deep learning)**
Subconjunto del ML que utiliza redes neuronales con múltiples capas para aprender representaciones complejas de los datos. Especialmente útil en procesamiento de imágenes (daños en automóvil y hogar) y texto (documentos de siniestros, contratos).

**Aprendizaje por refuerzo (reinforcement learning)**
Técnica en la que un modelo aprende a tomar decisiones recibiendo recompensas o penalizaciones por sus acciones. Se usa en optimización de precios dinámicos y en sistemas de recomendación de coberturas.

**API (Application Programming Interface)**
Interfaz que permite a diferentes sistemas de software comunicarse entre sí. En seguros, las APIs conectan plataformas de IA con sistemas core (pólizas, siniestros, CRM) sin necesidad de integración monolítica.

**Árbol de decisión (decision tree)**
Modelo de ML que representa decisiones en forma de árbol con ramas que corresponden a distintos valores de variables. Muy utilizado en suscripción por su interpretabilidad: se puede explicar qué criterios llevaron a aceptar o rechazar un riesgo.

**Automatización robótica de procesos (RPA)**
Tecnología que automatiza tareas repetitivas basadas en reglas mediante "robots" de software. No es IA en sentido estricto, pero frecuentemente se combina con ML para crear procesos híbridos en tramitación de siniestros y emisión de pólizas.

---

## B

**Sesgo algorítmico (algorithmic bias)**
Tendencia de un modelo de IA a producir resultados sistemáticamente injustos o discriminatorios, generalmente porque los datos de entrenamiento reflejan desigualdades históricas. En seguros, puede manifestarse como tarifas desproporcionadamente altas para ciertos grupos demográficos o denegaciones injustificadas de cobertura.

**Big data**
Conjuntos de datos de gran volumen, velocidad y variedad que superan la capacidad de las herramientas tradicionales de análisis. En seguros, incluye datos telemáticos, registros médicos, información de redes sociales y datos catastrales.

**Boosting**
Técnica de ensemble learning (véase) que combina múltiples modelos débiles en secuencia, donde cada modelo corrige los errores del anterior. XGBoost y LightGBM son implementaciones muy utilizadas en pricing y fraude.

---

## C

**Chatbot**
Sistema de software que simula conversaciones con personas. Los chatbots basados en reglas solo responden a palabras clave predefinidas; los basados en LLMs (véase) comprenden lenguaje natural y generan respuestas contextuales. La distinción es crítica para evaluar su fiabilidad en atención al cliente asegurador.

**Clasificación (classification)**
Tarea de ML que asigna una etiqueta a una entrada. En seguros: clasificar un siniestro como fraudulento o legítimo, categorizar una queja por tipo, asignar un nivel de riesgo a una solicitud.

**Computer vision (visión por computador)**
Campo de la IA que permite a los sistemas interpretar imágenes y vídeo. En seguros se aplica a la evaluación de daños en automóvil y hogar mediante fotografías del perito o del propio asegurado.

**Confianza calibrada**
Capacidad de un modelo para expresar adecuadamente su nivel de certeza. Un modelo bien calibrado dice "tengo un 70% de confianza" cuando acierta el 70% de las veces en esos casos. Fundamental en sistemas de apoyo a la decisión en suscripción.

---

## D

**Datos estructurados / no estructurados**
Los datos estructurados tienen un formato fijo y se almacenan en tablas (bases de datos relacionales, hojas de cálculo). Los no estructurados carecen de formato predefinido: correos, PDFs de pólizas, grabaciones de llamadas, imágenes de siniestros. La IA permite explotar ambos tipos, pero los no estructurados requieren modelos más complejos.

**Deep fake**
Contenido audiovisual generado por IA que imita a personas reales con alta fidelidad. En seguros, representa un riesgo emergente de fraude: vídeos o audios falsificados para respaldar reclamaciones inexistentes.

**Despliegue (deployment)**
Proceso de poner un modelo de IA en producción para que sea utilizado en operaciones reales. Incluye la integración con sistemas existentes, la monitorización del rendimiento y la gestión de la deriva del modelo (véase *model drift*).

---

## E

**Embedding**
Representación matemática de objetos (palabras, documentos, clientes) en un espacio vectorial de alta dimensión, donde elementos similares quedan próximos entre sí. Base técnica de muchos sistemas de recomendación y búsqueda semántica.

**Ensemble learning**
Técnica que combina múltiples modelos de ML para obtener predicciones más robustas que cualquiera de los modelos individuales. Random Forest y XGBoost son ejemplos habituales en tarificación.

**Explicabilidad (explainability / XAI)**
Capacidad de un sistema de IA para justificar sus decisiones en términos comprensibles para personas. Especialmente relevante en seguros por los requisitos del AI Act europeo y la obligación de explicar las decisiones que afectan a los asegurados (denegaciones, sobretarifas).

---

## F

**Feature engineering**
Proceso de seleccionar, transformar y crear variables (features) a partir de los datos brutos para mejorar el rendimiento de un modelo. En suscripción: construir variables como "frecuencia de siniestros en los últimos 3 años" a partir de registros históricos.

**Frecuencia siniestral predicha**
Estimación por modelo de ML de la probabilidad de que un riesgo genere siniestros en un periodo. Base del pricing técnico en modelos avanzados, complementa o sustituye a las tablas actuariales clásicas.

**Fraude organizado**
Tipo de fraude en el que redes de personas coordinadas generan reclamaciones falsas sistemáticamente. Los modelos de análisis de grafos (graph analytics) son especialmente eficaces para detectar conexiones entre reclamantes, talleres, peritos y abogados implicados.

---

## G

**Generative AI (IA generativa)**
Categoría de IA capaz de generar contenido nuevo: texto, imágenes, audio, código. Los modelos de lenguaje como GPT-4 o Claude son ejemplos. En seguros, con aplicaciones en redacción de pólizas, resúmenes de siniestros y atención al cliente.

**GDPR (Reglamento General de Protección de Datos)**
Regulación europea que establece los derechos de los ciudadanos sobre sus datos personales. En el contexto de IA en seguros: limita el uso de datos para entrenamiento de modelos, exige el derecho a no ser objeto de decisiones exclusivamente automatizadas (artículo 22) y requiere transparencia sobre el tratamiento.

**Gradiente descendente (gradient descent)**
Algoritmo de optimización que ajusta los parámetros de un modelo minimizando el error de predicción, avanzando iterativamente en la dirección que reduce más el error. Base del entrenamiento de redes neuronales.

---

## H

**Hallucination**
Véase *Alucinación*.

**Hiperparámetros**
Parámetros de un modelo de ML que se configuran antes del entrenamiento y no se aprenden de los datos. Su ajuste (hyperparameter tuning) es crítico para el rendimiento: un modelo con hiperparámetros mal configurados puede ser mucho menos preciso de lo necesario.

---

## I

**IA estrecha (narrow AI)**
Sistema de IA diseñado para una tarea específica, sin capacidad de generalizar a otros dominios. La práctica totalidad de la IA en uso hoy es estrecha: un modelo de detección de fraude no puede tarificar, y un modelo de pricing no puede procesar imágenes de daños.

**IA general (AGI)**
IA hipotética capaz de realizar cualquier tarea intelectual que pueda realizar un humano. No existe todavía en un sentido práctico; su mención en contextos de venta tecnológica suele ser especulativa.

**Inferencia**
Proceso de aplicar un modelo ya entrenado a datos nuevos para generar predicciones. En producción, la inferencia es lo que ocurre cada vez que el modelo evalúa un riesgo, clasifica un siniestro o responde a un cliente.

**InsurTech**
Empresas tecnológicas que aplican innovación digital, incluyendo IA, al sector asegurador. Abarca desde startups de distribución digital hasta plataformas especializadas en pricing, siniestros o datos.

---

## L

**LLM (Large Language Model)**
Modelo de lenguaje de gran escala entrenado sobre enormes volúmenes de texto para comprender y generar lenguaje natural. Claude, GPT-4 y Gemini son ejemplos. Capacidades: redacción, resumen, respuesta a preguntas, extracción de información, traducción. Limitaciones: pueden alucinar, su conocimiento tiene fecha de corte y no acceden a sistemas en tiempo real salvo integración explícita.

**Loss ratio (índice de siniestralidad)**
Relación entre los siniestros pagados y las primas cobradas. Un objetivo clave de los modelos de pricing y suscripción es predecir y optimizar el loss ratio por segmento.

---

## M

**Machine learning**
Véase *Aprendizaje automático*.

**Model drift (deriva del modelo)**
Degradación progresiva del rendimiento de un modelo en producción cuando los datos reales cambian respecto a los datos de entrenamiento. En seguros, el cambio en patrones de fraude, climatología o comportamiento de los asegurados puede provocar deriva. Requiere monitorización continua y reentrenamiento periódico.

**Modelo predictivo**
Modelo estadístico o de ML que estima valores futuros o desconocidos a partir de datos históricos. En seguros: predecir la probabilidad de siniestro, el coste esperado, la propensión al churn o el riesgo de fraude.

**MLOps (Machine Learning Operations)**
Conjunto de prácticas para desplegar, monitorizar y mantener modelos de ML en producción. En aseguradoras de cierto tamaño, la falta de MLOps es una causa frecuente de que los modelos desarrollados nunca lleguen a producción.

---

## N

**NLP (Natural Language Processing)**
Procesamiento del lenguaje natural: rama de la IA que permite a los sistemas comprender, interpretar y generar texto humano. Base de chatbots, sistemas de clasificación de quejas, extracción de información de pólizas y resumen automático de siniestros.

**Red neuronal (neural network)**
Arquitectura de ML inspirada vagamente en el cerebro humano, compuesta por capas de nodos interconectados. Las redes profundas (deep learning) tienen muchas capas y son especialmente potentes en imágenes y texto.

---

## O

**OCR (Optical Character Recognition)**
Tecnología que convierte imágenes de texto (documentos escaneados, fotografías de formularios) en texto digital procesable. En seguros: digitalización automática de partes de accidente, facturas médicas y declaraciones manuscritas.

**Overfitting (sobreajuste)**
Problema por el que un modelo aprende demasiado bien los datos de entrenamiento —incluyendo el ruido y los casos atípicos— y no generaliza bien a datos nuevos. Un modelo sobreajustado tiene rendimiento excelente en pruebas pero falla en producción.

---

## P

**Pipeline**
Secuencia automatizada de pasos de procesamiento de datos y modelado. Un pipeline de scoring de fraude, por ejemplo, incluye extracción de datos, limpieza, generación de features, predicción y entrega del resultado al sistema de tramitación.

**Prompt**
Instrucción o pregunta que se proporciona a un LLM para obtener una respuesta. La calidad del prompt tiene un impacto directo en la calidad del output: la ingeniería de prompts (prompt engineering) es una disciplina emergente con aplicaciones directas en el sector asegurador.

**Prompt engineering**
Diseño sistemático de instrucciones para modelos de lenguaje con el objetivo de obtener outputs precisos, completos y seguros. En el contexto asegurador: diseñar prompts que limiten las respuestas del chatbot al contenido de la póliza, eviten alucinaciones sobre coberturas y activen la escalada al agente humano cuando corresponde.

---

## R

**RAG (Retrieval-Augmented Generation)**
Técnica que combina la capacidad generativa de un LLM con la recuperación de información de una base de conocimiento específica. Permite que el modelo responda basándose en documentos reales (condiciones generales, manual de coberturas) en lugar de depender solo de su entrenamiento. Fundamental para reducir alucinaciones en chatbots aseguradores.

**Regresión**
Tarea de ML que predice un valor numérico continuo. En seguros: predecir el coste de un siniestro, el importe de la prima óptima o el valor de las reservas necesarias.

**RLHF (Reinforcement Learning from Human Feedback)**
Técnica de entrenamiento de LLMs en la que humanos evalúan y comparan respuestas del modelo para guiar su aprendizaje hacia outputs más útiles, precisos y seguros. Es parte del proceso de entrenamiento de modelos como Claude o GPT-4.

---

## S

**Scoring**
Asignación de una puntuación numérica a un individuo, entidad o evento basándose en un modelo predictivo. En seguros: scoring de riesgo en suscripción, scoring de fraude en siniestros, scoring de propensión en distribución.

**Sesgo**
Véase *Sesgo algorítmico*.

**Sistema experto**
Tipo de IA basado en reglas codificadas por expertos humanos. Precede al ML moderno. Aún en uso en sistemas core de muchas aseguradoras, frecuentemente combinados con modelos de ML para decisiones más complejas.

---

## T

**Telemática**
Tecnología que combina telecomunicaciones e informática para recoger datos de comportamiento en tiempo real. En seguros de automóvil: datos de velocidad, frenadas, conducción nocturna y kilometraje que permiten una tarificación basada en el uso real (UBI, Usage-Based Insurance).

**Transformador (transformer)**
Arquitectura de red neuronal introducida en 2017 que es la base de todos los LLMs modernos. Su mecanismo de atención permite al modelo relacionar palabras o fragmentos de texto entre sí, capturando el contexto con una eficacia muy superior a arquitecturas anteriores.

---

## U

**UBI (Usage-Based Insurance)**
Modelo de seguro donde la prima se calcula en función del uso real del bien asegurado, típicamente mediante telemática. En automóvil: pago por kilómetro recorrido, con ajustes según el comportamiento al volante. Requiere modelos de ML para procesar el volumen de datos generado.

**Underfitting (infraajuste)**
Problema opuesto al overfitting: el modelo es demasiado simple para capturar los patrones de los datos y tiene bajo rendimiento tanto en entrenamiento como en producción.

---

## V

**Validación cruzada (cross-validation)**
Técnica para evaluar la robustez de un modelo dividiéndolo en múltiples subconjuntos de entrenamiento y prueba, obteniendo una estimación más fiable de su rendimiento real que una única división. Práctica estándar en el desarrollo de modelos actuariales basados en ML.

**Variable objetivo (target variable)**
La variable que un modelo de ML intenta predecir. En suscripción: la ocurrencia o coste de un siniestro. En fraude: la probabilidad de que una reclamación sea fraudulenta. Definirla correctamente es una de las decisiones más importantes en el diseño de un modelo.

---

## X

**XAI (Explainable AI)**
Véase *Explicabilidad*.

**XGBoost**
Implementación de gradient boosting (véase *Boosting*) ampliamente utilizada en competiciones de ML y en producción en seguros por su rendimiento y velocidad. Muy frecuente en modelos de tarificación y detección de fraude.

---

*Términos adicionales pueden solicitarse al equipo de COI. Este glosario se actualiza con cada versión del curso.*

*Community of Insurance (COI) / CICA · carlos@communityofinsurance.es*
