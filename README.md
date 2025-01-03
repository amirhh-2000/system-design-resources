# System Design

## Contents
- [Overview](https://github.com/amirhh-2000/system-design-resources/blob/main/README.md#overview)
- [Resource Categories](https://github.com/amirhh-2000/system-design-resources/blob/main/README.md#resource-categories)
- [Contributing](https://github.com/amirhh-2000/system-design-resources/blob/main/README.md#contributing)
- [Contribution Guidelines](https://github.com/amirhh-2000/system-design-resources/blob/main/README.md#contribution-guidelines)
- [License](https://github.com/amirhh-2000/system-design-resources/blob/main/README.md#license)

## Overview
This repository contains links to valuable resources for learning and implementing system design. Whether you're preparing for interviews or architecting real-world systems, you'll find relevant materials here.

## Resource Categories
### Articles
- [Scalability](https://blog.algomaster.io/p/scalability)
- [Latency vs Throughput](https://aws.amazon.com/compare/the-difference-between-throughput-and-latency/)
- [CAP Theorem](https://www.bmc.com/blogs/cap-theorem/)
- [ACID Transactions](https://redis.io/glossary/acid-transactions/)
- [Consistent Hashing](https://arpitbhayani.me/blogs/consistent-hashing/)
- [Rate Limiting](https://www.imperva.com/learn/application-security/rate-limiting/)
- [API Design](https://blog.wahab2.com/api-architecture-best-practices-for-designing-rest-apis-bf907025f5f?gi=e5f33b0137fe)
- [Strong vs Eventual Consistency](https://systemdesignschool.io/blog/eventual-consistency-vs-strong-consistency)
- [Synchronous vs. asynchronous communications](https://www.techtarget.com/searchapparchitecture/tip/Synchronous-vs-asynchronous-communication-The-differences)
- [REST vs RPC](https://aws.amazon.com/compare/the-difference-between-rpc-and-rest/)
- [Batch Processing vs Stream Processing](https://atlan.com/batch-processing-vs-stream-processing/)
- [Fault Tolerance](https://www.cockroachlabs.com/blog/what-is-fault-tolerance/)
- [Consensus Algorithms](https://medium.com/@sourabhatta1819/consensus-in-distributed-system-ac79f8ba2b8c)
- [Gossip Protocol](https://highscalability.com/gossip-protocol-explained/)
- [Service Discovery](https://www.f5.com/es_es/company/blog/nginx/service-discovery-in-a-microservices-architecture)
- [Disaster Recovery](https://cloud.google.com/learn/what-is-disaster-recovery)
- [Distributed Tracing](https://www.dynatrace.com/news/blog/what-is-distributed-tracing/)
- [Top 15 Tradeoffs](https://blog.algomaster.io/p/system-design-top-15-trade-offs)
- [Horizontal vs Vertical Scaling](https://www.spiceworks.com/tech/cloud/articles/horizontal-vs-vertical-cloud-scaling/)
- [Databases](https://blog.algomaster.io/p/15-types-of-databases)
- [Content Delivery Network (CDN)](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)
- [Domain Name System (DNS)](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [Caching](https://medium.com/must-know-computer-science/system-design-caching-acbd1b02ca01)
- [Distributed Caching](https://redis.io/glossary/distributed-caching/)
- [Load Balancing](https://aws.amazon.com/what-is/load-balancing/)
- [SQL vs NoSQL](https://www.integrate.io/blog/the-sql-vs-nosql-difference/)
- [Database Indexs](https://www.progress.com/tutorials/odbc/using-indexes)
- [HeartBeat](https://martinfowler.com/articles/patterns-of-distributed-systems/heartbeat.html)
- [Circuit Breaker](https://medium.com/geekculture/design-patterns-for-microservices-circuit-breaker-pattern-276249ffab33)
- [Idempotency](https://blog.dreamfactory.com/what-is-idempotency)
- [Database Scaling](https://thenewstack.io/techniques-for-scaling-applications-with-a-database/)
- [Data Replication](https://redis.io/blog/what-is-data-replication/)
- [Data Redundancy](https://www.egnyte.com/guides/governance/data-redundancy)
- [Database Sharding](https://www.mongodb.com/resources/products/capabilities/database-sharding-explained)
- [Proxy Server](https://www.fortinet.com/resources/cyberglossary/proxy-server)
- [Message Queues](https://medium.com/must-know-computer-science/system-design-message-queues-245612428a22)
- [WebSockets](https://www.pubnub.com/guides/websockets/)
- [Bloom Filters](https://www.enjoyalgorithms.com/blog/bloom-filter)
- [API Gateway](https://www.f5.com/glossary/api-gateway)
- [Distributed Locking](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)
- [Checksum](https://www.lifewire.com/what-does-checksum-mean-2625825)

### Case Studies
- [Instagram](https://medium.com/coders-mojo/day-4-of-system-design-case-studies-series-design-instagram-part-1-10943440f29c)
- [Messenger App](https://medium.com/coders-mojo/day-5-of-system-design-case-studies-series-design-messenger-app-7b73c589f4a)
- [Twitter](https://medium.com/coders-mojo/day-7-of-system-design-case-studies-series-design-twitter-fd0722d7bb7c)
- [URL shortener](https://medium.com/coders-mojo/day-8-of-system-design-case-studies-series-design-url-shortener-91c812a08e0b)
- [Dropbox](https://medium.com/coders-mojo/day-9-of-system-design-case-studies-series-design-dropbox-ead523ccccfa)
- [Youtube](https://medium.com/coders-mojo/day-10-of-system-design-case-studies-series-design-youtube-58bc4ad09c4b)
- [API Rate Limiter](https://medium.com/coders-mojo/day-11-of-system-design-case-studies-series-design-api-rate-limiter-8627993c5a92)
- [Web Crawler](https://medium.com/coders-mojo/day-12-of-system-design-case-studies-series-design-web-crawler-efba93f40030)
- [Facebook’s Newsfeed](https://medium.com/coders-mojo/day-13-of-system-design-case-studies-series-design-facebooks-newsfeed-e96294c7d871)
- [Yelp](https://medium.com/coders-mojo/day-14-of-system-design-case-studies-series-design-yelp-af432d13e838)
- [Uber](https://medium.com/coders-mojo/day-15-of-system-design-case-studies-series-design-uber-2adc612701d)

### Low Level Design Problems
- [Interview practice](https://github.com/kumaransg/LLD)
- [Django rest](https://github.com/tushverma/splitwise)

### Books
- [System Design Interview (ENG)](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF?adgrpid=117434444859&dib=eyJ2IjoiMSJ9.yyx6qnDmeg4rnFaOPnFM6h6gj9iUB79NGrGtZkQxxv_JPaCzMFrY9FPgmj1gQo35FJokdHR8XM1Qb0TlTyIl_FaF5r2k2I4i4sr4F1bWUA0ZU1I-h_KhSESymANFdx7eaTMpLvP4_ikXp4z52HYWoVpisH8PnUlI46WMnDmp-XNKzuDZAsAG-9SFb_D2zdOdbV1qvC2D2GaA6TybnQzMOA.z6QOCqeDqKaC4pWiJ4LyO-sDDRl-wz3oYjtnPQrKKOQ&dib_tag=se&hvadid=604405567644&hvdev=m&hvlocint=9030938&hvlocphy=2364&hvnetw=g&hvqmt=e&hvrand=17935920220375622787&hvtargid=kwd-298507968466&hydadcr=19224_13432048&keywords=system+design+interview&qid=1734603404&sr=8-3)
- [System Design Interview (FA)](https://virgool.io/@dany_kh/%D9%85%D8%B9%D8%B1%D9%81%DB%8C-%DA%A9%D8%AA%D8%A7%D8%A8-%D8%B7%D8%B1%D8%A7%D8%AD%DB%8C-%D8%B3%DB%8C%D8%B3%D8%AA%D9%85-%D9%87%D8%A7%DB%8C-%D9%86%D8%B1%D9%85-%D8%A7%D9%81%D8%B2%D8%A7%D8%B1%DB%8C-%DB%B1-mox8la8vlwz8)

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b add-new-resource`)
3. Add your resources
4. Commit your changes (`git commit -m 'Add new resource'`)
5. Push to the branch (`git push origin add-new-resource`)
6. Create a Pull Request

## Contribution Guidelines
- Ensure links are valid and accessible
- Include a brief description for each resource
- Categorize appropriately
- Avoid duplicates

## License
MIT License - see the [LICENSE](https://github.com/amirhh-2000/system-design-resources/blob/main/LICENSE) file for details
