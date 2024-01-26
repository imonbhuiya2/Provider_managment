### DESCRIPTION
```json
{
  "Framework"                  : "Node JS", "Express JS",
  "Database"                   : "MySQL",
}


```
## Installation
Clone this repository:
 git clone: 
 ```
 https://github.com/imonbhuiya2/Provider_managment.git
 
 ```
```
Create .env file as .env.dist file.
```
docker-compose up -d --build
```
Run this application locally with a single command by docker-compose:
```
docker-compose up -d --build
```
Run migrations by Make file:
```
make dc-db-migrations
```
The application will be live at port: 3000 and swagger at http://localhost:3000/docs/ DB: http://localhost:8081