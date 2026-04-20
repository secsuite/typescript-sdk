# Reference
## Index
<details><summary><code>client.index.<a href="/src/api/resources/index/client/Client.ts">get</a>() -> SecsuiteApi.GetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.index.get();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `IndexClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Documentation
<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">getDocumentationPageTree</a>({ ...params }) -> SecsuiteApi.GetPublicDocsTreeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns the navigation structure for documentation
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.getDocumentationPageTree();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicDocsTreeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">getADocumentationPage</a>({ ...params }) -> SecsuiteApi.GetPublicDocsPageSlugResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns the content and metadata for a documentation page
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.getADocumentationPage({
    slug: "slug"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicDocsPageSlugRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">searchDocumentation</a>({ ...params }) -> SecsuiteApi.GetPublicDocsSearchResponseItem[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Search through documentation content using the pre-built index
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.searchDocumentation({
    q: "q"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicDocsSearchRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">getSearchIndex</a>({ ...params }) -> SecsuiteApi.GetPublicDocsSearchIndexResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns the pre-built Orama search index for client-side searching
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.getSearchIndex();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicDocsSearchIndexRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">getDocumentationAsset</a>({ ...params }) -> unknown | null</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Serves binary assets (images, PDFs, etc.) from the docs repo
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.getDocumentationAsset({
    path: "path"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicDocsAssetsPathRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.documentation.<a href="/src/api/resources/documentation/client/Client.ts">gitHubWebhookForCacheInvalidation</a>({ ...params }) -> SecsuiteApi.PostPublicDocsWebhookResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Called by GitHub when docs are updated. Invalidates cache and rebuilds search index.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documentation.gitHubWebhookForCacheInvalidation();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.PostPublicDocsWebhookRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Config
<details><summary><code>client.config.<a href="/src/api/resources/config/client/Client.ts">getPublicServerConfigurationFlags</a>() -> SecsuiteApi.ServerConfig</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.config.getPublicServerConfigurationFlags();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ConfigClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Updater
<details><summary><code>client.updater.<a href="/src/api/resources/updater/client/Client.ts">getLatestReleaseInfoForTauriAutoUpdater</a>() -> SecsuiteApi.LatestJson</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.updater.getLatestReleaseInfoForTauriAutoUpdater();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `UpdaterClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.updater.<a href="/src/api/resources/updater/client/Client.ts">downloadASpecificReleaseAssetByTagAndFilename</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.updater.downloadASpecificReleaseAssetByTagAndFilename({
    tag: "v0.1.0",
    filename: "SecSuite_0.1.0_aarch64.dmg"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetPublicUpdaterDownloadTagFilenameRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UpdaterClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## DesktopAuth
<details><summary><code>client.desktopAuth.<a href="/src/api/resources/desktopAuth/client/Client.ts">exchangeAOneTimeCodeForADesktopSession</a>({ ...params }) -> SecsuiteApi.ExchangeDesktopCodeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Exchanges a one-time authorization code for a session cookie. No authentication required.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.desktopAuth.exchangeAOneTimeCodeForADesktopSession({
    code: "a1b2c3d4e5f6..."
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.ExchangeDesktopCodeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DesktopAuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.desktopAuth.<a href="/src/api/resources/desktopAuth/client/Client.ts">getDesktopSessionFromBearerToken</a>() -> SecsuiteApi.DesktopSessionResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Validates the desktop bearer token and returns session and user data.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.desktopAuth.getDesktopSessionFromBearerToken();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DesktopAuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.desktopAuth.<a href="/src/api/resources/desktopAuth/client/Client.ts">createAOneTimeDesktopAuthorizationCode</a>({ ...params }) -> SecsuiteApi.CreateDesktopCodeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generates a short-lived, one-time authorization code for the desktop app. Requires authenticated session.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.desktopAuth.createAOneTimeDesktopAuthorizationCode();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.CreateDesktopCodeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DesktopAuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Gateway
<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">scanUrlViaInternalMlGateway</a>({ ...params }) -> SecsuiteApi.GatewaySuccessResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.scanUrlViaInternalMlGateway({
    url: "https://example.com/login"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.ScanGatewayRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">analyzeArticleNewsTextViaInternalMlGateway</a>({ ...params }) -> SecsuiteApi.AnalysisGatewaySuccessResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.analyzeArticleNewsTextViaInternalMlGateway({
    text: "https://edition.cnn.com/2026/04/19/asia/north-korea-defector-intl-hnk-dst"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.AnalysisGatewayRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">analyzeEmailTextViaPhishingMicroservice</a>({ ...params }) -> SecsuiteApi.PhishingGatewaySuccessResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.analyzeEmailTextViaPhishingMicroservice({
    text: "Your account is suspended. Click this link now."
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.PhishingGatewayRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.gateway.<a href="/src/api/resources/gateway/client/Client.ts">analyzeTwitterAccountViaBotDetectionMicroservice</a>({ ...params }) -> SecsuiteApi.BotDetectionGatewaySuccessResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.gateway.analyzeTwitterAccountViaBotDetectionMicroservice({
    twitterId: "1234567890"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.BotDetectionGatewayRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GatewayClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## History
<details><summary><code>client.history.<a href="/src/api/resources/history/client/Client.ts">getCurrentUsersAnalysisHistory</a>({ ...params }) -> SecsuiteApi.HistoryListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.history.getCurrentUsersAnalysisHistory({
    page: 1,
    pageSize: 20,
    cacheHit: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetApiV1HistoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HistoryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.history.<a href="/src/api/resources/history/client/Client.ts">getOneAnalysisHistoryRecord</a>({ ...params }) -> SecsuiteApi.HistoryDetailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.history.getOneAnalysisHistoryRecord({
    id: "c2b5ef2b-7c89-4c70-af12-5c5c216f2a2d"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.GetApiV1HistoryIdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HistoryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.history.<a href="/src/api/resources/history/client/Client.ts">deleteOneAnalysisHistoryRecord</a>({ ...params }) -> SecsuiteApi.DeleteHistoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.history.deleteOneAnalysisHistoryRecord({
    id: "c2b5ef2b-7c89-4c70-af12-5c5c216f2a2d"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.DeleteApiV1HistoryIdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HistoryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.history.<a href="/src/api/resources/history/client/Client.ts">deleteMultipleAnalysisHistoryRecords</a>({ ...params }) -> SecsuiteApi.BulkDeleteHistoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.history.deleteMultipleAnalysisHistoryRecords({
    ids: ["ids"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.BulkDeleteHistoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HistoryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.history.<a href="/src/api/resources/history/client/Client.ts">migrateGuestAnalysisHistoryToCurrentUser</a>({ ...params }) -> SecsuiteApi.MigrateGuestHistoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.history.migrateGuestAnalysisHistoryToCurrentUser({
    guestSessionToken: "sess_abc123"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.MigrateGuestHistoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HistoryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Settings
<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">getCurrentUserProfileAndDashboardPreferences</a>() -> SecsuiteApi.ProfilePreferencesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.getCurrentUserProfileAndDashboardPreferences();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">updateCurrentUserProfileAndDashboardPreferences</a>({ ...params }) -> SecsuiteApi.ProfilePreferencesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.updateCurrentUserProfileAndDashboardPreferences();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.UpdateProfilePreferencesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">listCurrentUsersApiKeysWithUsageFields</a>() -> SecsuiteApi.ApiKeyListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.listCurrentUsersApiKeysWithUsageFields();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">createANewApiKeyForCurrentUser</a>({ ...params }) -> SecsuiteApi.ApiKeyCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.createANewApiKeyForCurrentUser();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.ApiKeyCreateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">getApiKeyUsageSummaryForCurrentUser</a>() -> SecsuiteApi.ApiKeyUsageSummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.getApiKeyUsageSummaryForCurrentUser();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">disableAnApiKey</a>({ ...params }) -> SecsuiteApi.ApiKeyActionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.disableAnApiKey({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.PostApiV1SettingsApiKeysIdDisableRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">enableAnApiKey</a>({ ...params }) -> SecsuiteApi.ApiKeyActionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.enableAnApiKey({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.PostApiV1SettingsApiKeysIdEnableRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.settings.<a href="/src/api/resources/settings/client/Client.ts">deleteAnApiKey</a>({ ...params }) -> SecsuiteApi.ApiKeyActionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.settings.deleteAnApiKey({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `SecsuiteApi.DeleteApiV1SettingsApiKeysIdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SettingsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

