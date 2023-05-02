catatan

encode terminal
echo "ali" | base64


enkripsi

echo "ini pesan" | openssl aes-256-cbc -a -pass pass:ali -pbkdf2


dekripsi

echo "U2FsdGVkX1/h77ve37Yg4ZiLYS+3hfJ3X+0FmgN6iME=" | openssl aes-256-cbc -d -a -pass pass:ali -pbkdf2

