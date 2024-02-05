
# Assignment:

Try to do nested group in vertical bar visualization:
First group on the basis of uri and the second group on the basis of status code. And try to group them on a daily basis.
 
To complete the assignment, follow the below steps.



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
    
    
    
## Step 6. Selecting Required Options for (OR Group By Fields):

1.Under the "Buckets" section, click on the "Add" button to add a new bucket.
    
2.Choose the "X-axis" option for grouping.
    
3.Select the "Terms" in the "Aggregation" field.
    
4.In the "Field" option, choose the field you want to group by (e.g "elb_status_code").
    
5.In the "Order by" field, select the "Metric:Count" option.
    
6.In "Size" field, enter value "5"
    
7.In "Custom label" field, give name "elb status code".
    
8.Now go to the top, click on the calendar logo and select the "Last 1 hour" option.
    
9.Again Under the "Buckets" section, click on the "Add" button to add a sub bucket.
    
10.Choose the "Split Series" option for grouping.
    
11.Select the "Terms" in the "Aggregation" field.
    
12.In the "Field" option, choose the field you want to group by (e.g "http_uri.keyword").
    
13.In "Order by" field, select "Metric:Count" option.
    
14.In "Size" field, enter value "5".
    
15.In "Custom label" field, give name "URI".
       
    
	
**NOTE:**  Don't change any further settings.  
    
    
	 
## Step 7. Saving Visualization:
    
1.Navigate to the top, and click on "Save".

2.Give your visualization any required or suitable name.

3.Select on "Save as new virtualization".

4.Click on the "Save" button.
    
    
       	 
## Step 8. Adding Visualization on Dashboard:
    
1.Create a new dashboard or select any existing dashboard.

2.On top of the dashboard page click on the "Add" option.

3.Type the name of your visualization and click on the name. (It will added automatically on your dashboard, when you click on the name).
    
    
    
**NOTE:** The name of visualization should include "-" between them, such as "My - Status Code", "Dummy - Status Code - Countries".
    
    
    
**NOTE:** If any adjustments are needed or required for visualization, then adjust the visualization or drag the visualization according to the situation or requirements.
    
       	

