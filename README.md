# IBM webMethods Technology Utilization Patterns

This repository is a dictionary of IBM webMethods technology patterns and how they are used. It grows continuously.

Each pattern is discussed and measured for its readiness for continuous delivery, using the aspects, indicators, rating scale and environment model defined in the framework article [Readiness for Continuous Delivery](https://github.com/ibm-webmethods-continuous-delivery/1c-framework/blob/main/articles/ContinuousDeliveryReadiness.md). The article is the single place where the metrics are defined. This repository does not repeat or redefine them.

## How a pattern is described

Not every aspect is relevant to every pattern, so each entry picks the relevant ones and says why the others were left out. An entry contains:

1. **Name and intent**: what the pattern is and when it is used.
2. **Technology and version**: the webMethods product(s) and version(s) the assessment applies to. A rating without a version is incomplete.
3. **Assumptions**: the branching strategy and the environment model (ephemeral only, or permanent environments and how their distance is managed) the ratings assume.
4. **Ratings**: for each selected aspect, a rating of Full, Partial or None, the observation that supports it (command, API, documented behavior), and the workaround when Partial.
5. **Aspects not applicable**: the aspects left out and the reason.

Template:

```markdown
## <Pattern name>

<Intent in one or two sentences.>

- Technology and version: <product, version>
- Assumes: <branching strategy>; <environment model>

| Aspect | Rating | Observation / workaround |
|---|---|---|
| 2 Configurability | Partial | <e.g. configurable via API but requires a restart> |
| 5 Testability | Full | <e.g. service runs headless in a container; mocks available> |

Not applicable: <aspect> (<reason>)
```

## Patterns

No patterns have been recorded yet.
