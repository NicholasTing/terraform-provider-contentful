---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "contentful_space Resource - terraform-provider-contentful"
subcategory: ""
description: |-
  
---

# contentful_space (Resource)



## Example Usage

```terraform
resource "contentful_space" "example_space" {
  name = "example_space_name"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)

### Optional

- `default_locale` (String)

### Read-Only

- `id` (String) The ID of this resource.
- `version` (Number)
