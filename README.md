# cc2

Second set of examples to test confidential computing options

1) Start confisum, it starts a simple html gui on :8080 (unless u pass a httpPort=... flag)
2) Start encryptor - port :8090 by default
3) copy "session key" (the enclave public key) form confisum to encryptor
4) ...

You can filter the confisum gui by passing playerno=0|1|2 parameter in the url

An exaple private key (any hex-encoded 32-byte string will do):
c70426899a815facf48177fe6405c64c013d9e94a08678fb844c85df69d57f4c
