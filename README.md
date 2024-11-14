# Car Sales table data
- Data contained in the CarForSale, Centre, Salesperson, CarDetails, and Customer tables


1. Centre table

|CENTRENUMBER|NAME                          |ADDRESS                                           |EMAIL                         |PHONENUMBER   |CREATEDAT              |
|------------|------------------------------|--------------------------------------------------|------------------------------|--------------|-----------------------|
|CEN001      |Williams Landrover            |24 BARTON DOCK ROAD, Manchester, Lancashire       |williamsgroup@mail.co.uk      |01619376765   |2024-11-14 11:07:14.595|
|CEN002      |Vertu Motors Land Rover Nelson|TURNER ROAD, Nelson, Lancashire                   |vertumotors@mail.co.uk        |01282522836   |2024-11-14 11:07:14.602|
|CEN003      |Bristol Street Motors         |South Side, Eleanor Cross Road, Hertfordshire     |bristolstreet@mail.co.uk      |01992843665   |2024-11-14 11:07:14.608|
|CEN004      |Wings Skoda Peterborough      |FENLAKE BUSINESS CENTRE, FENGATE, Northamptonshire|wingsskoda@mail.co.uk         |01733850432   |2024-11-14 11:07:14.618|
|CEN005      |Johnsons Mazda Solihull       |Highlands Road, Solihull, West Midlands           |johnsonscars@mail.co.uk       |01216596666   |2024-11-14 11:07:14.626|



2. Salesperson table

|SALESPERSONNUMBER|FIRSTNAME                     |LASTNAME                      |ADDRESS                                           |PHONENUMBER   |EMAIL                         |CENTRENUMBER|CREATEDAT              |
|-----------------|------------------------------|------------------------------|--------------------------------------------------|--------------|------------------------------|------------|-----------------------|
|SAL001           |Luke                          |Bizza                         |Queen Street, Pontypridd, UK                      |              |lukebizza@mail.co.uk          |CEN001      |2024-11-14 11:07:14.789|
|SAL002           |Elizabeth                     |Mongera                       |Bertha Street, Pontypridd, UK                     |              |elizabethmongera@mail.co.uk   |CEN002      |2024-11-14 11:07:14.795|
|SAL003           |Mirriam                       |Wanjiru                       |Llantwit Road, Pontypridd, UK                     |447712345678  |mirriamwanjiru@mail.co.uk     |CEN003      |2024-11-14 11:07:14.800|
|SAL004           |Chris                         |Njagi                         |llandaff, Cardiff, UK                             |447456789012  |chrisnjagi@mail.co.uk         |CEN004      |2024-11-14 11:07:14.804|
|SAL005           |Dairus                        |Chikini                       | Aberdulais Road, Cardiff, UK                     |447598112233  |dairuschikini@mail.co.uk      |CEN005      |2024-11-14 11:07:14.809|
|SAL006           |Jabez                         |Mzito                         |,Aberdulais Road  Cardiff, UK                     |447812 334455 |jabezmzito@mail.co.uk         |CEN001      |2024-11-14 11:07:14.813|
|SAL007           |Janet                         |Smith                         |Beresford Road , Cardiff, UK                      |              |janetsmith@mail.co.uk         |CEN002      |2024-11-14 11:07:14.820|
|SAL008           |Newton                        |Zari                          |Bisley Close, Cardiff, UK                         |447945667788  |newtonzari@mail.co.uk         |CEN003      |2024-11-14 11:07:14.824|
|SAL009           |Martin                        |Shmoze                        |Ilsyn Grove, Bristol, UK                          |447564998877  |martinshmoze@mail.co.uk       |CEN004      |2024-11-14 11:07:14.831|
|SAL010           |Diamond                       |Platinumz                     |Irby Road, Bristol, UK                            |447300223344  |diamondplatinumz@mail.co.uk   |CEN005      |2024-11-14 11:07:14.837|
|SAL011           |Nandi                         |Billnass                      |Jocelyn Road, Bristol, UK                         |              |nandibillnass@mail.co.uk      |CEN002      |2024-11-14 11:07:14.843|
|SAL012           |Ruger                         |Mwakazi                       |Kellaway Crescent, Bristol, UK                    |              |rugermwakazi@mail.co.uk       |CEN003      |2024-11-14 11:07:14.848|
|SAL013           |Zion                          |lala                          |Kempton Close, Bristol, UK                        |447458123987  |zionlala@mail.co.uk           |CEN001      |2024-11-14 11:07:14.853|



3. Customer table

|CUSTOMERNUMBER|FIRSTNAME                     |LASTNAME                      |PHONENUMBER   |EMAIL                         |ADDRESS                                           |BADDEBTOR|CENTRENUMBER|CREATEDAT              |
|--------------|------------------------------|------------------------------|--------------|------------------------------|--------------------------------------------------|---------|------------|-----------------------|
|CUS001        |Hillary                       |Mongare                       |01235578836   |hillarymongare70@gmail.com    |45 Westbourne Road, London, W11 2BS               |0        |CEN001      |2024-11-14 11:07:14.679|
|CUS002        |Justus                        |Ofweneke                      |02244578836   |justusofweneke@gmail.com      |7 Oak Avenue, Manchester, M20 3LD                 |1        |CEN002      |2024-11-14 11:07:14.687|
|CUS003        |Mirriam                       |Akinyi                        |01669978811   |mirriamakinyi@gmail.com       |21 Highfield Street, Birmingham, B12 8QN          |0        |CEN001      |2024-11-14 11:07:14.693|
|CUS004        |Innocent                      |Mandu                         |08839978836   |innocentmandu@gmail.com       |128 Kings Road, Brighton, BN1 2FA                 |0        |CEN002      |2024-11-14 11:07:14.698|
|CUS005        |Yvonne                        |Mureithi                      |01776674436   |yvonnemureithi@gmail.com      |62 Maple Crescent, Cardiff, CF14 2JL              |1        |CEN002      |2024-11-14 11:07:14.702|
|CUS006        |Diana                         |Kairetu                       |01581174436   |dianakairetu@gmail.com        |9 Rose Lane, Bristol, BS6 5TU                     |0        |CEN003      |2024-11-14 11:07:14.707|
|CUS007        |Bill                          |Miregwa                       |01661277736   |billmiregwa@mail.co.uk        |34 Elmwood Drive, Leeds, LS8 2FG                  |0        |CEN002      |2024-11-14 11:07:14.710|
|CUS008        |Collins                       |Mongare                       |01446611436   |collinsmongare@gmail.com      |78 Parkside Road, Glasgow, G44 3AB                |0        |CEN003      |2024-11-14 11:07:14.714|
|CUS009        |Winnie                        |Miregwa                       |07590074406   |winniemiregwa@gmail.com       |14 Millbank Street, Edinburgh, EH8 9NG            |0        |CEN004      |2024-11-14 11:07:14.719|
|CUS010        |Jack                          |Ma                            |01788134536   |jackma@gmail.com              |6 Riverside Avenue, Liverpool, L7 2DW             |1        |CEN005      |2024-11-14 11:07:14.724|
|CUS011        |Lucy                          |Githinji                      |07551089906   |lucygithinji@gmail.com        |19 Castle Street, Nottingham, NG1 6FG             |0        |CEN004      |2024-11-14 11:07:14.729|
|CUS012        |Brian                         |Bahati                        |07661055406   |brianbahati@gmail.com         |50 Victoria Way, Newcastle upon Tyne, NE1 7RH     |0        |CEN005      |2024-11-14 11:07:14.734|
|CUS013        |John                          |Doe                           |07661088406   |johndoe@email.com             |123 Main St, City A                               |0        |CEN001      |2024-11-14 11:07:14.738|
|CUS014        |Jane                          |Smith                         |07668885406   |janesmith@email.com           |456 Elm St, City B                                |1        |CEN002      |2024-11-14 11:07:14.743|
|CUS015        |Alice                         |Johnson                       |07681855408   |alicejohnson@email.com        |789 Maple St, City C                              |0        |CEN003      |2024-11-14 11:07:14.748|



4. Car Details table

|CARNUMBER|CARMAKE                       |CARMODEL                      |CARMANUFACTUREYEAR|CARTYPE                       |CARCOLOR                      |CARTRANSMISSION|CARCONDITION|CARFUELTYPE                   |CARPRICE|
|---------|------------------------------|------------------------------|------------------|------------------------------|------------------------------|---------------|------------|------------------------------|--------|
|CAR001   |Toyota                        |Corolla                       |2020              |Sedan                         |Red                           |automatic      |new         |Petrol                        |15,000  |
|CAR002   |Honda                         |Civic                         |2019              |Sedan                         |Blue                          |manual         |used        |Petrol                        |12,000  |
|CAR003   |Ford                          |Focus                         |2018              |Hatchback                     |White                         |automatic      |used        |Diesel                        |10,000  |
|CAR004   |BMW                           |3 Series                      |2021              |Sedan                         |Black                         |automatic      |new         |Diesel                        |25,000  |
|CAR005   |Nissan                        |Altima                        |2017              |Sedan                         |Grey                          |manual         |used        |Petrol                        |8,000   |
|CAR006   |Chevrolet                     |Malibu                        |2018              |Sedan                         |Silver                        |automatic      |used        |Petrol                        |11,000  |
|CAR007   |Volkswagen                    |Golf                          |2019              |Hatchback                     |Blue                          |automatic      |used        |Diesel                        |13,000  |
|CAR008   |Mazda                         |CX-5                          |2020              |SUV                           |White                         |automatic      |new         |Petrol                        |18,000  |
|CAR009   |Mercedes-Benz                 |C-Class                       |2022              |Sedan                         |Black                         |automatic      |new         |Diesel                        |30,000  |
|CAR010   |Hyundai                       |Tucson                        |2019              |SUV                           |Red                           |manual         |used        |Petrol                        |14,000  |
|CAR011   |Audi                          |A4                            |2021              |Sedan                         |Grey                          |automatic      |new         |Diesel                        |28,000  |
|CAR012   |Lexus                         |RX 350                        |2020              |SUV                           |White                         |automatic      |new         |Petrol                        |35,000  |
|CAR013   |Kia                           |Sorento                       |2018              |SUV                           |Black                         |manual         |used        |Petrol                        |10,000  |
|CAR014   |Jeep                          |Wrangler                      |2022              |SUV                           |Green                         |automatic      |new         |Diesel                        |40,000  |
|CAR015   |Toyota                        |RAV4                          |2021              |SUV                           |Silver                        |automatic      |new         |Petrol                        |26,000  |
|CAR016   |Subaru                        |Forester                      |2017              |SUV                           |Blue                          |manual         |used        |Diesel                        |9,000   |
|CAR017   |Ford                          |Explorer                      |2022              |SUV                           |Black                         |automatic      |new         |Petrol                        |27,000  |
|CAR018   |Volvo                         |XC90                          |2021              |SUV                           |Black                         |automatic      |new         |Diesel                        |50,000  |
|CAR019   |Honda                         |Accord                        |2020              |Sedan                         |Grey                          |automatic      |new         |Petrol                        |23,000  |
|CAR020   |Toyota                        |Camry                         |2022              |Sedan                         |Blue                          |automatic      |new         |Petrol                        |27,000  |
|CAR021   |Toyota                        |Corolla                       |2020              |Sedan                         |Red                           |automatic      |new         |Petrol                        |15,000  |
|CAR022   |Nissan                        |Altima                        |2020              |Sedan                         |Red                           |manual         |new         |Petrol                        |18,000  |
|CAR023   |Chevrolet                     |Impala                        |2018              |Sedan                         |White                         |automatic      |used        |Petrol                        |12,000  |
|CAR024   |Mazda                         |CX-9                          |2019              |SUV                           |Black                         |automatic      |used        |Diesel                        |26,000  |
|CAR025   |Honda                         |Civic                         |2021              |Sedan                         |Blue                          |automatic      |new         |Petrol                        |20,000  |
|CAR026   |Hyundai                       |Elantra                       |2019              |Sedan                         |Gray                          |manual         |used        |Petrol                        |14,000  |
|CAR027   |Ford                          |Escape                        |2020              |SUV                           |Silver                        |automatic      |used        |Hybrid                        |22,000  |
|CAR028   |Kia                           |Sorento                       |2021              |SUV                           |White                         |automatic      |new         |Diesel                        |28,000  |
|CAR029   |Volkswagen                    |Golf                          |2018              |Hatchback                     |Red                           |manual         |used        |Petrol                        |16,000  |
|CAR030   |Subaru                        |Outback                       |2021              |SUV                           |Green                         |automatic      |new         |Diesel                        |30,000  |
|CAR031   |Toyota                        |RAV4                          |2022              |SUV                           |White                         |automatic      |new         |Hybrid                        |32,000  |
|CAR032   |Mazda                         |CX-5                          |2021              |SUV                           |Black                         |automatic      |new         |Petrol                        |31,000  |
|CAR033   |BMW                           |X3                            |2023              |SUV                           |Blue                          |automatic      |new         |Diesel                        |42,000  |
|CAR034   |Audi                          |Q5                            |2022              |SUV                           |Gray                          |automatic      |new         |Petrol                        |45,000  |
|CAR035   |Mercedes                      |GLC                           |2023              |SUV                           |Silver                        |automatic      |new         |Diesel                        |48,000  |
|CAR036   |Lexus                         |NX                            |2023              |SUV                           |Red                           |automatic      |new         |Hybrid                        |47,000  |



5. Car for Sale table

|CENTRENUMBER|SALESPERSONNUMBER|CUSTOMERNUMBER|CARNUMBER|COMMISSIONRATE|SOLD|SALEDATE               |ARCHIVED|
|------------|-----------------|--------------|---------|--------------|----|-----------------------|--------|
|CEN001      |SAL001           |CUS001        |CAR001   |4             |1   |2024-01-15 00:00:00.000|1       |
|CEN002      |SAL002           |CUS002        |CAR002   |4             |1   |2023-11-05 00:00:00.000|1       |
|CEN001      |SAL003           |CUS003        |CAR003   |3             |1   |2023-08-10 00:00:00.000|1       |
|CEN003      |SAL004           |CUS004        |CAR004   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN001      |SAL003           |CUS004        |CAR005   |3             |1   |2023-09-22 00:00:00.000|1       |
|CEN002      |SAL004           |CUS005        |CAR006   |4             |0   |2024-01-10 00:00:00.000|0       |
|CEN003      |SAL006           |CUS007        |CAR007   |4             |1   |2023-12-20 00:00:00.000|0       |
|CEN002      |SAL002           |CUS008        |CAR008   |5             |1   |2023-10-25 00:00:00.000|1       |
|CEN001      |SAL007           |CUS009        |CAR009   |5             |0   |2023-01-01 00:00:00.000|0       |
|CEN002      |SAL008           |CUS010        |CAR010   |4             |1   |2023-07-15 00:00:00.000|1       |
|CEN003      |SAL009           |CUS011        |CAR011   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN001      |SAL010           |CUS012        |CAR012   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN003      |SAL006           |CUS001        |CAR013   |3             |0   |2023-11-30 00:00:00.000|0       |
|CEN002      |SAL003           |CUS002        |CAR014   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN001      |SAL004           |CUS003        |CAR015   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN003      |SAL005           |CUS004        |CAR016   |3             |1   |2023-06-18 00:00:00.000|1       |
|CEN001      |SAL006           |CUS005        |CAR017   |5             |1   |2024-03-01 00:00:00.000|0       |
|CEN003      |SAL001           |CUS006        |CAR018   |5             |0   |2024-01-01 00:00:00.000|0       |
|CEN002      |SAL002           |CUS007        |CAR019   |5             |0   |2023-08-12 00:00:00.000|1       |
|CEN001      |SAL003           |CUS008        |CAR020   |5             |0   |2024-07-15 00:00:00.000|0       |
|CEN001      |SAL001           |CUS002        |CAR021   |4             |1   |2024-10-01 00:00:00.000|0       |
|CEN005      |SAL009           |CUS010        |CAR022   |5             |1   |2024-10-12 00:00:00.000|0       |
|CEN001      |SAL011           |CUS012        |CAR023   |4             |1   |2024-10-06 00:00:00.000|0       |
|CEN002      |SAL004           |CUS001        |CAR024   |5             |1   |2024-10-09 00:00:00.000|0       |
|CEN003      |SAL007           |CUS012        |CAR025   |5             |1   |2024-09-21 00:00:00.000|0       |
|CEN004      |SAL002           |CUS004        |CAR026   |4             |1   |2024-08-30 00:00:00.000|0       |
|CEN002      |SAL002           |CUS005        |CAR027   |5             |1   |2024-09-15 00:00:00.000|0       |
|CEN005      |SAL010           |CUS006        |CAR028   |5             |1   |2024-09-25 00:00:00.000|0       |
|CEN003      |SAL003           |CUS008        |CAR029   |5             |1   |2024-10-02 00:00:00.000|0       |
|CEN001      |SAL003           |CUS007        |CAR030   |5             |1   |2024-10-10 00:00:00.000|0       |
|CEN002      |SAL011           |CUS012        |CAR031   |5             |1   |2024-10-20 00:00:00.000|0       |
|CEN001      |SAL009           |CUS011        |CAR032   |5             |1   |2024-10-25 00:00:00.000|0       |
|CEN003      |SAL004           |CUS010        |CAR033   |5             |1   |2024-11-02 00:00:00.000|0       |
|CEN005      |SAL004           |CUS009        |CAR034   |5             |1   |2024-11-05 00:00:00.000|0       |
|CEN004      |SAL005           |CUS008        |CAR035   |5             |1   |2024-11-08 00:00:00.000|0       |
|CEN002      |SAL005           |CUS007        |CAR036   |5             |1   |2024-11-12 00:00:00.000|0       |

