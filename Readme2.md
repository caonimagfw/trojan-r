cargo build --release --target x86_64-unknown-linux-musl


#success
openssl req -x509 -nodes -days 36500 -newkey ec:<(openssl ecparam -name prime256v1) -keyout bmwpay.key.pem -out bmwpay.cert.pem -subj "/C=CN/ST=Fuck/L=GFW/O=Fuck GFW/OU=GFW Dead/CN=bmwpay.net/CN=*.bmwpay.net/emailAddress=gfw@fuck.com"
