# Projet Nest-Immo - BACKEND NEST
Yohan Maury

## TODO
- [x] Créer une entité "Category" avec les champs suivants :
    id    int[primary]
    nom   String
    [x] Réaliser les actions de crud coté back.
    [X] Réaliser les actions de crud coté front.

- [x] Ajouter la relation OneToMany
    Dans l'entité "Category" ajouter la relation:
        posts Post[]
    Ainsi que dans l'entité "Post"
        category Category

- [X] Modifier le back en conséquence pour permettre d'ajouter un post avec la relation.
- [X] Ajouter un select dans le PostForm pour selectionner la catégorie.



## Start project

```bash
  # Install dependencies
  npm install
  # Mount container
  docker-compose up -d
  # Run project
  npm run dev
```


## Dev line code
```bash
  # Create module with service ....
  nest generate resource post
  # Install TypeORM
  npm i @nestjs/typeorm pg typeorm
  # Install config
  npm i @nestjs/config
```


## TODO

- [X] Create entity User
- [X] CRUD into userService

```
UserEntity
  - id
  - username
  - email
```