# Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard developed as a freelance project for a family friend's small business in Myanmar. The report brings sales information into one view to support reviews of sales volume, product demand, and customer purchasing activity.

## Dashboard Preview

![Sales Analysis Dashboard](Sales%20analysis%20Dashboard%20Preview.png))

## Business Questions

- Which products account for the highest sales quantities?
- Which product categories contribute the most units sold?
- Which customers purchase the greatest quantities?
- How do sales quantities compare across employees?
- How is sales volume distributed across shipping countries?
- How does sales quantity vary across the months available in the dataset?

## Dashboard Features

| Feature | Description |
|---|---|
| Summary cards | Total sales quantity, customer count, product count, country count, and employee count |
| Monthly sales chart | Sales quantity grouped by month |
| Category breakdown | Sales quantity by product category |
| Top 10 products | Products ranked by total sales quantity |
| Top 10 customers | Customers ranked by total sales quantity |
| Employee comparison | Sales quantity associated with each employee |
| Geographic map | Sales quantity by shipping country |
| Shipping-name breakdown | Sales quantity grouped by the dataset's `ship_name` field |
| Year and month slicers | Filters for exploring reporting periods |

## Tools and Structure

- **Power BI Desktop:** Dashboard development and interactive visualisation.
- **DAX measures:** Sales quantity and summary indicators.
- **Sales table:** Product, category, customer, employee, and shipping fields.
- **Calendar table:** Year and month fields for time-based reporting.
- **Top N filters:** Rankings for the product and customer charts.

## How to View

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Use the year and month slicers to explore the available reporting periods.
4. Select chart elements to explore related sales activity.

## Interpretation and Limitations

The dashboard measures **sales quantity**, meaning units sold. It does not report revenue, profit, or margin.

Product and customer rankings are based on units sold, so a high ranking does not necessarily mean the highest financial contribution.

The monthly chart groups data by month. When comparing multiple years, use the year slicer to review each year separately.

## Author

**Kyaw Pyae Sone Hein**  
Bachelor of Computer Science, University of Wollongong  

[LinkedIn](https://www.linkedin.com/in/kyaw-pyae-sone-hein-849609292/)
