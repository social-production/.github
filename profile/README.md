# Social Production

Social Production is a coordination platform for collective activity. It is a social network built to help people organize work, events, services, software, mutual aid, and eventually larger real-world production outside the logic of markets, wages, and private profit.

The Phase 1 web prototype is focused on facilitation: helping people find each other, create projects and events, coordinate requests and activity, and test the social mechanics before legal, funding, asset-holding, and peer-to-peer infrastructure come online.

## Roadmap

### Phase 1: Web prototype

Current phase.

- Conventional FastAPI backend and SvelteKit PWA frontend.
- Facilitation only, with no asset holding.
- Testing for usability, security, and governance behavior.
- Open to public use as the prototype becomes stable.

### Phase 2: Legal entity and funding

- Non-profit foundation formed.
- Community funding and stewardship activated inside Social Production.
- Asset holding and physical asset coordination come online.

### Phase 3: Peer-to-peer backend

- Research and development toward Holochain, p2panda, or similar infrastructure.
- Gradual migration away from the conventional backend.

### Phase 4: Full model

- Shutdown-resistant infrastructure.
- Non-market coordination at scale.

## Run The Web Server Locally

Prerequisites:

- [Docker](https://docs.docker.com/get-docker/) and Docker Compose for the backend.
- [Node.js 18+](https://nodejs.org/) and npm for the frontend.

Start the backend:

```bash
docker compose up -d --build
```

Start the frontend:

```bash
npm install
npm run dev
```

Open `http://localhost:5173` for the app. Backend API docs are available at `http://localhost:8000/docs`.

See `web/README.md` and `web-backend/README.md` for fuller beginner setup instructions.

## Community

- Discord: https://discord.gg/VvbJ3hhEPb
- Reddit: https://www.reddit.com/r/SocialProduction/