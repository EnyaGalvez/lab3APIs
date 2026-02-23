Universidad del Valle de Guatemala <
Sistemas y Tecnologías Web
Docente: Marlon Fuentes
Estudiante: Enya Gálvez (24693)
Semestre 1, 2026

#API ONBOARDING REPORT

##Resumen de la API
* Nombre: The Dog API
* Versión: v1
* Base url: https://thedogapi.com/v1
* Tipo de auth: API Key via header x-api-key
* Rate limit: 10,000 request/mes en plan gratuito para estudiantes
* Documentación: https://docs.thedogapi.com
* Importante: La API requere que cada request incluya el header x-api-key en una llave que se obtiene al registrarse en https://thedogapi.com/en/students. Sin este header, la api responde con el status code 401.

##Tabla de endpoints probados

| # | Método | URL | Query params | Headers | Status esperado | Status obtenido |
|:--|:--------:|:--------:| :------------:| :--------:| --------:| --------:|
| 1 | GET   | /breeds  | ninguno |  x-api-key:{{apikey}} | 200 | OK |
| 2 | Center   | Right        | Right | Right | Right | Right |
| 3 | Center   | Right        | Right | Right | Right | Right |
