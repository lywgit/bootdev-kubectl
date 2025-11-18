
# generate self-signed key with
openssl req -x509 -newkey rsa:2048 -nodes -keyout private.key -out public.crt -days 365 -config cert.conf -sha256