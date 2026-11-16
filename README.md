# Automation Blueprints gallery

Source pages for the internal Automation Blueprints gallery. The published site is
rendered from the markdown files under `blueprints/`.

## Page format

Every page carries YAML front matter with the following fields:

| field | meaning |
| --- | --- |
| `blueprint_key` | stable identifier for the blueprint |
| `title` | display title |
| `status` | `published`, `draft` or `retired` |
| `domain` | owning domain |
| `owner_team` | owning team |
| `first_published` | date the blueprint first appeared in the gallery |
| `code_repo` | optional URL of the implementation repository for the blueprint |

Implementation repositories for gallery blueprints are named
`eg3454-impl-<blueprint_key>` and live under the gallery maintainer's account.

## Editing

Pages are edited directly in this repository; the gallery build picks up the
front matter on the next deployment.
