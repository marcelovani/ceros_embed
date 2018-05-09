# Ceros Embed

The [Ceros](https://www.ceros.com/) Embed Module allows Ceros to be embedded on
nodes.

## Installation

Install as you would normally install a contributed Drupal module. See:
https://www.drupal.org/docs/7/extend/installing-modules
for further information.

## Configuration

### Field
The module provides a Ceros Embed field type that allows embed snippets to be
added to nodes.

The field display can be configured to:
* Replace the node content on the same display
* Hide the page title

### Filter Format
* A Ceros Embed filter format is provided and can be configured at
`admin/config/content/formats/ceros_embed`

#### Default allowed tags

| tag      | attributes                                                             |
| -------- | ---------------------------------------------------------------------- |
| `div`    | `style`, `id`                                                          |
| `iframe` | `allowfullscreen`, `src`, `style`, `frameborder`, `class`, `scrolling` |

## Usage

* Add/edit a node and add the Ceros Embed code to the field
* See https://www.ceros.com/educate/knowledge_base/embedding-ceros-on-a-website
  for more information
