Save The Whales | Preserve and protect the ocean and its inhabitants.

Save the Whales is a worldwide nonprofit organization that began in 2018. Save the Whales continues to inspire children, the future of the planet, to know that their actions can promote change. Education is the key to saving whales, oceans, and ourselves.

Many people believe that whales have been protected by the 1986 worldwide ban on whaling, don't believe it!

Killings, captures, bombings, plastic ingestion, and pollution continue to threaten these peaceful creatures. We invite you to support Save The Whales, a widely-admired nonprofit organization that has been working tirelessly to protect marine life for 40 years.

Your contribution enables Save the Whales to continue their valuable work to protect marine mammals.
Key principle of CryptoNote is adaptive parameters. STW already has adaptive block size limit and difficulty. In addition to it STW will implement adaptive emission, adaptive minimal transaction fee and adaptive monetary deposit interest rate to achieve this goal.

Pools operating **'cryptonote-forknote-pool'** or compatible software should update Node-Cryptonote-Util to this version: https://github.com/STWcoin/node-cryptonote-util. The reference pool software is here: https://github.com/STWcoin/STWcoin-pool.

Pools operating **'cryptonote-nodejs-pool'** should _change config on hardfork height_. The changes in config are:
```
"daemonType": "default",
"cnAlgorithm": "cryptonight",
"cnVariant": 0,
"cnBlobType": 0,
```
The example of STWcoin config is here: https://github.com/STWcoin/cryptonote-nodejs-pool/blob/master/config_examples/stwcoin.json



## Building STWcoin
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcloudshin%2FSTWcoin.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcloudshin%2FSTWcoin?ref=badge_shield)


### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck and save the Whales!

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcloudshin%2FSTWcoin.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcloudshin%2FSTWcoin?ref=badge_large)