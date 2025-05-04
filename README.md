# Observability
Monitoring is collecting and visualising data about systems regularly so the system's health can be viewed and tracked.

Three questions of monitoring:
1. Is the service on?
2. Is the service functioning as expected?
3. Is the service performing well?

Monitoring vocabulary:
1. Rate(Throughput): Response per second
2. Duration(Latency): Transaction Response time

Four Golden signals methods(RED+S) from Google SRE handbook:
1. Latency
2. Traffic(Throughput)
3. Errors
4. Saturation(Resouces at 100% capacity)

Telemetry data:
1. The data that is collected for monitoring
2. Used to find where the problem might be
3. Types: MELT(Metric, Event, Log, Trace)

Event:
1. An action happened at a given time
2. A bag of chips purchased at a particular time
3. Events validate that an expected action happened

Metric:
1. Is an aggregated value representing events in a period of time
2. 100 bags of chips purchased every minute
3. Metrics are great for comparing the performance of the system with a time in the past

Log:
1. A very datailed representation of an event
2. Eg; chips, price, purchase time, vending machine ID, location, payment method

Trace:
1. Shows the interactions of microservices to fulfil a request

Methods of Metrics Collection:
1. Push
2. Scrape: Apps and MSs provide API end point for the time series DB to read the metrics. Eg; Prometheus scraping metrics








