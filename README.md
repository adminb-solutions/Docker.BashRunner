# Shunit 2 Test Runner

Docker image to run [shunit2](https://github.com/kward/shunit2) bash tests. 

## Usage

Mount or copy all the tests you wish to run in the directory `/test`. When the container starts it will then run all the tests found in there. The tests are expected to conform to the naming standard `test_*.sh`.
