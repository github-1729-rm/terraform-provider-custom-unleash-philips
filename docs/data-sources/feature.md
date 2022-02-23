---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "unleash_feature Data Source - terraform-provider-unleash"
subcategory: ""
description: |-
  Retrieve details of an existing feature
---

# unleash_feature (Data Source)

Retrieve details of an existing feature



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) Feature name
- **project_id** (String) The project id of the feature toggle

### Optional

- **id** (String) The ID of this resource.

### Read-Only

- **archived** (Boolean) Wether the feature toggle is archived or not
- **created_at** (String) The date the feature toggle was created
- **description** (String) The description of the feature toggle
- **environments** (List of Object) The environments of the feature toggle (see [below for nested schema](#nestedatt--environments))
- **stale** (Boolean) Wether the feature toggle is stale or not
- **type** (String) The type of the feature toggle

<a id="nestedatt--environments"></a>
### Nested Schema for `environments`

Read-Only:

- **enabled** (Boolean)
- **name** (String)

