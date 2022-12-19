Perform Foundational Infrastructure Tasks in Google Cloud: Challenge Lab


username-1 :-
username-2  :-
Password :- 
Project ID :-



step - 1 : Create Bucket
				Cloud Storage > Create Bucket
				
				Name : YOUR_PROJECT_ID
				Region : us-east1
				
				Create

Step - 2 : Create Pub/Sub Topic
				Pub/Sub > Topic > Create Topic
				
				Topic ID : jooli
				
				Create Topic

Step - 3 : Create Function
			
			Cloud Function > create Function 
			Name : [given name]
			Region : us-east1
			
			Trigger
				Trigger type : Cloud Storage
				Event type : Finalize/Create
				Bucket : Select_your_Project_id
				
				click to save
			 			
			
				Click on Next
				
				Entry Point : thumbnail
			index.js :
						// Chenge All file code With your give Code 
						Also change REPLACE_WITH_YOUR_TOPIC_ID in code (Line No. : 15)(jooli)
						
			package.json : 
						// Chenge All file code With your give Code
						
			
			Click on Deploy

Step - 4 :
			Download given image : https://storage.googleapis.com/cloud-training/gsp315/map.jpg
			Go To -> Storage / Your_Bucket
			Upload file -> Upload Image 
			

Step - 5 : 	
			Go to -> IAM & Admin
			Find UserName-2 in Permissions
			
			Select it and click on (pencil Icon)
			Delete View Role
			Save
