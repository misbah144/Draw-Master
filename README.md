


## Shape libraries

Find a growing list of libraries containing assets for your drawings at [libraries.excalidraw.com](https://libraries.excalidraw.com).

## Run the code

### Code Sandbox

- Go to https://codesandbox.io/s/github/excalidraw/excalidraw
  - You may need to sign in with Github and reload the page
- You can start coding instantly, and even send PRs from there!

### Local Installation

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Clone the repo

```bash
git clone https://github.com/excalidraw/excalidraw.git
```

#### Commands

| Command               | Description                       |
| --------------------- | --------------------------------- |
| `npm install`         | Install the dependencies          |
| `npm start`           | Run the project                   |
| `npm run fix`         | Reformat all files with Prettier  |
| `npm test`            | Run tests                         |
| `npm run test:update` | Update test snapshots             |
| `npm run test:code`   | Test for formatting with Prettier |

#### Docker Compose

You can use docker-compose to work on excalidraw locally if you don't want to setup a Node.js env.

```sh
docker-compose up --build -d
```

## Self hosting

We publish a Docker image with the Excalidraw client . You can use it to self host your own client under your own domain, on Kubernetes, AWS ECS, etc.

```sh
docker build -t excalidraw/excalidraw .
docker run --rm -dit --name excalidraw -p 5000:80 excalidraw/excalidraw:latest
```

The Docker image is free of analytics and other tracking libraries.

**At the moment, self-hosting your own instance doesn't support sharing or collaboration features.**

We are working towards providing a full-fledged solution for self hosting your own Excalidraw.

## Excalidraw is built using these awesome tools

- [React](https://reactjs.org)
- [Rough.js](https://roughjs.com)
- [TypeScript](https://www.typescriptlang.org)
- [Vercel](https://vercel.com)

