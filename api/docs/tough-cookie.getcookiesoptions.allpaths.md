<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tough-cookie](./tough-cookie.md) &gt; [GetCookiesOptions](./tough-cookie.getcookiesoptions.md) &gt; [allPaths](./tough-cookie.getcookiesoptions.allpaths.md)

## GetCookiesOptions.allPaths property

If `true`<!-- -->, do not scope cookies by path. If `false`<!-- -->, then RFC-compliant path scoping will be used.

**Signature:**

```typescript
allPaths?: boolean | undefined;
```

## Remarks

- May not be supported by the underlying store (the default [MemoryCookieStore](./tough-cookie.memorycookiestore.md) supports it).

Defaults to `false` if not provided.
