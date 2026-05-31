\# Project Hydra – Intelligence Center (.NET 10)



\## Overview



Project Hydra is an enterprise-style intelligence aggregation platform built to demonstrate modern software architecture, security, asynchronous programming, API integration, and frontend development using .NET 10, Angular, and Blazor.



The system simulates an intelligence center that gathers information from multiple backend services and presents a unified operational picture to authenticated users.



\## Architecture



```text

Angular Frontend

&#x20;       |

&#x20;       | JWT Authentication

&#x20;       |

Gateway API

&#x20;       |

&#x20;       | API Key Authentication

&#x20;       |

\-----------------------------

|                           |

Threat Intelligence API   Operations Intelligence API

|                           |

\-----------------------------

&#x20;       |

Aggregated Intelligence

&#x20;       |

Angular / Blazor UI

```



\## Technology Stack



\### Backend



\* .NET 10

\* ASP.NET Core Minimal APIs

\* JWT Authentication

\* Dependency Injection

\* HttpClientFactory

\* Swagger/OpenAPI



\### Frontend



\* Angular

\* Angular Signals

\* TypeScript

\* Blazor WebAssembly



\### Testing



\* NUnit



\## Key Features



\* API Gateway Pattern

\* JWT Authentication

\* API Key Security

\* Async Aggregation using Task.WhenAll

\* Angular Dashboard

\* Blazor Dashboard

\* Graceful Degradation

\* Service Layer Architecture

\* Automated Unit Testing



\## Author



Stephen Leonard

GitHub: https://github.com/khanleon



