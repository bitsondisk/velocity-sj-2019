# Schema Evolution Patterns

### Abstract

Everybody’s talking about microservices, but nobody seems to agree on how to make them talk to each other. How should you version your APIs, and how does API version deprecation actually work in practice? Do you use plain old JavaScript object notation (JSON), Thrift, protocol buffers, GraphQL? How do teams communicate changes in their services’ interfaces, and how do consumer services respond? Separately, nobody seems to agree on how to handle migrating a service’s structured data without downtime. Do you write to shadow tables? Chain new tables off the old ones? Just run the migration live and hope nothing bad happens? Switch everything over to NoSQL?

Both these problems are instances of issues with schema evolution: what happens when the structure of your structured data changes. Rather than taking a prescriptive approach, Alex Rasmussen distills a lot of institutional knowledge and computer science history into a set of patterns and examines the trade-offs between them.

## References

TODO

## Thank you

TODO
