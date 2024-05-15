# Google Tink

A multi-language, cross-platform library that provides cryptographic APIs that are secure, easy to use correctly, 
and hard(er) to misuse. See also: https://developers.google.com/tink.

The Tink Cryptography Library is split into multiple repositories.

Tink implementation | Repository
------------------- | ----------
Tink Java           | [tink-crypto/tink-java](https://github.com/tink-crypto/tink-java)
Tink C++            | [tink-crypto/tink-cc](https://github.com/tink-crypto/tink-cc)
Tink Go             | [tink-crypto/tink-go](https://github.com/tink-crypto/tink-go)
Tink Python         | [tink-crypto/tink-py](https://github.com/tink-crypto/tink-py)
Tink Obj-C          | [tink-crypto/tink-objc](https://github.com/tink-crypto/tink-objc)

We provide a command line interface for key management, named [Tinkey](https://github.com/tink-crypto/tink-tinkey)              

We also provide integrations with various key management systems (KMS) and other systems.

Tink extension                         | Repository
-------------------------------------- | ----------
Tink Java AWS KMS extension            | [tink-crypto/tink-java-awskms](https://github.com/tink-crypto/tink-java-awskms)
Tink Java Google Cloud KMS extension   | [tink-crypto/tink-java-gcpkms](https://github.com/tink-crypto/tink-java-gcpkms)
Tink Java apps extension               | [tink-crypto/tink-java-apps](https://github.com/tink-crypto/tink-java-apps)
Tink Java HashiCorp Vault KMSextension | [tink-crypto/tink-java-hcvault](https://github.com/tink-crypto/tink-java-hcvault)
Tink C++ AWS KMS extension             | [tink-crypto/tink-cc-awskms](https://github.com/tink-crypto/tink-cc-awskms)
Tink C++ Google Cloud KMS extension    | [tink-crypto/tink-cc-gcpkms](https://github.com/tink-crypto/tink-cc-gcpkms)
Tink Go AWS KMS extension              | [tink-crypto/tink-go-awskms](https://github.com/tink-crypto/tink-go-awskms)
Tink Go Google Cloud KMS extension     | [tink-crypto/tink-go-gcpkms](https://github.com/tink-crypto/tink-go-gcpkms)
Tink Go HashiCorp Vault KMS extension  | [tink-crypto/tink-go-hcvault](https://github.com/tink-crypto/tink-go-hcvault)
