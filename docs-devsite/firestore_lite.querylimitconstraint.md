Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# QueryLimitConstraint class
A `QueryLimitConstraint` is used to limit the number of documents returned by a Firestore query. `QueryLimitConstraint`<!-- -->s are created by invoking [limit()](./firestore_.md#limit) or [limitToLast()](./firestore_.md#limittolast) and can then be passed to [query()](./firestore_.md#query) to create a new query instance that also contains this `QueryLimitConstraint`<!-- -->.

<b>Signature:</b>

```typescript
export declare class QueryLimitConstraint extends QueryConstraint 
```
<b>Extends:</b> [QueryConstraint](./firestore_lite.queryconstraint.md#queryconstraint_class)

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [type](./firestore_lite.querylimitconstraint.md#querylimitconstrainttype) |  | 'limit' \| 'limitToLast' | The type of this query constraint |

## QueryLimitConstraint.type

The type of this query constraint

<b>Signature:</b>

```typescript
readonly type: 'limit' | 'limitToLast';
```