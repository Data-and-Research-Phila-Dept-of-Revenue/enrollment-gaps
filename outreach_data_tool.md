<link rel="stylesheet" href="styles.css">

# Outreach Data Tool

This data tool uses internal geospatial data on current enrollment in two assistance programs for homeowner-occupied residential properties - **Homestead Exemption and LOOP** - and compares it against the number of owner-occupied houses in each census tract, provided by the American Community Survey (ACS) published by the Census Bureau. 

## Enrollment Gap - Census Tracts
Below maps visualize total enrollment gap in absolute and percent terms to identify census tracts that need more attention for outreach.

##### **Calculation**  

>**Absolute Enrollment Gap** = Total Number of Owner Occupied Residences in a Census Tract - Total Enrollment in Homestead and LOOP in each Census Tract

>**Enrollment Gap in Percent** = (Absolute Enrollment Gap for each Census Tract / Total Number of Owner Occupied Residences in a Census Tract) * 100

### Maps

<iframe
    src="https://data-and-research-phila-dept-of-revenue.github.io/enrollment-gaps/figs/enrollmentGap_cdBound.html"
    width="100%"
    height="600"
    frameborder="0"
    scrolling="no">
</iframe>


<iframe
    src="https://data-and-research-phila-dept-of-revenue.github.io/enrollment-gaps/figs/enrollmentGapPercent_cdBound.html"
    width="100%"
    height="600"
    frameborder="0"
    scrolling="no">
</iframe>

<ins>Note</ins>: The above map visualizes enrollment <ins>gap</ins> percent rather than just enrollment percent. (see [Calculation](#calculation))


## Total Enrollment - Council Districts

The map below vislualizes enrollment in Homestead and LOOP across Council Districts.

<iframe
    src="https://data-and-research-phila-dept-of-revenue.github.io/enrollment-gaps/figs/enrollment_cd.html"
    width="100%"
    height="600"
    frameborder="0"
    scrolling="no">
</iframe>

<ins>Note</ins>: Calculating the enrollment gap for each council district is complex, as census tracts do not align perfectly with council district boundaries. Since ACS data on owner-occupied residences is not broken down by council district, it cannot be directly used to assign values to specific districts when a single census tract overlaps multiple districts.
