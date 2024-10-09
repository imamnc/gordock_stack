<p align="center">
    <a href="https://itpi.co.id" target="_blank">
        <img src="https://itpi.co.id/wp-content/uploads/2020/07/ITPI-THEME-THUMBNAIL.jpg" width="250" alt="Logo">
    </a>
</p>

# About Gordock

Hello world! Let us introduce Gordock to you. This is an awesome docker stack for developing agora app and also can use to deploy agora in native docker server.

## Tech Stack

- nginx
- postgres
- redis
- postgres
- mailpit

## How to use it ?

Clone this Gordock project

```bash
  git clone https://lab.itpi.co.id/research/gordock.git
```

Go to the cloned project directory

```bash
  cd gordock
```

Copy **.env** file

```bash
  cp .env.example .env
```

Run the stack using docker compose

```bash
  docker compose up -d
```

Last step you can create a nginx configuration in **nginx/sites** folder to listen your domain.