# Kerberos
This system uses PHP CIBonfire framwork as the backend.
This is commercial product used by manufacturers.
### Introduction
Use this link to read introduction: https://github.com/Shujjat/PHP/blob/main/Kerberos/Kerberous%20Introduction.pdf
### Ad
Click here to watch its video: https://www.youtube.com/watch?v=47j7U6FU2X4

### Components
This system has four main parts: EncryptCodeGenerator, EncryptCodeVerifier, SupplyChainManager, HyperLedger

### EncryptCodeGenerator
This system generates the required EncryptCodes (using our state of the art process, which generates unique, non-guessable one time used), inserts them in the HyperLedger and locks it with a SerialNumber. 

### EncryptCodeVerifier
This is the verification system which interfaces over WhatsApp, SMS, Email, Web or apps to recieve the EncryptCodeVerificationRequests. It returns whether the EncryptCode provided with the request is 
valid or not.

### SupplyChainManager
This subsystem takes care which product unit is shipped where. Using the SerailNumbers of the produced EncryptCodes, the system can be helpful in tracking which unit was sent where.

### HyperLedger
This is the main entry sheet recording each EncryptCode and its allocation and other metadata. It ensures every produced EncryptCode is maintained and tracked well. And every transaction is recorded in an 
immutable fashion.

### Demo
Live demo is available on demand. Send an email to me for a demo (shujjat.shirafat@gmail.com). Mention KerberosDemo in the subject.


### Pricing
Send an email to me for a pricing options (shujjat.shirafat@gmail.com). Mention KerberosDemo in the subject.



