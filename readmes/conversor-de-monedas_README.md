# Currency Converter — Java Console Project

> Documentation draft for [RichyTeller/conversor-de-monedas](https://github.com/RichyTeller/conversor-de-monedas). **Not published to GitHub.**

## Overview
A Java currency-conversion learning project. The original repository README describes an API client (`ConsultaApi`), a data `record`, JSON handling through Gson, and a `Principal` class. The exact source tree, JDK version, build configuration and API provider have not yet been verified.

## Technologies
- Java (version to confirm)
- Gson for JSON deserialization (as documented in the repository)
- External currency API (provider and authentication requirements to confirm)
- Console application

## Clone and inspect

```bash
git clone https://github.com/RichyTeller/conversor-de-monedas.git
cd conversor-de-monedas
```

1. Install a JDK matching the project configuration.
2. Open the cloned folder in IntelliJ IDEA or VS Code with Java extensions.
3. If `pom.xml` is present, import Maven dependencies. If `build.gradle` is present, import Gradle dependencies. Otherwise check how Gson is referenced before compiling.
4. Locate the `Principal` class and its `main` method. Run it through the IDE.
5. Configure the API endpoint and any required API key according to the source code. **Never commit API keys.**
6. Follow the menu prompts displayed by the application, if present.

## Troubleshooting
- **Class not found:** verify the configured source root, package and main class.
- **Gson missing:** resolve the Gson dependency in the actual build system.
- **API errors:** verify network access, provider availability and API credentials.
- **No Java source found:** the repository must include its runnable source before these instructions can be tested.

## Interview talking points
Explain request/response flow, JSON mapping with a Java record, input validation and error handling. Only describe behavior you can demonstrate in the checked-in code.

## Status
**Exact build/run commands pending inspection of the full Java source and build files.**
