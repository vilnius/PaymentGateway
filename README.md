# PaymentGateway
 Integracijos techninis dokumentas: GD.013 Išrašo įkėlimas iš išorinių sistemų (Techninė specifikacija)_v1.0.pdf
- WSDL: UploadBnkStmtService.wsdl
- XSD schemos: UploadBnkStmtService_1.xsd ir UploadBnkStmtService_2.xsd
- Testinis kliento sertifikatas: kreiptis atviriduomenys@vilnius.lt

+Papildoma informacija:+
- Integracijoje naudojama Mutual SSL autentifikacija. 
- Sertifikato pateikimui: pradiniam testavimui reikia kreiptis atviriduomenys@vilnius.lt 
- Tikram sertifikatui: vėlesniame etape reikalingas CSR failas (detaliau žr. PDF failą). Sertifikatą reikia susiimportuoti į savo KeyStore ir kviečiant WS jį.nurodyti.
- Papildomai reikalingas įmonės kodas, kuris bus įtrauktas į VMS apskaitos sistemos klasifikatorių registrą.
