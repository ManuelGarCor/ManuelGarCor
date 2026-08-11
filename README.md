# ¡Bienvenid@! Soy Manuel

<div align="center">
  
  **Ingeniero Informático | Seguridad y Criptografía | Máster en Sistemas Inteligentes**  
  *Universidad de Salamanca*

  $$E: y^2 = x^3 + ax + b \pmod{p}$$
  $$\phi : E \to E' \quad \text{tal que} \quad \ker(\phi) = \langle P \rangle$$

</div>

## 👨‍💻 Sobre mí

---

## 🔬 Líneas de investigación

Mi trabajo se sitúa en la intersección entre las matemáticas puras y la seguridad computacional. Actualmente desarrollo dos líneas de investigación paralelas en el ámbito de la seguridad computacional:

### 🔐 Criptografía Post-Cuántica: Isogenias

Evolucionando desde ECC (Elliptic Curve Cryptography) hacia esquemas basados en isogenias supersingulares. Centrada en la **teoría de grafos de isogenias supersingulares**.

* Estudio de la estructura de grafos de isogenias para la construcción de primitivas criptográficas resistentes a computación cuántica.
* Transición desde protocolos ECC clásicos (ECDH/ECDSA) hacia esquemas basados en acciones de grupo y caminos en grafos de isogenias.

### 🔐 Sistemas Complejos: Autómatas Celulares

Análisis de propiedades criptográficas en primitivas simétricas mediante **Autómatas Celulares**. Investigación sobre comportamiento emergente y computabilidad en sistemas discretos.

* Diseño y evaluación de **Cajas de Sustitución (S-Boxes)** dinámicas.
* Estudio de propiedades booleanas críticas: No-linealidad, Criterio de Avalancha (SAC) y uniformidad diferencial en reglas de evolución de autómatas.

---

## 📜 Trayectoria y Proyectos

### 🎓 Investigación y desarrollo académico (TFG)

*Proyecto de final de grado. Universidad de Salamanca*  

> **Cifrado de archivos mediante criptografía de curvas elípticas.**
> Calificación: 10 - Sobresaliente

Implementación desde cero de un criptosistema seguro, evitando el uso de librerías criptográficas de caja negra para garantizar la comprensión profunda de la aritmética subyacente. Utilización de curvas elípticas sobre cuerpos finitos para cifrado de archivos, con enfoque en la eficiencia y seguridad.

* **Fundamento Matemático:** Operaciones en la estructura de grupo de puntos racionales de una curva sobre cuerpos finitos $\mathbb{F}_p$. Implementación de algoritmos de suma de puntos, multiplicación escalar y generación de claves, junto
a los protocolos de cifrado. Las curvas elípticas se definen por la ecuación $y^2 = x^3 + ax + b \pmod{p}$, donde $a, b \in \mathbb{F}_p$ han de cumplir ciertas condiciones para garantizar la seguridad del sistema.

Desarrollo de un sistema de cifrado funcional, implementación de una librería de aritmética de curvas elípticas y documentación detallada del proceso de diseño e implementación, incluyendo análisis de seguridad y rendimiento. Junto con la creación de una aplicación de escritorio para cifrado y descifrado de archivos, apoyándose en un servidor de claves para la gestión de usuarios y claves públicas.

### 🎓 Investigación y desarrollo académico (TFM)

*Proyectos de final de máster. Universidad de Salamanca*  

> **Técnicas de aprendizaje por refuerzo en el ajuste de parámetros de curvas elípticas para criptografía**
> Calificación: 9.7 - Sobresaliente

Investigación sobre la viabilidad del aprendizaje por refuerzo (RL) para la optimización automática de parámetros de dominio en criptografía de curvas elípticas (ECC), conforme al estándar SEC1. El problema se formuló como un Proceso de Decisión de Markov sobre el espacio de coeficientes de Weierstrass $(a, b)$, con una función de recompensa derivada del grado de cumplimiento de los siete criterios de seguridad de SEC1 (resistencia al ataque MOV, validez del cofactor, primalidad del orden, entre otros).

* **Vacío de investigación cubierto:** los enfoques previos en la literatura (algoritmos genéticos, optimización por enjambre de partículas) habían señalado explícitamente el uso de RL como una dirección necesaria pero nunca explorada para este problema. Este trabajo es el primero en aplicarlo a la optimización de parámetros ECC.

* **Infraestructura desde cero:** desarrollo de un evaluador criptográfico nativo en C sin dependencias externas (validado con 76 tests unitarios) y de un entorno compatible con Gymnasium apoyado en una tabla precomputada de más de un millón de curvas sobre un cuerpo finito, alcanzando más de 100.000 evaluaciones por segundo en CPU convencional.
* **Comparativa de algoritmos:** evaluación empírica de PPO, SAC y TD3 a lo largo de cuatro experimentos secuenciales, analizando la topografía del paisaje de recompensa y el impacto de codificar información posicional en el vector de observación.

Los resultados muestran que PPO iguala a SAC en eficacia con una ventaja de un orden de magnitud en velocidad de cómputo, mientras que TD3 no logra converger a una política útil por las limitaciones de su discretización determinista sobre el espacio de acciones. Partiendo de una curva conocida pero insegura, el agente entrenado corrige el parámetro vulnerable con una única acción en dos de las tres semillas evaluadas, constituyendo una prueba de concepto reproducible de la viabilidad del RL como herramienta de optimización de parámetros criptográficos. El trabajo se documentó tanto en la memoria completa como en un artículo con formato de publicación científica, co-firmado junto al equipo de dirección del TFM.

---

### 🔬 Estancias de Investigación (Prácticas)

*Colaboración en grupos de investigación y desarrollo de soluciones reales.*

> **Investigador en ESALab (Verano 2024)**
> *Laboratorio de Sistemas Inteligentes y Simulación*

To do

---

### 🗣️ Mentoría y Eventos

*Roles de liderazgo técnico, divulgación y guía en competiciones de seguridad.*

> **Mentor de Criptografía - Space Cybersecurity Hackathon (2025)**
> *Competición de ciberseguridad y criptografía aplicada a la industria aeroespacial*

To do

---

<div align="center">

### *"Anyone who considers arithmetical methods of producing random digits is, of course, in a state of sin."*

  — John von Neumann

</div>
