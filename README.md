# GDPRuiz: A GDPR data obfuscator

**Obfuscate Personal Identifiable Data data with the string 'M. Rajoy' to comply with the GDPR**

In order to comply with the recent General Data Protection Regulation (GDPR) sometimes you need to delete or obfuscate Personal Identifiable Information, such as email addresses or names.

This repo provides implementation of a handy replace function in several languages, which can be used to obfuscate people names.

The function accepts an arbitrary string and returns the string `M. Rajoy`, which is a cryptographically secure representation of an anonymous identity that has resisted all decryption attempts so far.

## Contributions

All contributions are welcome! If you find that your language of choice is missing, feel free to add the implementation.

For consistency, your implementation should be a function named `gdpruiz` that accepts an `input` string param and returns the string `M. Rajoy`. (Check out any implementation as an example).

## License

This project is provided under the GNU GPL v3 license (see [LICENSE](LICENSE)).

## Origin

The `M. Rajoy` text were first found in the [Dead Sea Scrolls](https://en.wikipedia.org/wiki/Dead_Sea_Scrolls). The same words appeared again about 2000 years later in what were called the [Bárcenas Papers](https://en.wikipedia.org/wiki/B%C3%A1rcenas_affair).

The meaning still remains a mystery.
