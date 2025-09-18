# opentelemetry_tdc-sp-2025
Materiais de apresentação "Observabilidade Unificada com OpenTelemetry: tracing de aplicações distribuídas em .NET e outras stacks" realizada no dia 18/09/2025, durante o TDC São Paulo.

Palestrantes (links apontando para o LinkedIn, nos adicionem lá 😉):
- Renato Groffe | [LinkedIn](https://www.linkedin.com/in/renatogroffe/) :: [GitHub](https://github.com/renatogroffe)
- Alexandre Malavasi | [LinkedIn](https://www.linkedin.com/in/alexandremalavasi/) :: [GitHub](https://github.com/alexandremalavasi)

Repositorios com os scripts + Docker Compose para a criacao dos ambientes que faram uso do OpenTelemetry, PostgreSQL, MySQL e Redis:
- [Jaeger](https://github.com/renatogroffe/dockercompose-opentelemetry-jaeger-postgres-mysql-redis)
- [Grafana](https://github.com/renatogroffe/dockercompose-opentelemetry-grafana-postgres-mysql-redis)
- [Elastic APM](https://github.com/renatogroffe/dockercompose-opentelemetry-elasticapm-postgres-mysql-redis)
- [Zipkin](https://github.com/renatogroffe/dockercompose-opentelemetry-zipkin-postgres-mysql-redis)

Repositorios com as aplicacoes utilizadas nos testes com tracing distribuido:
- [Console App de orquestracao em .NET 9](https://github.com/renatogroffe/dotnet9-consoleapp-otel-grafana_consumoapis)
- [API que acessa PostgreSQL, MySQL e Redis - .NET 9 + ASP.NET Core](https://github.com/renatogroffe/aspnetcore9-otel-grafana-postgres-mysql-redis_apicontagem)
- [API REST criada com Node.js](https://github.com/renatogroffe/nodejs-otel_apiconsumobackend)
- [API REST criada com Java + Spring + Apache Camel](https://github.com/renatogroffe/java-spring-camel_apiconsumobackend)

Referências:
- OpenTelemetry: https://opentelemetry.io/
- OpenTelemetry + .NET: https://learn.microsoft.com/en-us/dotnet/core/diagnostics/observability-with-otel
- Jaeger: 
- Grafana: 
- Grafana Alloy: 
- Zipkin: 
- Elastic APM: 
