## Generate hash file name for Root CAs on Android
~~~
openssl x509 -in any.pem  -subject_hash_old -noout
~~~