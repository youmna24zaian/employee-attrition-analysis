# Data publication safety

The published CSV is a **de-identified analytical extract** created from a private workbook.
It contains no employee names, employee numbers, IDs, exact ages, exact salary/rate values,
addresses, dates, or other direct identifiers. Numerical personal attributes that were not
required for the requested questions were removed; age, salary, experience, and tenure are
represented only as broad bands.

The original workbook and the intermediate cleaned table remain local and are intentionally
excluded from GitHub. Because re-identification risk can never be proven to be zero from a
repository alone, treat the release as an educational aggregate-style extract and do not use
it to make decisions about real people.
