./gradlew runProducerInteractiveQueries produces the data needed for the examples.
./gradlew runInteractiveQueryApplicationOne starts a Kafka Streams application with HostInfo using port 4567.
./gradlew runInteractiveQueryApplicationTwo starts a Kafka Streams application with HostInfo using port 4568.


hen, point your browser to http://localhost:4568/window/NumberSharesPerPeriod/AEBB. Click Refresh a few time to see different results. Here’s a static list of company symbols for this example: AEBB, VABC, ALBC, EABC, BWBC, BNBC, MASH, BARX, WNBC, WKRP.

localhost:4568/iq 