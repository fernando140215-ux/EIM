# Documentación Técnica: Algoritmo Diagnóstico de Errores Innatos del Metabolismo (EIM)
## 1. Fundamento del Algoritmo
El algoritmo diagnóstico se basa en el sistema de clasificación de Prietsch et al. (2002) que divide los EIM en 5
categorías según su presentación bioquímica: intoxicación, déficit energético, trastornos de moléculas
complejas, neurotransmisores y disfunción orgánica.[1]
## 2. Flujograma Diagnóstico Visual
```
┌───────────────────────────────────────────────────────────────────────────
│ PACIENTE CON SOSPECHA DE EIM │
│ (Letargia, Vómitos, Convulsiones) │
└────────────────────────────────────┬──────────────────────────────────────
│
┌────────────────┴────────────────┐
│ │
┌─────▼─────┐ ┌─────▼─────┐
│OLOR ANORMAL│ │CRISIS CON │
│ (Ref 2,5) │ │ AYUNO │
│ BANDERA │ │ (Ref 4,5) │
│ ROJA │ │ BANDERA │
└───────────┘ │ ROJA │
└───────────┘
│
┌────────────────┴────────────────┐
│ EVALUACIÓN BIOQUÍMICA │
└────────────────┬────────────────┘
│
┌────────────────────────────┼────────────────────────────┐
│ │ │
┌───▼────┐ ┌───▼────┐ ┌───▼────┐
│GLUCOSA │ │ACIDOSIS│ │ NH3 │
│ <60 │ │METAB. │ │ >100 │
│mg/dL │ │pH<7.30 │ │μmol/L │
└───┬────┘ │HCO3<18 │ └───┬────┘
│ └───┬────┘ │
│ │ │
┌────▼────┐ │ ┌────▼─────┐
│CETONAS? │ │ │NH3 >200? │
└────┬────┘ │ └────┬─────┘
│ │ │
┌────┴────┐ │ ┌────▼─────┐
│ │ │ │ SÍ │
ALTO/POS BAJO/NEG │ └────┬─────┘
│ │ │ │
│ ┌────▼────────┐ │ ┌───────▼──────┐
│ │EDAD <3 años?│ │ │DEFECTO CICLO │
│ └────┬────────┘ │ │ UREA │
│ │ │ │ OTC, CPS1 │
│ ┌────▼────────┐ │ │ EMERGENCIA │
│ │ SÍ │ │ │ Score: 98 │
│ └────┬────────┘ │ │ (Ref 3) │
│ │ │ ├──────────────┤
│ ┌────▼─────────────┐ │ │• SUSPENDER │
│ │DEFECTO BETA- │ │ │ PROTEÍNAS │
│ │ OXIDACIÓN │ │ │• Benzoato IV │
│ │ MCAD, VLCAD │ │ │• HEMODIÁLISIS│
│ │ EMERGENCIA │ │ │ si >500 │
│ │ Score: 98 │ │ └──────────────┘
│ │ (Ref 4,5) │ │
│ ├──────────────────┤ │
│ │• NUNCA AYUNAR │ │
│ │• Glucosa IV │ │
│ │• Acilcarnitinas │ │
│ │• L-carnitina IV │ │
│ └──────────────────┘ │
│ │
┌──▼────────┐ │
│LACTATO >2.5│ │
│ mmol/L? │ │
└──┬─────┬───┘ │
│ │ │
SÍ NO │
│ │ ┌────▼─────┐
│ ┌──▼──────────┐ │ANION GAP │
│ │GLUCOGENOSIS │ │ >16? │
│ │ TIPO I │ └────┬─────┘
│ │(von Gierke) │ │
│ │ Alta │ ┌────┴────┐
│ │ Score: 90 │ │ SÍ │
│ │ (Ref 7) │ └────┬────┘
│ ├─────────────┤ │
│ │• Glucosa IV │ ┌────▼────────┐
│ │• Almidón │ │LACTATO >5 │
│ │ crudo 3-4h │ │ mmol/L? │
│ └─────────────┘ └────┬────┬───┘
│ │ │
┌──▼────────────────┐ SÍ NO
│DEFECTO GLUCO- │ │ │
│ NEOGÉNESIS │ │ │
│F-1,6-bifosfatasa │ ┌────▼────────────┐
│ URGENCIA │ │ACIDOSIS LÁCTICA │
│ Score: 95 │ │ MITOCONDRIAL │
│ (Ref 1) │ │ CRÍTICO │
├───────────────────┤ │ Score: 95 │
│• Glucosa IV │ │ (Ref 6) │
│ 10-15 mg/kg/min │ ├─────────────────┤
│• Lactato/Piruvato │ │• NO bicarbonato │
└───────────────────┘ │• CoQ10 │
│• L-carnitina │
│• Tiamina │
└─────────────────┘
│
┌────▼──────────┐
│CETONAS ALTAS? │
└────┬──────────┘
│
┌────▼──────────┐
│ SÍ │
└────┬──────────┘
│
┌─────────▼─────────┐
│ACIDEMIA ORGÁNICA │
│ MMA, PA │
│ EMERGENCIA │
│ Score: 97 │
│ (Ref 1,2) │
├───────────────────┤
│• SUSPENDER │
│ PROTEÍNAS │
│• Glucosa+Lípidos │
│• L-carnitina IV │
│• Hidroxicobalamina│
└───────────────────┘
┌─────────────────────────────────────────────────────────────────┐
│ EVALUACIÓN COMPLEMENTARIA │
└─────────────────────────────────────────────────────────────────┘
│
┌────▼────┐
│CPK >1000│
│ U/L? │
└────┬────┘
│
┌────▼────┐
│ SÍ │
└────┬────┘
│
┌─────────▼─────────┐
│MIOPATÍA METABÓLICA│
│ Alta │
│ Score: 85 │
│ (Ref 8) │
├───────────────────┤
│• HIDRATACIÓN │
│• Acilcarnitinas │
│• CPK seriada │
└───────────────────┘
┌──────────────────────────────────────────────────────────────────┐
│ LEYENDA DE SEVERIDAD │
├──────────────────────────────────────────────────────────────────┤
│ [EMERGENCIA/CRÍTICO] Score 95-100: Riesgo vital inmediato │
│ [URGENCIA/Alta] Score 85-94: Riesgo secuelas permanentes │
│ [Moderada] Score <85: Seguimiento estrecho │
└──────────────────────────────────────────────────────────────────┘
┌──────────────────────────────────────────────────────────────────┐
│ PRUEBAS CONFIRMATORIAS │
├──────────────────────────────────────────────────────────────────┤
│ • Acilcarnitinas (MS/MS): Para FAODs │
│ • Ácidos orgánicos (GC-MS): Para acidemias orgánicas │
│ • Aminoácidos plasma: Para ciclo urea │
│ • Lactato/Piruvato: Relación >20 sugiere mitocondrial │
└──────────────────────────────────────────────────────────────────┘
```
## 2.1 Flujograma Diagnóstico Detallado
### 2.1 Banderas Rojas Iniciales
**Olor Anormal**
- Indicador patognomónico de ciertos EIM
- Acidemia isovalérica: olor a "pies sudados"[5]
- Enfermedad de orina con olor a jarabe de arce (MSUD): olor dulce característico
- Referencia: Burton (1998) - banderas rojas clínicas en lactantes[2]
**Crisis con Ayuno**
- Sugiere defecto de beta-oxidación de ácidos grasos
- Presentación típica en menores de 3 años
- Referencia: Marsden et al. (2021) - impacto del tamizaje neonatal en FAODs[4]
### 2.2 Hipoglucemia (Glucosa <60 mg/dL)
#### Rama A: Hipoglucemia CON Cetonas (Cetosis positiva/alta)
**Con Lactato Elevado (>2.5 mmol/L)**
- Diagnóstico: Defecto de Gluconeogénesis (F-1,6-bifosfatasa)
- Puntuación: 95 (URGENCIA)
- Fundamento: La deficiencia de F-1,6-bifosfatasa causa hipoglucemia cetósica con lactato elevado por
acumulación de precursores gluconeogénicos
- Manejo: Glucosa IV 10-15 mg/kg/min, evitar ayuno
- Referencia: Prietsch et al. (2002)[1]
**Sin Lactato Elevado**
- Diagnóstico: Glucogenosis Tipo I (Enfermedad de von Gierke)
- Puntuación: 90 (Alta)
- Fundamento: Deficiencia de glucosa-6-fosfatasa causa hipoglucemia cetósica, hepatomegalia masiva, lactato
elevado, hiperuricemia
- Valor normal lactato: <2.5 mmol/L[6]
- Manejo: Almidón de maíz crudo cada 3-4 horas, evitar ayuno >3h
- Referencia: Rake et al. (2002) - estudio multicéntrico europeo[7]
#### Rama B: Hipoglucemia SIN Cetonas (Cetosis negativa/baja) + Edad <3 años
**Diagnóstico: Defecto de Beta-Oxidación de Ácidos Grasos**
- Subtipos: MCAD (Acil-CoA deshidrogenasa de cadena media), VLCAD (cadena muy larga)
- Puntuación: 98 (EMERGENCIA)
- Fundamento: La beta-oxidación es la vía de producción de cuerpos cetónicos. Su defecto causa hipoglucemia
HIPOCETÓSICA (sin cetonas)
- Edad crítica: <3 años porque tienen menor capacidad de gluconeogénesis y mayor dependencia de beta-
oxidación durante ayuno
- Crisis típica: Desencadenada por ayuno, infecciones, vacunas
- Manejo: **NUNCA AYUNAR**, glucosa IV continua, acilcarnitinas URGENTE, L-carnitina IV 100 mg/kg
- Referencias:
- Marsden et al. (2021)[4]
- Merritt et al. (2020) - revisión completa sobre FAODs[5]
### 2.3 Acidosis Metabólica (pH <7.30 o HCO3 <18 mEq/L)
**Valores normales:**
- pH: 7.35-7.45
- Bicarbonato (HCO3): 22-28 mEq/L
- Anion Gap: 8-16 mEq/L
- Fórmula Anion Gap: Na+ - (Cl- + HCO3-)
#### Con Anion Gap Elevado (>16 mEq/L)
**Rama A: Con Lactato muy Elevado (>5 mmol/L)**
- Diagnóstico: Acidosis Láctica de origen Mitocondrial
- Puntuación: 95 (CRÍTICO)
- Fundamento: Disfunción de la cadena respiratoria mitocondrial causa acumulación de lactato por metabolismo
anaeróbico
- Relación Lactato/Piruvato >20 sugiere defecto mitocondrial[6]
- **IMPORTANTE: Evitar bicarbonato** - empeora acidosis intracelular por aumento CO2
- Manejo: Bicarbonato cauteloso solo si pH <7.0, CoQ10 (100-400 mg/día), L-carnitina, Tiamina (vitamina B1)
- Referencia: Chinnery & Turnbull (1999) - Lancet[6]
**Rama B: Con Cetonas Elevadas**
- Diagnóstico: Acidemia Orgánica (Aciduria Metilmalónica-MMA, Acidemia Propiónica-PA)
- Puntuación: 97 (EMERGENCIA)
- Fundamento: Defecto en catabolismo de aminoácidos (leucina, isoleucina, valina, metionina) causa
acumulación de ácidos orgánicos
- Presentación: Acidosis con anion gap alto + cetonas + olor anormal
- Manejo urgente:
- **SUSPENDER PROTEÍNAS** (fuente de aminoácidos precursores)
- Glucosa + lípidos IV (calorías sin proteína)
- L-carnitina IV (facilita excreción de ácidos orgánicos)
- Hidroxicobalamina (vitamina B12 en altas dosis para cofactor)
- Pruebas: Ácidos orgánicos en orina por GC-MS
- Referencia: Burton (1998)[2], Prietsch et al. (2002)[1]
### 2.4 Hiperamonemia
**Valores normales NH3:**
- Neonatos: 45-150 μmol/L
- Niños y adultos: 20-100 μmol/L
**Interpretación según Häberle et al. (2012):[3]**
- NH3 >100 μmol/L: ANORMAL
- NH3 >200 μmol/L: EMERGENCIA
- NH3 >500 μmol/L: Indicación de HEMODIÁLISIS
**Diagnóstico: Defecto del Ciclo de Urea**
- Subtipos principales: OTC (Ornitina transcarbamilasa), CPS1 (Carbamil fosfato sintetasa 1)
- Puntuación: 98 (EMERGENCIA)
- Fundamento: Defecto en conversión de amonio (tóxico) a urea (excretable)
- Manifestaciones: Letargia, vómitos, convulsiones, encefalopatía
- Manejo urgente:
- **SUSPENDER PROTEÍNAS** (fuente de amonio)
- Benzoato sódico IV (vía alterna de excreción de nitrógeno)
- Fenilbutirato sódico
- **HEMODIÁLISIS** si NH3 >500 μmol/L (único método efectivo de eliminación rápida)
- Arginina IV (cofactor para ciclo de urea)
- Pruebas: Aminoácidos en plasma (citrulina baja en CPS1/OTC)
- Referencia: Häberle et al. (2012) - Guías internacionales[3]
### 2.5 CPK Elevada (>1000 U/L)
**Diagnóstico: Miopatía Metabólica**
- Causas: Defectos de beta-oxidación, glucogenosis tipo V (McArdle), tipo II (Pompe), defectos mitocondriales
- Puntuación: 85 (Alta)
- Fundamento: Músculo esquelético tiene alta demanda energética; defectos metabólicos causan rabdomiólisis
- Presentación: Mialgias, debilidad, orina oscura (mioglobinuria)
- Manejo:
- **HIDRATACIÓN agresiva** (prevenir insuficiencia renal por mioglobinuria)
- Acilcarnitinas (descartar FAOD)
- CPK seriada
- Referencia: Kishnani et al. (2006) - Pompe disease[8]
## 3. Valores de Referencia Completos
### 3.1 Gasometría y Electrolitos
- pH arterial: 7.35-7.45
- Bicarbonato (HCO3): 22-28 mEq/L
- Sodio (Na+): 135-145 mEq/L
- Cloro (Cl-): 95-105 mEq/L
- Anion Gap: 8-16 mEq/L (calculado)
### 3.2 Metabolitos Clave
- Glucosa: 70-100 mg/dL
- Lactato: <2.5 mmol/L (normal), >5 mmol/L (crítico)[6]
- Amonio (NH3): 20-100 μmol/L
- CPK: <200 U/L (normal), >1000 U/L (significativo)
### 3.3 Relaciones Diagnósticas
- Lactato/Piruvato: <20 (normal), >20 (sugiere mitocondrial)[6]
- Hipoglucemia con cetonas: Glucogenosis, déficit gluconeogénesis
- Hipoglucemia sin cetonas: Déficit beta-oxidación (FAOD)
## 4. Pruebas Confirmatorias
### 4.1 Primera Línea (Urgentes)
- **Acilcarnitinas** por espectrometría de masas (MS/MS): Para FAODs
- **Ácidos orgánicos** en orina por GC-MS: Para acidemias orgánicas
- **Aminoácidos** en plasma: Para defectos ciclo urea, aminoacidopatías
- **Lactato y Piruvato**: Relación para mitocondriopatías
### 4.2 Segunda Línea
- Enzimática en fibroblastos
- Secuenciación de DNA mitocondrial
- Panel genético de EIM
- Biopsia muscular (histoquímica, cadena respiratoria)
## 5. Sistema de Puntuación y Priorización
El algoritmo utiliza un sistema de scoring (0-100) basado en:
- Severidad clínica
- Especificidad bioquímica
- Urgencia terapéutica
- Evidencia en literatura
**Categorías:**
- 95-100: EMERGENCIA/CRÍTICO (riesgo vital inmediato)
- 85-94: URGENCIA/Alta (riesgo de secuelas permanentes)
- <85: Moderada
## 6. Limitaciones y Advertencias
1. **No reemplaza juicio clínico**: Es una herramienta de apoyo educativo
2. **Valores de corte**: Son orientativos; variar según laboratorio y edad
3. **Presentaciones atípicas**: Muchos EIM tienen fenotipos variables
4. **Diagnósticos no incluidos**: El algoritmo cubre principales categorías pero no todos los EIM
5. **Siempre considerar**: Historia familiar, consanguinidad, tamizaje neonatal
## 7. Referencias Bibliográficas Completas
[1] Prietsch V, Lindner M, Zschocke J, et al. Emergency management of inherited metabolic diseases. J Inherit
Metab Dis. 2002;25(7):531-546. doi:10.1023/A:1022040422590
[2] Burton BK. Inborn errors of metabolism in infancy: a guide to diagnosis. Pediatrics. 1998;102(6):e69.
doi:10.1542/peds.102.6.e69
[3] Häberle J, Boddaert N, Burlina A, et al. Guidelines for the diagnosis and management of urea cycle disorders.
Orphanet J Rare Dis. 2012;7:32. doi:10.1186/1750-1172-7-32
[4] Marsden D, Bedrosian CL, Vockley J. Impact of newborn screening on fatty acid oxidation disorders. Genet
Med. 2021;23(3):423-431. doi:10.1038/s41436-020-01070-0
[5] Merritt JL, MacLeod E, Jurecka A, Hainline B. Clinical manifestations and management of fatty acid oxidation
disorders. Rev Endocr Metab Disord. 2020;21(4):475-493. doi:10.1007/s11154-020-09568-3
[6] Chinnery PF, Turnbull DM. Mitochondrial DNA and disease. Lancet. 1999;354(Suppl 1):SI17-21.
doi:10.1016/S0140-6736(99)90244-1
[7] Rake JP, Visser G, Labrune P, et al. Glycogen storage disease type I: diagnosis, management, clinical course
and outcome. Eur J Pediatr. 2002;161(Suppl 1):S20-S34. doi:10.1007/s00431-002-0999-4
[8] Kishnani PS, Steiner RD, Bali D, et al. Pompe disease diagnosis and management guideline. Genet Med.
2006;8(5):267-288. doi:10.1097/01.gim.0000218152.87434.f3
## 8. Actualizaciones y Mejoras Futuras
- Incorporar algoritmos de machine learning para scoring
- Añadir más EIM (aminoacidopatías, peroxisomales, lisosomales)
- Integración con bases de datos genómicas
- Módulo de interpretación de acilcarnitinas
- Calculadora de fórmulas especiales y restricción proteica
---
**Versión:** 1.0
**Fecha:** Octubre 2024
**Autores:** Basado en guías internacionales de EIM
**Propósito:** Educativo - Soporte diagnóstico inicial
