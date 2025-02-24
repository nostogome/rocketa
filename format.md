---
schema-id: "github.com/nostagome/rocketa:v1"
created-ts: 2025-02-21 12:22:23T04:34:32Z
last-updated: 2025-02-21 12:22:23T04:34:32Z
sys-description: reservations for format.md files
---
#this is the base format ( **reserved** ) for `chats`, `conversations`, `prompts` files, usually named `chat.md` or `prompt.md`. It enables automation, (e.g. pull automation), and simple readability.  Extendable at any level in release dirs.  Frontmatter is optional, but if included, schema-id ***required*** in the format `"<host>/<user>/<repo>:tag"` (e.g. `"github.com/nostagome/rocketa:v1"`) , *Note*: proper `tag`ging will have version embedded (e.g. `v1`, `v2/feature`).  Timestamps optional, but if included use `created-ts` and `last-updated` as keys.

---
```
model: gpt-4o
provider:
> questions
< actual (raw) response
<- summary of response
<-- reaction to nominal response (addressing AI/(mis)conceptions/etc)
```