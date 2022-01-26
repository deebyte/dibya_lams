---
title: Issues - 22⛔ 78⚠️  
navigation: true
---

<p style="text-align:right;color:#cccs">
Generated Wed, 26 Jan 2022 09:42:45 GMT
</p>

<details style="margin-left: 3em" open="open">
<summary style="margin-left:-1em;border-bottom:solid 1px #333;font-size:200%;">Issues (22⛔78⚠️)</summary>

<details style="margin-left: 3em" open="open">
<summary style="margin-left:-1em;border-bottom:solid 1px #333;font-size:170%;"><a href="https://looker-open-source.github.io/look-at-me-sideways/rules.html#e2">E2</a>. Primary keys used (8⛔)</summary>

<table>
<thead><tr>
<th>Level</th>
<th>Location</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:events&#47;join:users </td>
<td>No PKs dimensions used for users in users join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:inventory_items&#47;join:products </td>
<td>No PKs dimensions used for products in products join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:inventory_items&#47;join:distribution_centers </td>
<td>No PKs dimensions used for distribution_centers in distribution_centers join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:order_items&#47;join:inventory_items </td>
<td>No PKs dimensions used for inventory_items in inventory_items join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:order_items&#47;join:users </td>
<td>No PKs dimensions used for users in users join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:order_items&#47;join:products </td>
<td>No PKs dimensions used for products in products join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:order_items&#47;join:distribution_centers </td>
<td>No PKs dimensions used for distribution_centers in distribution_centers join</td>
</tr>
<tr>
<td>⛔</td>
<td>model:dibya_lams&#47;explore:products&#47;join:distribution_centers </td>
<td>No PKs dimensions used for distribution_centers in distribution_centers join</td>
</tr></tbody></table></details>
<details style="margin-left: 3em" open="open">
<summary style="margin-left:-1em;border-bottom:solid 1px #333;font-size:170%;"><a href="https://looker-open-source.github.io/look-at-me-sideways/rules.html#f3">F3</a>. Count fields filtered (7⛔)</summary>

<table>
<thead><tr>
<th>Level</th>
<th>Location</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td>⛔</td>
<td>view:distribution_centers&#47;field:count </td>
<td>Type:count measure at view:distribution_centers/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:etl_jobs&#47;field:count </td>
<td>Type:count measure at view:etl_jobs/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:events&#47;field:count </td>
<td>Type:count measure at view:events/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:inventory_items&#47;field:count </td>
<td>Type:count measure at view:inventory_items/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:order_items&#47;field:count </td>
<td>Type:count measure at view:order_items/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:products&#47;field:count </td>
<td>Type:count measure at view:products/field:count does not have a filter applied</td>
</tr>
<tr>
<td>⛔</td>
<td>view:users&#47;field:count </td>
<td>Type:count measure at view:users/field:count does not have a filter applied</td>
</tr></tbody></table></details>
<details style="margin-left: 3em" open="open">
<summary style="margin-left:-1em;border-bottom:solid 1px #333;font-size:170%;"><a href="https://looker-open-source.github.io/look-at-me-sideways/rules.html#f4">F4</a>. Description or hidden (78⚠️)</summary>

<table>
<thead><tr>
<th>Level</th>
<th>Location</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:id </td>
<td>view:distribution_centers/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:latitude </td>
<td>view:distribution_centers/field:latitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:longitude </td>
<td>view:distribution_centers/field:longitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:name </td>
<td>view:distribution_centers/field:name is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:total_latitude </td>
<td>view:distribution_centers/field:total_latitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:average_latitude </td>
<td>view:distribution_centers/field:average_latitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:distribution_centers&#47;field:count </td>
<td>view:distribution_centers/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:etl_jobs&#47;field:id </td>
<td>view:etl_jobs/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:etl_jobs&#47;field:count </td>
<td>view:etl_jobs/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:id </td>
<td>view:events/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:browser </td>
<td>view:events/field:browser is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:city </td>
<td>view:events/field:city is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:country </td>
<td>view:events/field:country is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:event_type </td>
<td>view:events/field:event_type is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:ip_address </td>
<td>view:events/field:ip_address is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:latitude </td>
<td>view:events/field:latitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:longitude </td>
<td>view:events/field:longitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:os </td>
<td>view:events/field:os is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:sequence_number </td>
<td>view:events/field:sequence_number is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:session_id </td>
<td>view:events/field:session_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:state </td>
<td>view:events/field:state is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:traffic_source </td>
<td>view:events/field:traffic_source is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:uri </td>
<td>view:events/field:uri is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:user_id </td>
<td>view:events/field:user_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:zip </td>
<td>view:events/field:zip is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:total_sequence_number </td>
<td>view:events/field:total_sequence_number is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:average_sequence_number </td>
<td>view:events/field:average_sequence_number is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:events&#47;field:count </td>
<td>view:events/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:id </td>
<td>view:inventory_items/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:cost </td>
<td>view:inventory_items/field:cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_brand </td>
<td>view:inventory_items/field:product_brand is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_category </td>
<td>view:inventory_items/field:product_category is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_department </td>
<td>view:inventory_items/field:product_department is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_distribution_center_id </td>
<td>view:inventory_items/field:product_distribution_center_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_id </td>
<td>view:inventory_items/field:product_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_name </td>
<td>view:inventory_items/field:product_name is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_retail_price </td>
<td>view:inventory_items/field:product_retail_price is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:product_sku </td>
<td>view:inventory_items/field:product_sku is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:total_cost </td>
<td>view:inventory_items/field:total_cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:average_cost </td>
<td>view:inventory_items/field:average_cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:inventory_items&#47;field:count </td>
<td>view:inventory_items/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:id </td>
<td>view:order_items/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:inventory_item_id </td>
<td>view:order_items/field:inventory_item_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:order_id </td>
<td>view:order_items/field:order_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:sale_price </td>
<td>view:order_items/field:sale_price is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:status </td>
<td>view:order_items/field:status is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:user_id </td>
<td>view:order_items/field:user_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:total_sale_price </td>
<td>view:order_items/field:total_sale_price is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:average_sale_price </td>
<td>view:order_items/field:average_sale_price is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:order_items&#47;field:count </td>
<td>view:order_items/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:id </td>
<td>view:products/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:brand </td>
<td>view:products/field:brand is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:category </td>
<td>view:products/field:category is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:cost </td>
<td>view:products/field:cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:department </td>
<td>view:products/field:department is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:distribution_center_id </td>
<td>view:products/field:distribution_center_id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:name </td>
<td>view:products/field:name is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:retail_price </td>
<td>view:products/field:retail_price is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:sku </td>
<td>view:products/field:sku is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:total_cost </td>
<td>view:products/field:total_cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:average_cost </td>
<td>view:products/field:average_cost is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:products&#47;field:count </td>
<td>view:products/field:count is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:id </td>
<td>view:users/field:id is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:age </td>
<td>view:users/field:age is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:city </td>
<td>view:users/field:city is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:country </td>
<td>view:users/field:country is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:email </td>
<td>view:users/field:email is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:first_name </td>
<td>view:users/field:first_name is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:gender </td>
<td>view:users/field:gender is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:last_name </td>
<td>view:users/field:last_name is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:latitude </td>
<td>view:users/field:latitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:longitude </td>
<td>view:users/field:longitude is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:state </td>
<td>view:users/field:state is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:traffic_source </td>
<td>view:users/field:traffic_source is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:zip </td>
<td>view:users/field:zip is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:total_age </td>
<td>view:users/field:total_age is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:average_age </td>
<td>view:users/field:average_age is missing a description</td>
</tr>
<tr>
<td>⚠️</td>
<td>view:users&#47;field:count </td>
<td>view:users/field:count is missing a description</td>
</tr></tbody></table></details>
<details style="margin-left: 3em" open="open">
<summary style="margin-left:-1em;border-bottom:solid 1px #333;font-size:170%;"><a href="https://looker-open-source.github.io/look-at-me-sideways/rules.html#k1">K1</a>. Primary keys required (7⛔)</summary>

<table>
<thead><tr>
<th>Level</th>
<th>Location</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td>⛔</td>
<td>view: distribution_centers </td>
<td>No Primary Key Dimensions found in distribution_centers</td>
</tr>
<tr>
<td>⛔</td>
<td>view: etl_jobs </td>
<td>No Primary Key Dimensions found in etl_jobs</td>
</tr>
<tr>
<td>⛔</td>
<td>view: events </td>
<td>No Primary Key Dimensions found in events</td>
</tr>
<tr>
<td>⛔</td>
<td>view: inventory_items </td>
<td>No Primary Key Dimensions found in inventory_items</td>
</tr>
<tr>
<td>⛔</td>
<td>view: order_items </td>
<td>No Primary Key Dimensions found in order_items</td>
</tr>
<tr>
<td>⛔</td>
<td>view: products </td>
<td>No Primary Key Dimensions found in products</td>
</tr>
<tr>
<td>⛔</td>
<td>view: users </td>
<td>No Primary Key Dimensions found in users</td>
</tr></tbody></table></details></details>

---

### Icon Key
<table>
<thead><tr>
<th></th>
<th>non-exempted</th>
<th>exempted</th>
</tr></thead>
<tbody>
<tr>
<td>Error</td>
<td>⛔</td>
<td>🙈</td>
</tr>
<tr>
<td>Warning</td>
<td>⚠️</td>
<td>🚧</td>
</tr>
</tbody>
</table>


