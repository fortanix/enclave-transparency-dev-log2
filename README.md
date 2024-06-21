# Dev Log for Enclave Transparency

This repository contains the development enclave transparency log. This
log contains the enclave measurements of debug-signed enclaves for
test deployments. A separate log, with a different log signing
key, is used for production-signed enclave measurements.

# Key Name

The key name (for Note purposes) is fortanix_enclave_transparency_dev

# Log Name

The log name (for enclave transparency tooling purposes) is fortanix_enclave_transparency_dev_log2

# Log Public Key

The log's public key is the file public_key. This file is in the Golang Note format. This key is
used when sequencing new log entries with the sequence command and retrieiving log inclusion
proofs with the client command.
