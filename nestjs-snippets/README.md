# NestJS Snippets

`nestjs-snippets` is a Visual Studio Code extension that offers a collection of code snippets tailored for NestJS development. These snippets are designed to streamline the coding process, making it easier and faster to generate common NestJS structures and patterns.

## Features

This extension provides a wide range of snippets that cover various aspects of NestJS development, including TypeORM integrations, GraphQL setup, and common NestJS service patterns. Here are some of the key snippets included:

### TypeORM Snippets

- **getQueryBuilder (`gqb`)**: Create a static method for building custom queries using TypeORM's `SelectQueryBuilder`.
- **queryBuilder (`qb`)**: Insert a `queryBuilder` placeholder.
- **TypeORM OneToOne (`too`)**: Scaffold a one-to-one relationship in an entity.
- **TypeORM OneToOne Nullable (`toon`)**: Scaffold a nullable one-to-one relationship in an entity.
- **TypeORM ManyToOne (`tmo`)**: Scaffold a many-to-one relationship in an entity.
- **TypeORM ManyToOne Nullable (`tmon`)**: Scaffold a nullable many-to-one relationship in an entity.
- **TypeORM OneToMany (`tom`)**: Scaffold a one-to-many relationship in an entity.
- **TypeORM OneToMany Nullable (`tomn`)**: Scaffold a nullable one-to-many relationship in an entity.
- **TypeORM Field (`tf`)**: Define a basic field in an entity with `@Column` and `@Field` decorators.
- **TypeORM Column (`tc`)**: Define a basic column in an entity.
- **TypeORM Entity (`te`)**: Generate a full entity with common fields, `@Column` decorators, and timestamps.
- **TypeORM Entity List (`tel`)**: Create a paginated response DTO for listing entities.

### GraphQL Snippets

- **GraphQL Queries (`gq`)**: Scaffold a basic GraphQL query class.
- **GraphQL Queries Find One (`gqo`)**: Create a `findOne` query resolver method.
- **GraphQL Queries Find Many (`gqm`)**: Create a `findMany` query resolver method.
- **GraphQL Mutations (`gm`)**: Scaffold a basic GraphQL mutation class.
- **GraphQL Mutations Create (`gmc`)**: Generate a `create` mutation resolver method.
- **GraphQL Resolver (`gr`)**: Create a basic GraphQL resolver class.

### NestJS Service and Repository Snippets

- **Nest Service (`nss`)**: Scaffold a basic NestJS service with the `@Injectable()` decorator.
- **Nest Inject Repository (`nsir`)**: Inject a TypeORM repository into a service or resolver.
- **Private Readonly (`pr`)**: Create a private readonly property for dependency injection.
- **DataSource (`ds`)**: Define a `dataSource` property for working with TypeORM.

### Import and Export Snippets

- **Import * As Loaders (`isdl`)**: Import all exports from a `loaders` module.
- **Import * As Services (`iss`)**: Import all exports from a `services` module.
- **Import * As Resolvers (`isr`)**: Import all exports from a `resolvers` module.
- **Export Symbol (`es`)**: Export a named symbol.
- **Export * from (`ef`)**: Export all exports from a specified module.

### DataLoader Snippets

- **DataLoader (`dl`)**: Scaffold a basic DataLoader implementation for batching and caching database requests.

## Installation

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3. Search for `nestjs-snippets`.
4. Click **Install** on the `nestjs-snippets` extension.

## Usage

After installing the extension, you can use the snippets by typing the trigger prefix (e.g., `gqb`, `nss`, `too`) followed by a tab to expand the snippet into full code.

## Contributing

Contributions are welcome! If you have ideas for new snippets or improvements to existing ones, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Developed with ❤️ for NestJS developers.
