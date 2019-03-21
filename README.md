# joi-yup-validation
Week-10 Validation

## Success JOI:

curl --request POST \
  --url https://joi-yup-validation.iamharmangill.now.sh/api/joi \
  --header 'content-type: application/json' \
  --data '{
  "username": "hgill69",
  "password": "csGFj234s"
}'

## Fail JOI:

curl --request POST \
  --url https://joi-yup-validation.iamharmangill.now.sh/api/joi \
  --header 'content-type: application/json' \
  --data '{
  "username": "hgill69",
  "password": "csGFjvas"
}'

## Success YUP:

curl --request POST \
  --url https://joi-yup-validation.iamharmangill.now.sh/api/yup \
  --header 'content-type: application/json' \
  --data '{
	"name": "Harman Gill",
  "email": "hpsg@gmail.com",
	"age": "23",
  "password": "csGFj234s"
}'

## Fail YUP:

curl --request POST \
  --url https://joi-yup-validation.iamharmangill.now.sh/api/yup \
  --header 'content-type: application/json' \
  --data '{
	"name": "Harman Gill",
  "email": "hpsggmail.com",
	"age": "23",
  "password": "cGGj234s"
}'
