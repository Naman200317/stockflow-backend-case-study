Part 3: Low Stock Alerts API

Endpoint:
GET /api/companies/{company_id}/alerts/low-stock

Logic:
- Check inventory across warehouses
- Apply product-specific thresholds
- Filter products with recent sales
- Include supplier details

Assumptions documented separately.
