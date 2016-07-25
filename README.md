# MongoDbServiceProvider

[![Software License][ico-license]](LICENSE.md)

It's a MongoDbServiceProvider that's using the new Mongo Db library and extension (ie:`ext-mongodb`) for PHP 5.x, PHP 7.x and HHVM.

## Motivation
The motivation to public this service provider for silex, is because the others services provider for mongo are using the deprecated extension `ext-mongo`, instead the new extension `ext-mongodb`, created by Derick Rethans, Jeremy Mikola and Hannes Magnusson.

### MongoDb extension
You can read more about `ext-mongodb` here: the [History](https://derickrethans.nl/new-drivers.html), [Architecture](https://derickrethans.nl/new-drivers-part2.html), [Cursor Behaviour](https://derickrethans.nl/new-drivers-part3-cursor.html) and [PHP Documentation](http://php.net/manual/en/set.mongodb.php). This new extension improved the performance and allowed the support for PHP 5, PHP 7 and HHVM.

### PHP library for MongoDB 
This Service Provider use the recommend PHP library for MongoDb, too. You can read more about [here](http://php.net/manual/en/mongodb.tutorial.library.php).

## License
The MIT License (MIT). Please see [License File](https://github.com/marcusesa/MongoDbServiceProvider/blob/master/LICENSE) for more information.

[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
