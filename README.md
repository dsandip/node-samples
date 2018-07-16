# node-samples
Here there be samples.
And some gifs. Hopefully.

![](http://i.imgur.com/OUkLi.gif)

[![Docs](https://img.shields.io/badge/docs-v1.0-brightgreen.svg?style=flat)](https://docs.hasura.io)
<a href="https://github.com/hasura/graphql-engine/releases"><img src="https://img.shields.io/badge/release-v1.0.0alpha-brightgreen.svg?style=flat"/></a>
[![CircleCI](https://circleci.com/gh/hasura/graphql-engine.svg?style=shield)](https://circleci.com/gh/hasura/graphql-engine)


<a href="https://discord.gg/vBPpJkS"><img src="https://img.shields.io/badge/chat-discord-brightgreen.svg?logo=discord&style=flat"></a>
<a href="https://twitter.com/intent/follow?screen_name=HasuraHQ"><img src="https://img.shields.io/badge/Follow-HasuraHQ-blue.svg?style=flat&logo=twitter"></a>

Hasura GraphQL Engine is a blazing-fast GraphQL server that gives you **instant GraphQL APIs over Postgres**. Hasura helps you build GraphQL apps backed by Postgres or incrementally move to GraphQL for existing applications using Postgres.

------------------

_Insert GIF here_

-------------------

* **Make powerful queries**: Built-in filtering, pagination, pattern search, bulk insert, update, delete mutations.
* **Works with existing,live databases**: Point it to an existing Postgres database to instantly get a ready-to-use GraphQL API
* **Fine-grained access control**: Dynamic access control that integrates with your auth system (eg: auth0, firebase-auth)
* **High-performance & low-footprint**: ~15MB docker image; ~50MB RAM @ 1000 req/s; multi-core aware
* **Admin UI & Migrations**: Admin UI & Rails-inspired schema migrations
* **Postgres** ❤️: supports Postgres types (PostGIS/geo-location, etc.), turns views to *graphs*, trigger stored functions or procedures with mutations

Read more at: [https://hasura.io](https://hasura.io) and the [docs](https://docs.hasura.io).

**Demos:**

* **Add to Gitlab**: 
[![GraphQL on GitLab](https://img.youtube.com/vi/a2AhxKqd82Q/hqdefault.jpg)](http://www.youtube.com/watch?v=a2AhxKqd82Q "GraphQL on GitLab")

* **Integrate with Auth0** 
<table>
  <tr>
    <td>
      <a href="http://www.youtube.com/watch?feature=player_embedded&v=a2AhxKqd82Q" target="_blank"><img src="https://img.youtube.com/vi/a2AhxKqd82Q/hqdefault.jpg" 
alt="GraphQL on GitLab" width="240" height="180" border="10" /></a>
    </td>
    
    <td>
      <a href="http://www.youtube.com/watch?feature=player_embedded&v=15ITBYnccgc" target="_blank"><img src="https://img.youtube.com/vi/15ITBYnccgc/hqdefault.jpg" 
alt="GraphQL on GitLab" width="240" height="180" border="10" /></a>
    </td>
  </tr>

* **Process 10 million rows and use PostGIS for geo-location**
