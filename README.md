This project aimed to perform a quantitative geospatial assessment of the association between lymphatic filariasis (LF) and poverty at the sub-national level in Nigeria.  This investigation was motivated by a noticeable gap in the literature establishing magnitude and directionality of the aforementioned association.  
Poverty data, LF prevalence (represented as points) and covariates were layered atop each other for the whole of Nigeria. Using various tools available in ArcGIS, values for each variable were assigned to each LF prevalence point based on geographic location.  This data was merged into a single table and exported. This table was then imported to SAS and the data was explored and analyzed. 
Aspatial analyses: Simple linear regression as well as multiple linear regression models were run.  Multicollinearity tests were run to eliminate variables that threatened the validity of the measure of association. Multicollinearity was assessed by examining the condition indices (CNI > 30) and proportion of variance values (>0.5).  Once candidate variables were selected, an all-possible subsets, backwards elimination approach was employed to evaluate whether or not variables appeared to be confounders of the poverty-LF association.  Variables were considered confounders if they modified the relationship between poverty and LF by more than 10% in either direction.  If variables did not appear to be confounders, they were dropped from the model.  
Spatial analyses: Global and local analyses as well as geographically weighted regression were performed to assess the poverty-LF relationship in the Nigerian states of Benue and Imo.  These two states were chosen because they appeared to have the most heterogeneity of LF burden and poverty.  A 50 kilometer buffer was used for edge correction around each state.  
Global analyses included using Ripley’s K-function to investigate whether or not LF prevalence points were clustered in space.  A weighted K-function analysis followed to determine if the prevalence at each point were clustered, dispersed, or randomly distributed within the pattern of points.  Analyses were carried out in Point Pattern Analysis (PPA).
Local analyses included a hot spot analysis using the Getis statistic (Gi(d)) to identify the locations where clustering of LF occurred (using ArcMAP).  A distance band of 17,000 meters was used for the state of Benue, and 13,500 meters was used for Imo.  These bands were chosen based upon calculating the distance band from neighbor count tool in ArcMAP and designating two neighbors.  A bivariate cluster analysis using a bivariate LISA (local Moran’s I) using a 1/d weighting scheme was conducted to assess the relationship between poverty at a given point with the LF prevalence values of neighboring points (using Geoda).
Ordinary least squares unadjusted and adjusted models were run (using ArcMAP) to assess the spatial structure of the model residuals. Models were based upon findings in the aspatial analysis.  Geographically weighted regression was then performed on the unadjusted and adjusted models to examine whether allowing regression coefficients to vary spatially improved the fit of the model.
More detail and results can be found in the ‘Stearns_FinalReport’ document found in the ‘Documents’ folder.

