## Diagrama de flujo para identificar tipos de arcos:

1.  **¿El arco es semicircular?** 
    *   **Sí**: Ir a la pregunta 2.
    *   **No**: Ir a la pregunta 5.

2.  **¿La flecha del arco es igual a la mitad de su luz?**
    *   **Sí**: Se trata de un arco de **medio punto**.
    *   **No**: Ir a la pregunta 3.

3.  **¿El arco es más alto que un semicírculo, con los arranques a la misma altura?**
    *   **Sí**: Se trata de un arco de **herradura**.
        *   **¿El peralte es un tercio del radio?** 
            *   **Sí**: Se trata de un arco de herradura **visigodo**.
            *   **No**: **¿El peralte es la mitad del radio?**
                *   **Sí**: Se trata de un arco de herradura **califal**.
                *   **No**: No se puede determinar el estilo del arco de herradura basándose solo en la información proporcionada. 
    *   **No**: Ir a la pregunta 4.

4.  **¿El arco es más bajo que un semicírculo?**
    *   **Sí**: Se trata de un arco **rebajado**.
    *   **No**: Basándose en la información proporcionada, no se puede determinar el tipo de arco.

5.  **¿El arco tiene forma de punta, con dos porciones de curva que forman un ángulo en la clave?**
    *   **Sí**: Se trata de un arco **apuntado**.
        *   **¿El arco apuntado también tiene forma de herradura?**
            *   **Sí**: Se trata de un arco de **herradura apuntado**.
            *   **No**: Se trata de un arco apuntado.
    *   **No**: Ir a la pregunta 6.

6.  **¿El arco tiene forma de quilla invertida, con cuatro centros?**
    *   **Sí**: Se trata de un arco **conopial**.
    *   **No**: Ir a la pregunta 7.

7.  **¿El intradós del arco está decorado con lóbulos?**
    *   **Sí**:
        *   **¿Cuántos lóbulos tiene?**
            *   **Tres**: Se trata de un arco **trilobulado** o **trifoliado**.
            *   **Más de tres**: Se trata de un arco **lobulado**.
    *   **No**: Ir a la pregunta 8.

8.  **¿El arco combina formas rectas y curvas en su intradós?**
    *   **Sí**: Se trata de un arco **mixtilíneo**.
    *   **No**: Ir a la pregunta 9.

9.  **¿El arco se construyó sobre un dintel para aliviar el peso del muro?**
    *   **Sí**: Se trata de un arco de **descarga**.
    *   **No**: Ir a la pregunta 10.

10. **¿El arco tiene alguna de estas características?**:
    *   **Alberga y cubre un sepulcro**: Se trata de un **arcosolio**.
    *   **Presenta apoyos oblicuos con respecto a su planta**: Se trata de un arco **esviado**.
    *   **Refuerza y corta una bóveda de cañón en sentido transversal**: Se trata de un arco **fajón**.
    *   **Es transversal al eje de una bóveda de crucería**: Se trata de un arco **perpiaño**.
    *   **Forma parte de los cuatro arcos que sostienen una cúpula en el crucero**: Se trata de un arco **toral**.
    *   **Da acceso desde la nave al presbiterio o al ábside de una iglesia**: Se trata de un arco **triunfal**.
    *   **Es paralelo al eje longitudinal de la nave y recibe el arranque de la bóveda**: Se trata de un arco **formero**.
    *   **Está enmarcado por un alfiz**:  Se trata de un arco con **alfiz**. 
    *   **No**: Basándose en la información proporcionada, no se puede determinar el tipo de arco. 

```
          ┌─────────────────────────────┐
          │  ¿El arco es semicircular?   │
          └──────────────┬───────────────┘
                         │
            ┌────────────┴────────────┐
            │                         │
         ┌─►Sí                       No◄─┐
         │  │                           │
         │  ▼                           ▼
┌─────────────────────────┐     ┌──────────────────────┐
│ ¿La flecha es la mitad  │     │ ¿Tiene forma de punta,│
│ de su luz?              │     │ con un ángulo en la   │
└──────────────┬──────────┘     │ clave?                │
               │                 └─────────────┬────────┘
     ┌─────────┴───────┐                       │
     │                 │                  ┌────┴─────┐
    Sí                No                  Sí         No
     │                 │                  │           │
     ▼                 ▼         ┌────────┴──┐  ┌─────▼────┐
┌─────────────┐ ┌─────────────┐  │ ¿También   │  │ ¿Tiene   │
│ Arco de     │ │ ¿El arco es  │  │ tiene forma│  │ forma de │
│ medio punto │ │ más alto que │  │ de herradura?│quillainvertida?│
└─────────────┘ │ un semicírculo?│ └───────┬──┘  └──────────┬─┘
                └─────┬─────────┘         Sí│              │
                      │             ┌──────┘              │
                    Sí│            No              ┌──────▼────┐
                      │                          Sí│            No
┌──────────────┐ ┌─────▼─────────┐   ┌─────────┐    ┌───────────▼─────┐
│ Arco de      │ │ ¿El peralte   │   │ Arco de │    │ ¿El intradós del│
│ herradura    │ │ es 1/3 del    │   │ herradura│   │ arco tiene      │
└──────────────┘ │ radio?        │   │ apuntado │   │ lóbulos?        │
                 └─────┬─────────┘   └─────────┘    └──────┬──────────┘
                       │                                    │
                    ┌──▼───┐                       ┌────────▼────┐
                    │ Sí   │                       │  ¿Cuántos   │
                    └──┬───┘                       │  lóbulos?   │
┌────────────────┐     │                            └──────┬─────┘
│ Arco herradura │  ┌──▼─────────┐              Tres◄──────┘  Más de tres
│ visigodo       │  │ 1/2 radio? │                │                │
└────────────────┘  └───────┬────┘     ┌──────────▼──┐   ┌─────────▼─────┐
                            │          │ Arco        │   │ Arco          │
┌────────────────┐      ┌───▼─────┐    │ trilobulado │   │ lobulado      │
│ Arco herradura │      │ No se   │    │ o trifoliado│   └───────────────┘
│ califal        │      │ puede   │    └─────────────┘
└────────────────┘      │ determinar │
                        └────────────┘
```
