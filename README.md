# 🔍 Spring AI Log Model Requests and Responses - 3 Easy Ways

This repository demonstrates **three beginner-friendly approaches** to log requests and responses when using **Spring AI**.

---

## 📌 What are we trying to achieve?

We want to **log both the requests** and the **responses** when making use of Spring AI in a Spring Boot application.

We found **three effective approaches** to make this happen—thanks to:
- [GitHub discussion thread](https://github.com/spring-projects/spring-ai/discussions/450)
- [GitHub issue comment](https://github.com/spring-projects/spring-ai/issues/883#issuecomment-2739772323)
- [Official Spring AI docs on ChatClient logging](https://docs.spring.io/spring-ai/reference/api/chatclient.html#_logging)

---
## 📚 Want a deeper explanation?

We’ve written a **detailed blog** that explains each logging method with code snippets, setup instructions, and FAQs to help you get started:

**🔗 Blog:** [Spring AI Log Model Requests and Responses - 3 Easy Ways](https://bootcamptoprod.com/spring-ai-log-model-requests-and-responses/)

---

## 🛠️ 3 Approaches for Logging Requests & Responses

| Approach | Description | Branch |
|---------|-------------|--------|
| ✅ **Custom Interceptor** | Uses `RestClientCustomizer` and a custom interceptor to log request/response details. | [`main`](https://github.com/BootcampToProd/spring-boot-ai-logging-demo/tree/main) |
| 📒 **Logbook Integration** | Leverages [Zalando’s Logbook](https://github.com/zalando/logbook) to log HTTP traffic cleanly. | [`logbook-logging`](https://github.com/BootcampToProd/spring-boot-ai-logging-demo/tree/logbook-logging) |
| 🧩 **SimpleLoggerAdvisor** | Uses Spring AI’s built-in `SimpleLoggerAdvisor` for logging. | [`simple-logger-advisor-logging`](https://github.com/BootcampToProd/spring-boot-ai-logging-demo/tree/simple-logger-advisor-logging) |

> ✨ Choose the branch based on the implementation you'd like to explore.



