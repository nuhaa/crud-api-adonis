tutorial dari https://gits.id/blog/membuat-crud-api-dengan-adonisjs-5/

Step
================================================================================
                            install adonis
================================================================================
1. npm init adonis-ts-app@latest {{nama-project}}
2. node ace serve --watch => (run serve)
================================================================================
                               install ORM
================================================================================
3. npm i @adonisjs/lucid => (install orm db using lucid)
4. node ace configure @adonisjs/lucid => (untuk konfigurasi database)
    - pilih db (postgres/mysql)
    - pilih intruksi (terminal/browser)
    - setting database di .env
================================================================================
                            setting model
================================================================================
5. node ace make:model User => (untuk buat model)
6. node ace migration:run => (untuk migrate)
