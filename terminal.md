cd          change directory // tabbal kiegészíti a mappa nevet
cd ..       visszalépés a mappából
ls          listázza mi van a mappában amiben éppen vagyunk
mkdir       make directory (ne legyen space a nevében)
npm init    node package manager (js-ts project létrehozása) --> enter addig amig megkérdi hogy "is this ok?"
code .      megnyitja a vs code-ot ebben a mappában (látunk egy package.json filet amiben a "srcripts":{"test": "..."}--át kell írni "srcripts":{"build": "tsc"})
npm install -D typescript       ehhez a projekthez installáljuk a ts-t, (a D azért kell mert jelezzük hogy fejlesztéshez kell)
                                ezután már egy package-lock.json-t és egy node modules mappát is látunk
npx tsc --init      létrehoz egy tsconfig.json-t ("outdir": "./out"-ki kell venni a commentet. ez azt jelenti hogy az out mappába rakja majd a generált js filet)
npm run build       ts filet berakja az out mappába js-ként
npm start           package.json-be "scripts":{"build" : "tsc, "start": "node out/index.js"} megadni node paranccsal h melyik mappából melyik filet futtassa
ni          new item (új file-t lehet létrehozni)
pwd         print working directory (kiírja melyik mappában vagy éppen )
rm -Force   mappa törlés (majd y-nal jóvá kell hagyni)
rm          remove (file törlése)
mv + átnevezni kívánt file + új neve
