---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "fly_ip Resource - terraform-provider-fly"
subcategory: ""
description: |-
  Fly volume resource
---

# fly_ip (Resource)

Fly volume resource

## Example Usage

```terraform
resource "fly_ip" "exampleIp" {
  app  = "hellofromterraform"
  type = "v4"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `app` (String) Name of app to attach
- `type` (String) v4 or v6

### Read-Only

- `address` (String) ID of volume
- `id` (String) ID of address
- `region` (String) region

