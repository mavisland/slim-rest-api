# Simple REST API with Slim Framework

This is an example project that illustrates creating a REST API in PHP with Slim Framework.

## Getting Started

### Requirements

-   GIT
-   PHP 7.1 or greater
-   Composer

### Install the project

1. Clone this repository

```bash
git clone https://github.com/mavisland/slim-rest-api.git [my-app-name]
```

2. Go to the project folder

```bash
cd [my-app-name]
```

3. Install dependencies with composer

```bash
composer install
```

## Endpoints

| Method   | URI                                   | Description                    |
| -------- | ------------------------------------- | ------------------------------ |
| `GET`    | `/projects`                           | Get all projects               |
| `POST`   | `/projects`                           | Create a new project           |
| `GET`    | `/projects/:title`                    | Get a project                  |
| `PUT`    | `/projects/:title`                    | Update a project               |
| `DELETE` | `/projects/:title`                    | Delete a project               |
| `PUT`    | `/projects/:title/archive`            | Archive a project              |
| `DELETE` | `/projects/:title/archive`            | Restore a project              |
| `GET`    | `/projects/:title/tasks`              | Get all tasks of a project     |
| `POST`   | `/projects/:title/tasks`              | Create a new task in a project |
| `GET`    | `/projects/:title/tasks/:id`          | Get a task of a project        |
| `PUT`    | `/projects/:title/tasks/:id`          | Update a task of a project     |
| `DELETE` | `/projects/:title/tasks/:id`          | Delete a task of a project     |
| `PUT`    | `/projects/:title/tasks/:id/complete` | Complete a task of a project   |
| `DELETE` | `/projects/:title/tasks/:id/complete` | Undo a task of a project       |

## Dependencies

-   [slim/slim](https://github.com/slimphp/Slim): Slim is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs.

## License

The code is released under the MIT License (MIT). See [LICENSE](LICENSE.md) for details.
