# PaymentGateway
 Integracijos techninis dokumentas: GD.013 Išrašo įkėlimas iš išorinių sistemų (Techninė specifikacija)_v1.0.pdf
- WSDL: UploadBnkStmtService.wsdl
- XSD schemos: UploadBnkStmtService_1.xsd ir UploadBnkStmtService_2.xsd
- Testinis kliento sertifikatas: kreiptis atviriduomenys@vilnius.lt

+Papildoma informacija:+
- Integracijoje naudojamas Mutual SSL autentifikacija. 
- Pradiniam testavimui reikia kreiptis atviriduomenys@vilnius.lt, kad pateikti  sertifikatą. 
- Vėlesniame etape reikalingas CSR failas tikram sertifikatui, detaliau žr. PDF failą. Sertifikatą reikia susiimportuoti į savo KeyStore ir kviečiant WS nurodyti jį.
- Papildomai reikalingas įmonės kodas, kuris bus įtrauktas į VMS apskaitos sistemos klasifikatorių registrą.
