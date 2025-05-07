# projecte_tarracogol
# 1.Tema/motivació.
 
## El nostre objectiu

El projecte TARRACOGOL neix amb la finalitat de posar en valor els espais esportius, fomentar-ne l’ús i facilitar-ne l’accés a tota la ciutadania.

## Què fem?

Documentem els camps de futbol de Tarragona amb informació detallada, sobre la superfície de joc i localització geogràfica. A més, creem una plataforma visual i interactiva que permet conèixer els equips locals, els espais on entrenen i competeixen. En un futur proper, també promoverem iniciatives per impulsar el futbol base i les activitats esportives als barris, fomentant l'ús d'aquestes instal·lacions i fent tornejos entre barris en un futur.

## Per què és important?

Els camps de futbol són espais clau per a la cohesió social, la salut i l’educació en valors com l’esforç i el treball en equip. Donar-los visibilitat contribueix a reforçar la identitat dels barris, promoure l’activitat física i reconèixer la tasca dels clubs i entitats locals que mantenen viva la passió pel futbol a Tarragona.

## La història darrera del nostre emblema.

La llegenda de TarracoGol: un pont entre Roma i el futbol.
Diu la llegenda que, a l'antiga ciutat de Tàrraco, capital romana de Hispània, els ciutadans no només admiraven les curses de quadrigues i els combats de gladiadors, sinó que també jugaven una forma primitiva de futbol als camps propers a l’amfiteatre.

Segles més tard, renaixent d’aquest esperit, neix TarracoGol: una plataforma que uneix el patrimoni històric amb la passió moderna pel futbol. El logo simbolitza exactament això:

L’arc de triomf daurat: símbol de persistència, memòria i identitat.
La pilota blanca i negra: el futbol com a llenguatge universal.
Les lletres "TarracoGol": amb les barres grogues i vermelles de la senyera catalana.
L’escut inferior: un segell de comunitat, arrelament i passió.
TarracoGol no és només una web, és un homenatge a la història, al joc i al territori.


# 2.Dades/continguts.
 
Les dades utilitzades en el projecte provenen de diverses fonts:
Dades esportives: Estadístiques de partits, gols i equips extrets de la Federació Catalana de Futbol, diaris locals o arxius històrics.
Informació geogràfica: Ubicacions exactes dels camps de futbol obtingudes mitjançant OpenStreetMap o API de Google Maps.
Imatges i textos: Fotografies antigues de l’Arxiu Municipal de Tarragona, articles periodístics i mapes històrics digitalitzats.

# 3.Estructura de la Web
   
La web es divideix en cinc seccions: INICI, QUI SOM, PROJECTE, MAPA i CONTACTE. Aquesta estructura permet una navegació intuïtiva. En l’apartat PROJECTE, s’ha optat per mostrar les imatges dels camps com a targetes interactives que giren en fer clic, mostrant al darrere informació rellevant de cada espai. El MAPA incorpora la localització geogràfica dels camps.

L'estructura segueix una jerarquia clara:

-Pàgina d'Inici: Presentació del projecte amb secció hero

-Membres: Equip de treball amb foto i descripció

-Projecte: Detalls tècnics de la investigació

-Mapa: Visualització interactiva dels nostres resultats

-Contacte: Formulari per col·laboracions

Elements utilitzats:

-Flexbox per a layouts responsius

-W3.CSS per a components UI

-Cards per a presentació de membres

-Mapa interactiu amb Leaflet

# 4.Web Responsive

La adaptabilitat a diferents dispositius ha estat una prioritat en el nostre desenvolupament. Hem implementat un enfocament mobile-first, utilitzant media queries per a tres punts de ruptura principals: 320px (mòbils), 768px (tablets) i 1024px (escriptoris). El sistema de grid basat en flexbox permet que els elements es reorganitzin fluidament. Per a les imatges, hem combinat tècniques de lazy loading amb l'ús del tag picture per servir formats i resolucions diferents segons el dispositiu. El menú de navegació es transforma en un menú hamburguesa en pantalles petites, millorant l'usabilitat tàctil. Les tipografies utilitzen unitats rem per a un escalat coherent, i els botons tenen àrees de toc suficients per a ús amb dits.

# 5.Cartografia
   
Els mapes s’han elaborat amb Leaflet.js, una llibreria lleugera que permet afegir capes interactives. Les dades geogràfiques s’han processat en format GeoJSON, i s’han enriquit amb QGIS abans de pujar-les a la web. Per exemple: Els camps de futbol es mostren com a marcadors amb pop-ups que inclouen fotos o estadístiques.

# 6.Dificultats/millores

Una de les dificultats principals ha estat fer que la web sigui completament responsive i que els elements interactius (com el gir de les targetes dels camps) funcionin de manera correcta en tots els navegadors. També s’ha hagut de controlar el pes total de les imatges per no alentir la càrrega. 

En el futur, una de les millores que hem plantejo, es crear una classificació interactiva pels tornejosque es puguin dur a terme.
