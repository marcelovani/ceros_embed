# Ceros Embed

The [Ceros](https://www.ceros.com/) Embed Module allows Ceros to the embedded on nodes.

## Installation

Install as you would normally install a contributed Drupal module. See:
https://www.drupal.org/docs/7/extend/installing-modules
for further information.

## Configuration

### Field
* Add a Ceros Embed field to a content type
* Configure the field display on the node display settings

### Filter Format
* A Ceros Embed filter format is provided and can be configured at `admin/config/content/formats/ceros_embed`

#### Default allowed tags

| tag      | attributes                                                             |
| -------- | ---------------------------------------------------------------------- |
| `div`    | `style`, `id`                                                          |
| `iframe` | `allowfullscreen`, `src`, `style`, `frameborder`, `class`, `scrolling` |

## Usage

* Add/edit a node and add the Ceros Embed code to the field
* See https://www.ceros.com/educate/knowledge_base/embedding-ceros-on-a-website/ for more information