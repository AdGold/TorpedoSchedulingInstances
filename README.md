Instances used for Optimal Torpedo Scheduling
===

This repository contains all of the instances used in the paper Optimal Torpedo Scheduling, they are organised as follows.

```
small/              # Instances used in small dataset
    comp-test/      # Small instances from the competition (included in small)
medium/             # Instances used in medium dataset
large/              # Instances used in large dataset
massive/            # Instances used to test the limits of our approach
comp/               # ACP 2016 Competition instances
configs/            # Configuration files used for generating instances
```

All instances were generated using the instance generator available from the ACP website and the configuration files included.

Results are summurised below, for full details, see results.csv file. Zeros for both nTorpedoes and desulfTime indicate that the instance was infeasible.

|Instance|nTorpedoes|desulfTime|total runtime|
|---:|---|---|---|
|config1 30x20|3|125|0.315|
|config2 30x20|3|144|0.377|
|config3 30x20|3|84|0.153|
|config1 100x50|3|77|0.400|
|config2 100x50|4|154|0.340|
|config3 100x50|3|190|0.390|
|config1 300x200|3|1482|1.911|
|config2 300x200|3|720|2.330|
|config3 300x200|4|615|1.873|
|instance01|4|7695|41.331|
|instance02|4|5302|118.720|
|instance03|3|27150|415.389|
|instance04|3|10676|34.754|
|instance05|4|16308|574.852|
|instance06|4|7755|1133.542|
|config1 300x100|4|216|1.615|
|config2 300x100|4|52|1.701|
|config3 300x100|4|56|1.642|
|config1 500x200|4|130|5.337|
|config2 500x200|3|1150|5.381|
|config3 500x200|4|238|7.579|
|config1 1000x500|4|546|28.414|
|config2 1000x500|0|0|0.482|
|config3 1000x500|4|432|25.661|
|config1 1500x1000|4|1250|87.387|
|config2 1500x1000|0|0|1.297|
|config3 1500x1000|4|1815|88.609|
|config1 2000x1000|4|1638|194.296|
|config2 2000x1000|5|870|552.648|
|config3 2000x1000|5|845|354.375|
|config1 3000x500|5|25|1897.999|
|config2 3000x500|5|140|412.892|
|config3 3000x500|5|60|440.939|
|config1 3000x1000|5|468|519.113|
|config2 3000x1000|0|0|3.254|
|config3 3000x1000|4|564|529.804|
|config1 3000x2000|4|5301|773.672|
|config2 3000x2000|0|0|5.217|
|config3 3000x2000|4|3180|876.566|
|config1 10000x5000|4|10374|102591.355|
|config2 10000x5000|0|0|57.092|
|config3 10000x5000|5|2587|145594.688|
|config1 100000x50000|5|28237|4311^|
|config2 100000x50000|0|0|9^|
|config3 100000x50000|5|20860|13275^|

^ Note that these were run with a forward limit of 20
