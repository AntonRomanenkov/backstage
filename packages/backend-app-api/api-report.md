## API Report File for "@backstage/backend-app-api"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { BackendFeature } from '@backstage/backend-plugin-api';
import { BackendLifecycle } from '@backstage/backend-plugin-api';
import { Config } from '@backstage/config';
import { ExtensionPoint } from '@backstage/backend-plugin-api';
import { HttpRouterService } from '@backstage/backend-plugin-api';
import { Logger } from '@backstage/backend-plugin-api';
import { PermissionAuthorizer } from '@backstage/plugin-permission-common';
import { PermissionEvaluator } from '@backstage/plugin-permission-common';
import { PluginCacheManager } from '@backstage/backend-common';
import { PluginDatabaseManager } from '@backstage/backend-common';
import { PluginEndpointDiscovery } from '@backstage/backend-common';
import { PluginTaskScheduler } from '@backstage/backend-tasks';
import { ServiceFactory } from '@backstage/backend-plugin-api';
import { ServiceRef } from '@backstage/backend-plugin-api';
import { TokenManager } from '@backstage/backend-common';
import { UrlReader } from '@backstage/backend-common';

// @public (undocumented)
export interface Backend {
  // (undocumented)
  add(feature: BackendFeature): void;
  // (undocumented)
  start(): Promise<void>;
}

// @public (undocumented)
export const cacheFactory: (
  options?: undefined,
) => ServiceFactory<PluginCacheManager>;

// @public (undocumented)
export const configFactory: (options?: undefined) => ServiceFactory<Config>;

// @public (undocumented)
export function createSpecializedBackend(
  options: CreateSpecializedBackendOptions,
): Backend;

// @public (undocumented)
export interface CreateSpecializedBackendOptions {
  // (undocumented)
  services: (ServiceFactory | (() => ServiceFactory))[];
}

// @public (undocumented)
export const databaseFactory: (
  options?: undefined,
) => ServiceFactory<PluginDatabaseManager>;

// @public (undocumented)
export const discoveryFactory: (
  options?: undefined,
) => ServiceFactory<PluginEndpointDiscovery>;

// @public (undocumented)
export const httpRouterFactory: (
  options?: HttpRouterFactoryOptions | undefined,
) => ServiceFactory<HttpRouterService>;

// @public (undocumented)
export type HttpRouterFactoryOptions = {
  indexPlugin?: string;
};

// @public
export const lifecycleFactory: (
  options?: undefined,
) => ServiceFactory<BackendLifecycle>;

// @public (undocumented)
export const loggerFactory: (options?: undefined) => ServiceFactory<Logger>;

// @public (undocumented)
export const permissionsFactory: (
  options?: undefined,
) => ServiceFactory<PermissionAuthorizer | PermissionEvaluator>;

// @public (undocumented)
export const rootLoggerFactory: (options?: undefined) => ServiceFactory<Logger>;

// @public (undocumented)
export const schedulerFactory: (
  options?: undefined,
) => ServiceFactory<PluginTaskScheduler>;

// @public (undocumented)
export type ServiceOrExtensionPoint<T = unknown> =
  | ExtensionPoint<T>
  | ServiceRef<T>;

// @public (undocumented)
export const tokenManagerFactory: (
  options?: undefined,
) => ServiceFactory<TokenManager>;

// @public (undocumented)
export const urlReaderFactory: (
  options?: undefined,
) => ServiceFactory<UrlReader>;
```
