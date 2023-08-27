# Welcome To RailsBusters

Pagina para gestionar y administrar el arriendo de películas, con objetivo de demostrar las relaciones 1 a N en rails usando base de datos postgresql.

Visitala en https://railsbuster-0e592e3b3718.herokuapp.com

## Details

Esta página muestra como funcionan las relaciones en rails.

- Crear nuevas películas y clientes.
- Editar las películas y clientes.
- Asignar una película a un cliente de forma fácil y amigable.
- Eliminar un cliente o una película.

## Screenshoots

Vista principal de la página:

![Vista principal](/public/client.png)

Vista secundaria de la página:

![Vista secundaria](/public/movieview.png)

Panel de edicion para cliente y película:

![Vista editar](/public/movie.png)

## Ready, Steady, GO 🚀

Estas instrucciones te guiarán para obtener una copia de este proyecto en funcionamiento en tu máquina local con fines de desarrollo y pruebas.

### Pre-Requisitos 📋

- Sistema Operativo: Windows, Ubuntu o macOS
- Lenguaje de programación: Ruby 3.1.1
- Framework Rails: 7.0.4
- PostgreSQL: 14.8

### Instalación 🔧

Clona el repositorio con el siguiente comando:

```bash
git clone https://github.com/DevilAbbath/railsBuster.git
```

En la terminal, accede a la carpeta donde se encuentra el repositorio y ejecuta (recuerda que para que esto funcione, debes tener instalado Ruby y la gema bundle):

```bash
bundle install
```

Inicia la base de datos, migra los cambios y agrega información con el siguiente comando:

```bash
rails db:create db:migrate db:seed
```

Finalmente, ejecuta el proyecto con el siguiente comando y ve a la dirección IP que aparecerá en la consola:

```bash
rails s
```

## Construido Con 🛠️

- [Ruby](https://www.ruby-lang.org/es/) - El lenguaje utilizado
- [Ruby on Rails](https://rubyonrails.org) - El framework web utilizado
- [Ruby gems](https://rubygems.org) - Gestión de dependencias
- [Postgresql](https://www.postgresql.org) - Sistema de base de datos
- [Bootstrap](https://getbootstrap.com/) - Framework de CSS

## Soporte

Si tienes algún problema o sugerencia, por favor abre un problema [aquí](https://github.com/DevilAbbath/railsBuster/issues).

## Versionado 📌

Usamos [Git](https://git-scm.com) para el versionado.

## Autores ✒️

- **Luis Miño Bustos** Encuéntrame en [github](https://github.com/DevilAbbath)
