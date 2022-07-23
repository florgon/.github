## Florgon is project aimed to create new services, applications for users. Currently Florgon is developed mostly by one person. Florgon includes all projects under *.florgon.space domain, connected with SSO authentication (with OAuth). Currently Florgon being in fresh state, when there almost all breaks, and requires a lot of work.
# Projects.
### Web.
- Florgon ([florgon.space](https://florgon.space))
- Florgon account ([profile.florgon.space](https://profile.florgon.space))
- Florgon users (Florgon public profile) ([users.florgon.space](https://users.florgon.space/kirillzhosul))
- Florgon for developers (Documentation, developer profile) ([dev.florgon.space](https://dev.florgon.space))
- Florgon Notes (**Disabled, frozen for now**) ([notes.florgon.space](https://notes.florgon.space))
- Florgon Gatey (**Landing, work will start soon**) ([gatey.florgon.space](https://gatey.florgon.space))
- Florgon Ads ([ads.florgon.space](https://ads.florgon.space)) (Check disabled AdBlock)
### APIs.
- Florgon API (Account, OAuth) ([GitHub](https://github.com/florgon/api) , [API endpoint](https://api.florgon.space))
- Florgon Notes API (**WIP**) ([GitHub](https://github.com/florgon/notes-api) , [API endpoint](https://api.florgon.space/notes))
- Florgon Gatey API (**Not implemented yet**) ([GitHub](https://github.com/florgon/gatey-api) , [API endpoint](https://api.florgon.space/gatey))
- Florgon Ads API ([GitHub](https://github.com/florgon/ads-api) , [API endpoint](https://api.florgon.space/ads))
### Other.
- Florgon API SDK (JS) ([GitHub](https://github.com/florgon/auth-sdk-js))
# Documentation.
- Florgon documentation for developers ([dev.florgon.space](https://dev.florgon.space))
- Florgon OAuth documentation ([dev.florgon.space/oauth](https://dev.florgon.space/oauth))
- Manage your OAuth clients ([dev.florgon.space/profile](https://dev.florgon.space/profile))
# Technologies.
- Frontenend:
- - JavaScript (NextJS (ReactJS, Node.js)) as client language with SSR.
- - HTML (Bootstrap CSS) as markup.
- Backend: 
- - Python (FastAPI, SQLAlchemy) as core language for APIs (With framework and ORM).
- - Docker (Docker-Compose) for deployment, containerization. 
- - PostgreSQL (with pgBouncer) as DBMS (Database).
- - PyTest (with GitHub workflows) for CI/CD (Including Deploy).
- - Redis as database for storing requests limits.
- - Uvicorn (with Gunicorn) as server with process manager.
- Server:
- - Linux (Ubuntu) as OS.
- - Nginx as proxy server.
- WIP:
- - Planning to use RabbitMQ (AMQP).

# Contacts.
Support: [support@florgon.space](mailto:support@florgon.space) \
CEO, Lead Developer: [kirillzhosul@florgon.space](mailto:kirillzhosul@florgon.space), [@kirillzhosul](https://github.com/kirillzhosul)
