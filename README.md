# FindFace

Principalment pensat pera reconeixer treballadors d’una empresa i aixı donar o nouna autoritzacio.  El sistema consta tambe d’un modul quedetecta les cares d’una imatge i retorna un retall d’aquestesper tal de facilitar el reconeixement. Aix ́ı doncs, el sistemaes  basa  en  passar-li  les  imatges  dels  treballadors  a  unaxarxa neuronal i aixı entrenar-la, llavors cada vegada que algu vulgui accedir, la camera captura la imatge, passa pelmodul de deteccio de cares i llavors pel modul de reconeixement de cares, que es l’encarregat de dir si l’individu esta autoritzat o no.

## Guia de execució

pip install -r llibreries.txt

Per iniciar l'execució s'ha de executar el fitxer 'main.py'
