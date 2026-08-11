# Cache lookups in the resolver hot path

Requests could previously hang forever when the upstream stopped responding. This adds an explicit timeout and surfaces it as a typed error.

Change #1 of 6 on branch `pr/20260811-121032-1-cache-lookups-in-the-resolver-hot-path`.
