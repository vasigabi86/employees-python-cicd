#employees documentation
This file is for documentation.
Language: Python
Push test
Pull test
Kiskutya
22222
33333
33333

change1 
PULL request
PULL 2
PULL 3

docker run -d -e POSTGRES_DB=employees -e POSTGRES_USER=employees  -e POSTGRES_PASSWORD=employees  -p 5432:5432  --name employees-postgres postgres

flask --app employees run --debug
