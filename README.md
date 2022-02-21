
<!-- ABOUT THE PROJECT -->
## SaTT Wallet API
<p align="center">
  <img 
   width="100"
  height="100"
  src="docs/img/logo-s.png"
  >
</p>

Welcome to SaTT Webservice endpoint, this backend provides webservice to SaTT WebWallet and advertising campaign manager : [Wallet](https://satt.atayen.us/)

It provides :
* Masterseed HD Wallet management for SaTT and other main cryptos.
* Transaction management
* Advertising campaign management


### Built With

This projetct is build in JavaScript for NodeJS and these main npm modules :
* [Express](https://expressjs.com/)
* [Mongodb](https://github.com/mongodb/node-mongodb-native)
* [Web3.js](https://web3js.readthedocs.io/en/v1.3.0/)                   
* [Passport.js](http://www.passportjs.org/)
* [bn.js](https://github.com/indutny/bn.js/)



<!-- GETTING STARTED -->



## Usage

After you run the project, you can navigate to [https://localhost:3015/docs](http://localhost:3015/docs) to see the full list of available endpoints.
## Project Structure
The folder structure of this app is explained below:


| Name                     | Description                                                                                   |
| ------------------------ | --------------------------------------------------------------------------------------------- |
| **node_modules**         | Contains all  npm dependencies                                                                |
| **helpers**              | Contains all requirements and the cron job actions                                            |
| **manager**              | Contains all the definitions of oracles                                                       |
| **conf**                 | Contains all configuration for the blockChain part.                                           |
| **controllers**          | Controllers define functions to serve various express routes.                                 |
| **routes**               | Contain all express routes, separated by module/area of application .                         |
| **middlewares**          | Express middlewares which process the incoming requests before handling them down to the routes
| **routes**               | Contain all express routes, separated by module/area of application                           |
|  app.js                  | Entry point to express app                                                                    |
| package.json             | Contains npm dependencies as well as the scripts  
                                                                                                                           |



<!-- Project Structure -->

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Atayen/node-satt/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

For more information don't hesitate to contact us by email to dev@atayen.us
