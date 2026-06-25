# Pian Virtual cu Efecte Audio în LabVIEW

Acest proiect reprezintă implementarea unui pian virtual interactiv realizat integral în mediul de dezvoltare grafic **LabVIEW**. Aplicația permite simularea notelor muzicale, generarea de frecvențe specifice în timp real și aplicarea unor efecte audio digitale.

## Caracteristici și Module
* **Pian_Virtual_Main.vi:** Modulul principal care gestionează interfața grafică cu utilizatorul (Front Panel), preia comenzile (clapele apasate) și coordonează execuția întregului instrument.
* **Nota_Frecventa.vi:** SubVI dedicat mapării clapelor muzicale pe frecvențele lor matematice corespunzătoare (calculul în Hz pentru fiecare notă).
* **Efecte_Audio.vi:** SubVI responsabil cu manipularea semnalului sonor generat, permițând aplicarea de filtre sau efecte dinamice asupra sunetului.

## Prezentare Vizuală

### Interfața Grafică (Front Panel)
![Front Panel](screenshots/Interfata.png)

### Logica Programului (Block Diagram)
![Block Diagram](screenshots/cod_block_diagram.png)

## Cerințe de sistem
* NI LabVIEW (recomandat versiunea cu care a fost creat sau mai nouă)
* Placă de sunet funcțională pentru redarea audio
