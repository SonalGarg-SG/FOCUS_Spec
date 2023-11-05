# Column: SkuCategory

## Example provider mappings

Current column mappings found in available data sets:

| Provider  | Data set                 | Column        |
| --------- | ------------------------ | ------------- |
| AWS       | CUR                      | None          |
| GCP       | Big Query Billing Export | None          |
| Microsoft | Cost details             | ServiceFamily |

## Discussion / Scratch space

SKU Category should align to the same principles as Service Category. They are synonymous in terms of categorization and only differ in that a SKU is often used as part of a larger service.

In reference to Service Category, we provide an example of how resources under the Databases service category may have storage and compute costs. Those storage and compute costs, while separate from the service category, would be tracked as a SKU category, where the compute usage and storage usage are separate SKUs being used as part of the larger database service.