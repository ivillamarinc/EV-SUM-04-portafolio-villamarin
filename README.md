# EV-SUM-04 — Portafolio de Evidencias Individuales

Portafolio individual correspondiente a la asignatura **Aplicaciones Distribuidas (ISR-701)** de la carrera de Ingeniería de Software.

El documento presenta evidencias verificables de aprendizaje y contribución individual realizadas durante el desarrollo del Proyecto Fin de Curso (PFC). Incluye fragmentos de código propio, análisis técnico sobre datos obtenidos durante las pruebas del sistema, una reflexión documentada sobre decisiones técnicas y el historial de contribuciones realizadas en los repositorios del proyecto.

## Estructura del repositorio

```text
docs/
├── EV-SUM-04.pdf
├── EV-SUM-04.tex
├── referencias.bib
└── img/
    ├── commits_e3_antiguo.png
    └── commits_e4_nuevo.png
```

## Archivos principales

* **`EV-SUM-04.tex`**: archivo fuente principal del portafolio desarrollado en LaTeX con formato IEEE de doble columna.
* **`EV-SUM-04.pdf`**: versión compilada del portafolio lista para revisión y entrega.
* **`referencias.bib`**: archivo bibliográfico que contiene las fuentes académicas citadas en el documento.
* **`img/`**: carpeta que almacena las evidencias gráficas utilizadas en el portafolio.

## Evidencias gráficas

La carpeta `img/` contiene las capturas del historial de commits utilizadas para demostrar la contribución individual al PFC:

* `commits_e3_antiguo.png`: historial de commits correspondiente al repositorio utilizado durante la Entrega 3.
* `commits_e4_nuevo.png`: historial de commits correspondiente al repositorio utilizado durante la Entrega 4.

Las capturas permiten verificar el autor, las fechas, los mensajes y los hashes de los commits incluidos en el documento.

## Compilación

El archivo principal es:

```text
EV-SUM-04.tex
```

El documento utiliza referencias bibliográficas almacenadas en `referencias.bib` y procesadas mediante **Biber**.

Para compilar completamente el portafolio se debe ejecutar:

```bash
pdflatex EV-SUM-04.tex
biber EV-SUM-04
pdflatex EV-SUM-04.tex
pdflatex EV-SUM-04.tex
```

Como resultado se genera el archivo:

```text
EV-SUM-04.pdf
```

## Bibliografía

Las referencias se encuentran en:

```text
referencias.bib
```

Las citas se realizan en el documento mediante comandos como:

```latex
\cite{kleppmann2015}
\cite{barletta2024}
\cite{chen2025}
```

y se presentan mediante numeración siguiendo el formato IEEE.

## Contenido del portafolio

El documento incluye:

* Evidencia de código propio con trazabilidad mediante archivo y hash de commit.
* Análisis técnico basado en datos obtenidos durante pruebas del sistema.
* Reflexión crítica sobre una decisión técnica tomada durante el desarrollo.
* Historial verificable de contribuciones individuales realizadas en los repositorios del PFC.
* Capturas del historial de commits.
* Declaración de uso de inteligencia artificial generativa.
* Referencias bibliográficas académicas en formato IEEE.

## Repositorios del PFC

El portafolio utiliza evidencias provenientes de los repositorios desarrollados durante las diferentes entregas del Proyecto Fin de Curso:

**Repositorio anterior — Entrega 3**

```text
https://github.com/iavillamarin98-pred/Proyecto_Fin_de_Curso_scli
```

**Repositorio — Entrega 4**

```text
https://github.com/ffarinangog2/Entrega-final-del-PFC
```

## Autor

**Iván Villamarín Cuenca**
Equipo PFC: **FUVV — ForáCode**
Carrera de Ingeniería de Software
Universidad Técnica Estatal de Quevedo

