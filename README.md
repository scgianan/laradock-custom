# Laradock
This is a custom laradock workspace build php7.1 with ms sql tools support.

Clone the laradock-custom in your root directory. Dont forget to add this in the .gitignore.After cloning, cd to the laradock directory, this is where you will run docker compose.


## To start containers:
docker-compose up -d apache2 php-fpm workspace redis 

## To stop containers:
docker-compose stop

## To delete containers:
docker-compose down

## To access the workspace
docker-compose exec workspace bash

To know more about the laradock commands, please see the official documentation below.

> Use Docker first and learn about it later.

[![forthebadge](http://forthebadge.com/images/badges/built-by-developers.svg)](http://zalt.me)

Laradock is a Docker PHP development environment that facilitate running **PHP** Apps on **Docker**.

## Documentation

[**Full Documentation Here**](http://laradock.io)

## Credits

**Super Admins:**

- [Mahmoud Zalt](https://github.com/Mahmoudz) (mahmoudz)  [ [Twitter](https://twitter.com/Mahmoud_Zalt) | [Personal Site](http://zalt.me) | [LinkedIn](https://www.linkedin.com/in/mahmoudzalt) ]
- [Bo-Yi Wu](https://github.com/appleboy) (appleboy) [ [Twitter](https://twitter.com/appleboy) ]
- [Philippe Trépanier](https://github.com/philtrep) (philtrep)
- [Mike Erickson](https://github.com/mikeerickson) (mikeerickson)
- [Dwi Fahni Denni](https://github.com/zeroc0d3) (zeroc0d3)
- [Thor Erik](https://github.com/thorerik) (thorerik)
- Contribute and join us!

**Amazing Contributors:**

- [Contributors](https://github.com/laradock/laradock/graphs/contributors)

## License

[MIT License](https://github.com/laradock/laradock/blob/master/LICENSE) (MIT)
