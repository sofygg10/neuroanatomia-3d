# 🧠 NeuroLab 3D · Atlas de neuroanatomía interactivo

Aplicación web interactiva para estudiar **neuroanatomía** (pensada para estudiantes de **psicología**).
Un cerebro 3D que se **desarma/arma**, con **112 estructuras** documentadas y un **quiz** configurable.

## 🔗 Ver en línea

**https://sofygg10.github.io/neuroanatomia-3d/**

> La primera vez necesita conexión a internet para cargar el motor 3D (Three.js).
> El **Atlas** y el **Quiz** funcionan también sin conexión.

## ✨ Características

- **Modelo 3D interactivo** con 16 regiones que se desarman, giran y se pueden **cortar** (sagital / coronal / axial) para ver el interior.
- **Atlas de 112 estructuras** — cada una con **definición**, **función** y **qué pasa si se lesiona**:
  áreas de Brodmann, giros y surcos, ganglios basales, núcleos talámicos, sistema límbico,
  tronco encefálico, cerebelo, sustancia blanca, los 12 pares craneales, el sistema endocrino,
  las meninges, el sistema ventricular (LCR) y la médula espinal.
- **Buscador y filtros** por sistema anatómico.
- **Etiquetas**, modo **aislar** una estructura y **resaltado** al pasar el cursor.
- **Mapa mental interactivo**: árbol *Cerebro → sistema → estructura* con nodos clicables,
  colores por sistema, expandir/contraer, zoom y arrastre, y **bibliografía citada por sistema**.
  Cada estructura enlaza con su ficha y su botón *Ver en 3D*.
- **Quiz auto-generado y configurable**: 10 / 15 / 25 / 40 / maratón, por sistema o todos.
  4 tipos de pregunta (función, definición, lesión, sistema) con corrección y lista de repaso.

## 📚 Fuentes

Las definiciones, funciones y efectos de lesión se apoyan en los manuales de referencia de
neuroanatomía y neurociencia: **Kandel** (*Principios de Neurociencia*), **Purves** (*Neuroscience*),
**Snell** (*Neuroanatomía clínica*), **Nolte** (*El cerebro humano*), **Afifi & Bergman**,
**Bear, Connors & Paradiso**, **Crossman & Neary** y **Haines**. La bibliografía completa aparece
en la pestaña **Mapa mental**. Es material educativo: no es una citación dato a dato, así que
contrasta siempre con tu bibliografía oficial.

## 🚀 Uso local

Descarga `index.html` y ábrelo con doble clic en Chrome, Edge o Firefox. No requiere instalación.

## 🛠️ Tecnología

HTML + CSS + JavaScript en un solo archivo, con [Three.js](https://threejs.org/) para el 3D (WebGL).

---

*Herramienta educativa. El modelo 3D es esquemático, con fines didácticos.*
