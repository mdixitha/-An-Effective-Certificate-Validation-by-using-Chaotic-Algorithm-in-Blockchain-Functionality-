
# An Effective Certificate Validation by using Chaotic Algorithm in Blockchain Functionality:

### I designed a validation system for blockchains using Python, employing a chaotic algorithm to verify hash values and guarantee the integrity of stored certificates. This implementation significantly bolstered security measures, effectively mitigating risks associated with tampering and enhancing protection for sensitive data.

Library for verifying blockchain certificates.

## Using the pypi package

The most common way to use this is to add the [latest cert-verifier pypi package](https://badge.fury.io/py/cert-verifier) to your project dependencies. 

## Verify a certificate by command line

1. Ensure you have an python environment. [Recommendations](https://github.com/blockchain-certificates/cert-issuer/blob/master/docs/virtualenv.md)

2. Git clone the repository and change to the directory

  ```bash
  git clone https://github.com/blockchain-certificates/cert-verifier.git && cd cert-verifier
  ```

3. Run cert-viewer setup

  ```bash
  pip install .
  ```

4. Run the main program

  ```bash
  cd cert_verifier
  python verifier.py
  ```
  
## Verification process

[Read about how Blockcerts verification works](https://github.com/blockchain-certificates/cert-verifier-js#verification-process)

## Unit tests

This project uses tox to validate against several python environments.

1. Ensure you have an python environment. [Recommendations](https://github.com/blockchain-certificates/cert-issuer/blob/master/docs/virtualenv.md)

2. Run tests
    ```
    ./run_tests.sh
    ```
