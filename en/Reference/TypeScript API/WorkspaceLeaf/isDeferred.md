---
aliases: "WorkspaceLeaf.isDeferred"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`WorkspaceLeaf`](WorkspaceLeaf) › [`isDeferred`](WorkspaceLeaf/isDeferred)

## WorkspaceLeaf.isDeferred property

Returns true if this leaf is currently deferred because it is in the background. A deferred leaf will have a DeferredView as its view, instead of the View that it should normally have for its type (like MarkdownView for the `markdown` type).  1.7.2

**Signature:**

```typescript
get isDeferred(): boolean;
```