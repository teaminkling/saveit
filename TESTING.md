# Testing Guidelines

Testing is vital to software development.

## Behaviour-Driven Testing

### Contract Testing

A frontend and a group of individually-maintained services need to determine a contract for what it produces and
expects to consume. A frontend will only expect to consume.

If all contracts are fulfilled, testing each individual application will test the entire system without needing to
package an entire environment and run extremely costly tests.

### Acceptance Criteria

For each individual service, however, acceptance criteria is known through the software requirements defined as Epics.
Epics also correspond to major features in the software. Each of these are tested from the component-level, just not
the interactions between them and the other components.

## Integration Tests

Services individually may be a collection of different functions or microservices, and integrating important
functionality must be tested. Rust provides a very good framework for this, but all frameworks used in our projects
must be able to define this type of test.

## Unit Tests

Unitary tests must be written for "complex" public functions/methods to ensure correctness. They should abide by
Test-Driven Development (TDD).
