# FabCar
Installing and using HyperLedger Fabric

        Kaip veikė "FabCar" Kai viskas vyko sklandžiai:
    
        Paleidimas:
![startFabric](https://user-images.githubusercontent.com/78845735/149855265-3073f332-c653-483d-979c-93f14a99ee70.jpg)

        Funckijų paleidimas:
![functions](https://user-images.githubusercontent.com/78845735/149855305-ecc48374-d2de-463e-a5d9-ab6d71532e0d.jpg)

        peer chaincode invoke funkcija (su "queryAllCars"):
![peer chaincode invoke](https://user-images.githubusercontent.com/78845735/149855341-627ac78e-5a1a-48d3-bf81-8aff74169974.png)

        peer chaincode invoke funkcija (su "changeCarOwner"):
![peer chaincode invoke change car owner](https://user-images.githubusercontent.com/78845735/149855406-5b9dba47-de0e-47d4-984b-535191ef0688.png)

        kaip atrodo svetainė ištestavus "fabcar":
![utils](https://user-images.githubusercontent.com/78845735/149855434-c77a4ac1-4b42-4ed8-8369-2bbdbc00ff83.png)

        Database CAR0 po pakeitimų naudojantis chaincode invoke funkciją:
![saved car](https://user-images.githubusercontent.com/78845735/149855522-4ec47555-e3fa-46d8-a309-69ae2146dde4.png)

        Susidurta su daug sunkumų, ypač naudojantis Windows 10 operacinę sistemą.
        Nežinau ar užduotį buvo galima atlikti naudojantis Windows operacine sistema aplamai, kadangi bandant ja atlikti su windowsais, kiekviena komanda turėjo daugybę        problemų, pradedant tuo, kad aplamai nebuvo galima net panaudoti " ./startFabric.sh javascript " komandos, nes nebuvo generuojama daugelis reikalingų failų, kad ši             programa būtų ištestuota.
        Tačiau pasiskolinus kompiuterį su "linuxais" programa vykdėsi ganėtinai sklandžiai. Turėjau problemų su dockeriu, tačiau jos nebuvo neišsprendžiamos. Galbūt pirmu       bandymų neteisingai sekiau skaidres ir kažką sugadinau, tad teko per naujo įsirašyti hyperledger fabric failus.
        Tai padarius, ir atidžiai sekant nurodymus, užduotis buvo atlikta.
