# @backstage/plugin-tech-insights-node

## 0.3.7-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.16.1-next.0
  - @backstage/types@1.0.2-next.0
  - @backstage/backend-tasks@0.3.8-next.0
  - @backstage/config@1.0.5-next.0
  - @backstage/plugin-tech-insights-common@0.2.9-next.0

## 0.3.6

### Patch Changes

- 06cf8f1cf2: Add a default delay to the fact retrievers to prevent cold-start errors
- 30e43717c7: Use `HumanDuration` from `@backstage/types`
- Updated dependencies
  - @backstage/backend-common@0.16.0
  - @backstage/backend-tasks@0.3.7
  - @backstage/types@1.0.1
  - @backstage/config@1.0.4
  - @backstage/plugin-tech-insights-common@0.2.8

## 0.3.6-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.16.0-next.1
  - @backstage/backend-tasks@0.3.7-next.1
  - @backstage/config@1.0.4-next.0
  - @backstage/types@1.0.1-next.0
  - @backstage/plugin-tech-insights-common@0.2.8-next.0

## 0.3.6-next.0

### Patch Changes

- 06cf8f1cf2: Add a default delay to the fact retrievers to prevent cold-start errors
- 30e43717c7: Use `HumanDuration` from `@backstage/types`
- Updated dependencies
  - @backstage/backend-common@0.16.0-next.0
  - @backstage/backend-tasks@0.3.7-next.0
  - @backstage/types@1.0.1-next.0
  - @backstage/config@1.0.4-next.0
  - @backstage/plugin-tech-insights-common@0.2.8-next.0

## 0.3.5

### Patch Changes

- 0963b4d5fb: Updated package role to be `node-library`.
- Updated dependencies
  - @backstage/backend-common@0.15.2
  - @backstage/backend-tasks@0.3.6
  - @backstage/config@1.0.3
  - @backstage/types@1.0.0
  - @backstage/plugin-tech-insights-common@0.2.7

## 0.3.5-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-tasks@0.3.6-next.2
  - @backstage/backend-common@0.15.2-next.2
  - @backstage/config@1.0.3-next.2
  - @backstage/types@1.0.0
  - @backstage/plugin-tech-insights-common@0.2.7-next.2

## 0.3.5-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.15.2-next.1
  - @backstage/backend-tasks@0.3.6-next.1
  - @backstage/config@1.0.3-next.1
  - @backstage/types@1.0.0
  - @backstage/plugin-tech-insights-common@0.2.7-next.1

## 0.3.5-next.0

### Patch Changes

- 0963b4d5fb: Updated package role to be `node-library`.
- Updated dependencies
  - @backstage/backend-common@0.15.2-next.0
  - @backstage/backend-tasks@0.3.6-next.0
  - @backstage/config@1.0.3-next.0
  - @backstage/types@1.0.0
  - @backstage/plugin-tech-insights-common@0.2.7-next.0

## 0.3.4

### Patch Changes

- 3f739be9d9: Minor API signatures cleanup
- 2e0689e536: Support for timeout in FactRetrieverRegistrationOptions
- Updated dependencies
  - @backstage/backend-common@0.15.1
  - @backstage/backend-tasks@0.3.5
  - @backstage/config@1.0.2

## 0.3.4-next.1

### Patch Changes

- Updated dependencies
  - @backstage/config@1.0.2-next.0
  - @backstage/backend-common@0.15.1-next.3
  - @backstage/backend-tasks@0.3.5-next.1

## 0.3.4-next.0

### Patch Changes

- 3f739be9d9: Minor API signatures cleanup
- 2e0689e536: Support for timeout in FactRetrieverRegistrationOptions
- Updated dependencies
  - @backstage/backend-common@0.15.1-next.0
  - @backstage/backend-tasks@0.3.5-next.0

## 0.3.3

### Patch Changes

- 29f782eb37: Updated dependency `@types/luxon` to `^3.0.0`.
- Updated dependencies
  - @backstage/backend-common@0.15.0
  - @backstage/plugin-tech-insights-common@0.2.6

## 0.3.3-next.0

### Patch Changes

- 29f782eb37: Updated dependency `@types/luxon` to `^3.0.0`.
- Updated dependencies
  - @backstage/backend-common@0.15.0-next.0
  - @backstage/plugin-tech-insights-common@0.2.6-next.0

## 0.3.2

### Patch Changes

- 4e9a90e307: Updated dependency `luxon` to `^3.0.0`.
- bcc122c46d: The `FactRetriever` model has been extended by adding optional title and description fields, allowing you to display them in the UI.
- Updated dependencies
  - @backstage/backend-common@0.14.1
  - @backstage/plugin-tech-insights-common@0.2.5

## 0.3.2-next.1

### Patch Changes

- 4e9a90e307: Updated dependency `luxon` to `^3.0.0`.
- bcc122c46d: The `FactRetriever` model has been extended by adding optional title and description fields, allowing you to display them in the UI.
- Updated dependencies
  - @backstage/backend-common@0.14.1-next.3
  - @backstage/plugin-tech-insights-common@0.2.5-next.0

## 0.3.2-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.14.1-next.0

## 0.3.1

### Patch Changes

- aa15229ec3: Introduce additional JsonValue types to be storable as facts. This enables the possibility to store more complex objects for fact checking purposes. The rules engine supports walking keyed object values directly to create rules and checks

  Modify facts database table to have a more restricted timestamp precision for cases where the postgres server isn't configured to contain such value. This fixes the issue where in some cases `maxItems` lifecycle condition didn't work as expected.

- Updated dependencies
  - @backstage/backend-common@0.14.0

## 0.3.1-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.14.0-next.2

## 0.3.1-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.6-next.0

## 0.3.0

### Minor Changes

- 58e2c46151: **BREAKING**: The `FactRetrieverContext` type now contains an additional
  field: `tokenManager`.

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.3
  - @backstage/config@1.0.1

## 0.3.0-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.3-next.2
  - @backstage/config@1.0.1-next.0

## 0.3.0-next.1

### Minor Changes

- 58e2c46151: **BREAKING**: The `FactRetrieverContext` type now contains an additional
  field: `tokenManager`.

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.3-next.1

## 0.2.10-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.3-next.0

## 0.2.9

### Patch Changes

- 231fee736b: Adds an optional timeout to fact retriever registrations to stop a task if it runs too long.
- Updated dependencies
  - @backstage/backend-common@0.13.2

## 0.2.9-next.1

### Patch Changes

- 231fee736b: Adds an optional timeout to fact retriever registrations to stop a task if it runs too long.
- Updated dependencies
  - @backstage/backend-common@0.13.2-next.1

## 0.2.9-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.2-next.0

## 0.2.8

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.1
  - @backstage/config@1.0.0
  - @backstage/plugin-tech-insights-common@0.2.4

## 0.2.7

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.0

## 0.2.7-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.13.0-next.0

## 0.2.6

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.12.0

## 0.2.5

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.11.0

## 0.2.4

### Patch Changes

- Fix for the previous release with missing type declarations.
- Updated dependencies
  - @backstage/backend-common@0.10.9
  - @backstage/config@0.1.15
  - @backstage/plugin-tech-insights-common@0.2.3

## 0.2.3

### Patch Changes

- c77c5c7eb6: Added `backstage.role` to `package.json`
- Updated dependencies
  - @backstage/backend-common@0.10.8
  - @backstage/config@0.1.14
  - @backstage/plugin-tech-insights-common@0.2.2

## 0.2.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.7

## 0.2.2-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.7-next.0

## 0.2.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.6

## 0.2.1-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.6-next.0

## 0.2.0

### Minor Changes

- dfd5e81721: BREAKING CHANGES:

  - The helper function to create a fact retriever registration is now expecting an object of configuration items instead of individual arguments.
    Modify your `techInsights.ts` plugin configuration in `packages/backend/src/plugins/techInsights.ts` (or equivalent) the following way:

  ```diff
  -createFactRetrieverRegistration(
  -  '1 1 1 * *', // Example cron, At 01:01 on day-of-month 1.
  -  entityOwnershipFactRetriever,
  -),
  +createFactRetrieverRegistration({
  +  cadende: '1 1 1 * *', // Example cron, At 01:01 on day-of-month 1.
  +  factRetriever: entityOwnershipFactRetriever,
  +}),

  ```

  - `TechInsightsStore` interface has changed its signature of `insertFacts` method. If you have created your own implementation of either `TechInsightsDatabase` or `FactRetrieverEngine` you need to modify the implementation/call to this method to accept/pass-in an object instead if individual arguments. The interface now accepts an additional `lifecycle` argument which is optional (defined below). An example modification to fact retriever engine:

  ```diff
  -await this.repository.insertFacts(factRetriever.id, facts);
  +await this.repository.insertFacts({
  + id: factRetriever.id,
  + facts,
  + lifecycle,
  +});
  ```

  Adds a configuration option to fact retrievers to define lifecycle for facts the retriever persists. Possible values are either 'max items' or 'time-to-live'. The former will keep only n number of items in the database for each fact per entity. The latter will remove all facts that are older than the TTL value.

  Possible values:

  - `{ maxItems: 5 }` // Deletes all facts for the retriever/entity pair, apart from the last five
  - `{ ttl: 1209600000 }` // (2 weeks) Deletes all facts older than 2 weeks for the retriever/entity pair
  - `{ ttl: { weeks: 2 } }` // Deletes all facts older than 2 weeks for the retriever/entity pair

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.4
  - @backstage/config@0.1.13

## 0.2.0-next.0

### Minor Changes

- dfd5e81721: BREAKING CHANGES:

  - The helper function to create a fact retriever registration is now expecting an object of configuration items instead of individual arguments.
    Modify your `techInsights.ts` plugin configuration in `packages/backend/src/plugins/techInsights.ts` (or equivalent) the following way:

  ```diff
  -createFactRetrieverRegistration(
  -  '1 1 1 * *', // Example cron, At 01:01 on day-of-month 1.
  -  entityOwnershipFactRetriever,
  -),
  +createFactRetrieverRegistration({
  +  cadende: '1 1 1 * *', // Example cron, At 01:01 on day-of-month 1.
  +  factRetriever: entityOwnershipFactRetriever,
  +}),

  ```

  - `TechInsightsStore` interface has changed its signature of `insertFacts` method. If you have created your own implementation of either `TechInsightsDatabase` or `FactRetrieverEngine` you need to modify the implementation/call to this method to accept/pass-in an object instead if individual arguments. The interface now accepts an additional `lifecycle` argument which is optional (defined below). An example modification to fact retriever engine:

  ```diff
  -await this.repository.insertFacts(factRetriever.id, facts);
  +await this.repository.insertFacts({
  + id: factRetriever.id,
  + facts,
  + lifecycle,
  +});
  ```

  Adds a configuration option to fact retrievers to define lifecycle for facts the retriever persists. Possible values are either 'max items' or 'time-to-live'. The former will keep only n number of items in the database for each fact per entity. The latter will remove all facts that are older than the TTL value.

  Possible values:

  - `{ maxItems: 5 }` // Deletes all facts for the retriever/entity pair, apart from the last five
  - `{ ttl: 1209600000 }` // (2 weeks) Deletes all facts older than 2 weeks for the retriever/entity pair
  - `{ ttl: { weeks: 2 } }` // Deletes all facts older than 2 weeks for the retriever/entity pair

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.4-next.0
  - @backstage/config@0.1.13-next.0

## 0.1.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-common@0.10.0

## 0.1.1

### Patch Changes

- Updated dependencies
  - @backstage/plugin-tech-insights-common@0.2.0
  - @backstage/backend-common@0.9.12
