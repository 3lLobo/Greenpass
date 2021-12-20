# Covid1984 Green Pass

Just for fun. No fraud intended :ghost:

Use the decoder notebook to decode your QR-code and display the stored information.

Use the encoder notebook to encode your data into a custom QR-code.

### Important note

I thought the following would be obvious to everyone, but considering the amount of people who reached out to me privately, apparently it's not.

I posted this code just for education purposes, it can create plausible Green Pass QRs in a (mostly) correct format which are parsed correctly by the checker apps (at least the ones I tried) but obviously **no one but who has one of the "authorized" key pairs** will ever be able to generate valid signatures.

It's cryptography, there's no magic trick. You can see also in the example image that the signature verification fails.

![Green Pass QR](res/qr_new.png "Green Pass QR")
![Your Government](res/thegovt.png "Your Government")


'<p><strong>Schema version</strong>:1.3.0</p><p><strong>Date of birth</strong>:1999-03-11</p><p><strong>Surname(s), forename(s)</strong></p><p>&nbsp;<strong>Surname</strong>:Diks</p><p>&nbsp;<strong>Standardised surname</strong>:DIKS</p><p>&nbsp;<strong>Forename</strong>:Celine</p><p>&nbsp;<strong>Standardised forename</strong>:CELINE</p><p><strong>Vaccination Group</strong></p><p>&nbsp;<strong>disease or agent targeted</strong>:840539006</p><p>&nbsp;<strong>vaccine or prophylaxis</strong>:J07BX03</p><p>&nbsp;<strong>vaccine medicinal product</strong>:EU/1/20/1525</p><p>&nbsp;<strong>Marketing Authorization Holder</strong>:ORG-100001417</p><p>&nbsp;<strong>Dose Number</strong>:1</p><p>&nbsp;<strong>Total Series of Doses</strong>:1</p><p>&nbsp;<strong>ISO8601 complete date: Date of Vaccination</strong>:2021-07-06</p><p>&nbsp;<strong>Country of Vaccination</strong>:NL</p><p>&nbsp;<strong>Certificate Issuer</strong>:Ministry of Health Welfare and Sport</p><p>&nbsp;<strong>Unique Certificate Identifier: UVCI</strong>:URN:UCI:01:NL:OOAOUJ2LTFDLJEDST2VY42#I</p>'