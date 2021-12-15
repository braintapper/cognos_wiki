# NIST Conformance



Filesystem Location

`/ibm/cognos/analytics/jre/lib/security`
OR
`/ibm/cognos/analytics/ibm-jre/jre/lib/security/policy/unlimited`

Copy `local_policy.jar` and `US_export_policy.jar` in `/ibm/cognos/analytics/ibm-jre/jre/lib/security/policy/unlimited`
to
`/ibm/cognos/analytics/ibm-jre/jre/lib/security`



## Steps

In Cognos Configuration:

* Cryptography > Cognos
* PDF Confidentiality Algorithm - Change this to 256 bit key


## Links

* https://senturus.com/blog/yikes-what-is-that-nist-conformance-warning-in-cognos/