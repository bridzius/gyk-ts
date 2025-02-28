# GYK TypeScript užduotis

Parašykite **nedidelę TypeScript programą**, kuri simuliuoja prekių valdymo sistemą.

Nepamirškite:
1. Naujas npm package.
2. `npm install typescript`
3. Kodą runniname su `npx tsx <failas>`

Užduotis:
1. Sukurkite `enum Kategorija`, kuri apibrėžtų tokias reikšmes kaip `Maistas`, `Elektronika`, `Drabužiai`.
2. Sukurkite `interface Preke,` kuri turėtų `id`, `pavadinimas`, `kaina` ir `kategorija`.
3. Parašykite `class ParduotuvesSistema`, kuri valdytų prekių sąrašą:
   1. Metodą `pridetiPreke(preke: Preke)`, kuris įtraukia naują prekę į sąrašą.
   2. Metodą `gautiPrekesPagalKategorija(kategorija: Kategorija)`, kuris grąžina visas prekes iš nurodytos kategorijos.
   3. Metodą `salintiPreke(id: number)`, kuris pašalina prekę pagal id.
   4. Metodą `rodytiPrekes()`, kuris parodo visas pridėtas prekes.
4. Naudokite Generiką, kad sukurtumėte funkciją `ieskotiPagalKriteriju<T>`, kuri filtruoja prekes pagal perduotą kriterijų (kriterijus paduodamas kaip anoniminė funkcija, kuri grąžina .
5. Pademonstruokite "Sąjungų tipus" (union types), kad prekė galėtų turėti tiek nuolaidą procentais (`number`), tiek fiksuotą kainos sumažinimą (`string`).

Extra:
1. Pridėkite naują klasės metodą, kuris atnaujina prekę pagal id.
2. Leiskite prekei priskirti kelias kategorijas naudojant sąjungos tipą.
