# Schema Evolution Patterns

### Abstract

Everybody’s talking about microservices, but nobody seems to agree on how to make them talk to each other. How should you version your APIs, and how does API version deprecation actually work in practice? Do you use plain old JavaScript object notation (JSON), Thrift, protocol buffers, GraphQL? How do teams communicate changes in their services’ interfaces, and how do consumer services respond? Separately, nobody seems to agree on how to handle migrating a service’s structured data without downtime. Do you write to shadow tables? Chain new tables off the old ones? Just run the migration live and hope nothing bad happens? Switch everything over to NoSQL?

Both these problems are instances of issues with schema evolution: what happens when the structure of your structured data changes. Rather than taking a prescriptive approach, Alex Rasmussen distills a lot of institutional knowledge and computer science history into a set of patterns and examines the trade-offs between them.

## References

* [Designing Data Intensive Applications](https://dataintensive.net/)
* [Schema Management - Confluent](https://docs.confluent.io/current/schema-registry/docs/index.html)
* [The Problem of Managing Schemas](https://www.oreilly.com/ideas/the-problem-of-managing-schemas)
* [Continuous Evolution & GraphQL: A Double-Edged Sword](https://medium.com/@__xuorig__/continuous-evolution-graphql-a-double-edged-sword-512f147c4083)
* [GraphQL Schema Design: Building Evolvable Schemas](https://blog.apollographql.com/graphql-schema-design-building-evolvable-schemas-1501f3c59ed5)
* [APIs as infrastructure: future-proofing Stripe with versioning](https://stripe.com/blog/api-versioning)
* [How to manage changes to your database?](https://www.depesz.com/2010/08/22/versioning/)
* [MongoDB Schema Validation](https://docs.mongodb.com/manual/core/schema-validation/)
* [Schema-on-need](http://www.dbms2.com/2013/09/21/schema-on-need-hadapt/)
* [Semantic Versioning 2.0.0](https://semver.org/)
* [Schema on Read vs. Schema on Write Explained](https://www.thomashenson.com/schema-read-vs-schema-write-explained/)
* [Google Cloud Spanner - Schema Updates](https://cloud.google.com/spanner/docs/schema-updates)
* [proto3 Language Guide](https://developers.google.com/protocol-buffers/docs/proto3)
* [Thrift](https://thrift.apache.org/)
* [Stripe's definition of backwards-compatible changes](https://stripe.com/docs/upgrades#what-changes-does-stripe-consider-to-be-backwards-compatible)
* [pt-online-schema-change](https://www.percona.com/doc/percona-toolkit/2.1/pt-online-schema-change.html)
* [gh-ost](https://github.com/github/gh-ost)
* [Facebook OSC](https://github.com/facebookincubator/OnlineSchemaChange)
* [Arrested by the CAP: Handling Data in Distributed Systems](https://speakerdeck.com/aviranm/handling-data-in-distributed-systems)
