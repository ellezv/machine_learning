# Introduction to Machine Learning

Using Pandas, Numpy, Matplotlib, and Jupyter Notebook to analyze data sets.

## Analyze a Data Set:

The data set concerns housing values in suburbs of Boston. You can find more [here](https://archive.ics.uci.edu/ml/datasets/Housing)

### Attribute Information:

1. CRIM: per capita crime rate by town 
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft. 
3. INDUS: proportion of non-retail business acres per town 
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) 
5. NOX: nitric oxides concentration (parts per 10 million) 
6. RM: average number of rooms per dwelling 
7. AGE: proportion of owner-occupied units built prior to 1940 
8. DIS: weighted distances to five Boston employment centres 
9. RAD: index of accessibility to radial highways 
10. TAX: full-value property-tax rate per $10,000 
11. PTRATIO: pupil-teacher ratio by town 
12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town 
13. LSTAT: % lower status of the population 
14. MEDV: Median value of owner-occupied homes in $1000's

### Analysis:

- The median and average home values across all Boston Suburbs in dollars.
- The median home value of the suburb with the newest houses.
- The relationship between per-capita crime rate and the pupil-teacher ratio. Differentiate between whether or not the suburb is bounded by the Charles River.
- The relationship between the proportion of black citizens and the distance to employment centers in Boston.
- The relationship between median value of owner-occuped homes and nitric oxide concentration along with median home value and the proportion of non-retail business (on the same plot).
- The full-value property-tax rate per \$10,000 in suburbs with the most newest constructions vs in suburbs with most older houses



## Work with Imperfect Data:

For this exercise I worked with a data set from data.seattle.gov. [This DataSet](https://data.seattle.gov/Permitting/seattle-demolition/j6ng-5q2r) concerns the recent building permits for demolition only.

### Attributes Informations : 

1. **Application/Permit Number:** *The tracking number used to refer to this application or permit record in various Seattle DCI tracking systems.*
2. **Permit Type:** *Type of activity covered by the permit.*
3. **Address:** *Street address of the work site.*
4. **Description:** *Brief description of the work that will be done under this permit. This is subject to change prior to issuance of the permit, but generally more stable if an issue date exists. Very long descriptions have been truncated.*
5. **Category:** *The broad category of use or occupancy for the building where work is proposed. Valid choices are Commercial, Industrial, Institutional, Multifamily, and Single Family/Duplex. Mixed use structures are generally represented as Commercial.*
6. **Action Type:** *Subclassification for type of work being proposed. Valid choices will vary depending on the permit type.*
7. **Work Type:** *An indicator of the complexity of the project proposed. Easier projects can be issued without plan review; more complex projects generally require plan submittal and review.*
8. **Value:** *The value of the work being proposed based on fair market value (parts plus labor). The value displayed (if any) represents the best available information to date, and is subject to change if the project is modified. Value is not collected for all permit types.*
9. **Applicant Name:** *The name of the person or company listed on the application as the “primary applicant”. This may be the property owner, contractor, design professional, or other type of agent.*
10. **Application Date:** *The date the application was accepted as a complete submittal. If no Application Date exists this generally means the application is in a very early stage.*
11. **Issue Date:** *The date the application was issued as a valid permit. If an Application Date exists but no Issue Date exists, this generally means the application is still under review.*
12. **Final Date:** *The date the permit had all its inspections completed. If an Issue Date exists but no Final Date exists, this generally means the permit is still under inspection.*
13. **Expiration Date:** *The date the application is due to expire. Generally, this is the date by which work is supposed to be completed (baring renewals or further extensions). If no Expiration Date exists, this generally means the application is has not been issued yet.*
14. **Status:** *The current status in the application/review/inspection lifecycle. Indicates the last process step that was fully completed.*
15. **Permit and Complaint Status URL:** *Link to view full details and current status information about this permit at Seattle DCI's website.*
16. **Latitude:** *Latitude of the worksite where permit activity occurs. May be missing for a small number of permits considered "Unaddressable"*
17. **Longitude:** *Longitude of the worksite where permit activity occurs. May be missing for a small number of permits considered "Unaddressable"*
18. **Location:** *Mapping coordinates for the permit address.*

### Analysis:

1. What is the proportion of single family house being demolished?
2. What is the proportion of pending permits ?
3. Who has the most applications pending ?
4. Who has the most applications ?
5. What is the proportion of single applications applicants vs multiple applications applicants?

