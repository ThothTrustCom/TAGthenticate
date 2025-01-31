# Overview #
## About TAGthenticate ##
TAGthenticate is a product authentication and attestation technology developed by ThothTrust since 2022. TAGthenticate integrates an NFC tag that stores small amounts of critical provenance information together with a randomly generated ECC keypair on the NFC tag's JavaCard secure element used to identify and attest to the product it is paired to.

TAGthenticate currently uses the Ethereum blockchain to create an immutable link to the product description (provenance information) via inserting a provenance certificate hash to the Ethereum blockchain transaction.

Detailed product information are stored in the IPFS network that can be queried on demand.

## About TAGthenticate Applet License ##
The TAGthenticate Applet is a JavaCard applet developed by ThothTrust for the NFC secure element used in the TAGthenticate production authentication system. The JavaCard applet source code is currently not open to the public as a proprietary codebase.

The published APDU commands and responses in the repository's resources are open to the public.

## About The TAGthenticate Public Git Repository ##
The TAGthenticate Public Git repository will host publicly available information and APIs regarding the TAGthenticate system and product line for developers to tinker around with the NFC tags they acquired from us or our partners.

Open source implementations regarding the TAGthenticate system will also be posted in this repository and discussions and issues for open source implementations can be raised here.

## Brief Overview of TAGthenticate Applet Features ##
The Tagthenticate Applet is a custom applet specifically designed for the Tagthenticate System’s Blockchain Based Digital Attestation use case. The applet maybe used to store and attest to critical pieces of digital information and assets not more than 255 bytes in size.

One of the most important use case for the Tagthenticate Applet is to be used for digital attestation of physical or digital objects. The Tagthenticate Applet supports ECC-P256K1 private key algorithm that is used in Bitcoin, Ethereum and many other types of Blockchains. The applet also reserves 255 bytes of memory to store important descriptors and information of the object to be attested (i.e. smart contract address).

The private key maybe used to host an initial value for the Blockchain and to publish its smart contract in the beginning phases of the deployment of the applet with a subsequent attestation of the applet via its replay attack resistant Digital Signature Challenge-Response based digital attestation protocol.

## Potential Use Cases for TAGthenticate Applet ##
Below are a list of conventional and unconventional use cases which the TAGthenticate Applet maybe used. More ideas can be generated base on the applet's capabilities described above.

* Product authentication and attestation 
	* Backed by blockchain and distributed metadata information storage platform.
	* Backed by centralized PKI and metadata information storage platform.

* Digital signing applet when applet is used in `LOADED` state(ECC-P256K1 curve only).

* IIoT deployment to authenticate to distributed node's identity.
	* Simple IoT node identification scheme through ECC digital signature challenge and response.
	* QFN packaging for PCB board mounting can be requested.

## Resources ##


## Products with TAGthenticate Applet ##
Below are a list of known partners distributing the TAGthenticate Applet equipped products and solutions.

* [CodeWav NFC Sticker Tag Micro Edition](https://www.codewav.com/product-page/codewav-module-nfc-tag)

## Opening Support Cases ##
Support cases maybe opened for open source codebases hosted in the Github repository. Product related cases should be opened via emailing the partner whom you have purchase the product from.