![alt text][logo]

[logo]: https://github.com/MagnumOpuses/project-meta/blob/master/img/jobtechdev_black.png "JobTech dev logo"

[A JobTech Project](https://www.jobtechdev.se)

# AF Connect a JobtechDev Open Source Project
## Mission
Our mission with this project is to help job seekers and employers to find each other, to boost innovation within the labor market and to create opportunities for all actors within the industry sector.
## Vision
Arbetsförmedlingen has made the commitment to implement parts of the MyData principles within the JobTech MyData initiative.

“ MyData Global is a registered non-profit association and a global network with the mission to empower individuals by improving their right to self-determination regarding their personal data . "  
[Read more about MyData principles](https://mydata.org/)


![](AF-Connect-Demo.gif)

## Definitions:
* User(s): Job-seekers, individually that passively or actively are seeking for employmenet.
* Client(s): Generally businesses that handles CV-data within the job market (not employers). E.g. Job sites, Talent Tracking Systems, Research agencies etc.

## Product description:
An intermediate layer between systems in the labor market where the individual is given the opportunity to handle approval of what information is to be shared and to whom.

## Product features:
* Export of CV-data from Swedish Public Employment Service (AF);
* Import of CV-data: An API allowing third parties to receive CV data from AF;
* CV-data standardization: A mapping allowing third parties to understand the data sent;
* User consent: An interface where the individual requests the collection of own data and handles the consent for the data transfer;

## Architectural constituent:
* Storage: Users store their CV profiles on Swedish Public Employment Service site;
* Consent: A middleware where users handle the consent to transfer their data;
* Operator: Technical service that coordinates information flows between services;
* Encryption: Modules to facilitate and ensure that data is encrypted upon creation, transfer and consumption..

## Software modules
* [AF Connect](https://github.com/MagnumOpuses/af-connect)
* [AF Connect Demo](https://github.com/MagnumOpuses/af-connect-demo)
* [AF Connect Module](https://github.com/MagnumOpuses/af-connect-module)
* [AF Portability](https://github.com/MagnumOpuses/af-portability)
* [Common CV Model](https://github.com/MagnumOpuses/common-cv-model)

## Contributing

We would love if you'd like to help us build and improve this product for the benefit of everyone. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org/) code of conduct.

Any contributions, feedback and suggestions are more than welcome.

Please read our guidelines for contribution [here](CONTRIBUTING_TEMPLATE.md).

## License

[Apache License 2.0](LICENSE.md)

## Acknowledgments

No acknowledgments yet.
