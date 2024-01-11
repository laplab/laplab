Hi, my name is Nikita, I am a low-level Rust engineer.

### Stuff I worked on before

- **[New Query Engine of MongoDB.](https://laplab.me/posts/inside-new-query-engine-of-mongodb/)** I worked on a compiler to lower queries into internal bytecode as well as a virtual machine to execute this bytecode. Had a lot of fun with performance optimization and correctness.
- **Query Profiler of [ClickHouse](https://github.com/ClickHouse/ClickHouse).** Implemented low-overhead, always-running sampling profiler, showing which lines of code were slow for a particular query. [This feature](https://clickhouse.com/docs/en/operations/optimizing-performance/sampling-query-profiler) is turned on by default on all ClickHouse deployments (cloud and on-premise).
- **JSON Querying and Binary Storage in [YDB](https://github.com/ydb-platform/ydb).** Added functionality to query JSON documents from SQL. I have also invented a [custom binary format](https://laplab.me/posts/how-binary-json-works-in-ydb/) to store JSON documents to optimize read performance.

This was all in C++, but then I [decided to switch to Rust](https://laplab.me/posts/switching-from-cpp-to-rust/).

After that, I worked in an NDA High-Frequency Trading company for a while. Using Rust, I developed custom time-series storage solution for structured data and contributed to a distributed actor system called [Elfo](https://github.com/elfo-rs/elfo).

### Things I do now

- I work in [Prisma](https://www.prisma.io/), where I optimize performance of the query engine written in Rust. This engine powers Prisma ORM, which is the most popular TypeScript ORM on the planet.
- Open-source Rust, see pinned repositories.
- Occasional [microcontroller shenanigans](https://laplab.me/posts/family-photos-vs-256-kb-ram/) and [other stuff](https://laplab.me/posts/).

### Public speaking

- (EN) [SQL's Inner Workings @ Handmade Seattle 2023](https://laplab.me/posts/handmade-seattle-2023/)
- (RU) [Introducing JSON Support @ Yandex Database New Features Overview 2020](https://cloud.yandex.ru/ru/events/110)
- (RU) [ClickHouse Query Profiler @ Highload++ 2019](https://highload.ru/moscow/2019/abstracts/5835)
- (RU) ClickHouse Query Profiler @ ClickHouse Meetup Novosibirsk 2019 ([part 1](https://youtu.be/FsBWk-hKG3A?si=UvAKQPv5HcPPyil_), [part 2](https://youtu.be/TC3PFAGgSrg?si=BrG9twRnBbllsElj))

### How to contact me

- I am available for hire for short-term consulting and training.
- The best way to reach me is by email: [hi@laplab.me](mailto:hi@laplab.me). I usually respond within the same day if I am not on a vacation.
- Memes and experiments can be found on [Mastodon](https://mastodon.social/@laplab).
- You can also ping me on [LinkedIn](https://www.linkedin.com/in/nikitalapkov/).
