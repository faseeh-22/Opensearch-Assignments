# Assignment:

Please create the following visualizations:

1.Use Vertical bar visualization, place count on y-axis and elb status count on x-axis for only 2xx.

2.Use Vertical bar visualization, place count on y-axis and elb status count on x-axis for only 3xx.

3.Use Vertical bar visualization, place count on y-axis and elb status count on x-axis and then group countries as well on x-axis.

4.And add these visualizations to your dashboard.

To complete the assignment, follow the below steps:



**NOTE:** We are first creating Vertical Bar Visualization for 2xx status code.



## Step 1. Accessing OpenSearch:

 Open your preferred web browser and navigate to the OpenSearch URL.

    
    
## Step 2. Login to OpenSearch:

Enter your credentials (username and password) to login to the OpenSearch cluster.



## Step 3. Navigate to Visualize:

In the OpenSearch dashboard, click on the "Visualize" section.



## Step 4. Creating New Vertical Bar Visualization:

Click on the "Create visualization" button, select "Vertical Bar", to start creating a new "Vertical Bar" Visualization.



## Step 5. Choose Data Source:

Select the appropriate index pattern that contains the data you want to visualize.
        

    
## Step 6. Selecting Required Options:

1.Under the "Buckets" section, click on the "Add" button to add a new bucket.

2.Choose the "X-axis" option for grouping.

3.Select the "Terms" in the "Aggregation" field.

4.In the "Field" option, choose the field you want to group by (e.g "elb_status_code").

5.In the "Order by" field, select the "Metric:Count" option.

6.In the "Size" field, enter the value "5".

7.In "Custom label" field, give name "elb status code".

8.Now go to the top, click on the calendar logo and select the "Last 1 hour" option.

9.On top left corner, under the "Search" field, click the "Add filter" option.

10.Select the field "elb_status_code" and in the "Operator" dropdown, select "is not between" option.

11.Now give the desired range for each status code you want to exclude (e.g 300 to 399, 400 to 499, 500 to 599 etc.).
    

     
 **NOTE:** Don`t change any further settings.  
	 

  
## Step 7. Saving Visualization:
    
1.Navigate to the top, and click on "Save".

2.Give your visualization any required or suitable name.

3.Select on "Save as new virtualization".

4.Click on the "Save" button.
    

    
 **NOTE:** Follow the above steps for "3xx status code" visualization and also for the 3rd visualization. In 3rd visualization you only have to click on twice "Add" option
      	under "Buckets" section,  to create a sub bucket e.g first bucket:"X-axis", second bucket:"Split series", the "Field" option should be "geoip.country_name.keyword"
      	And Don`t change any further settings, just save them with any required names.

       
    
## Step 8. Adding Visualization on Dashboard:
    
1.Create a new dashboard or select any existing dashboard.

2.On top of the dashboard page click on the "Add" option.

3.Type the names of your visualizations and click on their names one by one.(They will be added automatically on your dashboard, when you click on their names).
    

	 
 **NOTE:** The names of each visualization should include "-" between them, such as "My - Status Code", "Dummy - Status Code - Countries".

    
    
 **NOTE:** If any adjustments are needed or required for visualizations, then adjust the visualizations or drag the visualizations according to the situation or requirements.
    
      	 
    
	

