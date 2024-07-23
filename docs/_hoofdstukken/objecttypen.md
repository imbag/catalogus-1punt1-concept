---
layout: page
title: 6 Objecttypen
date: 2018-03-05
description:
lijstvolgorde: 160
toc:
- 6 Objecttypen
- 6.1 Woonplaats
- 6.2 Openbare ruimte
- 6.3 Nummeraanduiding
- 6.4 Pand
- 6.5 Adresseerbaar object
- 6.6 Ligplaats
- 6.7 Standplaats
- 6.8 Verblijfsobject
---

# Inhoud van hoofdstuk 6 Objecttypen
{:.no_toc}

* ToC
{:toc}

---

# 6 Objecttypen
{:.no_toc}

## 6.1 Woonplaats

Deze paragraaf geeft een beschrijving (zie tabel 6.1.a) en benoemt de attributen (zie tabel 6.1.b) van het objecttype Woonplaats.

_Tabel 6.1.a: Beschrijving van het objecttype Woonplaats_

| Naam | Woonplaats |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 11.7 |
| **Definitie** | Een Woonplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Augustus 2004 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen bevat alle officieel als zodanig vastgestelde woonplaatsen op het Nederlandse grondgebied. Nieuwe woonplaatsen worden in de basisregistratie adressen en gebouwen opgenomen op basis van daartoe aangewezen brondocumenten waarin het ontstaan van de woonplaats als zodanig is vastgelegd. Daarnaast bevat de basisregistratie adressen en gebouwen alle geconstateerde woonplaatsen in de zin van artikel 2, tweede lid, onderdeel b, sub 3 van de wet. De gegevens over woonplaatsen blijven in de basisregistratie aanwezig, ook indien de woonplaats als zodanig wordt opgeheven. De basisregistratie bevat in principe geen gegevens over woonplaatsen die voor 1 juli 2009 zijn opgeheven. |
| **Kwaliteit** | Een Woonplaats bestaat als hiertoe door het bevoegde gemeentelijke orgaan als zodanig een besluit is genomen. |
| **Toelichting** | Zie [paragraaf 10.4](objectafbakening.md#104-indeling-in-woonplaatsen) voor de interpretatie van de definitie van het objecttype Woonplaats. |
| **Indicatie abstract object** | Nee |

_Tabel 6.1.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.1.1](attributen--relaties.md#711-identificatie) |
| naam | \[1\] | Zie [paragraaf 7.1.2](attributen--relaties.md#712-naam) |
| geometrie | \[1\] | Zie [paragraaf 7.1.3](attributen--relaties.md#713-geometrie) |
| status | \[1\] | Zie [paragraaf 7.1.4](attributen--relaties.md#714-status) |
| geconstateerd | \[1\] | Zie [paragraaf 7.1.5](attributen--relaties.md#715-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.1.6](attributen--relaties.md#716-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.1.7](attributen--relaties.md#717-documentnummer) |

## 6.2 Openbare ruimte

Deze paragraaf geeft een beschrijving (zie tabel 6.2.a) en benoemt de attributen (zie tabel 6.2.b) en relaties (zie tabel 6.2.c) van het objecttype Openbare ruimte.

_Tabel 6.2.a: Beschrijving van het objecttype Openbare ruimte_

| Naam | Openbare ruimte |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 11.1 |
| **Definitie** | Een Openbare ruimte is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Oktober 2002 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen bevat alle officieel als zodanig aangewezen openbare ruimten op het Nederlands grondgebied. Nieuwe openbare ruimten worden in de basisregistratie adressen en gebouwen opgenomen op basis van daartoe aangewezen brondocumenten waarin het ontstaan van de openbare ruimte als zodanig is vastgelegd. Daarnaast bevat de basisregistratie adressen en gebouwen alle geconstateerde openbare ruimten in de zin van artikel 2, tweede lid, onderdeel b, sub 4 van de wet. De gegevens over openbare ruimten blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien de openbare ruimte als zodanig wordt ingetrokken. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over openbare ruimten die voor 1 juli 2009 zijn ingetrokken. |
| **Kwaliteit** | Een Openbare ruimte bestaat als hiertoe door het bevoegde gemeentelijke orgaan als zodanig een besluit is genomen. |
| **Toelichting** | Als openbare ruimte worden onder meer aangemerkt wegen, water, spoorbanen en landschappelijke gebieden. Zie [paragraaf 10.3](objectafbakening.md#103-vaststelling-van-openbare-ruimten) voor de interpretatie van de definitie van het objecttype Openbare ruimte. |
| **Indicatie abstract object** | Nee |

_Tabel 6.2.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.2.1](attributen--relaties.md#721-identificatie) |
| naam | \[1\] | Zie [paragraaf 7.2.2](attributen--relaties.md#722-naam) |
| type | \[1\] | Zie [paragraaf 7.2.3](attributen--relaties.md#723-type) |
| status | \[1\] | Zie [paragraaf 7.2.4](attributen--relaties.md#724-status) |
| geconstateerd | \[1\] | Zie [paragraaf 7.2.5](attributen--relaties.md#725-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.2.6](attributen--relaties.md#726-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.2.7](attributen--relaties.md#727-documentnummer) |

_Tabel 6.2.c: Overzicht relaties_

| Relatiesoort | Relatierol | Kardinaliteit | Beschrijving |
| :---: | :---: | :---: | :--- |
| ligt in | gerelateerde woonplaats | \[1\] | Zie [paragraaf 7.2.8](attributen--relaties.md#728-relatie-ligt-in-gerelateerde-woonplaats) |

## 6.3 Nummeraanduiding

Deze paragraaf geeft een beschrijving (zie tabel 6.3.a) en benoemt de attributen (zie tabel 6.3.b) en relaties (zie tabel 6.3.c) van het objecttype Nummeraanduiding.

_Tabel 6.3.a: Beschrijving van het objecttype Nummeraanduiding_

| Naam | Nummeraanduiding |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 11.2 |
| **Definitie** | Een Nummeraanduiding is een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject, een standplaats of een ligplaats. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie en gebouwen |
| **Datum opname** | Oktober 2002 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen bevat alle officieel als zodanig toegekende nummeraanduidingen op het Nederlandse grondgebied. Nieuwe nummeraanduidingen worden in de basisregistratie adressen en gebouwen opgenomen op basis van daartoe aangewezen brondocumenten waarin het ontstaan van de nummeraanduiding als zodanig is vastgelegd. Daarnaast bevat de basisregistratie adressen en gebouwen alle geconstateerde nummeraanduidingen in de zin van artikel 2, tweede lid, onderdeel b, sub 5 van de wet. De gegevens over nummeraanduidingen blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien de nummeraanduiding als zodanig wordt ingetrokken. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over nummeraanduidingen die voor 1 juli 2009 zijn ingetrokken. |
| **Kwaliteit** | Een Nummeraanduiding bestaat als hiertoe door het bevoegde gemeentelijke orgaan als zodanig een besluit is genomen. Een Nummeraanduiding heeft altijd betrekking op een enkel adresseerbaar object. |
| **Toelichting** | Nummeraanduidingen kunnen alleen worden toegekend aan als zodanig aangewezen adresseerbare objecttypen. De thans aangewezen adresseerbare objecttypen zijn verblijfsobjecten, standplaatsen en ligplaatsen. Zie [paragraaf 10.2](objectafbakening.md#102-toekenning-van-nummeraanduidingen) voor de interpretatie van de definitie van het objecttype Nummeraanduiding. |
| **Indicatie abstract object** | Nee |

_Tabel 6.3.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.3.1](attributen--relaties.md#731-identificatie) |
| huisnummer | \[1\] | Zie [paragraaf 7.3.2](attributen--relaties.md#732-huisnummer) |
| huisletter | \[0..1\] | Zie [paragraaf 7.3.3](attributen--relaties.md#733-huisletter) |
| huisnummertoevoeging | \[0..1\] | Zie [paragraaf 7.3.4](attributen--relaties.md#734-huisnummertoevoeging) |
| postcode | \[0..1\] | Zie [paragraaf 7.3.5](attributen--relaties.md#735-postcode) |
| type adresseerbaar object | \[1\] | Zie [paragraaf 7.3.6](attributen--relaties.md#736-type-adresseerbaar-object) |
| status | \[1\] | Zie [paragraaf 7.3.7](attributen--relaties.md#737-status) |
| geconstateerd | \[1\] | Zie [paragraaf 7.3.8](attributen--relaties.md#738-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.3.9](attributen--relaties.md#739-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.3.10](attributen--relaties.md#7310-documentnummer) |

_Tabel 6.3.c: Overzicht relaties_

| Relatiesoort | Relatierol | Kardinaliteit | Beschrijving |
| :---: | :---: | :---: | :--- |
| ligt in | gerelateerde woonplaats | \[0..1\] | Zie [paragraaf 7.3.11](attributen--relaties.md#7311-relatie-ligt-in-gerelateerde-woonplaats) |
| ligt aan | gerelateerde openbare ruimte | \[1\] | Zie [paragraaf 7.3.12](attributen--relaties.md#7312-relatie-ligt-aan-gerelateerde-openbare-ruimte) |

## 6.4 Pand

Deze paragraaf geeft een beschrijving (zie tabel 6.4.a) en benoemt de attributen (zie tabel 6.4.b) van het objecttype Pand.

_Tabel 6.4.a: Beschrijving van het objecttype Pand_

| Naam | Pand |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 55 |
| **Definitie** | Een Pand is de kleinste, bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Februari 2004 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen omvat gegevens over alle panden op het Nederlands grondgebied, die voldoen aan bovenstaande objectdefinitie. Gegevens over een nieuw pand worden in de basisregistratie adressen en gebouwen opgenomen bij verlening van de voor het realiseren van het pand benodigde toestemming of het opmaken van een in artikel 10, onderdeel b van de wet genoemd document van constatering. De gegevens over panden blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien het pand als zodanig niet meer aanwezig is. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over panden die op 1 juli 2009 niet meer als zodanig aanwezig waren. |
| **Kwaliteit** | |
| **Toelichting** | Zie [paragraaf 10.6](objectafbakening.md#106-afbakening-van-panden) voor de interpretatie van de definitie van het objecttype Pand. |
| **Indicatie abstract object** | Nee |

_Tabel 6.4.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.4.1](attributen--relaties.md#741-identificatie) |
| geometrie | \[1\] | Zie [paragraaf 7.4.2](attributen--relaties.md#742-geometrie) |
| oorspronkelijk bouwjaar | \[1\] | Zie [paragraaf 7.4.3](attributen--relaties.md#743-oorspronkelijk-bouwjaar) |
| status | \[1\] | Zie [paragraaf 7.4.4](attributen--relaties.md#744-status) |
| geconstateerd | \[1\] | Zie [paragraaf 7.4.5](attributen--relaties.md#745-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.4.6](attributen--relaties.md#746-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.4.7](attributen--relaties.md#747-documentnummer) |

## 6.5 Adresseerbaar object

Deze paragraaf geeft een beschrijving (zie tabel 6.5.a) en benoemt de relaties (zie tabel 6.5.b) van het objecttype Adresseerbaar object.

_Tabel 6.5.a: Beschrijving van het objecttype Adresseerbaar object_

| Naam | Adresseerbaar object |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 101 |
| **Definitie** | Een Adresseerbaar object is een (abstract) object waaraan adressen kunnen worden toegekend. |
| **Herkomst definitie** | BAG |
| **Datum opname** | Januari 2017 |
| **Unieke aanduiding** | |
| **Populatie** | |
| **Kwaliteit** | |
| **Toelichting** | Een Adresseerbaar object is een Standplaats, een Ligplaats of een Verblijfsobject. |
| **Indicatie abstract object** | Ja |

_Tabel 6.5.b: Overzicht relaties_

| Relatiesoort | Relatierol | Kardinaliteit | Beschrijving |
| :---: | :---: | :---: | :--- |
| heeft als hoofdadres | hoofdadres | \[1\] | Zie [paragraaf 7.5.1](attributen--relaties.md#751-relatie-heeft-als-hoofdadres-hoofdadres) |
| heeft als nevenadres | nevenadres | \[0..\*\] | Zie [paragraaf 7.5.2](attributen--relaties.md#752-relatie-heeft-als-nevenadres-nevenadres) |

## 6.6 Ligplaats

Deze paragraaf geeft een beschrijving (zie tabel 6.6.a) en benoemt de attributen (zie tabel 6.6.b) van het objecttype Ligplaats.

_Tabel 6.6.a: Beschrijving van het objecttype Ligplaats_

| Naam | Ligplaats |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 58 |
| **Definitie** | Een Ligplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt drijvend object. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Februari 2004 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen omvat gegevens over alle ligplaatsen op het Nederlands grondgebied, die daartoe officieel als zodanig zijn aangewezen. Nieuwe ligplaatsen worden in de basisregistratie adressen en gebouwen opgenomen op basis van daartoe aangewezen brondocumenten, waarin het ontstaan van de ligplaats als zodanig is vastgelegd. Daarnaast bevat de basisregistratie adressen en gebouwen alle geconstateerde ligplaatsen in de zin van artikel 2, tweede lid, onderdeel b, sub 2 van de wet. De gegevens over ligplaatsen blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien de ligplaats als zodanig wordt ingetrokken. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over ligplaatsen die voor 1 juli 2009 zijn ingetrokken. |
| **Kwaliteit** | Een Ligplaats bestaat op het moment dat er sprake is van een aanwijzing als ligplaats door het bevoegde gemeentelijke orgaan. |
| **Toelichting** | Zie [paragraaf 10.5](objectafbakening.md#105-afbakening-van-ligplaatsen) voor de interpretatie van de definitie van het objecttype Ligplaats. |
| **Indicatie abstract object** | Nee |

_Tabel 6.6.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.6.1](attributen--relaties.md#761-identificatie) |
| status | \[1\] | Zie [paragraaf 7.6.2](attributen--relaties.md#762-status) |
| geometrie | \[1\] | Zie [paragraaf 7.6.3](attributen--relaties.md#763-geometrie) |
| geconstateerd | \[1\] | Zie [paragraaf 7.6.4](attributen--relaties.md#764-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.6.5](attributen--relaties.md#765-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.6.6](attributen--relaties.md#766-documentnummer) |

## 6.7 Standplaats

Deze paragraaf geeft een beschrijving (zie tabel 6.7.a) en benoemt de attributen (zie tabel 6.7.b) van het objecttype Standplaats.

_Tabel 6.7.a: Beschrijving van het objecttype Standplaats_

| Naam | Standplaats |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 57 |
| **Definitie** | Een Standplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Februari 2004 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen omvat gegevens over alle standplaatsen op het Nederlands grondgebied, die daartoe officieel als zodanig zijn aangewezen. Nieuwe standplaatsen worden in de basisregistratie adressen en gebouwen opgenomen op basis van daartoe aangewezen brondocumenten, waarin het ontstaan van de standplaats als zodanig is vastgelegd. Daarnaast bevat de basisregistratie adressen en gebouwen alle geconstateerde standplaatsen in de zin van artikel 10, tweede lid, onderdeel b van de wet. De gegevens over standplaatsen blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien de standplaats als zodanig wordt ingetrokken. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over standplaatsen die voor 1 juli 2009 zijn ingetrokken. |
| **Kwaliteit** | |
| **Toelichting** | Zie [paragraaf 10.7](objectafbakening.md#107-afbakening-van-standplaatsen) voor de interpretatie van de definitie van het objecttype Standplaats. |
| **Indicatie abstract object** | Nee |

_Tabel 6.7.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.7.1](attributen--relaties.md#771-identificatie) |
| status | \[1\] | Zie [paragraaf 7.7.2](attributen--relaties.md#772-status) |
| geometrie | \[1\] | Zie [paragraaf 7.7.3](attributen--relaties.md#773-geometrie) |
| geconstateerd | \[1\] | Zie [paragraaf 7.7.4](attributen--relaties.md#774-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.7.5](attributen--relaties.md#775-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.7.6](attributen--relaties.md#776-documentnummer) |

## 6.8 Verblijfsobject

Deze paragraaf geeft een beschrijving (zie tabel 6.8.a) en benoemt de attributen (zie tabel 6.8.b) en relaties (zie tabel 6.8.c) van het objecttype Verblijfsobject.

_Tabel 6.8.a: Beschrijving van het objecttype Verblijfsobject_

| Naam | Verblijfsobject |
| :--- | :--- |
| **Stereotype** | «Objecttype» |
| **Herkomst** | BAG |
| **Code** | 56 |
| **Definitie** | Een Verblijfsobject is de kleinste binnen een of meer panden gelegen en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is. |
| **Herkomst definitie** | Artikel 1 Wet basisregistratie adressen en gebouwen |
| **Datum opname** | Februari 2004 |
| **Unieke aanduiding** | identificatie |
| **Populatie** | De basisregistratie adressen en gebouwen omvat gegevens over alle verblijfsobjecten op het Nederlands grondgebied die voldoen aan bovenstaande objectdefinitie. Gegevens over een nieuw verblijfsobject worden in de basisregistratie adressen en gebouwen opgenomen bij verlening van de voor het realiseren van het verblijfsobject benodigde toestemming of het opmaken van een in artikel 10, onderdeel b van de wet genoemd document van constatering. De gegevens over verblijfsobjecten blijven in de basisregistratie adressen en gebouwen aanwezig, ook indien het verblijfsobject als zodanig niet meer aanwezig is. De basisregistratie adressen en gebouwen bevat in principe geen gegevens over verblijfsobjecten die op 1 juli 2009 niet meer als zodanig aanwezig waren. |
| **Kwaliteit** | |
| **Toelichting** | Zie [paragraaf 10.8](objectafbakening.md#108-afbakening-van-verblijfsobjecten) voor de interpretatie van de definitie van het objecttype Verblijfsobject. |
| **Indicatie abstract object** | Nee |

_Tabel 6.8.b: Overzicht attributen_

| Attribuut | Kardinaliteit | Beschrijving |
| :---: | :---: | :--- |
| identificatie | \[1\] | Zie [paragraaf 7.8.1](attributen--relaties.md#781-identificatie) |
| geometrie | \[1\] | Zie [paragraaf 7.8.2](attributen--relaties.md#782-geometrie) |
| gebruiksdoel | \[1..\*\] | Zie [paragraaf 7.8.3](attributen--relaties.md#783-gebruiksdoel) |
| oppervlakte | \[1\] | Zie [paragraaf 7.8.4](attributen--relaties.md#784-oppervlakte) |
| status | \[1\] | Zie [paragraaf 7.8.5](attributen--relaties.md#785-status) |
| geconstateerd | \[1\] | Zie [paragraaf 7.8.6](attributen--relaties.md#786-geconstateerd) |
| documentdatum | \[1\] | Zie [paragraaf 7.8.7](attributen--relaties.md#787-documentdatum) |
| documentnummer | \[1\] | Zie [paragraaf 7.8.8](attributen--relaties.md#788-documentnummer) |

_Tabel 6.8.c: Overzicht relaties_

| Relatiesoort | Relatierol | Kardinaliteit | Beschrijving |
| :---: | :---: | :---: | :--- |
| maakt deel uit van | gerelateerd pand | \[1..\*\] | Zie [paragraaf 7.8.9](attributen--relaties.md#789-relatie-maakt-deel-uit-van-gerelateerd-pand) |