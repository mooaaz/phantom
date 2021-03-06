
Roadmap
========

#### Phantom 1.x.x

In maintenance mode, users are actively encouraged to upgrade to 2.0.x series.

#### Phantom 2.0.x series

- [ ] Support for case sensitive Cassandra tables and keyspace names.

- [ ] Support for tuple columns and collection columns

- [ ] SASI Index support.

- [ ] Use `QueryPart` as a building block for schema inference during table auto-generation.

- [ ] Deeper integration of CQL features, such as advanced `USING` clauses, `GROUP BY` and `PER PARTITION LIMIT`.(2.0.0)

- [ ] Move documentation back to a branch and to a dedicated versioned website based on Git tags.

- [ ] Added implicit.ly integration to notify our audience of new releases.

- [ ] Bring test coverage to 100%(2.0.0)

- [ ] Add ability to specify compile time implicit configuration, such as case sensitive column names.

- [ ] A new website with highly improved documentation, as well as a per version docs browser.

- [x] Replacing Travis Cassandra service with CCM to natively include multi-version testing in our setup.

- [x] Add support for macro derived primitives for complex types.

### Phantom Pro

#### v0.1.0

- [x] Full support for UDTs.
- [x] Support for UDT collection types.
- [ ] Scala language based User defined functions.
- [ ] Scala language based User defined aggregates.
- [ ] Cassandra 3.8+ support.
- [ ] Materialised views.
- [ ] Development automated schema migrations.

#### v0.3.0
- [ ] Auto-tables, ability to generate queries entirely of out `case class` definitions.
- [ ] Advanced table migrations.
