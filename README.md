# Hola!👋 
## Soy Pedro Gallino Ingeniero informático graduado en la Facultad de Ingeniería de la UBA (FIUBA) 📚

## GEduNet - Trabajo Profesional Final 🌐

Simulador gráfico educativo de redes de computadoras, diseñado para ayudar a estudiantes a comprender conceptos fundamentales de redes de manera interactiva. Permite visualizar el flujo de paquetes y experimentar con escenarios de red, facilitando el aprendizaje práctico.

* Simulación de capas de transporte, red y enlace, con abstracción de otras capas para un enfoque modular.
* Interfaz gráfica interactiva, optimizada para estudiantes sin experiencia en redes.
* Aplicación web client-side, desarrollada en TypeScript.
* Basado en el modelo top-down del libro Computer Networking: A Top-Down Approach.

[App](https://megaredhand.github.io/network-simulator/)

[Repositorio](https://github.com/MegaRedHand/network-simulator)

## Microservicio Backend: Arquitectura, Calidad y Despliegue⚡

* Diseño e implementación de una API REST (FastAPI/Python) aplicando arquitectura Hexagonal (ports & adapters).
* Implementación de Testing Unitario y Tests de Aceptación (BDD), utilizando herramientas como Cucumber para validar la lógica de negocio.
* Entorno de desarrollo estandarizado con Docker y Docker Compose. 
* Gestión de despliegue automatizada (CI/CD con GitHub Actions) para AWS y Render.
* Manejo de la persistencia en Neon DB, incluyendo la gestión de migraciones de bases de datos con alembic.

[Microservicio Backend](https://github.com/pgallino/backend-base)

## SteamyAnalytics 🖧

Sistema distribuido diseñado para procesar y analizar datos de Steam en paralelo. Recibe datasets sobre juegos y reseñas y ejecuta consultas predefinidas, como identificar los juegos con más reseñas positivas o aquellos con mayor tiempo de juego.

* Pipeline distribuido con nodos especializados en filtrado, conteo y unión de datos.
* Comunicación vía RabbitMQ para coordinar los nodos de procesamiento.
* Optimizado para entornos de multicomputing, permitiendo escalabilidad horizontal con Docker y Docker Compose.
* Tolerancia a fallos con réplicas y monitoreo automático mediante Watchdog.

[SteamyAnalytics](https://github.com/pgallino/Distribuidos-TP-Grupal)

## Turnero Médico 🤖🩺

Sistema para la gestión de turnos médicos, compuesto por una API REST y un bot de Telegram como interfaz.

* Bot de Telegram en Ruby que permite a pacientes solicitar, cancelar y consultar turnos médicos de forma intuitiva.
* API en Ruby que gestiona usuarios, médicos, agendas, turnos y validaciones de disponibilidad.

[turnero-bot-telegram](https://github.com/pgallino/turnero-bot-telegram)

[tunero-api](https://github.com/pgallino/turnero-api)

## Técnicas de Programación Concurrente I 🧵

Heladería Robotizada: Sistema distribuido que simula el procesamiento concurrente de pedidos en una heladería automatizada. El sistema está diseñado para ser altamente concurrente y tolerante a fallos, coordinando múltiples robots que preparan pedidos de manera eficiente.

* Procesamiento concurrente de pedidos mediante múltiples robots trabajando en paralelo.
* Elección de líder con el algoritmo Bully, permitiendo resiliencia ante fallos y asegurando la continuidad operativa.
* Modelo centralizado con distribución de carga, optimizando la asignación de pedidos y evitando sobrecarga en la comunicación.
* Mecanismos de tolerancia a fallos, garantizando que el sistema continúe funcionando incluso si robots o pantallas fallan.
* Implementación en Rust, aprovechando concurrencia y sincronización eficiente entre procesos.

[Repositorio Concurrente](https://github.com/pgallino/Programacion-Concurrente)

## Redes 🛜

File Transfer: Desarrollo de una aplicación cliente-servidor que garantiza la transferencia fiable de archivos sobre la red utilizando UDP y técnicas de retransmisión.

* Implementación de un protocolo confiable sobre UDP mediante Stop-And-Wait y Go-Back-N.
* Arquitectura Cliente-Servidor Multi-thread, permitiendo concurrencia y múltiples clientes simultáneos.
* Mecanismo de detección y recuperación de pérdida de paquetes.
* Simulación de condiciones adversas en la red utilizando Comcast para evaluar rendimiento y confiabilidad.
* Pruebas con Mininet y topologías personalizadas.

[Repositorio Redes](https://github.com/pgallino/REDES)

## Taller de Programación I 🧶

Left4Dead2D: Juego online en C++ con arquitectura cliente-servidor, utilizando sockets y threads.

* Cliente multi-threaded, con hilos independientes para recepción y envío de datos.
* Servidor concurrente, gestionando múltiples clientes de manera eficiente.
* Manejo de memoria seguro con RAII, evitando fugas de memoria y asegurando recursos correctamente.
* Renderizado con SDL2, optimizando gráficos y animaciones.

[Left4Dead2D-repositorio](https://github.com/pgallino/Taller1-TP-Left4Dead)

[Left4Dead2D-gameplay](https://www.youtube.com/watch?v=bAsRP4NCzlE)

Trabajos Prácticos sobre Sockets y Threads. Cliente-Servidor. (C++).

[Tps: Sockets & Threads](https://github.com/pgallino/Taller-De-Programacion-1C2023)

## Sistemas Operativos 🐧

TP1: Implementación de una Shell.

TP2: Implementación de un Scheduler.

TP3: Implementación de un FileSystem FUSE para un sistema operativo Unix-Like. (C y Assembly)

[Repositorio SISOP](https://github.com/pgallino/SISOP)

## Ciencia de Datos 💻🧪

Machine learning: Clasificación y Regresión - Métricas y Errores - Linear y logistic regression, KNN, Árboles, Random Forest y XGBoost - Feature Engineering. (python scikit-learn)

Trabajo práctico: Modelo para predecir si un hongo es venenoso o no.

[Machine learning: Hongo venenoso](https://github.com/pgallino/MACHINE-LEARNING-DATOS-1C2023)

Análisis de Datos: Pandas - Spark - visualización de datos - NLP. (python).

[Análisis de Datos](https://github.com/pgallino/PANDAS-SPARK-DATOS-1C2023)

## Aprendizaje Automático 🤖

Trabajo práctico: Modelo para predecir si un paciente es fumador o no.

[Machine learning: Fumador o no.](https://github.com/pgallino/Aprendizaje-Automatico)

## Análisis de la Información 📄👥

Desarrollo de un sistema de gestión web de proyectos y tickets para una empresa ficticia PSA. 

Inicialmente se descubrió el producto a desarrollar mediante técnicas de la Ingeniería de requisitos: Entrevistas - Backlog (Historias de usuario y criterios de aceptación) - Modelo de Dominio - Modelo C4 - Modelo de Datos - Organigrama - Onion Model - Minutas - Matriz de trazabilidad - Prototipos.

Finalmente se implementó utilizando: API-REST - React-js - TailWindcss - Java - SpringBoot - Gherkin.

[Back-End módulo soporte](https://github.com/pgallino/Soporte-API-REST-Backend)

[Back-End módulo proyectos](https://github.com/Sando-dev/back-psa) 

[Front-End](https://github.com/gcaldev/front-psa)

[sitio web PSA](https://front-psa.vercel.app/home)

## Gestión del Desarrollo de Sistemas Informáticos 🗂️

Desarrollo de App similar a splitwise con el fin de aplicar técnicas de gestión del desarrollo de sistemas informáticos.

Modelos en etapas, iterativos, incrementales, ágiles y de flujo continuo.
Procesos clásicos de la administración de proyectos: gestión de alcance, tiempos, costos y calidad.

[Front-End](https://github.com/Manuel-Pol/GastandoAndo-GDSI)

[Documentos de Gestión](https://drive.google.com/drive/folders/1gzjWJ1dfg9RUBsc62_XaZMTIl53W71iK?usp=drive_link)

[Video Presentación](https://drive.google.com/file/d/1C6Mm39lUlGXehQFdnex5_-bRawrbAdJM/view?usp=drive_link)


## Teoría de Algoritmos 🧩🧠
Busqueda Exhaustiva - Problemas greedy - División y conquista - Teorema del maestro - Programación dinámica - Flujo en redes - Reducciones - Certificados - Problemas NP completos - Algoritmos randomizados - Algoritmos de aproximación - Análisis amortizado - Computabilidad.

[Repositorio Trabajos TDA](https://github.com/pgallino/Teoria-De-Algoritmos)

## Algoritmos & Programación III 👾

Programación orientada a objetos. (Java - Smalltalk) 

MiniJuego siguiendo los lineamientos de POO.

[Juego POO](https://github.com/pgallino/GPS-1C2022)

## Algoritmos & Programación II 🌲

Implementación de tipos de dato Abstracto (TDA): Árboles - hash - Grafo - Heap - lista - pila - cola. 

Recursividad - Fuerza bruta - Manejo de memoria - Algoritmos sobre grafos (C - Python)

[Repositorio Algo2](https://github.com/pgallino/AlGO-2)

## Algoritmos & Programación I ⚡

Minijuego Pokedex (python).

[Pokedex](https://github.com/pgallino/Pokedex-1C2021)

Minijuego Batallas Pokemon. (python)

[Batallas Pokemon](https://github.com/pgallino/Pokemon-Battles-1C2021)

<!--
**pgallino/pgallino** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
