## RKVR uue x-tee teenuse spetsifikatsioon (draft, viited olemasoleva [wsdl](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl)'i andmeelementidele)

Teenuse esimeseks tarbijaks on kinnistusraamat, kus selle abil kuvatakse kinnistu riigivara valitseja jm andmeid. 

### Sisend

Nr | Name | Type | Title
------------ | ------------- | ------------- | -------------
1 | [roNumber](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L358) | string | Kinnistu registriosa number

### Väljund

Nr | Name | Type | Title
------------ | ------------- | ------------- | -------------
1 | [roNumber](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L358) | string | Kinnistu registriosa number
2 | [objektiKood](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L15) | string | Riigi kinnisvararegistri vara kood
3 | [valitseja](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L316) | string | Valitseja registrikood
4 | [volitatud](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L323) | string | Volitatud asutuse registrikood
5 | [volitus](https://github.com/kinnisvara/RKVR/blob/master/rkvr.wsdl#L346) | date | Valitsemise algusaeg
6 | varaURL | string | Vara URL
