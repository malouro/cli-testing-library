---
id: buildQueries
title: buildQueries
---

<!-- DO NOT EDIT: this page is autogenerated from the type comments -->

# Function: buildQueries()

```ts
function buildQueries(queryBy, getMissingError): readonly [<T>(container, ...args) => T, <T>(container, ...args) => T, <T>(instance, text, options?, waitForOptions?) => Promise<T>]
```

Defined in: [query-helpers.ts:115](https://github.com/crutchcorn/cli-testing-library/blob/main/packages/cli-testing-library/src/query-helpers.ts#L115)

## Parameters

### queryBy

[`QueryMethod`](../type-aliases/querymethod.md)\<\[[`Matcher`](../type-aliases/matcher.md), [`MatcherOptions`](../interfaces/matcheroptions.md)\], `null` \| `TestInstance`\>

### getMissingError

[`GetErrorFunction`](../type-aliases/geterrorfunction.md)\<\[[`Matcher`](../type-aliases/matcher.md), [`MatcherOptions`](../interfaces/matcheroptions.md)\]\>

## Returns

readonly \[\<`T`\>(`container`, ...`args`) => `T`, \<`T`\>(`container`, ...`args`) => `T`, \<`T`\>(`instance`, `text`, `options`?, `waitForOptions`?) => `Promise`\<`T`\>\]
