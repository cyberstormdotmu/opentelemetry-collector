# Memory Limiter Extension

<!-- status autogenerated section -->
| Status        |           |
| ------------- |-----------|
| Stability     | [development]  |
| Distributions | [] |
| Issues        | [![Open issues](https://img.shields.io/github/issues-search/open-telemetry/opentelemetry-collector?query=is%3Aissue%20is%3Aopen%20label%3Aextension%2Fmemorylimiter%20&label=open&color=orange&logo=opentelemetry)](https://github.com/open-telemetry/opentelemetry-collector/issues?q=is%3Aopen+is%3Aissue+label%3Aextension%2Fmemorylimiter) [![Closed issues](https://img.shields.io/github/issues-search/open-telemetry/opentelemetry-collector?query=is%3Aissue%20is%3Aclosed%20label%3Aextension%2Fmemorylimiter%20&label=closed&color=blue&logo=opentelemetry)](https://github.com/open-telemetry/opentelemetry-collector/issues?q=is%3Aclosed+is%3Aissue+label%3Aextension%2Fmemorylimiter) |

[development]: https://github.com/open-telemetry/opentelemetry-collector/blob/main/docs/component-stability.md#development
<!-- end autogenerated section -->

The memory limiter extension is used to prevent out of memory situations on
the collector. The extension will potentially replace the Memory Limiter Processor. 
It provides better guarantees from running out of memory as it will be used by the 
receivers to reject requests before converting them into OTLP. All the configurations 
are the same as Memory Limiter Processor. The extension is under development and does nothing.

see [memorylimiterprocessor](../../processor/memorylimiterprocessor/README.md) for additional details
