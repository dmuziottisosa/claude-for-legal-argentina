# Registro de marca ALIVEAR + ALIVE — Investigación y plan propuesto (Argentina)

> **Fecha:** 30/05/2026 · **Jurisdicción:** Argentina (INPI) · **Régimen:** Ley 22.362 + reformas 2018/2019 + Res. INPI 583/2025 y 75/2026
>
> **AVISO IMPORTANTE — ESTO NO ES ASESORAMIENTO LEGAL.** Este documento lo armó un asistente de IA a pedido del founder, para que llegue **informado** a su gestor / agente de la propiedad industrial, no para reemplazarlo. La disponibilidad real de las marcas y la decisión final de clases y estrategia las tiene que confirmar un **agente de la propiedad industrial matriculado** con una búsqueda de antecedentes en la base del INPI. Donde digo "confirmar con el agente", es literal.

---

## PARTE 0 — Barrido del repositorio: qué encontré (y qué NO)

Revisé el repo completo y sus Claude Skills. Conclusión honesta para que no te hagas falsas expectativas:

**Lo que SÍ hay:**
- Un plugin **`ip-legal/`** (propiedad intelectual) con skills de marcas: `clearance` (chequeo de disponibilidad / knockout), `portfolio`, `fto-triage`, `infringement-triage`, `cease-desist`. La **metodología** es excelente y la usé como esqueleto del análisis (chequeo de impedimentos absolutos, búsqueda de marcas similares, factores de confusión, familias adyacentes a barrer).
- Un sistema **`argentina/`** adaptado a derecho argentino: civil, laboral, penal, contratos, societario, concursos, administrativo, plazos.

**Lo que NO hay — y es la limitación clave:**
- El plugin `ip-legal` está construido **para Estados Unidos** (USPTO, tests *du Pont / Polaroid / Sleekcraft*, doctrina de *secondary meaning*, etc.). Su propia skill `clearance` dice explícitamente: *"No apliques doctrina de EE.UU. en silencio a otra jurisdicción"* y **nunca concluye que una marca está libre**. Es decir: el repo **no tiene un módulo de marcas argentino** ni conexión a la base del INPI.
- El sistema `argentina/` **no cubre marcas / INPI** — está enfocado en litigio, laboral, civil y administrativo. No hay skill de propiedad industrial argentina.

**Traducción:** ninguna skill de este repo puede hacerte la búsqueda de antecedentes ni darte una opinión de disponibilidad en Argentina. Lo que sirve es el **marco metodológico** del `ip-legal` + el **research externo** que sigue abajo. La búsqueda real en la base del INPI la hace tu gestor.

---

## PARTE 1 — Validación del marco legal que citaste (punto por punto)

| # | Lo que afirmaste | Veredicto | Corrección / matiz |
|---|---|---|---|
| 1 | Sistema **NO multiclase**, una solicitud por clase (Art. 10) | ✅ **Correcto** | Confirmado. Art. 10 Ley 22.362: una solicitud por cada clase. Cada clase = arancel + expediente separado. |
| 2 | **First-to-file**, prioridad por día y hora (Art. 8) | ✅ **Correcto** | Confirmado. La prioridad se acuerda por la fecha (y hora) de presentación. Por eso **presentar ya** importa. |
| 3 | Protección contra similares confundibles, no solo copias idénticas | ✅ **Correcto** | …pero con un **PERO enorme** en 2026 — ver Parte 2.B. La protección existe, pero ahora **depende de que VOS vigiles y te opongas**. |
| 4 | Denominativa protege el nombre en cualquier tipografía/color | ✅ **Correcto** | Es la protección más fuerte sobre la palabra. |
| 5 | Mixta protege el conjunto nombre+logo | ✅ **Correcto** | Protege el conjunto. Más fácil de conceder, pero **más acotada** (no monopoliza la palabra sola). |
| 6 | Palabra extranjera de uso común ("ALIVE") puede tener fricción | ⚠️ **Parcialmente** | Matiz importante abajo (Parte 3, pregunta 3). El riesgo de "uso común" aplica a impedimentos **absolutos** (genérico/descriptivo). "ALIVE" para gorros **no es descriptivo del producto** → probablemente registrable incluso como denominativa. El riesgo real es otro (marcas previas similares). |
| 7 | **Clase 10** = dispositivos terapéuticos / aparatos de masaje | ✅ **Correcto** | Confirmado en la Clasificación de Niza (12ª ed.). Clase 10 incluye textualmente "dispositivos terapéuticos" y "aparatos de masaje". Un gorro de gel de crioterapia encaja. |
| 8 | **Clase 35** = publicidad, gestión, venta minorista | ✅ **Correcto** | Confirmado. |
| 9 | **Clase 25** = prendas, calzado, sombrerería | ✅ **Correcto** | Confirmado, pero ojo con la caducidad por falta de uso (Parte 2.C). |
| 10 | Res. 583/25 + 75/2026 redujeron el plazo a ~2 meses; aranceles en UMAPI | ✅ **Correcto** (con matices grandes) | Plazo más corto **sí**, pero a costa de **menos examen de oficio** → más riesgo. Ver Parte 2.B. Aranceles confirmados en UMAPI (Parte 4). |
| 11 | Vigencia 10 años, renovable | ✅ **Correcto** | Confirmado. |

**Conclusión de la Parte 1:** tu marco está **muy bien armado**. La Ley 22.362 sigue vigente como columna vertebral. Los errores no son de lo que pusiste, sino de **lo que falta** — y eso es lo que puede generarte los "dolores de cabeza futuros". Va en la Parte 2.

---

## PARTE 2 — Las 3 correcciones / agregados CRÍTICOS que tu brief no contemplaba

### 2.A — ❌ CORRECCIÓN GRANDE: Argentina NO está en el Protocolo de Madrid

Tu pregunta 9 asume que podés usar el **Sistema de Madrid** para exportar a USA/Brasil/México. **Argentina NO es miembro del Protocolo de Madrid ni del Arreglo de Madrid.** (Confirmado en las listas de miembros de WIPO y USPTO; es uno de los pocos países de América sin acceso a Madrid. Un blog suelto dice lo contrario, pero está equivocado.)

**Qué significa para vos:**
- **No podés** registrar internacionalmente "desde Argentina" con una sola solicitud vía Madrid. No existe esa vía partiendo de una base argentina.
- Para proteger ALIVEAR/ALIVE en **USA, Brasil, México**, hay que hacer **solicitudes nacionales directas** en cada país (vía agente local en cada uno), o usar bloques regionales donde apliquen.
- La buena noticia: Argentina **sí** es parte del **Convenio de París**, que te da un **derecho de prioridad de 6 meses**. Si presentás en Argentina hoy, tenés 6 meses para presentar en esos países **reclamando la fecha argentina** como fecha de prioridad. Eso protege tu lugar en la fila allá sin tener que presentar todo simultáneamente.

**Recomendación:** Brasil y México **sí** están en Madrid, pero como vos no podés originar desde Argentina, eso no te sirve directamente. Si la exportación es a 2-3 años, **no gastes en registro internacional ahora**, pero **anotá la ventana de prioridad de 6 meses** por si decidís lanzar antes. Si hay un mercado prioritario claro (ej. Brasil por cercanía), conviene presentar nacional allá dentro de esos 6 meses.

### 2.B — ⚠️ EL CAMBIO 2026 QUE TE CAMBIA LA ESTRATEGIA: "más rápido pero más riesgoso"

Las Resoluciones **583/2025** y **75/2026** no solo aceleraron el trámite. Cambiaron **qué examina el INPI**:

- **Antes:** el INPI examinaba de oficio tanto impedimentos **absolutos** (que la marca no sea genérica, descriptiva, engañosa, contraria al orden público) **como relativos** (que no choque con marcas previas similares). Si había una marca parecida, el INPI te la observaba.
- **Ahora (vigencia escalonada, etapas del nuevo procedimiento desde el 1/3/2026):** el INPI examina **solo los impedimentos ABSOLUTOS**. Los **relativos** (parecido con marcas anteriores) **ya NO se examinan de oficio** — solo se discuten **si un tercero se opone** dentro de los 30 días de la publicación.

**Por qué esto es un arma de doble filo para tu objetivo "bulletproof":**
1. **A tu favor:** tu marca se concede más rápido (~2 meses si nadie se opone) porque el INPI no se traba buscando conflictos.
2. **En tu contra (el verdadero dolor de cabeza):**
   - El INPI **ya no te protege de oficio** de que entre una marca confundible **después** de la tuya. Si mañana alguien presenta "ALIVEAR" o "ALIVET" o "ALIVE-AR" en clase 10, el INPI **no lo va a frenar solo**: **vos** tenés que detectarlo en el Boletín de Marcas y **oponerte** dentro de los 30 días.
   - Inversamente, que tu marca se conceda **NO garantiza** que no pise una marca previa: como el INPI no revisa relativos, podrías obtener el registro y **igual recibir una demanda/nulidad** de un titular anterior. Por eso la **búsqueda de antecedentes previa** (que hace tu gestor) pasó de "recomendable" a **imprescindible**.

**Conclusión accionable:** "bulletproof" en 2026 **no es solo registrar**. Es **registrar + vigilar + estar listo para oponerte**. Pasá a leer la Parte 5 (plan), donde esto se traduce en un servicio de **vigilancia de marca** que tenés que sumar sí o sí.

### 2.C — ⚠️ DOS OBLIGACIONES POST-REGISTRO que tu brief no menciona (y que tumban marcas)

**(1) Declaración jurada de uso de medio término (entre el 5º y 6º año).**
Después de la reforma, el titular **debe presentar una declaración jurada de uso** de la marca entre el quinto y sexto año de vigencia. Hoy el INPI **no exige acompañar pruebas**, solo la declaración. **Si no la presentás, se presume que NO usaste la marca** (salvo prueba en contrario) — y eso te deja expuesto a la caducidad. Es un trámite barato y rápido, pero **si te olvidás, es un agujero**. Tu gestor debería ponerlo en agenda al momento de registrar.

**(2) Caducidad por falta de uso (a los 5 años).**
Una marca registrada hace **más de 5 años** puede ser **caducada total o parcialmente** —a pedido de un tercero— **respecto de los productos/servicios para los que no se usó** en los últimos 5 años. Esto impacta directo tu **estrategia defensiva**:
- Registrar **Clase 25 (sombrerería)** "por las dudas" sin venderla efectivamente como prenda te deja esa clase **vulnerable a caducidad parcial** pasados 5 años. Un competidor que quiera "ALIVE" para ropa podría pedir la caducidad de tu clase 25 por no uso.
- **Atenuante legal:** la marca no caduca en una clase si la usaste para un producto/servicio **relacionado o similar**, aunque esté en otra clase. Como vendés el gorro (clase 10) que **se usa puesto en la cabeza**, hay argumento de conexidad con clase 25, pero **no es garantía**. La defensa real de la clase 25 es **usarla** (vender el gorro también como "prenda/accesorio") o aceptar que es defensa temporal.

---

## PARTE 3 — Respuestas directas a tus 10 preguntas

**1. ¿Es correcto el marco legal (Ley 22.362)?**
Sí, en lo esencial. La ley sigue vigente. Lo que faltaba: (a) Madrid no aplica (2.A), (b) el cambio 2026 a examen solo de absolutos (2.B), (c) declaración de uso de medio término y caducidad por no uso (2.C).

**2. Disponibilidad de ALIVEAR / ALIVE en clases 10, 25, 35.**
**No la puedo responder y nadie debería responderla sin una búsqueda en la base del INPI.** Esto es exactamente lo que tu gestor tiene que hacer (búsqueda de antecedentes / "denominativa + fonética + figurativa" por clase). **Pedile que la búsqueda incluya las familias adyacentes**, no solo coincidencias exactas (ver lista abajo). Que **ALIVE** sea palabra común en inglés hace **más probable** que ya exista alguien usándola/registrándola en alguna clase — razón de más para buscar antes de invertir.

> **Familias adyacentes a barrer (pedíselas al gestor):**
> - Raíz **ALIVE / ALIV-**: ALIVE, ALIV, ALIVIO, ALIVIAR, ALIVEN, ALIVET, ALIVIA.
> - Gemelos fonéticos de **ALIVEAR**: ALIVIAR, ALIVEAR, ALIVE-AR, ALIBEAR, ALIVER.
> - Categoría migraña/dolor/frío-calor: marcas que combinen alivio + cabeza/migraña/cool/gel/therapy en clase 10/5.
> - Variantes con guion/junto/separado y con sufijo -AR/-AT/-EX.

**3. ¿"ALIVE" es registrable? ¿Solo como mixta?**
Separá dos riesgos:
- **Impedimento absoluto (genérico/descriptivo):** "ALIVE" = "vivo" en inglés. Para **gorros de gel terapéutico** NO describe el producto ni es genérico de la categoría — es **evocativo/sugestivo** a lo sumo. Por eso, en cuanto a absolutos, **debería ser registrable incluso como denominativa**. La idea de que "es palabra común y por eso no se puede" está sobre-simplificada: lo que importa es si es común/descriptiva **respecto de estos productos**, no en abstracto.
- **Impedimento relativo (marca previa):** ACÁ está el riesgo real, y **ahora el INPI no lo examina** (2.B). Si ya hay un "ALIVE" o confundible previo en clase 10, te lo pueden oponer/anular. La **mixta** ayuda a diferenciar visualmente y a sortear una eventual oposición, pero **no te blinda** si hay un denominativo previo fuerte.
- **Recomendación:** intentar **ALIVE denominativa en clase 10** (la protección más fuerte) **y** la **mixta** como refuerzo, pero **condicionado a la búsqueda de antecedentes**. Si la búsqueda muestra un previo riesgoso, replegarse a mixta o reforzar con ALIVEAR (que por ser inventada es marca "fuerte" y fácil).

**4. ¿Las clases propuestas son correctas?**
- **Clase 10 como principal: ✅ correcta.** Es la clase del producto (dispositivo terapéutico). Es tu "pieza maestra". Bien identificada.
- **Clase 35 para la tienda/paraguas: ✅ tiene sentido**, sobre todo porque vendés por e-commerce propio + MercadoLibre (servicios de venta minorista / publicidad / tienda online). Útil para proteger "ALIVEAR" como marca-paraguas comercial. Confirmá con el gestor la redacción del listado (los servicios de venta minorista en clase 35 requieren describir bien el rubro).
- **Clase 25 (sombrerería): defensa útil pero con fecha de vencimiento.** Sirve para bloquear a quien quiera vender "gorros ALIVE" como ropa, **pero** es vulnerable a caducidad por no uso a los 5 años si no la usás como prenda (2.C). Decisión de costo/beneficio: si el presupuesto es ajustado, es la primera que recortaría del Tier 1.
- **¿Falta alguna clase?** Dos a evaluar con el gestor:
  - **Clase 5** (productos farmacéuticos, higiénicos para uso médico, "compresas, apósitos"). Si en algún momento vendés **geles/compresas medicinales** o posicionás el producto con claim terapéutico fuerte, clase 5 puede ser relevante. Para el gorro-dispositivo, la 10 es la correcta; la 5 es para sustancias/preparados. **Probablemente no la necesites ahora**, pero vale la pregunta.
  - **Clase 44** (servicios médicos/de bienestar) — solo si a futuro ofrecés un servicio (no un producto), p. ej. terapia. Hoy no.

**5. ¿Conviene registrar el logo (flor de loto) como FIGURATIVA por separado?**
**Sí, vale la pena si el logo tiene valor propio** y lo usás a veces **solo** (sin el nombre al lado: ícono de app, favicon, sello en el producto, redes). Una **figurativa pura** protege el dibujo de la flor de loto **independientemente del texto**, y te deja parar a quien copie el ícono aunque le cambie el nombre. Si el logo **siempre** va pegado al texto, la **mixta** alcanza y la figurativa es opcional. Dado que querés "bulletproof" y ya tenés brand equity, la figurativa de la flor de loto es una **buena inversión de Tier 2** — pero ojo, una flor de loto estilizada es un símbolo bastante usado: la búsqueda figurativa (por clasificación de Viena) es clave para ver si hay logos similares.

**6. ¿El orden Tier 1 / Tier 2 es eficiente?**
Casi. Le haría dos ajustes (ver Parte 5): subir **ALIVEAR denominativa clase 10** y **clase 35** al núcleo absoluto, y mover **ALIVE** a depender de la búsqueda. La clase 25 baja un escalón. Y agrego un Tier 0 que tu brief no tenía: **búsqueda de antecedentes + decisión de titularidad** ANTES de presentar nada.

**7. ¿Denominativa + Mixta del mismo nombre es redundante o complementario?**
**Complementario, no redundante** — pero con prioridad clara:
- La **denominativa** es la que de verdad te blinda: protege la **palabra** en cualquier tipografía/color. Si solo pudieras pagar una de ALIVEAR, es **esta**.
- La **mixta** protege el conjunto visual (útil contra copias del "look") y a veces se concede cuando la denominativa tiene fricción.
- Para "ALIVEAR" (inventada, fuerte): la **denominativa es suficiente y prioritaria**; la mixta es refuerzo opcional.
- Para "ALIVE" (palabra común): tiene **más sentido** tener ambas, porque la mixta cubre el flanco si la denominativa recibe oposición.

**8. Costos estimados (UMAPI) + plazos.** Ver Parte 4.

**9. ¿Registro internacional ahora (Madrid)?**
**No vía Madrid** — Argentina no es miembro (2.A). Si exportás a 2-3 años: dejalo para después, **pero** registrá ya en Argentina para activar la **ventana de prioridad de 6 meses** del Convenio de París, y reevaluá si algún mercado (Brasil/México/USA) se adelanta. No gastes hoy en internacional especulativo.

**10. ¿Dolores de cabeza que tu plan no contempla?** Ver Parte 6 (lista completa).

---

## PARTE 4 — Costos y plazos (valores 2026, confirmar tarifario INPI vigente)

**Sistema de aranceles (Res. 75/2026):**
- Se creó la **UMAPI** (Unidad de Medida Arancelaria de la Propiedad Industrial), que se **actualiza todos los meses por el IPC del INDEC**. Valor inicial ≈ **$372 ARS por UMAPI** (sube mes a mes).
- **Solicitud de marca nueva (hasta 20 productos/servicios): 100 UMAPI ≈ $36.000 ARS** por clase (valor abril 2026; hoy algo más alto por ajuste mensual).

**Estimación por línea del plan** (orden de magnitud, **por clase y por marca**, sin honorarios del gestor):

| Concepto | Costo aprox. (ARS, abril 2026) | Nota |
|---|---|---|
| 1 solicitud de marca nueva (1 clase, ≤20 prod./serv.) | ~$36.000 (100 UMAPI) | Se multiplica por **cada marca × cada clase × cada tipo** (denominativa y mixta cuentan separado) |
| Productos/servicios adicionales (>20) | arancel adicional escalonado | Solo si tu listado es muy largo |
| Oposición a marca de un tercero (vigilancia) | arancel propio | Lo vas a necesitar bajo el régimen 2026 |
| Declaración jurada de uso (año 5-6) | arancel menor | Obligatoria — agendar |
| Renovación (cada 10 años) | arancel propio | — |

**Importante sobre el cálculo:** como NO es multiclase, cada combinación cuesta una solicitud entera. Tu Tier 1 original (4 solicitudes) ≈ **4 × ~$36.000 = ~$144.000 ARS** en tasas oficiales, **más honorarios del gestor** (esto último suele ser el grueso del costo real; pedí presupuesto cerrado). Los montos en pesos son relativamente bajos en dólares, pero **se acumulan rápido** al multiplicar marca × clase × tipo. Por eso conviene **priorizar** (Parte 5) en vez de registrar todo de una.

**Plazos:** si **nadie se opone**, concesión en ~2 meses desde la publicación (mucho más rápido que el >1 año histórico). Si hay oposición, se abre el procedimiento de los arts. 15-16 y se alarga. La ventana de **oposición de terceros es de 30 días** desde la publicación en el Boletín de Marcas.

> Verificá el tarifario vigente en el portal del INPI al momento de presentar — la UMAPI cambia todos los meses.

---

## PARTE 5 — Plan propuesto REVISADO (priorización eficiente)

### TIER 0 — ANTES de presentar nada (lo que tu brief saltaba)
1. **Búsqueda de antecedentes** con el gestor en la base del INPI: ALIVEAR y ALIVE en clases 10, 35, 25 (+ 5 si aplica), **incluyendo familias adyacentes y fonéticas** (lista en Parte 3.2) y **búsqueda figurativa** de la flor de loto (clasificación de Viena). **Esto es lo más importante de todo el plan** bajo el régimen 2026, porque el INPI ya no chequea conflictos por vos.
2. **Decidir la titularidad ahora:** ¿registrás a tu nombre (persona física) o a nombre de una sociedad (SAS/SRL)? Cambiar el titular después implica **cesión de marca** (trámite + costo + arancel). Si pensás meter inversores, vender, o separar patrimonio, registrar directo a la sociedad evita una cesión futura. Definilo **antes** de presentar. (Tema societario — consultá también esa pata.)

### TIER 1 — Núcleo bulletproof (presentar primero, juntos)
| # | Marca | Tipo | Clase | Por qué |
|---|---|---|---|---|
| 1 | **ALIVEAR** | **Denominativa** | **10** | Pieza maestra. Marca inventada (fuerte) sobre el producto. La protección más sólida. |
| 2 | **ALIVEAR** | **Denominativa** | **35** | Protege la marca-paraguas en e-commerce / venta minorista (tu canal real: tienda + MercadoLibre). |
| 3 | **ALIVE** | **Denominativa** | **10** | Intentar primero la denominativa (más fuerte). **Condicionada a la búsqueda**: si hay previo riesgoso, ir a mixta. |
| 4 | **ALIVE** | **Mixta** | **10** | Refuerzo / plan B si la denominativa recibe oposición. Cubre el conjunto nombre+logo del producto. |

*(Ajuste vs. tu brief: subí ALIVE denominativa al núcleo en vez de la ALIVEAR mixta, porque proteger la palabra "ALIVE" —tu nombre de producto— vale más que duplicar el logo de la marca-paraguas. La ALIVEAR mixta pasa a Tier 2.)*

### TIER 2 — Perímetro (según presupuesto, en este orden)
| # | Marca | Tipo | Clase | Por qué |
|---|---|---|---|---|
| 5 | **ALIVEAR** | **Mixta** | **10** | Refuerzo visual del combo nombre+logo de la marca-paraguas. |
| 6 | **Flor de loto** | **Figurativa** | **10** (y/o 35) | Solo si usás el ícono **sin** texto. Protege el dibujo por sí mismo. |
| 7 | **ALIVEAR** | **Denominativa** | **25** | Defensa contra "gorros ALIVE como ropa". **Recordá:** vulnerable a caducidad si no la usás como prenda (2.C). |

### TIER 3 — Servicio CONTINUO (no es un trámite, es un hábito — y es lo que te hace "bulletproof" de verdad en 2026)
8. **Vigilancia de marca:** contratá (con el gestor o un servicio) el **monitoreo del Boletín de Marcas** para detectar solicitudes de terceros confundibles y **oponerte dentro de los 30 días**. Sin esto, el registro 2026 es a medias: tenés el título pero no la defensa automática.
9. **Agenda de plazos:** declaración jurada de uso (año 5-6) y renovación (año 10). Que el gestor te las deje calendarizadas.

---

## PARTE 6 — Dolores de cabeza futuros que tu plan no contemplaba (checklist)

1. **Madrid no existe para vos** → exportación = solicitudes nacionales país por país; usá la prioridad de 6 meses del Convenio de París (2.A).
2. **El INPI ya no te defiende de oficio** → necesitás **vigilancia + oposición activa** (2.B). Sin esto, "registrado" ≠ "protegido".
3. **Registrar no garantiza que no pises a un previo** → la búsqueda de antecedentes pasó a ser imprescindible, no opcional (2.B / Tier 0).
4. **Declaración jurada de uso (año 5-6)** → si te olvidás, se presume no uso (2.C).
5. **Caducidad por falta de uso (5 años)** → las clases defensivas que no usás (25) son atacables (2.C).
6. **Uso intercambiable ALIVEAR/ALIVE** → está bien tener empresa+producto, pero **registrá las dos** en las clases núcleo; no asumas que registrar una protege a la otra. Son signos distintos. Definí también cuál es la marca-madre para el branding.
7. **Marca ≠ nombre comercial / razón social** → registrar la marca en el INPI **no** reserva el nombre de tu sociedad ni el dominio. Ya tenés `gorroalive.com.ar`; considerá también registrar dominios defensivos (alivear.com.ar, .com) — barato y evita ciberocupación.
8. **Titularidad persona física vs. jurídica** → decidir antes de presentar para no pagar una cesión después (Tier 0.2).
9. **Brand equity ya construido sin registro** → estás vendiendo hace meses sin marca registrada. Eso te da algún derecho como **usuario de hecho / marca notoria incipiente**, pero es débil frente a un first-to-file. **Riesgo concreto:** que alguien que vea tu éxito en MercadoLibre **registre "ALIVE" antes que vos** y después te reclame. Esto hace que **presentar ya** (Tier 1) sea urgente, no opcional.
10. **(Regulatorio, fuera de marcas, pero te puede frenar):** un gorro que se promociona para "aliviar la migraña / el dolor de cabeza" puede ser considerado **producto médico** y caer bajo control de **ANMAT**, y los **claims terapéuticos** en la publicidad pueden ser observados (defensa del consumidor / publicidad engañosa). Esto **no es un tema de marca**, pero es un "dolor de cabeza futuro" real para tu negocio. Vale consultarlo aparte (la pata regulatoria/sanitaria), porque afecta cómo podés comunicar el producto.

---

## PARTE 7 — Qué llevarle al gestor (resumen de 1 minuto)

1. "Quiero **búsqueda de antecedentes** de ALIVEAR y ALIVE en clases **10, 35, 25** (y consultame si conviene 5), **incluyendo familias fonéticas/adyacentes y búsqueda figurativa de la flor de loto**."
2. "Confirmame disponibilidad y decime si **ALIVE** la puedo ir **denominativa** o solo **mixta**."
3. "Quiero presentar el **Tier 1** (4 solicitudes) cuanto antes — me preocupa que alguien registre ALIVE antes que yo."
4. "¿A nombre de quién conviene registrar: yo o la sociedad? Si es la sociedad, hagámoslo directo para no pagar cesión después."
5. "Necesito **servicio de vigilancia** del Boletín y que me **agendes** la declaración de uso (año 5-6) y la renovación (año 10)."
6. "Pasame **presupuesto cerrado** (tasas INPI + tus honorarios) por cada línea, así priorizo Tier 1 vs Tier 2."
7. "Para exportar a futuro (Brasil/México/USA): ya sé que **Madrid no aplica desde Argentina**; recordame la **ventana de prioridad de 6 meses** del Convenio de París cuando decida el primer mercado."

---

### Fuentes consultadas (research externo)
- Ley 22.362 de Marcas y Designaciones (texto actualizado) — Argentina.gob.ar / WIPO Lex / INPI.
- Reglamentación Decreto 242/2019 y modificaciones DNU 27/2018 (régimen de oposiciones administrativas).
- INPI — Resolución 583/2025 (procedimiento de examen: solo impedimentos absolutos de oficio; relativos vía oposición; vigencia escalonada desde 1/3/2026).
- INPI — Resolución 75/2026 (creación de UMAPI; aranceles; marca nueva = 100 UMAPI; actualización mensual por IPC). Boletín Oficial 20/03/2026.
- WIPO / USPTO — listas de miembros del Sistema de Madrid (Argentina **no** es miembro).
- Convenio de París — derecho de prioridad de 6 meses para marcas.
- Clasificación de Niza (12ª ed., WIPO) — Clase 10 (dispositivos terapéuticos, aparatos de masaje), Clase 35, Clase 25, Clase 5.
- Declaración jurada de uso de medio término y caducidad parcial por falta de uso (reforma Ley 22.362) — análisis de estudios de PI (Clarke Modet, SBM, HyA, LexLatin).

> **Recordatorio final:** documento de investigación para llegar informado al gestor. **No** es opinión legal ni de disponibilidad. La decisión final, la búsqueda en la base del INPI y la estrategia las confirma tu **agente de la propiedad industrial matriculado**.

---

# PARTE 8 — ACTUALIZACIÓN con datos confirmados por el founder (esta parte AJUSTA las anteriores)

**Datos nuevos:**
1. El producto **se importa y se vende como PRENDA TEXTIL (gorro)**, no como dispositivo médico. **No tiene uso médico**, solo posicionamiento **wellness / terapéutico**.
2. El founder es **responsable inscripto (persona física)** → registra **a su nombre**.

### Impacto en la estrategia
- **Clase 25 sube a núcleo (deja de ser defensiva).** Como el producto **ES** un gorro/prenda y **lo vas a usar** como tal, la clase 25 es **clase de uso real** → **NO** corre riesgo de caducidad por falta de uso (era el riesgo de la Parte 2.C). Probablemente sea, junto con la 10, la clase **más defendible** porque coincide con la naturaleza física del producto.
- **Clase 10 sigue valiendo, pero confirmá la redacción.** Sin uso médico, la 10 ("dispositivos terapéuticos") puede igual aceptarse describiendo el producto como aparato de termoterapia/crioterapia de bienestar, pero **es la pregunta nº1 para el gestor**: ¿la 10 conviene igual, o la 25 alcanza como ancla y la 10 es para bloquear a quien lo venda como "aparato terapéutico"? Mi lectura: **registrá ambas** — 25 (lo que el producto es) + 10 (la función que vendés) — para tapar los dos flancos.
- **Desaparece la alerta ANMAT** (dolor de cabeza nº10): al no haber uso médico, no es producto médico. **Queda solo** cuidar que la publicidad no haga claims terapéuticos médicos absolutos (defensa del consumidor / publicidad), pero es riesgo menor.
- **Titularidad resuelta:** a nombre de la **persona física (responsable inscripto)**. Listo, sin cesión pendiente. *Solo* si a futuro armás una SAS/SRL para el negocio, ahí sí conviene ceder la marca a la sociedad (trámite con arancel).

### Plan de clases REVISADO (definitivo para llevar al gestor)
**Núcleo (Tier 1):** 25 (denominativa ALIVEAR) · 25 (denominativa ALIVE) · 10 (denominativa ALIVE) · 35 (denominativa ALIVEAR).
**Refuerzo (Tier 2):** 10 (denominativa ALIVEAR) · mixtas de ALIVE y ALIVEAR · figurativa flor de loto.
*(Todo sujeto a la búsqueda de antecedentes del Tier 0.)*

---

## PARTE 9 — PLAN TÁCTICO-ESTRATÉGICO DE REGISTRO (paso a paso)

**FASE 0 — Antes de presentar (esta semana):**
- Pedir al gestor la **búsqueda de antecedentes** de ALIVEAR y ALIVE en clases **25, 10, 35** + familias fonéticas/adyacentes + figurativa de la flor de loto.
- Confirmar redacción de productos/servicios por clase (≤20 ítems por solicitud para pagar la tasa base).

**FASE 1 — Presentación del núcleo (apenas la búsqueda dé luz verde):**
- Presentar las **4 solicitudes del Tier 1 el mismo día** (importa por el first-to-file, Art. 8: prioridad por día y hora).
- Titular: **persona física (vos), responsable inscripto.**

**FASE 2 — Publicación y oposiciones (mes 1):**
- Cada solicitud se publica en el Boletín de Marcas. Se abre la ventana de **oposición de terceros (30 días)**.
- Si nadie se opone y no hay impedimento absoluto → **concesión en ~2 meses**.

**FASE 3 — Refuerzo (Tier 2, según presupuesto):**
- Una vez asegurado el núcleo, sumar mixtas + figurativa + ALIVEAR clase 10.

**FASE 4 — Mantenimiento permanente (esto es lo que te hace "bulletproof"):**
- **Vigilancia del Boletín** para oponerte a confundibles (obligatorio en el régimen 2026).
- **Declaración jurada de uso** entre año 5 y 6.
- **Renovación** cada 10 años.

---

## PARTE 10 — ¿ES UN SOLO PAGO?

**No.** No existe el "pago único que te deja cubierto para siempre". Los pagos son:
1. **Por cada solicitud** = marca × clase × tipo. Núcleo (4 solicitudes) ≈ 4 × 100 UMAPI ≈ **~$144.000 ARS** en tasas oficiales (abril 2026), **+ honorarios del gestor por cada una** (suele ser el grueso — pedí presupuesto cerrado).
2. **Vigilancia** (servicio mensual/anual, opcional pero recomendado).
3. **Oposición** (arancel, solo si necesitás frenar a alguien).
4. **Declaración de uso** (año 5-6, arancel menor).
5. **Renovación** (cada 10 años, arancel propio).

Es decir: un **desembolso inicial fuerte** (las solicitudes) + **costos chicos recurrentes** (mantenimiento). No es suscripción, pero tampoco "pagás una vez y listo".

---

## PARTE 11 — SI ME COPIAN, ¿PUEDO RECLAMAR / DEFENDERME?

**Con la marca registrada: SÍ, y con herramientas fuertes.** Sin registro: muy poco.

**Con registro (lo que ganás):**
- **Oposición:** frenar en el INPI a quien intente registrar una marca confundible (dentro de los 30 días de su publicación — por eso necesitás vigilancia).
- **Acción de cese de uso + daños y perjuicios** (civil, Ley 22.362): exigir que dejen de usar la marca y reclamar indemnización.
- **Medidas cautelares:** secuestro/embargo de la mercadería en infracción.
- **Vía penal** (Ley 22.362, arts. 31-34): la falsificación o imitación fraudulenta de una marca registrada es **delito** (prisión + multa). Solo disponible **si la marca está registrada**.
- **Medidas en frontera (Aduana):** inscribir la marca para que la Aduana retenga importaciones de copias.
- **Bajada de publicaciones en MercadoLibre** (Programa de Protección de Propiedad Intelectual de MELI): denunciar y dar de baja publicaciones de copias — **te piden el número de marca registrada**.

**Sin registro (lo que tenés hoy):** solo competencia desleal / lealtad comercial / "marca de hecho". Es **mucho más débil**: sin vía penal, sin medidas en frontera, y los programas de las plataformas te piden registro. Además, bajo first-to-file, **un tercero podría registrar ALIVE antes que vos** y darte vuelta el reclamo. Por eso registrar **ya** es urgente.

> **Resumen:** registrar = pasás de "casi indefenso" a tener oposición + civil + penal + aduana + takedowns. Pero en 2026 la defensa **no es automática**: el escudo lo activás vos vigilando el Boletín y oponiéndote a tiempo.

---

# PARTE 12 — PLAN FINAL "CERO HUECOS" (matriz definitiva, eficiente)

**Activos:** 2 nombres (ALIVE = producto insignia; ALIVEAR = marca paraguas/tienda) · 2 logos (el de ALIVE va impreso en el gorro; el de ALIVEAR es el de la marca) · 3 terrenos (terapéutico/bienestar, prenda/gorro, tienda/ecommerce).

**Dato relevante:** la tienda es `gorroalive.com.ar` → "ALIVE" no es solo el producto, también es identidad comercial. Por eso ALIVE va también en tienda.

### Tabla completa de huecos (nombres + logos + terrenos + fase)

| # | Hueco posible (qué podría hacer un copión) | Se cierra registrando | Fase / estado |
|---|---|---|---|
| 1 | Gorro ALIVE (prenda) | ALIVE nombre en prenda | Fase 1 |
| 2 | Logo de ALIVE copiado en un gorro | ALIVE logo en prenda | Fase 1 |
| 3 | Gorro/antifaz ALIVE terapéutico | ALIVE nombre en terapéutico | Fase 1 |
| 4 | Logo de ALIVE en versión terapéutica | ALIVE logo en terapéutico | Fase 1 |
| 5 | Tienda/ecommerce ALIVE (dominio gorroalive) | ALIVE nombre en tienda | Fase 1 |
| 6 | Tienda/ecommerce ALIVEAR | ALIVEAR nombre en tienda | Fase 1 |
| 7 | Logo de ALIVEAR copiado en la tienda | ALIVEAR logo en tienda | Fase 1 |
| 8 | Gorro ALIVEAR (prenda) | ALIVEAR nombre en prenda | Fase 2 |
| 9 | Gorro ALIVEAR terapéutico | ALIVEAR nombre en terapéutico | Fase 2 |
| 10 | Logo de ALIVEAR en el producto (caja/etiqueta/gorro) | ALIVEAR logo en prenda + terapéutico | Fase 2 · ◻️ solo si el logo de ALIVEAR va en el producto |
| 11 | Logo de ALIVE usado como marca de tienda de otro rubro | — (no se registra) | Abierto a propósito: riesgo remoto; lo cubre indirecto la fila 5 + filas 2/4 |

**Recuento:** filas 1-9 = 9 registros (✅) que cierran todos los huecos reales · fila 10 = +2 condicionales (◻️) · fila 11 = único gap, remoto, no se paga por cerrar.

---

# PARTE 13 — CIERRE FINAL (juzgado con el producto a la vista)

**Producto confirmado por imagen:** gorro de gel antimigraña, tela elástica + inserto de gel, usable como gorro 360°, antifaz y vincha. En el producto van estampados **el logo (planta estilizada) + la palabra ALIVE**. **ALIVEAR NO aparece en el producto** (vive en tienda/comunicación).

**Esto resuelve dos cosas:**
1. Es inequívocamente una **prenda textil para la cabeza** → **Clase 25 es el ancla, inatacable** (uso real).
2. Como el logo de ALIVEAR no va en el producto, la fila condicional 10 **se descarta** → **9 registros, cero huecos de diseño.**

**Advertencia crítica sobre Clase 10:** las 3 entradas de Clase 10 (terapéutico) son **defensivas y la pata más floja**: (a) encaje opinable —el agente puede decir "es 25 nomás"—, y (b) más expuestas a caducidad por falta de uso (no vendés un dispositivo médico clase 10). Registrables porque el producto se promociona "antimigraña" (claim terapéutico real), pero con redacción cuidada para no reivindicar "dispositivo médico" (evita roce con ANMAT). **Si hay que recortar por presupuesto, se recortan estas, nunca las de Clase 25/35.**

### Tabla final (9 registros)

| # | Si te copian… | Lo frena | Clase* | Solidez |
|---|---|---|---|---|
| 1 | Gorro/antifaz/vincha "ALIVE" | ALIVE nombre | 25 | 🟢 Roca (uso real) |
| 2 | El logo (planta) en un gorro | ALIVE logo | 25 | 🟢 Roca |
| 3 | Gorro "antimigraña/terapéutico" ALIVE | ALIVE nombre | 10 | 🟡 Defensiva |
| 4 | El logo en versión terapéutica | ALIVE logo | 10 | 🟡 Defensiva |
| 5 | Tienda/ecommerce ALIVE (gorroalive) | ALIVE nombre | 35 | 🟢 Sólida |
| 6 | Tienda/ecommerce ALIVEAR | ALIVEAR nombre | 35 | 🟢 Sólida |
| 7 | Logo de ALIVEAR en la tienda | ALIVEAR logo | 35 | 🟢 Sólida |
| 8 | Gorro ALIVEAR | ALIVEAR nombre | 25 | 🟢 Roca |
| 9 | Gorro "terapéutico" ALIVEAR | ALIVEAR nombre | 10 | 🟡 Defensiva |

\* Clases = hipótesis a confirmar por el agente. Excluido a propósito: logo de ALIVE en tienda (redundante) y logo de ALIVEAR en producto (no va en el gorro).

### Lo que se puede firmar / lo que no
- **SÍ:** con estos 9 concedidos, nadie vende un gorro ni abre una tienda usando ALIVE/ALIVEAR o el logo sin que el titular tenga con qué frenarlo (oposición, cese, daños, penal, aduana, takedown ML).
- **NO (queda fuera de control del plan):** (a) que ALIVE esté libre → lo define la búsqueda del agente, es lo único que puede volar el plan; (b) copia del gorro con otro nombre → la marca protege identidad, no el molde (producto genérico, habrá clones); (c) tranquilidad pasiva → el INPI 2026 no vigila de oficio, hace falta vigilancia + oposición a tiempo.

### Afinado final (aclaración del founder: "es un gorro con gel, NO fármaco ni utensilio médico")

Confirma que el producto es **una prenda textil** (el gel es una característica, no lo vuelve dispositivo médico). Consecuencias:
- **Clase 25 = casa real e inatacable.** No hay discusión de encaje.
- **Clase 10 = aún más marginal y frágil.** Sin producto médico que usar, ese registro es puramente defensivo y el más caducable; el agente puede rechazarlo como "esto es 25". El vector que cubriría es débil (un clon "terapéutico" también es un gorro → cae en Clase 25 igual).
- **ANMAT: descartado** (no es fármaco ni dispositivo). Solo cuidar lenguaje publicitario ("alivia/calma" ok; evitar "cura").

### CORRECCIÓN (PARTE 14) — el founder precisa: "es como vender una compresa"

La aclaración anterior llevó a subestimar la Clase 10. **Se corrige:** el producto es **una compresa de gel terapéutica usada como gorro** → tiene naturaleza **dual**.

- **"Dispositivo médico" (ANMAT) ≠ "Clase 10" (Niza).** La Clase 10 de Niza incluye **artículos terapéuticos humildes** — compresas, bolsas de gel frío/calor, almohadillas térmicas — no solo aparatos sofisticados/regulados. Fuente: clasificaciondeniza.com/clases/10 ; Alyafi IP (Class 10). Por eso un **gorro-compresa de gel encaja legítimamente en Clase 10**, aunque NO sea dispositivo médico ANMAT.
- **El producto es dual:** Clase 25 (gorro/prenda) **y** Clase 10 (compresa terapéutica de gel). Ambas correctas, ninguna es misfit.
- **Caducidad de Clase 10 se atenúa fuerte:** como SÍ se vende una compresa de gel terapéutica, hay **uso real** de un bien Clase 10 → no es registro vacío. (Vindica la conclusión —no el razonamiento— de la "Precisión B" discutida en chat.)

**Recomendación corregida sobre Clase 10:** para **ALIVE** (producto estrella), registrar en Clase 10 (nombre + logo) ya **NO es reflejo, es fundado** — es la segunda casa real del producto. ALIVEAR en Clase 10 sigue siendo opcional. El núcleo de 6 (25+35) sigue siendo base válida de arranque; sumar ALIVE en 10 es una mejora bien fundada. El agente confirma redacción y si va 25, 10 o ambas (ambas, bien fundado).

### PIVOTE FINAL (PARTE 15) — el founder precisa: "NO es para vestirse, es un gorro TERAPÉUTICO"

La clasificación de Niza se rige por la **FUNCIÓN PRINCIPAL** del producto. El founder define la función principal como **terapéutica** (alivio de migraña), no de vestir. Verificado:
- Los artículos con función terapéutica están **excluidos de la Clase 25** aunque se usen puestos — igual que vestuario de quirófano y calzado ortopédico van a **Clase 10**. Un gorro de alivio de migraña, por ser artículo terapéutico, **se clasifica en Clase 10**. (Fuentes: Easy Trademarks — Class 25 exclusiones; clasificaciondeniza.com/clases/10.)
- Regla: "si un artículo es terapéutico y usable, la clase depende de cuál función es la principal".

**Consecuencia — INVERSIÓN de la estrategia:**
- **Clase 10 (terapéutico) = PRINCIPAL para ALIVE** (la pieza maestra). Sin problema de caducidad: el uso real ES terapéutico.
- **Clase 25 (gorro/usable) = DEFENSIVA** (pasa de ancla a defensa; tapar a quien lo venda como "gorro").
- **Clase 35 (tienda) = sí.**

**Estrategia final:** ALIVE → Clase 10 (principal, nombre+logo) + Clase 25 (defensiva, nombre+logo) + Clase 35 (nombre). ALIVEAR → Clase 35 (nombre+logo) + Clase 25/10 (nombre, defensivo). La clase 10 deja de ser opcional: es la casa principal del producto. El agente confirma con la práctica del INPI; si ancla en 25 e ignora la 10, cuestionar (función principal = terapéutica).

### TRAMPA A EVITAR (PARTE 16) — defender Clase 10 ≠ etiquetar como dispositivo médico

Riesgo de caducidad de Clase 10 = **bajo** para este producto: venderlo (aunque se comunique como "gorro de gel para migraña") ya es **uso de un bien Clase 10**, porque es un artículo terapéutico por naturaleza; además la afinidad con el uso real lo respalda. **No hace falta "reforzar" el uso de Clase 10.**

**Trampa:** un consejo común es "etiquetá el producto como dispositivo de crioterapia/médico para defender Clase 10". **NO hacerlo.** Distinción clave:
- **Registrar en Clase 10 de Niza → NO dispara ANMAT** (la clase de marca es administrativa, ANMAT no la mira).
- **Etiquetar/publicitar como "dispositivo médico de crioterapia" → SÍ puede disparar ANMAT** (producto médico regulado).

Comunicar **"alivio / bienestar / uso terapéutico"** sostiene Clase 10 por la naturaleza del producto **y** es ANMAT-safe. Pregunta correcta al agente: cómo describir el producto para sostener Clase 10 **sin** que sea considerado dispositivo médico regulado por ANMAT.

### CIERRE (PARTE 17) — verificación final (mayo 2026) y vía rápida

**Repo:** confirmado que no existe módulo de marcas argentino; el plugin `ip-legal` es US-only y deriva jurisdicciones no-US. La clasificación Niza AR y la búsqueda INPI las hace la gestora.

**Externo (vigente a mayo 2026):** Res. INPI 583/25 operando (examen solo de absolutos; relativos por oposición de 30 días; concesión automática ~2 meses sin oposición). Argentina fuera de Madrid. Clasificación por función principal (terapéutico → Clase 10) sin cambios.

**Vía rápida (2 meses) — requisitos:** la solicitud NO debe (a) invocar prioridad extranjera, (b) usar "gestor de negocios", (c) cargar productos a mano → debe usar **términos predefinidos del nomenclador del INPI**. Beneficio colateral: usar términos del nomenclador (no "dispositivo médico" inventado) refuerza el ángulo ANMAT-safe de forma natural.

**Mensaje a la gestora: APROBADO.** Describe el producto como "gorro de uso terapéutico" (señal correcta para Clase 10 + decide 25/35), es ANMAT-safe ("no es dispositivo médico regulado por ANMAT"), pide clases + costo + pago único, conciso. Sin correcciones pendientes.

### MENSAJE FINAL ENVIADO (versión definitiva, el founder asume el gasto)

```
Hola, ¿cómo están? Mi nombre es Diógenes, quiero consultar por el registro de mi marca.

Tengo una marca llamada ALIVEAR, y dentro de ella mi producto principal, ALIVE: un gorro de gel frío/calor para el alivio de la migraña. Es un producto textil (con gel de agua insertado), de uso terapéutico / bienestar.

Me gustaría protegerlo así:

Fase 1 — ALIVE:
* ALIVE nombre + logo como producto de uso terapéutico / bienestar (alivio de migraña)
* ALIVE nombre + logo como gorro / artículo textil que se usa en la cabeza
* ALIVE nombre en tienda / ecommerce

Fase 2 — ALIVEAR:
* ALIVEAR nombre + logo en tienda / ecommerce
* ALIVEAR nombre como gorro y como producto de uso terapéutico

¿Me podrías indicar en qué clases corresponde, cómo conviene encararlo, el costo y si es un pago único o hay costos posteriores? Abierto a tu recomendación.

Aclaración: no es un dispositivo médico regulado por ANMAT, es un producto de uso terapéutico / bienestar.

¡Gracias!
```

Cubre las tres clases del producto de forma explícita: terapéutico (10, principal), gorro/textil (25, defensiva), tienda (35). Pendiente del lado del founder: (1) que la búsqueda de antecedentes dé limpia, (2) activar vigilancia del Boletín post-registro.

### PARTE 18 — BÚSQUEDA DE ANTECEDENTES REAL + estructura óptima

El founder corrió la búsqueda en la base del INPI. Conflictos relevantes encontrados:
- **ALIVE (denominativa exacta) — CONCEDIDA — Clase 35** (Beatriz Luis Guido, venc. 2031; "Excepto A…" en protección). → bloquea/expone ALIVE en 35.
- **ALIVIAR — CONCEDIDA — Clase 35** (Milton Muñoz) y **ALIVIAR SALUD — CONCEDIDA — Clase 10** (Aliviar S.A.S.). → ALIVIAR ≈ ALIVEAR (una vocal); amenaza ALIVEAR en 35 y 10.
- **Clase 25 (gorro): sin conflicto directo de ALIVE/ALIVEAR** (solo "ALOUD ALIVE & PROUD", composite). → terreno limpio.
- Ruido en otras industrias (ALIVIRA salud animal cl.5/35, ALIVIS cl.5, ALIV cl.35, ALIVERA cl.35) — no son la pelea del founder.
- A favor: ALIVEAR es **inventada (marca fuerte)**; ALIVIAR es **palabra común (marca débil)** + uso previo del founder.

**Estructura óptima (5 registros):**

| # | Marca | Tipo | Clase | Riesgo |
|---|---|---|---|---|
| 1 | ALIVE | Denominativa | 25 (gorro) | 🟢 limpio — roca |
| 2 | Logo ALIVE | Figurativa | 25 | 🟢 limpio — diferenciador clave |
| 3 | ALIVEAR | Denominativa | 25 (gorro) | 🟢-🟡 casi limpio |
| 4 | ALIVE | Mixta (nombre+logo) | 10 (terapéutico) | 🟠 contestado (ALIVIAR SALUD) |
| 5 | ALIVEAR | Mixta (nombre+logo) | 35 (ecommerce) | 🟠 contestado (ALIVE + ALIVIAR) |

**Mapa de fricción:** Clase 10 (ALIVE) ← ALIVIAR SALUD; Clase 35 (ALIVEAR) ← ALIVE exacta + ALIVIAR (la más caliente). En clases contestadas: ir **mixta** (el logo diferencia). El logo es el activo más defendible contra todo el clan ALIV-.

**Orden de fuego:** primero las 3 limpias de Clase 25 (mismo día, prioridad); luego las 2 contestadas con mixta. Moat real e inatacable = ALIVE + logo en gorro (25). Pregunta decisiva a la gestora: ¿ALIVIAR (débil, común) bloquea ALIVEAR (inventada, en uso)? Confusión fina = su llamada.

### PARTE 19 — Cotización de la gestora + clase 5 verificada + contrapropuesta

**Cotización recibida:** $225.500 por clase + $95.500 (título) por clase, + IVA. Propuso registrar AMBAS marcas en clases **5, 10, 25 y 35** = 8 registros ≈ $2,57M. Incluye custodia/vigilancia 10 años. Es enfoque "todo a todo", no estratégico.

**Clase 5 — VERIFICADA como misfit:** Niza clase 5 = medicamentos/farmacéuticos + apósitos medicinales (consumibles con sustancia activa). El producto es una **compresa de gel reutilizable = dispositivo = Clase 10**, no clase 5. "Geles antiinflamatorios" (clase 5) = medicina con principio activo; "compresas medicinales" = apósitos medicados de un solo uso. El founder no vende ninguno → clase 5 = goods que no vende → caducable + costo inútil + contradice "no es medicamento". Fuentes: WIPO Niza clase 5; clasificaciondeniza.com/clases/10.

**Contrapropuesta quirúrgica (4 registros, ~mitad del costo):**
- ALIVE (nombre y logo) → clase 10 (compresa de gel reutilizable / dispositivo terapéutico) + clase 25 (gorros/indumentaria)
- ALIVEAR (nombre y logo) → clase 25 (gorros/indumentaria) + clase 35 (tienda/ecommerce)

Preguntas a la gestora: (1) ¿hizo búsqueda de antecedentes? (ALIVE en 35 ocupada; ALIVIAR/ALIVIAR SALUD); (2) ¿el precio por clase incluye logo o va aparte?; (3) costo total con esta estructura. Excluido: clase 5 (misfit), ALIVE/35 (ocupada por Beatriz), ALIVEAR/10 (alto choque con ALIVIAR SALUD).

**Estructura recomendada:**

🟢 **Núcleo sólido — 6 registros** (uso real / objetivo claro, sin exposición a caducidad):
1. ALIVE nombre — 25 · 2. ALIVE logo — 25 · 3. ALIVE nombre — 35 · 4. ALIVEAR nombre — 35 · 5. ALIVEAR logo — 35 · 6. ALIVEAR nombre — 25

🟡 **Anillo defensivo — 3 registros (opcional, lo primero que se recorta):**
7. ALIVE nombre — 10 · 8. ALIVE logo — 10 · 9. ALIVEAR nombre — 10

**Firma realista:** con el núcleo de 6 registrado y la búsqueda limpia, nadie vende un gorro ni abre una tienda con el nombre/logo del founder sin que tenga con qué frenarlo. El anillo de Clase 10 es extra, no requisito.

### Matriz final (✅ = registrar · ◻️ = condicional · — = innecesario)

| Activo | Terapéutico | Prenda (gorro) | Tienda / ecommerce |
|---|:---:|:---:|:---:|
| ALIVE — nombre | ✅ | ✅ | ✅ |
| ALIVE — logo | ✅ | ✅ | — |
| ALIVEAR — nombre | ✅ | ✅ | ✅ |
| ALIVEAR — logo | ◻️ | ◻️ | ✅ |

**= 9 registros** (los ✅) cierran los 6 huecos.

### Decisiones de eficiencia (qué se deja afuera y por qué NO es hueco)
- **Logo de ALIVE en tienda → no.** El nombre ALIVE ya está en tienda y el logo está en los dos terrenos del producto. Que alguien use el dibujo exacto como marca de una tienda de otro rubro es escenario remoto; no justifica el registro.
- **Logo de ALIVEAR en el producto → ◻️ condicional:** registrarlo en terapéutico y prenda **solo si** el logo de ALIVEAR va en la caja/etiqueta/gorro. Si vive solo en la tienda/web, no hace falta (no hay nada que copiar ahí).

### Secuencia (respeta prioridad ALIVE + presupuesto)
- **Fase 1 (urgente):** ALIVE nombre+logo (terapéutico + prenda) · ALIVE nombre (tienda) · ALIVEAR nombre+logo (tienda). → Blinda todo lo realmente copiable.
- **Fase 2 (cierre total):** ALIVEAR nombre (terapéutico + prenda) [+ logo de ALIVEAR ahí si va en el producto]. → Cero huecos absolutos.

**Operativo:** presentar toda la línea ALIVE el mismo día (first-to-file, prioridad por día y hora). Búsqueda de antecedentes previa obligatoria (incluida figurativa por Clasificación de Viena para los logos). Titular: persona física (responsable inscripto).
