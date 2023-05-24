# App

 
Hypass style app

 ## RFs ( Requisitos funcionais)
- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possivel obter o perfil de um usuário logado
- [ ]  Deve ser possivel obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuárioo obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academis próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia
 
 ## RNs (Regras de negocio)
- [ ] O usuário não pode se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia
- [ ] O usuário não pode fazer check-in se não estive perto (100m) da academia;
- [ ] O check-in só pode ser validade até 20 minutos após criado;
- [ ] O check-in só pode ser validade por admnistradores;
- [ ] A academia só pode ser cadastrada por administradores

## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptografada
- [ ] Os dados da aplicação precisam estar persistidos em um banco postgresSQl
- [ ] Todas Listas de dados precisam estar paginadas com 20 items por pagina
- [ ] O usuário deve ser identificado por um JWT (JSON Wb Token)
