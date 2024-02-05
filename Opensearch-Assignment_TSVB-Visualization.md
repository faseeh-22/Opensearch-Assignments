# Assignment:

Create  new TSVB visualizations which are grouped by following:
	
1.cip
	
2.country
	
3.status_code
	
4.method
	
5.http_uri

To complete the assignment, follow the below steps:



## Step 1. Accessing OpenSearch:

Open your preferred web browser and navigate to the OpenSearch URL.
    
    
	
## Step 2. Login to OpenSearch:

Enter your credentials (username and password) to login to the OpenSearch cluster.



## Step 3. Navigate to TSVB:

In the OpenSearch dashboard, click on the "Visualize" section.



## Step 4. Creating New TSVB Visualization:

Click on the "Create visualization" button, select TSVB, to start creating a new TSVB visualization.


	
## Step 5. Choose Data Source:

Select the appropriate index pattern that contains the data you want to visualize. This should match the data you want to group by the specified fields.
    


## Step 6. Configure TSVB Visualization:

1.Under the "Metrics" section, See "Aggregation" field.

2.Choose the suitable "Aggregation"you want to visualize (e.g."Count").

3.In "Group by" options, select "Terms" and in "By" field select "geoip.country_name.keyword" option.

4.In "Order By" field, select "Count".

5.In "Top" field, input numeric values according to your requirement (e.g 10).

6.Now click on "Panel Options" section, in "Time Field" select "request_creation_time" option.

7.In "Index Pattern" field, type "tap*" or any required source.

8.In "Interval" field, type "1h".
    
    
    
**NOTE:** Don`t change any further settings.
    
    
    
## Step 7. Save Visualization:

1.Once you are satisfied with the visualization, click on the "Save" button.

2.Provide a meaningful name and description for the visualization.

3.Choose the appropriate dashboard and add this visualization in it.
    
    
    
**Note:** For other visualizations the method is same as narrated in above steps, just follow the "Step 6" for other visualizations and in the "By" field which is in the "Metrics" section under the "Data" section.



Try to create each remaining visualizations  select the provided options for each separate visualizations during their creation process :
    For status code: "elb_status_code", for URI: "http_uri.keyword", for client ip: "c_ip.keyword", for method: "http_method.keyword"
    
And don`t forget to save them with their names.
    
    
    
    
	

