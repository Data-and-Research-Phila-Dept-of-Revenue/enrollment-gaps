# Outreach Data Tool

This data tool uses internal geospatial data on current enrollment in two assistance programs for homeowner-occupied residential properties - **Homestead Exemption and LOOP** - and compares it against the number of owner-occupied houses in each census tract, provided by the American Community Survey (ACS) published by the Census Bureau. 

## Enrollment Gap - Census
This data tool shows a map highlighting total enrollment gapa and in percent terms to identify census tracts that need more attention for outreach.

**Calculation**  

>**Absolute Enrollment Gap** = Total Number of Owner Occupied Residences in a Census Tract - Total Enrollment in Homestead and LOOP in each Census Tract

>**Enrollment Gap in Percent** = (Absolute Enrollment for each Census Tract / Total Number of Owner Occupied Residences in a Census Tract) * 100

### Maps

<div style="display: flex; justify-content: space-between;">
  <!-- First Plot -->
  <iframe
      src="https://data-and-research-phila-dept-of-revenue.github.io/enrollment-gaps/figs/enrollmentGap.html"
      width="49%"
      height="600"
      frameborder="0"
      scrolling="no">
  </iframe>

  <!-- Second Plot -->
  <iframe
      src="https://data-and-research-phila-dept-of-revenue.github.io/enrollment-gaps/figs/enrollmentGapPercent.html"
      width="49%"
      height="600"
      frameborder="0"
      scrolling="no">
  </iframe>
</div>


