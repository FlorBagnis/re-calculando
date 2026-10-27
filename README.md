# 💗 Re Calculando · Super Calculadora Interactiva

<p align="center">

<img width="1360" height="886" alt="image" src="https://github.com/user-attachments/assets/b10f037f-b74f-4a8d-8768-b412b99df8b2" />


> **Re Calculando** es una aplicación web diseñada como una **super calculadora interactiva** que va mucho más allá de las cuentas básicas: permite registrar operaciones, **editar y eliminar** ítems o resultados en tiempo real, personalizar la interfaz con **4 temas visuales** y exportar todo tu historial de cálculos en **PDF** y **CSV**.

<p align="center">
  <a href="https://florbagnis.github.io/re-calculando/">
    <img src="https://img.shields.io/badge/Ver_Demo-Abrir_Calculadora-ff69b4?style=for-the-badge&logo=github&logoColor=white" alt="Ver Demo" />
  </a>
</p>

---

## ✨ Características Principales

* 🧮 **Super Calculadora Interactiva:** Resolución ágil de operaciones matemáticas y financieras cotidianas con registro dinámico en pantalla.
* ✏️ **Edición en Tiempo Real:** Modificá valores, conceptos o cálculos ya ingresados sin necesidad de borrar todo y empezar de cero.
* 🗑️ **Control Total de Registros:** Eliminación individual de operaciones o limpieza completa del listado con un solo clic.
* 📄 **Exportación en PDF y CSV:** Descargá tus cuentas, listados y totales en formato **PDF** (listo para imprimir o compartir) o en **CSV** para llevar tus números a Excel o Google Sheets.
* 🎨 **Sistema Multi-Tema (4 Modos):** Personalización visual instantánea con persistencia en el navegador (`localStorage`) para adaptar la calculadora a tu estilo:
  - 🌸 **Modo Claro / Pastel**
  - 🌙 **Modo Oscuro (Dark Pink)**
  - 💙 **Modo Azul Profundo**
  - 🖤 **Modo Black (OLED)**
* 💾 **Persistencia Local:** Tus cálculos y el tema elegido se mantienen guardados automáticamente en el dispositivo para que no pierdas información al recargar la página.
* 📱 **Diseño Responsive:** Interfaz adaptable, cómoda y fluida tanto en celulares como en escritorio.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5 semántico, CSS3 moderno (Variables CSS para gestión de temas, Flexbox, Grid), JavaScript (Vanilla ES6+).
* **Almacenamiento:** `localStorage` para persistencia de historial de cálculos y preferencias de tema.
* **Exportación de Datos:** Generación dinámica de documentos **PDF** (jsPDF) y archivos **CSV**.
* **Entorno & Deploy:** Git, GitHub Pages.

---

### 🎯 Objetivo del proyecto

El objetivo principal es consolidar conceptos fundamentales de **desarrollo frontend**, **manipulación del DOM** y **lógica de negocio aplicada a herramientas de productividad**, poniendo en práctica habilidades técnicas clave en roles como:

* **Technical Support Specialist**
* **Technical Support Analyst**
* **Customer Support / Customer Experience**
* **Product Operations / Operations Support**

El proyecto busca transformar una calculadora tradicional en una herramienta auditable y flexible, resolviendo el problema clásico de *"equivocarse en un número y tener que volver a sumar todo"*, mediante manejo reactivo del estado en **JavaScript**, edición en vivo y exportación directa de reportes.

---

## 🗄️ Estructura de Datos (`localStorage`)

Los registros y preferencias se almacenan localmente en el navegador del usuario para garantizar velocidad y privacidad:

```text
localStorage/
├── recalculando_theme       <- "light" | "dark" | "blue" | "black"
└── recalculando_history     <- Array de operaciones / registros
    └── {item}/
        ├── id: string | number
        ├── description: string
        ├── expression: string
        ├── result: number
        └── date: string


```

## 📝 Historial de Actualizaciones (Changelog)

### 🚀 Lanzamiento y Funciones Core (Octubre 2026)

**🧮 Motor de Cálculo e Historial**
* Registro interactivo de cálculos con soporte para **editar (✏️)** y **borrar (🗑️)** cada fila de forma independiente.
* Recálculo automático de totales al modificar o eliminar un ítem existente.

**📄 Exportación de Reportes**
* Integración de descarga directa en **PDF** con formato limpio y estructurado.
* Botón de exportación a **CSV** compatible con hojas de cálculo.

**🎨 Personalización e Interfaz**
* Implementación de los **4 temas visuales**: Modo Claro, Modo Oscuro, Modo Azul y Modo Black.
* Botones de acción limpios e intuitivos adaptados al contraste de cada paleta de colores.

---

¿Te sirvió? Dejale una ⭐ al repo.

---

## 📄 Licencia

Distribuido bajo licencia MIT. Ver el archivo `LICENSE`.

## 👩‍💻 Autora

**Florencia Bagnis**

* 💼 [LinkedIn](https://www.linkedin.com/in/florencia-bagnis)
* 💻 [Portfolio](https://florbagnis.github.io/Portfolio-FlorBagnis/)
* 📧 [florenciasoledadbagnis@gmail.com](mailto:florenciasoledadbagnis@gmail.com)

<br>

> 🌸 Proyecto personal desarrollado para ofrecer una **super calculadora editable y personalizable**, enfocado en **JavaScript moderno**, exportación de datos (**PDF/CSV**), diseño de interfaces limpias con **HTML5/CSS3** y una experiencia de usuario totalmente **responsive**.
