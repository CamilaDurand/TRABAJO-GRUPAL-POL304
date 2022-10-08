# TRABAJO-GRUPAL-POL304
# Integrantes :relaxed:	  :
- Camila Durand 
- Héctor Delgado
- Carlos Chávarri

# Tema: Migraciones y Variable Dependiente :globe_with_meridians:

Las migraciones han sido desde la antigüedad uno de los fenómenos de mayores resultados y por ende más estudiados.  Hoy  sin duda alguna hay patrones históricos que se mantienen, pero por lo general la globalización y la modernidad han alterado en gran manera las dinámicas de movilidad social. Bajo esta perspectiva se buscan incluir en nuestro análisis factores comúnmente incluidos como cuestiones económicas pero también factores muy característicos del siglo XXI y la modernidad. Hoy existen variables como el impacto del cambio climático y/o el acceso a servicios básicos tales como el internet que pueden influir directamente en el incremento o reducción de migraciones. Este trabajo parte desde la curiosidad académica y una necesidad práctica de responder efectivamente a los flujos migratorios cada vez mayores, mediante la identificación de principales factores que lo provocan y con ello se busca incidir en un futuro próximo en la toma de mejores decisiones que reduzcan la vulnerabilidad de las personas y los estados. Con este propósito es que el presente trabajo indaga en los factores que influyen en la migración, su evolución y tendencias a nivel global a partir de la selección del año 2019 como base de la investigación, por razones metodológicas.
                
        
        - VD1: Net migration (migrant(s)/1,000 population)
        
                Base de Datos: CIA (The World Fact Book) (Netmigration2022.csv
                
                
        - VD2: Número de Migrantes (Emigranstes Totales)
               Base de Datos: Datos Macro ( Emigración) (EMIGRANTES2019.csv)   
               
               
        
# Responsable: Camila Durand. 	:flying_saucer:

Variable 1: Impacto del cambio climatico

Base de datos: Germanwatch (GLOBAL CLIMATE RISK INDEX) (climaterisk-index - 2019.csv)

Justificacion: El cambio climático es una de las problemáticas más grandes en el contexto actual, la falta de respuestas adecuadas para mitigar sus efectos ha causado innumerables pérdidas en términos materiales y vidas humanas. Es por ello que hoy el cambio climático se ha convertido en una variable de gran importancia que ha producido un incremento en el desplazamiento forzado. De hecho es cada vez más frecuente que entre la academia se discuta el concepto de refugiado climático y aunque aún no hay una marco jurídico que reconozca ello, es innegable  la enorme repercusión de los efectos del cambio climático como un factor que impulsa y acentúa la migración  en poblaciones que buscan sobrevivir.

Variable 2: Desempleo (% de la poblacion activa total)

Base de datos: Banco Mundial (desempleo-2019.csv)

Justificacion:Uno de los factores que históricamente más han influido en los flujos migratorios son las situaciones de subempleo en el país de origen. Son muchos los individuos que emigran de sus hogares al padecer continuos periodos de desempleo, en búsqueda de mayores oportunidades de ellos y sus familias. Particularmente hoy este es un factor primordial al considerar para ver el aumento de las migraciones, dadas las condiciones de emayor movilidad social gracias a las facilidades tecnológicas en el área de transporte.

Variable 3: Aceso a servicios publicos

Base de datos: fragilestatesindex (publicservices-2019.csv)

Justificacion: La vida de muchas personas son seriamente afectadas por las condiciones que encuentran en sus países, estas dependen en gran medida del acceso que tengan a los servicios públicos tales como salud, educación, agua y saneamiento, infraestructura de transporte, electricidad y energía, y conectividad. Consideramos el estado de dichos servicios básicos como factores determinantes para la migración pues el encontrarlos o no en sus respectivos países pues incrementar o reducir la migración respectivamente. 


# Responsable: Carlos Ch. 	:flying_saucer:
 
 Variable 4:  Uso del internet (% población)
 
 Base de Datos: World Bank (DataBank) (usodelinternet.csv)
 
 Justificación:  El internet ha pasado a ser considerado un casi un derecho debido a su importancia para el desarrollo de la vida de las personas. En ese sentido, 
 se considera que la ausencia o problemas de acceso a este servicio por parte de la población podría ayudar a explicar un aumento en la probabilidad de abandoanr 
 el país. 
 
 Variable 5: Población sin electricidad, (# personas)

Base de Datos: Our world in Data (withoutelec.csv)

Justificación: La falta de acceso a electricidad, bajo la misma lógica de la falta de acceso al internete, puede representar un desincentivo para permanecer en el país y un incentivo para buscar otras oportunidades fuera del mismo. También está asociado a la posibilidad de generar ingresos económicos que permitan la subsitencia. Además de un aumento del costo de vida, pues se tienen que recurrir a otros medios más costosos para dimensiones básicas de la vida. 

Variable 6: Índice de Democracia

Base de datos: The Economist (Wikipedia) (ID2019.csv)

Justificación:  Este indicador que está sujeto a evaluación y posible cambios. Sin embargo, parte del supuesto en el cual las limitaciones en términos de libertades, falta de tolerancia política, persecución por razones étnicas, religiosas u otras, tendrían importantes efectos en las posibilidades de desarrollo de una ciudadanía, por tanto, implicaría un aumento sobre la intención de abandonar un país determinado.


# Responsable: Héctor Delgado. 	:flying_saucer:

Variable 7: Índice de Percepción de la Corrupción

Base de datos: Transparency International (Corrupción-2019)

Justificación: Un país con niveles de corrupción alto en el sector público trae consigo inestabilidad y un requebrajamiento en las instituciones de un país, algo muy cercano a la realidad peruana. En ese sentido, evaluar como es que la corrupción estatal tiene consecuencias directas en la migración de personas recae en el factor de inestabilidad política que genera tener altos indices de corrupción por lo que este indice califica a 180 países y territorios en función de los niveles percibidos de corrupción en el sector público

Variable 8: Indicador de Derechos Humanos y Estado de Derecho

Base de datos: Foro de la Paz (DDHH.csv)

Justificación: Este indicador analiza si se protegen los derechos humanos fundamentales y si se respetan las libertades civiles individuales. Consideramos que si un país no respeta los derechos basicos de la población (incluyendo minorias sociales) existira un mayor numero de migrantes.

Variable 9: Indice de la Paz Global

Base de datos: Vision of Humanity (CPI2019-1.xlsx - CPI2019.csv)

Justificación: Tener paz en un país es una pieza clave para que la migración no sea acelerada a niveles descontrolados debido a que un Estado en conflicto tiende a ser menos atractivo para sus ciudadanos. Es por ello que este indicador que clasifica a 163 estados y territorios independientes según su nivel de paz.
        
# SEGUNDA ENTREGA :globe_with_meridians:
- Rmd con la limpieza y unificación de las bases de datos (idealmente, ustedes jalan en R las bases de datos sucias, limpian, unifican y exportan la base de datos final)
  - partes individuales, avance con union d elas 3 variables de cado uno
   - camila: merge-data-camila.rmd
   - hector: data_hector.rmd
   - carlos: base_carlos.rmd
    
- Base de datos unificada: base limpia con sus variable independientes y la variable dependiente del grupo 
    - DataGRUPAL.csv
    - DATAUNIFICADA.Rmd
 

- Rmd y HTML con tres regresiones: debe haber un HTML en el repo con tres regresiones. Cada persona del grupo hace una regresión con las variables independientes que llevó al grupo en la primera entrega.
  - REGRESIONES.Rmd
  - REGRESIONES.html
