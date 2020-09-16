# APP Hospitals

> Introducció

Tots, em alguna vegada a la nostra vida, ens hem vist obligats a pendre aquesta decisió: a quin hospital 

anar? De vegades la decisió es prén sobre dades completament subjectives: 

    "M'agrada més l'hospital de Sant Pau".
    "El Clínic no te parangón a la ciutat". 
    "La Vall d'Hebrón disosa dels medis més moderns a la sanitat pública". 
    "El servei humà de L'hospital del Mar es imbatible".

Plantejo una manera objectiva de respondre a aquesta questió: quin hospital està més a prop?

Dos punts de coordenades en un mapa que ens indiquin quin es l'hospital que queda més a prop de la nostra 

posició actual, també ensenyant la resta de hospitals en llistat amb els Km que hi han. 

Per qué una App com aquesta? Fent treball de camp, m'he adonat que no hi hà una App com aquesta al mercat. 

#### Pacients i usuaris sense haver-hi hospital fixe

> * ![Pacients](https://imgur.com/nbbIR7R.png)

 [noticia](https://www.metropoliabierta.com/el-pulso-de-la-ciudad/sanidad/hospitales-barcelona-seguimiento-pacientes-movil_27546_102.html)

> * ![Seguiment pacients](https://imgur.com/KrFCzSU.png)

[noticia](https://www.clinicbarcelona.org/noticias/el-clinic-coordinara-la-validacion-de-una-app-europea-para-facilitar-el-seguimiento-de-los-pacientes-con-vih)

#### Relació pacients-hospitals

> * ![Bellvitge](https://imgur.com/8GPX5pu.png)

> * ![Clínic](https://imgur.com/kHEKxON.png)

> * ![Vall d'Hebrón](https://imgur.com/8lzbhdi.png)

#### Usuaris treballadors hospitals

> * ![Joan de Déu](https://imgur.com/zw0bLJX.png)

Com podem comprobar no hi hà un App d'aquestes característiques.

#### Com fer-ho

[Geolocation.getCurrentPosition()](https://developer.mozilla.org/es/docs/Web/API/Geolocation/getCurrentPosition)

L'API de Google es pot col.locar tant com a funció de JavaScript 

[stackoverflow](https://stackoverflow.com/questions/16202077/high-accuracy-geolocation-html5) o com a 

script al document HTML [w3schools](https://www.w3schools.com/html/html5_geolocation.asp)

Aquest [exercici](https://developers.arcgis.com/labs/javascript/get-map-coordinates/) m'ajudarà a entendre 

les implicacions de les API necesaries per l'implementació a l'APP.

#### Comparacions.

En no tenir una APP directament similar, les úniques comparacions poden ser amb les App dels hospitals, tant

en les seves versions de [`pacients`](#Pacients), [`hospitals`](#Bellvitge) i [usuaris](#Usuaris) poden 

donar-me informació de quins par&agrave;metres treballar.  

### Inici de la maquetació

##### Colors

[paletton](https://paletton.com/#uid=13K0u0kllllc0wdgGqHp+fYuFaB)

Elecció de colors blaus, desaturats (les pantalles dels móbils tenen molta brillantor) o verds. Blau per la resonancia sanitaria, 

verd per la tranquilitat i esprença que reportar. 

![paleta de colors](https://imgur.com/3PORJ2Q.png)

Conjunt de blaus, verds and blancs. Flat Design. Simplicitat per a la seva utilització.


#### Col.locació botó landing page

![estudi pantalles](https://imgur.com/oAwG3PC.png)

#### Wireframes

![landing prtotype](https://imgur.com/oKlI3Uc.png)

![GPDR](https://imgur.com/FRVU46n.png)

Important: Recorde'm que no podem evitar aquest pas donat la nova llei de dades de l'UE.

![Form](https://imgur.com/gwMBGSA.png)

Formulari que s'ha d'omplir la primera vegada que utilitzem l'app

![Loading](https://imgur.com/CLv185S.png)

Plana de càrrega de l'app. 

![OK page](https://imgur.com/v6kHT7L.png)

![Error page](https://imgur.com/yDwDaOr.png)

#### Concept Map
![Concept map site](https://imgur.com/7t0km5R.png)








