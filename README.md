![Sawtooth](https://raw.githubusercontent.com/splintercommunity/sawtooth-core/master/images/sawtooth_logo_light_blue-small.png)

Sawtooth Devmode
-------------

Sawtooth dev mode is a consensus engine for Sawtooth that offers a
simplified random-leader algorithm. This method is intended for testing
applications built on top of the Sawtooth platform. It is useful
when developing transaction processors, smart contracts, or other components
because of its high commit rate. Dev mode commits batches as fast as possible,
in order to provide quick feedback to the developer.

Dev mode also demonstrates how to use the Sawtooth consensus engine API for a
lottery-style consensus implementation. Developers interested in implementing
a consensus engine can use the dev mode source code as an example.

Although the dev mode consensus engine can be used in a Sawtooth network, it
has a very inefficient fork-resolution algorithm and makes no guarantees about
crash fault tolerance. It should not be used in a production environment.

Documentation
-------------

Documentation for how to run and extend Sawtooth is available here:
https://sawtooth.splinter.dev/docs/1.2/


License
-------

Sawtooth software is licensed under the [Apache License Version 2.0](LICENSE) software license.
