# Dependency Injection Capabilities

Capabilities and concerns addressed by the Dependency Injection (DI) design pattern.

## Decoupling Capabilities

- Separates object construction from object behavior.
- Lets components depend on abstractions instead of concrete types.
- Enables substitution of implementations without modifying consumers.

## Injection Style Capabilities

- **Constructor injection** for required collaborators.
- **Setter injection** for optional or reconfigurable collaborators.
- **Interface injection** for frameworks that demand explicit injection contracts.
- **Method injection** for one-off contextual dependencies.

## Lifecycle Capabilities

- Singleton, scoped (per-request, per-conversation), and transient lifetimes.
- Lazy resolution of expensive dependencies.
- Disposal coordination for components holding native or remote resources.

## Composition Capabilities

- Composition root that assembles the object graph at startup.
- Auto-registration via convention or annotation scanning.
- Conditional registration based on environment, profile, or feature flag.
- Decorator and interceptor composition for cross-cutting concerns.

## Testing Capabilities

- Direct instantiation with test doubles in unit tests.
- Container-driven integration tests with test-only registrations.
- Clear seams for mocks, fakes, and stubs.

## Configuration Capabilities

- Externalized configuration through code, attributes, or configuration files.
- Profile and environment overrides.
- Resolution of named and keyed implementations.
