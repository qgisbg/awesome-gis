# ГИС? Яко!

Колекция от бази данни, обучителни материали, инструменти, карти и други полезни ресурси свързани с географска тематика. 

Но какво е ГИС?
> Географска информационна система (ГИС) е информационна система за създаване, манипулиране, съхраняване, анализ и визуализация на географски обвързани (пространствени) данни (на английски: Geographic data and information). 
> ГИС може да се отнася за различни технологии, процеси и методи. Технологията съпътства много операции и има много приложения в техниката, планирането, управлението, транспорта, застраховането, телекомуникациите, индустрията и във все повече области на човешкия живот[3] Поради това ГИС и приложенията, свързани с местоположението (на английски: location-based service, LBS), дават възможност за разработка на множество услуги за анализ и визуализация.

https://bg.wikipedia.org/wiki/Географска_информационна_система

Яко!

**Тук е информация! Да направим тоя списък още по-як!** При нови добавки моля последвайте инструкциите на [Инструкции за нови добавки](https://github.com/geographybg/awesome-gis/blob/main/ContributingGuidelines.md). Ако имате общи идеи и/или коментари за подобряване на този списък, моля пишете във [Въпроси](https://github.com/geographybg/awesome-gis/).

Създаването на този списък беше вдъхновено от еквивалента му на английски [Awesome GIS](https://github.com/sshuair/awesome-gis).


## Легенда

За по-лесно ориентиране в списъкът по-долу, със система от емоджита се допълват някои белези на описаните ресурси по-долу.

- :euro: - затворен или платен софтуер за обучителни или доброволчески цели
- :baby: - подходящ за начинаещи
- :snake: - наличен като Python библиотека
- :keyboard: - наличен като програма от командния ред


## ГИС софтуер

Софтуерни продукти, които помагат за работата с пространствени данни:


### Настолни

- [QGIS](https://qgis.org/) :baby: :snake: - Най-разпространеният и богат на функционалности безплатен и отворен ГИС софтуер.


### Мобилни

- [QField](https://qfield.org/) :baby: - Цялата сила на QGIS в ръцете ти, безплатно. Мобилна версия на QGIS. 


### Команден ред :keyboard:

- [GDAL](https://gdal.org) :snake: - GDAL - Geospatial Data Abstraction Library е преводач между различни растерни и векторни геопространствени формати. Сърцето на почти всички софтуери с отворен код.
- [PCRaster](https://pcraster.geo.uu.nl) :snake: - Колекция от софтуер за прилагане на пространствено-времеви модели и анализи.


### Визуализации онлайн

Създаване на интерактивни карти, достъпни чрез интернет:

- [MapChart](https://mapchart.net) :baby: - MapChart е софтуер за лесно изчертаване на карти онлайн изцяло с безплатен онлайн интерфейс.
- [Leaflet](https://leafletjs.com/) :baby: - JavaScript библиотека за създаване на инстерактивни карти удобни за преглед и на мобилно устройство.
- [leaflet-providers](https://github.com/leaflet-extras/leaflet-providers) - Разширение за Leaflet, което позволява зареждането на базови слоеве от различни безплатни (но понякога лимитирани) доставчици.
- [OpenLayers](http://openlayers.org/) - JavaScript библиотека за визуализиране на карти.
- [D3.js](https://d3js.org/) - JavaScript библиотека за интерактивни документи създадени от данни.

### Сървърни продукти

- [Geoserver](http://geoserver.org/) - Java сървър за публикуване на ГИС данни в уеб среда, съгласно OGC (WMS/WFS/WCS). 

### QGIS - плъгини и благинки

- [Геоложки символи за QGIS](https://github.com/afrigeri/geologic-symbols-qgis) - Набор от символи използвани в геология, готови за използване във всеки проект.

### Библиотеки :snake:
- [Shapely](https://github.com/Toblerity/Shapely) - Библиотека за работа с геометрични фигури в декартовата (правоъгълна) координатна система.
- [Fiona](http://github.com/toblerity/fiona/) :keyboard: - Четене и писане на векторни ГИС данни в Python.
- [Rasterio](https://github.com/mapbox/rasterio) :keyboard: - Четене и писане на растерни геопрастранствени данни в Python.
- [NumPy](http://www.numpy.org/) - NumPy е в основата за научна работа с числа в Python.
- [pandas](https://pandas.pydata.org) - Бърза, мощна, гъвкава и лесна библиотека за работа със статистически данни.
- [GeoPandas](https://github.com/geopandas/geopandas) - GeoPandas разширява pandas за работа с географски обекти.
- [pyproj](https://github.com/jswhit/pyproj) - Библиотека за картографски проекции и трансформации, Python интерфейс на [PROJ](https://proj.org).
- [matplotlib](http://matplotlib.org/) - Чертаене на графики с Python.
- [networkx](http://networkx.github.io/) - За работа с графи (мрежи).
- [pyesridump](https://github.com/openaddresses/pyesridump) :keyboard: - Изтегляне на всички обекти от ESRI MapServer слой в GeoJson.
- [momepy](https://github.com/martinfleis/momepy) - Библиотека за количествени измерения на формите в застроените територии.

## Данни

Наличните набори данни и техните източници са описани [тук](https://github.com/geographybg/awesome-gis/blob/main/data.md).

- [Национален статистически институт (НСИ)](https://www.nsi.bg/bg/content/766/статистически-данни) - Национален статистически институт на България. 
- [Национален регистър на населените места (НРНМ)](https://www.nsi.bg/nrnm/) - Данни за населените места и административно-териториална структура на България.
- [Sentinel-Hub EO Browser](https://apps.sentinel-hub.com/eo-browser/) - Преглед и изтегляне на изображения от европейскш мисии (Sentinel).
- [USGS EarthExplorer](https://earthexplorer.usgs.gov) - Преглед и изтегляне на изображения от американски мисии (Landsat).
- [Urban Atlas](https://land.copernicus.eu/local/urban-atlas) - Urban Atlas предоставя общоевропейски сравними данни за земното покритие и земеползването във Функционални Урбанизирани Ареали (ФУА).
- [OpenDataBG](https://data.egov.bg/) - Портал за отворени данни на Република България. Данните са разделени по теми: Икономика, Здравеопазване, Околна среда, Население, Градове, Транспорт, Енергетика и др.
- [Климатична класификация по Кьопен-Гайгер](https://figshare.com/articles/dataset/Present_and_future_K_ppen-Geiger_climate_classification_maps_at_1-km_resolution/6396959/2) - Климатична класификация по Кьопен-Гайгер с разделителна способност от 1km2 с покритие за целия свят.
- [GlobalMaps](https://globalmaps.github.io/) - Отворени векторни и растерни данни за света и отделните държави - DEM, физикогеографски и антропогенни обекти. Пряка връзка към данните за България [тук](https://github.com/globalmaps/gmbg10).
- [OpenTopography.org](https://portal.opentopography.org/dataCatalog) - Отворени топографски данни с висока резолюция - облаци от точки и растери.
- [ФАО - ООН](https://data.apps.fao.org/map/catalog/srv/eng/catalog.search#/home) - Отворени данни с разнообразна насоченост предоставени от ФАО към ООН.

## Картни основи
- [Sentinel2](https://s2maps.eu) - безоблачна сателитна растерна мозайка на света без облаци. Възможност за изтегляне и вграждане в ГИС.
- [Stamen Maps](http://maps.stamen.com) - разнообразни картни основи. Възможност за изтегляне и вграждане в ГИС.
- [BGTopoVJ](http://web.uni-plovdiv.bg/vedrin/) - руски топографски карти на България и Македония в мащаб 1:50000.

## Онлайн карти
- [blitzortung.org](https://map.blitzortung.org/) - Светкавиците по света в реално време.
- [WAQI замърсяване на въздуха](https://waqi.info/bg) - Световното качество на въздуха: Индекс на качеството на въздуха в реално време.
- [AirBg замърсяване на въздуха](https://airbg.info/map/) - Карта в реално време на качеството на въздуха в България.
- [Народи и племена в Новия свят](https://native-land.ca/) - Ареали на местното население в Новия свят - онлайн карта.
- [EarthNow! Landsat изображения](https://earthnow.usgs.gov/observer/) - Преглед на изображенията на американските сателити Landsat 7 и 8 в (почти) реално време.
- [Застрашените езици по света](http://www.unesco.org/languages-atlas/) - Атлас на застрашените от изчезване езици на UNESCO- онлайн карта.
- [ИПИ 265 общини](http://265obshtini.bg/) - Интерактивна карта на общините за достъпно и разбираемо представяне на голямо количество данни.
- [ИПИ регионални профили](https://www.regionalprofiles.bg/bg/) - Информация за развитието на областите в страната и допълването им с анализи на икономическите и социалните аспекти.
- [Windy.com](https://www.windy.com) - Интерактивна карта на посоката и скоростта на вятъра в реално време.
- [flightradar24](https://www.flightradar24.com) - Самолети в реално време.
- [Туристически маршрути в България](https://tripsjournal.com/marshruti) - Интерактивна карта на пешеходни и вело маршрути и еко пътеки в България.
- [BG Industry Map](https://bgindustrymap.com/bg) - Подробни карти и бази данни за 14 избрани индустриални сектора в България.
- [Meteoblue](https://www.meteoblue.com/) - Точна информация и прогнози за времето във всяка точка на света. Интерактивни прогнозни карти и карти метеорологичната обстановка в реално време.
- [Zoom Earth](https://zoom.earth/) - Визуализация на това как изглежда Земята в настоящият момент, с възможност за връщане назад във времето и проследяване развитието и движението на циклонални явления в различни точки на земното кълбо.
- [Ancient Earth globe](https://dinosaurpictures.org/ancient-earth) - Интерактивен глобус, показващ промените настъпили върху лицето на Земята от преди 750 милиона години до днес.
- [Геоложка карта на света](https://macrostrat.org/map) - Геоложка карта на света.
- [CadastreBG](https://kais.cadastre.bg/bg/Map) :euro: - Интерактивена кадастрална карта на България, с възможност за закупуване на данни за избрани имоти, сгради и самостоятелни обекти на собственост.
- [Геокартфонд](https://gkf.cadastre.bg/) :euro: - Интерактивена карта Геокартфонд, съдържа ЕТК в М 1:5000 и 1:10 000 с възможност за закупуване на карти във висока резолюция. 
- [Глобус с подводни интернет кабели](https://globe.gl/example/submarine-cables/) - Интерактивен глобус с активните подводни кабели, по които текат сигналите на интернет.


## Онлайн визуализации
- [The Atlas of Economic Complexity](https://atlas.cid.harvard.edu/explore) - Визуализация на икономическия стокообмен по сектори и държави в света.


## Картографски визуализации
- [Сравняване на картографските проекции](https://observablehq.com/@d3/projection-comparison) - Интерактивно сравнение на световната карта в различните картографски проекции с d3.
- [Изкривяване на картографските проекции](https://bl.ocks.org/syntagmatic/ba569633d51ebec6ec6e) - Интерактивно сравнение на изкривяванията на различните картографски проекции с d3.
- [Светът в различни картографски проекции](https://observablehq.com/@d3/projection-transitions) - Интерактивна визуализация на световната карта в различни картографски проекции с d3.
- [Сравнение на реалните размери на  държавите в света](https://thetruesize.com/) - Възможност за сравнение на реалните размери на  държавите в света, без деформациите при проекцията на Меркатор.
- [Екстремен Меркатор](https://mrgris.com/projects/merc-extreme/#7d2b28c5@43.83557,25.96566) - Използване на меркаторовата проекция с изключителни изкривявания на площите.


## Географски игри

- [Sporcle](https://www.sporcle.com/games/category/geography) - Колекция от игри тип викторина на географска и не само тематика. Лесен начин за запаметяване на държави, столици, градове и др.
- [geoguessr](https://www.geoguessr.com) - Познай къде се намираш на картата по снимка от гугъл мапс.


## Инструменти за градско планиране

- [Streetmix](https://streetmix.net) - Напречен профил на улици. Нарисувай уличното платно такова каквото е или каквото искаш да бъде - с велоалеи, тротоари и активни ленти.

