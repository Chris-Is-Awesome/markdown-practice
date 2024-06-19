# About
This is my Markdown playground for testing more advanced Markdown features and seeing what works with the GitHub Markdown parser.

[What works](/WorksOnGithub.md) | [What doesn't work](/DoesNotWorkOnGithub.md)

<details id="setitems">
<summary><b>setitems</b></summary>

<div style="border: 1px solid #FFF; padding: 10px; margin: 10px 0;">

**Alias(es):**
- `giveitems`

**Argument(s):**

| Index | Type   | Explanation |
| ----- | ------ | ----------- |
| 0     | text   | The item to set, the name of the melee item (`stick`, `sword`, `mace`, or `efcs`), or a shorthand for setting multiple (`all`, `dev`, or `none`)
| 1     | number | The level/count for the item

**Flag(s):**

| Flag        | Explanation |
| ----------- | ----------- |
| `--no-save` | Don't save the items to the save file automatically.

**Examples:**
- `setitems ice 4` will give you Ice Ring level 4
- `setitems mace` will give you Fire Mace
- `giveitems melee 0` will give you Stick
- `giveitems all` will give you all items at max (non-dev) level/counts
- `setitems dev --no-save` will give you all items at max level/counts, but it won't save them
</div>
</details>