En el següent projecte de data science hem analitzat dos diferents dataframes, un sobre els preus dels lloguers de diferents barris de Barcelona durant l'any 2023, que sería el DF principal i l'altre sobre l'exposició del soroll també de diferents barris de Barcelona.


Durant la manipulació de les dades, he començat fent un merge de la totalitat de les dues fent que coincidici tant els noms dels barris i els districtes com els seus respectius codis. Un cop unificats he eliminat els valors nuls per tal de deixar les dades netes i que poguessim treballar sense errors. Un cop aquí habia de decidir per on tirar per tal d'analitzar les dades, encara soc un principiant i la veritat que l'única cosa que he pogut veure era que els preus dels lloguers es dividia per la totalitat del mes o bé per el seu preu per metre quadrat, i utilitzant les màscares booleanes he filtrat per un i per l'altre per generar dos dataframes diferents. Tant amb l'un com amb l'altre he fet un groupby agrupant per el nom del districte, el nom del barri i l'exposició d'aquests al soroll, així fent la mitja dels preus dels lloguers i veure si es veuen afectats segons els DB's.


Com a resultats he pogut observar que el preu del lloguer es basa més en la zona que en l'exposició al soroll del que pateixen.


M'agradaria tenir més experiència per donar-vos uns resultats més enriquits, però no puc dir més sobre les dades ara mateix i pel poc temps que li he pogut dedicar, no sé si es molt demanar, sé que no passaré la proba però podrieu dir-me les pautes que s'haurien hagut de seguir? I quina mena de README es el que s'hauria d'haver entregat? Ara mateix estic en un moment en el que vull aprendre tot el que pugui.
