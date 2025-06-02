![image](https://github.com/user-attachments/assets/91f70c24-0ced-4d8b-b644-343dc7acdb49)# Canadian Pipeline Throughput Visualization

This project examines throughput and capacity trends for major Canadian pipelines, utilizing data from the Canada Energy Regulator (CER). The assignment includes data processing in R and visualizations for three pipelines: Enbridge Mainline, Trans Mountain, and TCPL Mainline.

### Enbridge Mainline Throughput by Product

![Enbridge Mainline Plot](Images/enbridge_plot.png)

> This plot shows monthly shipments through the Enbridge Mainline by product type, with dual-axis conversion to barrels/day.

---

### Trans Mountain Shipments by Product and Destination

![Trans Mountain Plot](Images/transmountain_plot.png)

> Area chart visualizing shipment volumes at Burnaby, Sumas, and Westridge terminals by product type.

---

### TCPL Mainline: Throughput vs. Capacity

![TCPL Plot](Images/tcpl_plot.png)

> Rolling-average throughput vs. nameplate capacity at three key points on the TCPL mainline. Annotated with stylized themes and clear faceting.

---

### U.S. Crude Imports by Origin

![U.S. Crude Imports Plot](Images/us_imports_plot.png)

> This area plot shows Canadian vs. Rest of World (ROW) crude imports by U.S. refining PADD and grade.

---

### Alberta Royalty Revenue (1970–2023)

![Alberta Royalty Revenue Plot](Images/royalty_rev_plot.png)

> Historical visualization of Alberta's royalty revenues across six key resource categories. Y-axis scaled in billions of CAD.

---

## Tools & Packages Used

- **R** (`tidyverse`, `ggplot2`, `lubridate`, `janitor`, `zoo`)
- **Data Sources**:
  - Canada Energy Regulator (CER)
  - Open CER CSV Downloads (throughput & capacity)


