---
schema-id: "github.com/nostagome/rocketa:example-v1"
created-ts: 2025-02-21 12:22:23T04:34:32Z
last-updated: 2025-02-21 12:22:23T04:34:32Z
sys-description: This is an example format.md extension to https://github.com/nostogome/rocketa/tree/main/format.md reservations.  Describes >>> as an extension, using a unique namespace (schema-id)
---
#this is the base format ( **reserved** ) for `chats`, `conversations`, `prompts` files, usually named `chat.md` or `prompt.md`. It enables automation, (e.g. pull automation), and simple readability.  Extendable at any level in release dirs.  Frontmatter is optional, but if included, schema-id ***required*** in the format `"<host>/<user>/<repo>:tag"` (e.g. `"github.com/nostagome/rocketa:v1"`) , *Note*: proper `tag`ging will have version embedded (e.g. `v1`, `v2/feature`).  Timestamps optional, but if included use `created-ts` and `last-updated` as keys.

---

model: com.openai.gpt4o,o1,o1-mini,com.openai.o3-mini
model: deepseek-r1
model-tunings: perplexity/uncensored
model-size: 14B
model-quants: Q6_K
model-url: perplexity.ai
provider: 
model: claude-sonnet-3.5
model-url: https://www.anthropic.com/claude/sonnet
provider: Vertex

```
> questions
< actual (raw) response
<- summary of response
<-- reaction to nominal response (addressing AI/(mis)conceptions/etc)
>> AI generated question (i.e. not the target AI response, a separate AI)
>>> a new extension for automated testing
```
