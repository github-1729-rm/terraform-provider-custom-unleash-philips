---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "unleash_strategy_assignment Resource - terraform-provider-unleash"
subcategory: ""
description: |-
  Provides a resource for add strategy to a feature toggle in the given environment.
---

# unleash_strategy_assignment (Resource)

Provides a resource for add strategy to a feature toggle in the given environment.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **environment** (String) The environment where the strategy will take place
- **feature_name** (String) Feature name to assign the strategy to
- **project_id** (String) The unleash project the feature is in
- **strategy_name** (String) Strategy unique name

### Optional

- **id** (String) The ID of this resource.
- **parameters** (Map of String) Strategy parameters. All the values need to informed as strings.

### Read-Only

- **strategy_id** (String) Strategy id

