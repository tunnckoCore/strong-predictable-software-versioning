# Strong Predictable Software Versioning (DRAFT)
Strong, easy and predictable, date-based software versioning. Similar to SemVer.

Just like SemVer's signature is `major.minor.patch`, here it is based on the ISO-8601 date format `YYYY.MM.DD`, except that we don't put the day, so the signature is `year.month.patch`. This allows us to more freely whatever changes we want through the `patch`. Of course not breaking changes, and primarly bug and security fixes, dependency updates, docs, chore and etc.

This software versioning doesn't mess with SemVer and doesn't breaking it, nor the normal SemVer workflow and tooling. It's just a different perspective of versioning allowing few very unique and otherwise hard to implement or predict things/features.
