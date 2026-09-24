# Proyecto P1: Análisis exploratorio del Titanic (numpy y pandas)

Optativa Python para IA, 2º DAM.

## Dataset

Titanic (versión de seaborn), en `data/titanic.csv`. Es el dataset recomendado en el enunciado: público, 891 filas y columnas numéricas y categóricas.

## Reparto

| Persona | Nombre | Tarea | Qué entrega | Fichero |
|---|---|---|---|---|
| P1 | [JiaXi] | T1 Carga e inspección | head, info, describe, shape y diccionario de datos | T1_carga_inspeccion.ipynb |
| P2 | [Alejandro] | T2a Nulos | isna().sum(), decisión y justificación por columna | T2a_nulos.ipynb |
| P3 | [Noel] | T2b Duplicados | duplicated(), decisión justificada y chequeo de valores raros | T2b_duplicados.ipynb |
| P4 | [Jorge] | T3a Franja de edad | columna franja_edad con numpy, sin bucles | T3a_franja_edad.ipynb |
| P5 | [Sergio] | T3b Normalización | columnas tarifa_norm y tam_familia con numpy, sin bucles | T3b_normalizacion.ipynb |
| P6 | [Argail] | T4a Filtrado | 2 filtros con condiciones distintas y 2 estadísticas sobre ellos | T4a_filtrado.ipynb |
| P7 | [Ainoha] | T4b Groupby | 4 agregaciones por categoría (sexo, clase, sexo y clase) | T4b_groupby.ipynb |
| Jefe | [Daniel] | T5 y revisión final | conclusiones, unión de notebooks y entrega | P1_analisis_titanic.ipynb |

## Contrato (todos seguimos esto)

| Decisión | Valor |
|---|---|
| Nombres de columnas | Los del CSV, sin renombrar (age, sex, pclass, survived...) |
| Nulos | age: mediana. embarked y embark_town: moda. deck: se elimina la columna |
| Duplicados | Nadie elimina filas hasta que P3 decida |
| Columnas nuevas | franja_edad, tarifa_norm, tam_familia (tam_familia = sibsp + parch + 1) |
| Franjas de edad | 0-12, 13-17, 18-59, 60+ |
| Bucles for sobre filas | Prohibidos, todo vectorizado |

## Cómo trabajar

1. Cada persona trabaja solo en su notebook, sin tocar los de los demás.
2. Empieza copiando la plantilla (`notebooks/plantilla.ipynb`).
3. Comenta el código y organízalo por tareas.
4. Termina con una celda de texto llamada "Hallazgo": 2-3 líneas con datos concretos.
5. Sube tu notebook a la carpeta `notebooks/` con Add file → Upload files.

Fecha límite de subida: [29 de Septiembre] (Para que me de tiempo a juntar todo, porfa acabar antes para no matarme del todo). 
Entrega final: [30 de septiembre].

## Conclusiones (Esto lo hago cuando esté todo)
