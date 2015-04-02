# database-lingo
A cheatsheet for understanding database terminology

- ACID: Acronym which describes a transaction system that ensures transactional atomicity (see atomic transaction below), consistency (see below), isolation (see below), and durability (see below).
- atomic transaction: A database transaction that is guaranteed to fail or succeed, and never generate side effects on a failure.
- consistency: Any given transaction must happen the same way every time.
- deadlock: A state that occurs when two or more transactions are waiting for the other to finish, and thus neither ever do.
- durability: Transactions are saved to disk upon the transaction completing. Power loss does not result in data loss.
- isolation: Refers to the level at which the DBMS ensures concurrency. This is usually the most looseley interpreted qualification of ACID. Lower levels of isolation result in higher availability but may introduce concurrency related data integrity issues, while higher levels of isolation may result in deadlock.
- online transaction processing (OLTP): A row oriented way of storing data.
- online analytical processing (OLAP): A multiview orientation of data, useful for statisical analysis.
- persistence: Saves to disk, rather than memory.
- transaction: A unit of work for a DBMS. Generally represents any command given to a DBMS that alters data.
