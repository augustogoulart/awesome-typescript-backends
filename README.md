# Awesome TypeScript Backends [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of **TypeScript backend frameworks, libraries, fullstack examples, starters, and learning resources**.  
Focused on production-grade tooling, patterns, and real-world apps.  



## Contents

- [Awesome TypeScript Backends ](#awesome-typescript-backends-)
  - [Contents](#contents)
  - [Frameworks](#frameworks)
  - [Libraries](#libraries)
  - [Validation \& Types](#validation--types)
  - [Databases \& ORMs](#databases--orms)
  - [Authentication \& Security](#authentication--security)
  - [Architectural Patterns](#architectural-patterns)
  - [Starters \& Boilerplates](#starters--boilerplates)
  - [Fullstack Examples](#fullstack-examples)
  - [Companies Using TypeScript Backends](#companies-using-typescript-backends)
  - [Learning Resources](#learning-resources)
  - [Contributing](#contributing)
  - [License](#license)

---

## Frameworks

- [NestJS](https://nestjs.com/) - Progressive Node.js framework with modular architecture and DI.
- [Fastify](https://fastify.dev/) - High-performance HTTP framework, great TypeScript support.
- [Hono](https://hono.dev/) - Tiny, fast web framework for Node.js, Bun, Deno, and Edge runtimes.
- [FoalTS](https://foalts.org/) - TypeScript-first Node.js framework with batteries included.
- [AdonisJS](https://adonisjs.com/) - Full-featured backend framework with TS-first philosophy.
- [Blitz.js](https://blitzjs.com/) - Fullstack framework built on Next.js with APIs included.
- [RedwoodJS](https://redwoodjs.com/) - Opinionated fullstack JS/TS framework (GraphQL + React).
- [Remix](https://remix.run/) - Fullstack framework with first-class TS support.
- [tRPC](https://trpc.io/) - End-to-end type-safe APIs without code generation.

---

## Libraries

- [Effect](https://effect.website/) - Effect system for structured concurrency, typed errors, and resources.
- [fp-ts](https://gcanti.github.io/fp-ts/) - Functional programming primitives and data types.
- [ts-pattern](https://github.com/gvergnaud/ts-pattern) - Exhaustive pattern matching.
- [superstruct](https://github.com/ianstormtaylor/superstruct) - Simple schema validation for TS.
- [io-ts](https://github.com/gcanti/io-ts) - Runtime type checking and static type inference.
- [routing-controllers](https://github.com/typestack/routing-controllers) - Create Express/Koa controllers with decorators.
- [class-validator](https://github.com/typestack/class-validator) - Declarative validation decorators.
- [typedi](https://github.com/typestack/typedi) - Dependency injection container for TS.

---

## Validation & Types

- [Zod](https://zod.dev/) - Type-safe schema validation and parsing.
- [Valibot](https://valibot.dev/) - Lightweight schema library with great TS inference.
- [TypeBox](https://github.com/sinclairzx81/typebox) - JSON schema builder with static type resolution.
- [arktype](https://arktype.io/) - Type-level builder with runtime validation.
- [runtypes](https://github.com/pelotom/runtypes) - Runtime validation for static types.
- [Spectypes](https://github.com/vega/Spectypes) - Fast TS validator generator.

---

## Databases & ORMs

- [Prisma](https://www.prisma.io/) - Type-safe ORM with migrations and tooling.
- [Drizzle ORM](https://orm.drizzle.team/) - Lightweight, SQL-first ORM with TS support.
- [TypeORM](https://typeorm.io/) - Mature ORM supporting Active Record & Data Mapper.
- [Kysely](https://kysely.dev/) - Type-safe SQL query builder.
- [Sequelize](https://sequelize.org/) - Classic ORM with TS typings.
- [MikroORM](https://mikro-orm.io/) - TS-first ORM with Data Mapper and Unit of Work.

---

## Authentication & Security

- [Passport](https://www.passportjs.org/) - Widely used authentication middleware (TS typings available).
- [Lucia](https://lucia-auth.com/) - TS-first authentication library for modern apps.
- [Clerk](https://clerk.com/) - Authentication & user management SDK with TS support.
- [SuperTokens](https://supertokens.com/) - Open-source authentication with sessions.
- [jose](https://github.com/panva/jose) - Modern JOSE implementation for JWT/JWS/JWE.
- [node-jose](https://github.com/cisco/node-jose) - Another JOSE standards implementation.

---

## Architectural Patterns

- [Clean Architecture in TypeScript](https://khalilstemmler.com/articles/typescript-clean-architecture/) - Practical backend structuring guide.
- [Hexagonal Architecture with NestJS](https://github.com/Sairyss/domain-driven-hexagon) - DDD/Hexagonal example in NestJS/TS.
- [Node.js DDD Boilerplate](https://github.com/jonathanpalma/ts-ddd-boilerplate) - DDD boilerplate for Node/TS.
- [Clean Node.js Architecture](https://github.com/bespoyasov/node-clean-architecture) - Examples in Node/TS following clean architecture.
- [Domain-Driven Design with TS](https://github.com/Sairyss/domain-driven-hexagon) - Large repo with DDD patterns and explanations.

---

## Starters & Boilerplates

- [jsynowiec/node-typescript-boilerplate](https://github.com/jsynowiec/node-typescript-boilerplate) - Minimal, opinionated Node.js project template with TS.
- [express-typescript-boilerplate](https://github.com/w3tecch/express-typescript-boilerplate) - Express.js starter with TypeScript, Docker, and testing.
- [typescript-express-starter](https://github.com/ljlm0402/typescript-express-starter) - Clean architecture starter for Express + TS.
- [nestjs-boilerplate](https://github.com/Vivify-Ideas/nestjs-boilerplate) - Enterprise-ready NestJS boilerplate with TypeORM, Passport, and testing.
- [typescript-backend-toolkit](https://github.com/muneebhashone/typescript-backend-toolkit) - Toolkit with Express, Prisma, testing, and configs.
- [bulletproof-nodejs](https://github.com/santiq/bulletproof-nodejs) - Node.js + TypeScript project architecture example.

---

## Fullstack Examples

- [Sairyss/fullstack-starter-template](https://github.com/Sairyss/fullstack-starter-template) - React + Fastify + tRPC + Prisma + Zod.
- [payloadcms/payload](https://github.com/payloadcms/payload) - TS CMS with Next.js frontend and Node backend.
- [LandazuriPaul/nest-react](https://github.com/LandazuriPaul/nest-react) - Monorepo with NestJS backend and React frontend.
- [yemiwebby/nest-react-project](https://github.com/yemiwebby/nest-react-project) - Blog app with Nest backend and React frontend.
- [lujakob/nestjs-realworld-example-app](https://github.com/lujakob/nestjs-realworld-example-app) - Conduit API (RealWorld spec) in NestJS.
- [redwoodjs/redwood](https://github.com/redwoodjs/redwood) - Fullstack framework, GraphQL + React.
- [blitz-js/blitz](https://github.com/blitz-js/blitz) - Fullstack framework on Next.js.
- [calcom/cal.com](https://github.com/calcom/cal.com) - Open-source scheduling platform, fullstack TS.
- [Medplum/medplum](https://github.com/medplum/medplum) - Open-source healthcare platform with React + Node.
- [supabase/supabase](https://github.com/supabase/supabase) - BaaS with strong TS ecosystem.

---

## Companies Using TypeScript Backends

- **Slack** - Uses TypeScript in backend services and SDKs to improve maintainability.  
- **Cal.com** - Open-source scheduling platform built entirely in TypeScript.  
- **Supabase** - Firebase alternative with a strong TypeScript backend.  
- **Medplum** - Open-source healthcare platform with TypeScript backend and React frontend.  
- **PayPal** - Large portions of backend services in Node.js + TypeScript.  
- **Atlassian** - Uses TypeScript across backend microservices.  
- **Microsoft** - Extensively uses TS in backend services and tooling (e.g. Azure SDKs).  

---

## Learning Resources

- [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/) - Comprehensive free TS book.
- [Clean Code concepts adapted for TypeScript](https://github.com/labs42io/clean-code-typescript) - Idiomatic clean code practices in TS.
- [Practical Guide to FP in TS](https://dev.to/gcanti/getting-started-with-fp-ts-setoid-39f3) - Intro to fp-ts & functional backend programming.
- [NestJS Docs](https://docs.nestjs.com/) - Official docs for modular backend architecture.
- [Effect Docs](https://effect.website/docs/essentials/overview) - Structured concurrency and typed effects in TS.
- [tRPC Docs](https://trpc.io/docs) - Learn type-safe API design.
- [Prisma Docs](https://www.prisma.io/docs) - Type-safe DB integration.
- [Drizzle ORM Guide](https://orm.drizzle.team/docs/overview) - Lightweight SQL-first ORM with TS.
- [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) - Broader TS list including backend and tooling.

---

## Contributing

Contributions are welcome! Please open an issue or pull request with:

- A link to the project/resource.
- A short description (max 1–2 lines).
- Why it’s awesome for TypeScript backends.

---

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - Share and adapt with attribution.

