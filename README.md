# MB5370-Module-2-Workshop-2

Workshop 2: Advanced data wrangling built on the foundational skills from workshop 1 and focussed on reshaping data and merging it with spatial and temporal metadata to extract clearer biological signals from noisy ecological data. The workshop centred on tidy data principles and the tidyverse tools needed to reshape, clean, and join real world datasets.
 
The workshop covered reshaping data using pivot_longer() and pivot_wider() which was applied to example datasets that included table1, table2, table3, billboard, cms_patient_experience, and palmerpenguins. It converted morphometric measurements into long format for faceted histogram plotting, and widening summarised mass data into a species by island matrix. Separate() and unite() was also introduced for splitting and rejoining columns. 
 
String and dates were cleaned using stringr functions like str_to_lower(), str_trim(), and str_replace_all() to standardise messy site names. Lubridate functions like dmy(), ymd(), and dmy_hms() were used to parse inconsistent date and datetime formats. Relational joins like left_join(), inner_join(), and anti_join() were then used to merge biological observation data with spatial site metadata.
 
Handling missing values was covered in depth and included converting error codes to true NA values with na_if(), replacing missing counts with coalesce(), understanding NaN results from calculations like CPUE, revealing implicit missing combinations with complete(), and removing incomplete rows with drop_na().
 
The workshop concluded with a penguin’s dataset exercise. The exercise involved cleaning messy island metadata like standardising text and parsing inconsistent date formats and joining this metadata to the penguin’s dataset and producing a widened summary table of maximum body mass by species and island.
