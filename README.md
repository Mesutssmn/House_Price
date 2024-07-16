<div style="border-radius: 40px; border: #5E5772 solid; padding: 12px; background-color: #2995; font-size: 150%; text-align: left;">

<h3 align="center"><font color='#30000' size=120%>House Price Prediction</font></h3>

    
<h4 align="left"><font color='#30000' size=5%>To Do :</font></h4>
    
<li> Cleaning dataset for classification</li>
    
<li> Some analysis and statistics</li>
    
<li> ML, ANN
    
    

<h3 align="left"><font color='#300000' size=5%>ABOUT DATA:</font></h3>

This dataset is related to housing prices in Ames, Iowa, and is designed to facilitate predictive modeling of property sale prices. It includes comprehensive information about various attributes of residential homes, covering aspects such as the physical characteristics of the properties, their quality and condition, and their geographical locations within the city. The dataset comprises several files: train.csv for training the model, test.csv for testing, and a sample_submission.csv which provides a benchmark prediction model based on a linear regression. The columns range from basic information like lot area and number of bedrooms to more specific details like the quality of the basement and type of garage. The target variable to be predicted is the SalePrice, representing the sale price of the property in dollars. The data description file provides detailed explanations of each column, assisting in the understanding and preprocessing of the dataset for predictive analytics.
    

<div style="border-radius: 10px; overflow: hidden; text-align: center;">
    <img src="https://www.essential-business.pt/wp-content/uploads/2024/05/housingcosts-1024x626-1.jpg" alt="Price" width="900"></div>

<div style="border-radius: 10px; overflow: hidden; text-align: left;">
    <img src="https://media.istockphoto.com/id/1320991884/photo/aerial-view-of-residential-distratic-at-major-mackenzie-dr-and-islinton-ave-detached-and.jpg?s=612x612&w=0&k=20&c=KY59fkCfg9zz9LkQRCRDn84j9xcNdG7NSgZ3jGJC81A=" alt="Price" width="900"></div>
</div>

<h1>FEATURES</h1>

<div style="display: flex; justify-content: space-between; background-color: #f0f0f0; padding: 20px; font-family: Arial, sans-serif;">
  <div style="width: 30%; background-color: #e6f3ff; padding: 15px; border-radius: 10px;">
    <p style="color: #333;"><strong style="color: #0066cc;">SalePrice</strong>: the property's sale price in dollars. This is the target variable that you're trying to predict.</p>
    <p style="color: #333;"><strong style="color: #0066cc;">MSSubClass</strong>: The building class</p>
    <p style="color: #333;"><strong style="color: #0066cc;">MSZoning</strong>: The general zoning classification</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LotFrontage</strong>: Linear feet of street connected to property</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LotArea</strong>: Lot size in square feet</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Street</strong>: Type of road access</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Alley</strong>: Type of alley access</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LotShape</strong>: General shape of property</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LandContour</strong>: Flatness of the property</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Utilities</strong>: Type of utilities available</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LotConfig</strong>: Lot configuration</p>
    <p style="color: #333;"><strong style="color: #0066cc;">LandSlope</strong>: Slope of property</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Neighborhood</strong>: Physical locations within Ames city limits</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Condition1</strong>: Proximity to main road or railroad</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Condition2</strong>: Proximity to main road or railroad (if a second is present)</p>
    <p style="color: #333;"><strong style="color: #0066cc;">BldgType</strong>: Type of dwelling</p>
    <p style="color: #333;"><strong style="color: #0066cc;">HouseStyle</strong>: Style of dwelling</p>
    <p style="color: #333;"><strong style="color: #0066cc;">OverallQual</strong>: Overall material and finish quality</p>
    <p style="color: #333;"><strong style="color: #0066cc;">OverallCond</strong>: Overall condition rating</p>
    <p style="color: #333;"><strong style="color: #0066cc;">YearBuilt</strong>: Original construction date</p>
    <p style="color: #333;"><strong style="color: #0066cc;">YearRemodAdd</strong>: Remodel date</p>
    <p style="color: #333;"><strong style="color: #0066cc;">RoofStyle</strong>: Type of roof</p>
    <p style="color: #333;"><strong style="color: #0066cc;">RoofMatl</strong>: Roof material</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Exterior1st</strong>: Exterior covering on house</p>
    <p style="color: #333;"><strong style="color: #0066cc;">Exterior2nd</strong>: Exterior covering on house (if more than one material)</p>
  </div>
  
  <div style="width: 30%; background-color: #fff0e6; padding: 15px; border-radius: 10px;">
    <p style="color: #333;"><strong style="color: #cc6600;">MasVnrType</strong>: Masonry veneer type</p>
    <p style="color: #333;"><strong style="color: #cc6600;">MasVnrArea</strong>: Masonry veneer area in square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">ExterQual</strong>: Exterior material quality</p>
    <p style="color: #333;"><strong style="color: #cc6600;">ExterCond</strong>: Present condition of the material on the exterior</p>
    <p style="color: #333;"><strong style="color: #cc6600;">Foundation</strong>: Type of foundation</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtQual</strong>: Height of the basement</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtCond</strong>: General condition of the basement</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtExposure</strong>: Walkout or garden level basement walls</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtFinType1</strong>: Quality of basement finished area</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtFinSF1</strong>: Type 1 finished square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtFinType2</strong>: Quality of second finished area (if present)</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtFinSF2</strong>: Type 2 finished square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtUnfSF</strong>: Unfinished square feet of basement area</p>
    <p style="color: #333;"><strong style="color: #cc6600;">TotalBsmtSF</strong>: Total square feet of basement area</p>
    <p style="color: #333;"><strong style="color: #cc6600;">Heating</strong>: Type of heating</p>
    <p style="color: #333;"><strong style="color: #cc6600;">HeatingQC</strong>: Heating quality and condition</p>
    <p style="color: #333;"><strong style="color: #cc6600;">CentralAir</strong>: Central air conditioning</p>
    <p style="color: #333;"><strong style="color: #cc6600;">Electrical</strong>: Electrical system</p>
    <p style="color: #333;"><strong style="color: #cc6600;">1stFlrSF</strong>: First Floor square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">2ndFlrSF</strong>: Second floor square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">LowQualFinSF</strong>: Low quality finished square feet (all floors)</p>
    <p style="color: #333;"><strong style="color: #cc6600;">GrLivArea</strong>: Above grade (ground) living area square feet</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtFullBath</strong>: Basement full bathrooms</p>
    <p style="color: #333;"><strong style="color: #cc6600;">BsmtHalfBath</strong>: Basement half bathrooms</p>
    <p style="color: #333;"><strong style="color: #cc6600;">FullBath</strong>: Full bathrooms above grade</p>
  </div>
  
  <div style="width: 30%; background-color: #e6ffe6; padding: 15px; border-radius: 10px;">
    <p style="color: #333;"><strong style="color: #006600;">HalfBath</strong>: Half baths above grade</p>
    <p style="color: #333;"><strong style="color: #006600;">Bedroom</strong>: Number of bedrooms above basement level</p>
    <p style="color: #333;"><strong style="color: #006600;">Kitchen</strong>: Number of kitchens</p>
    <p style="color: #333;"><strong style="color: #006600;">KitchenQual</strong>: Kitchen quality</p>
    <p style="color: #333;"><strong style="color: #006600;">TotRmsAbvGrd</strong>: Total rooms above grade (does not include bathrooms)</p>
    <p style="color: #333;"><strong style="color: #006600;">Functional</strong>: Home functionality rating</p>
    <p style="color: #333;"><strong style="color: #006600;">Fireplaces</strong>: Number of fireplaces</p>
    <p style="color: #333;"><strong style="color: #006600;">FireplaceQu</strong>: Fireplace quality</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageType</strong>: Garage location</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageYrBlt</strong>: Year garage was built</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageFinish</strong>: Interior finish of the garage</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageCars</strong>: Size of garage in car capacity</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageArea</strong>: Size of garage in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageQual</strong>: Garage quality</p>
    <p style="color: #333;"><strong style="color: #006600;">GarageCond</strong>: Garage condition</p>
    <p style="color: #333;"><strong style="color: #006600;">PavedDrive</strong>: Paved driveway</p>
    <p style="color: #333;"><strong style="color: #006600;">WoodDeckSF</strong>: Wood deck area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">OpenPorchSF</strong>: Open porch area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">EnclosedPorch</strong>: Enclosed porch area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">3SsnPorch</strong>: Three season porch area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">ScreenPorch</strong>: Screen porch area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">PoolArea</strong>: Pool area in square feet</p>
    <p style="color: #333;"><strong style="color: #006600;">PoolQC</strong>: Pool quality</p>
    <p style="color: #333;"><strong style="color: #006600;">Fence</strong>: Fence quality</p>
    <p style="color: #333;"><strong style="color: #006600;">MiscFeature</strong>: Miscellaneous feature not covered in other categories</p>
    <p style="color: #333;"><strong style="color: #006600;">MiscVal</strong>: Value of miscellaneous feature</p>
    <p style="color: #333;"><strong style="color: #006600;">MoSold</strong>: Month Sold</p>
    <p style="color: #333;"><strong style="color: #006600;">YrSold</strong>: Year Sold</p>
    <p style="color: #333;"><strong style="color: #006600;">SaleType</strong>: Type of sale</p>
    <p style="color: #333;"><strong style="color: #006600;">SaleCondition</strong>: Condition of sale</p>
  </div>
</div>
