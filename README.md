<div align="center">
  <br />
  <br />
  
  # <code>COURSE_PORTOFOLIO</code>
  
  **MINIMAL CV / RESUME WEB TEMPLATE**
  
  <br />

  <img src="https://img.shields.io/badge/ASTRO-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />


  <br />
  <br />
</div>

---

### 00 __ PREVIEW

![Hero Preview](portada.webp)

> **ABSTRACT:** Curriculum minimalista maquetado para web y listo para imprimir. Implementación de JSON Resume schema con keyboard shortcuts y diseño print-optimized.
>
> <br />
>
> **ORIGIN:** Based on [Tutorial Midudev](https://midu.dev).
> *Adapted with JSON Resume schema and keyboard navigation.*
>
> <br />
>
> **DEMO:** [curriculum-astro-curse.vercel.app](https://curriculum-astro-curse.vercel.app/)

---

### 01 __ ARCHITECTURE & DECISIONS

| COMPONENT | TECH | NOTE |
| :--- | :--- | :--- |
| **Core** | `Astro 4.15` | Static site generation. |
| **Language** | `TypeScript` | Type-safe development. |
| **Schema** | `JSON Resume` | Standard CV format. |
| **UX** | `HotKeyPad` | Keyboard shortcuts menu. |

<br>

### 02 __ INSTALLATION

*Run local environment:*

```bash
# 1. Clone or use as template
pnpm create astro@latest -- --template samuhlo-training/course-portofolio

# 2. Install dependencies (pnpm enforced)
pnpm install

# 3. Ignite
pnpm dev
```

### 03 __ USAGE

Edita el archivo `cv.json` para crear tu propio Portafolio/CV imprimible siguiendo el esquema de [jsonresume.org](https://jsonresume.org/schema/).

#### Available Commands

| Comando | Acción |
| :--- | :--- |
| `pnpm dev` | Lanza servidor de desarrollo en `localhost:4321` |
| `pnpm build` | Comprueba errores y genera build en `./dist/` |
| `pnpm preview` | Preview del build en `localhost:4321` |

<br/>
<br/>
<br/>

<div align="center">


<code>DESIGNED & CODED BY <a href='https://github.com/samuhlo'>samuhlo</a></code>


<small>Lugo, Galicia</small>

</div>
