# introducao-ao-SOLID

Desafio do curso Ignite da Rocketseat.

 UsersRepository should be able to create new users
 UsersRepository should be able to list all users
 UsersRepository should be able to find user by ID
 UsersRepository should be able to find user by e-mail address
 UsersRepository should be able to turn an user as admin
 ListAllUsersUseCase should be able to list all users
 ListAllUsersUseCase should not be able to a non admin user get list of all users
 ListAllUsersUseCase should not be able to a non existing user get list of all users
 TurnUserAdminUseCase should be able to turn an user as admin
 TurnUserAdminUseCase should not be able to turn a non existing user as admin
 ShowUserProfileUseCase should be able to get user profile by ID
 ShowUserProfileUseCase should not be able to show profile of a non existing user
 [POST] /users should be able to create new users
 [POST] /users should not be able to create new users when email is already taken
 [PATCH] /users/:user_id/admin should be able to turn an user as admin
 [PATCH] /users/:user_id/admin should not be able to turn a non existing user as admin
 [GET] /users/:user_id should be able to get user profile by ID
 [GET] /users/:user_id should not be able to show profile of a non existing user
 [GET] /users should be able to list all users
 [GET] /users should not be able to a non admin user get list of all users
 [GET] /users should not be able to a non admin user get list of all users
 [GET] /users should not be able to a non existing user get list of all users
 User model should be able to create an user with all props
 CreateUserUseCase should be able to create new users
 CreateUserUseCase should not be able to create new users when email is already taken
