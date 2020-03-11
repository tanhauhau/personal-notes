---
tags: framework,reactivity
---

read: https://medium.com/@ryansolid/b-y-o-f-part-3-change-management-in-javascript-frameworks-6af6e436f63c

unique dimension to look at change maangement
- granularity
  - the boundary of mutable meets immutable
  - eg: observable (eg: vue, angular), components (eg: react), root (eg: redux)

- propagation
  - where does the change starts to kick off
  - data flow
  - eg: top down (eg: react), events (eg: angular)

- scheduling
  - when to kick off
  - eg: manual, immediate, deferred, windowed
