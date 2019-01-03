# clara-bug
Minimal reproducible case of bug encountered in clara

`:exists` is sugar for an accumulator. But when using it, if your project hasn't required accumulator `clara.rules.accumulators` you get a ClassNotFoundException. This repo just takes the minimal example from the clara docs and adds an exists predicate to it to show the bug.