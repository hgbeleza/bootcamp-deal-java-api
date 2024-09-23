# Bootcamp deal java spring boot
Olá mundo! Essa api foi desenvolvida no bootcamp da deal com parceria 
com a Dio 

## Funcionalidades 
antes de qualquer teste da api, certifique-se que você
bebeu água hoje, hoje


```mermaid
classDiagram
    class Post {
        +int id
        +string title
        +string content
        +DateTime createdAt
        +DateTime updatedAt
    }

    class Comment {
        +int id
        +string content
        +DateTime createdAt
        +int postId
    }

    class User {
        +int id
        +string username
        +string email
    }

    Post "1" -- "0..*" Comment : has
    User "1" -- "0..*" Comment : writes

```
