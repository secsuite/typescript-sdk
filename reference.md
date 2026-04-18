# Reference
<details><summary><code>client.<a href="/src/Client.ts">predictPredictTwitterIdGet</a>({ ...params }) -> SecsuiteApi.BotDetectionSubgraphResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.predictPredictTwitterIdGet({
    twitter_id: "twitter_id"
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

**request:** `SecsuiteApi.PredictPredictTwitterIdGetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SecsuiteApiClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Scan
<details><summary><code>client.scan.<a href="/src/api/resources/scan/client/Client.ts">urlScanPost</a>({ ...params }) -> SecsuiteApi.ScanningScanResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Runs the full analysis pipeline: Google Safe Browsing, VirusTotal, reputation checking (WHOIS, DNS, Tranco, Shodan), SSL validation, screenshot capture, conditional file download & ML-based threat detection.
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
await client.scan.urlScanPost({
    url: "url"
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

**request:** `SecsuiteApi.ScanningScanRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ScanClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## System
<details><summary><code>client.system.<a href="/src/api/resources/system/client/Client.ts">healthHealthGet</a>() -> Record&lt;string, string&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.system.healthHealthGet();

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

**requestOptions:** `SystemClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.system.<a href="/src/api/resources/system/client/Client.ts">healthCheckHealthGet</a>() -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.system.healthCheckHealthGet();

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

**requestOptions:** `SystemClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Analysis
<details><summary><code>client.analysis.<a href="/src/api/resources/analysis/client/Client.ts">analyzeNewsApiV1AnalyzeNewsPost</a>({ ...params }) -> SecsuiteApi.FakeNewsNewsAnalysisResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.analysis.analyzeNewsApiV1AnalyzeNewsPost({
    text: "text"
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

**request:** `SecsuiteApi.FakeNewsNewsAnalysisRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AnalysisClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Scanner
<details><summary><code>client.scanner.<a href="/src/api/resources/scanner/client/Client.ts">scanEmailApiV1ScanEmailPost</a>({ ...params }) -> SecsuiteApi.PhishingEmailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.scanner.scanEmailApiV1ScanEmailPost({
    text: "Your account will be suspended. Click here to verify."
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

**request:** `SecsuiteApi.PhishingEmailRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ScannerClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

