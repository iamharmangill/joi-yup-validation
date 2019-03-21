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
