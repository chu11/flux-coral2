flux-coral2 0.4.0 - 2023-04-07
------------------------------

### New Features

 * dws: Rabbits are chosen based on compute nodes (#53)
 * dws: Workflows in 'Error' state too long are now killed (#49)
 * dws: hold jobs in epilog for data movement (#46)
 * dws: support multiple DW directives in a single string (#54)
 * dws: package coral2_dws.py as a systemd unit (#47)
 * pals: support for `-o pmi=cray-pals` (#58)
 * pals: added an rc script for loading port distributor in all Flux instances (#58)

### Fixes

 * dws: shorten workflow names to prevent DWS overflow errors (#39)
 * build: add missing header file (#38)
 * dws: improve error messages (#54)

### Testsuite

 * testsuite: update uses of `flux mini CMD` (#50)
 * testsuite: add tests for jobtap prolog exceptions (#51)
 * github: add 'make distcheck' to CI (#48)


flux-coral2 0.3.0 - 2023-01-31
------------------------------

Initial release of DWS/Rabbit plugins.


flux-coral2 0.2.0 - 2022-10-12
------------------------------

Fixes for Cray MPI plugins



flux-coral2 0.1.0 - 2022-08-18
------------------------------

Initial release of Cray MPI plugins


flux-coral2 0.0.0 - 2021-04-14
------------------------------

Inital release - for building and testing only
