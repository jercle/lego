# Export shell-env for OracleCloud

## In Bash

```
export OCI_PRIVKEY_FILE="/.oci/oci_api_key.pem"
export OCI_PRIVKEY_PASS="secret"
export OCI_TENANCY_OCID="ocid1.tenancy.oc1..secret"
export OCI_USER_OCID="ocid1.user.oc1..secret"
export OCI_PUBKEY_FINGERPRINT="00:00:00:00:00:00:00:00:00:00:00:00:00:00:00:00"
export OCI_REGION="us-phoenix-1"
export OCI_COMPARTMENT_OCID="ocid1.tenancy.oc1..secret"
```

```
export OCI_PRIVKEY=`base64 ~/.oci/oci_api_key.pem`
export OCI_PRIVKEY_PASS="secret"
export OCI_TENANCY_OCID="ocid1.tenancy.oc1..secret"
export OCI_USER_OCID="ocid1.user.oc1..secret"
export OCI_PUBKEY_FINGERPRINT="00:00:00:00:00:00:00:00:00:00:00:00:00:00:00:00"
export OCI_REGION="us-phoenix-1"
export OCI_COMPARTMENT_OCID="ocid1.tenancy.oc1..secret"
```

## In Fish

```
set -x OCI_PRIVKEY_FILE '~/.oci/oci_api_key.pem'
set -x OCI_PRIVKEY_PASS 'secret'
set -x OCI_TENANCY_OCID 'ocid1.tenancy.oc1..secret'
set -x OCI_USER_OCID 'ocid1.user.oc1..secret'
set -x OCI_PUBKEY_FINGERPRINT '00:00:00:00:00:00:00:00:00:00:00:00:00:00:00:00'
set -x OCI_REGION 'us-phoenix-1'
set -x OCI_COMPARTMENT_OCID 'ocid1.tenancy.oc1..secret'
```

```
set IFS
set -x OCI_PRIVKEY (base64 ~/.oci/oci_api_key.pem)
set IFS \n" "\t

set -x OCI_PRIVKEY_PASS 'secret'
set -x OCI_TENANCY_OCID 'ocid1.tenancy.oc1..secret'
set -x OCI_USER_OCID 'ocid1.user.oc1..secret'
set -x OCI_PUBKEY_FINGERPRINT '00:00:00:00:00:00:00:00:00:00:00:00:00:00:00:00'
set -x OCI_REGION 'us-phoenix-1'
set -x OCI_COMPARTMENT_OCID 'ocid1.tenancy.oc1..secret'
```