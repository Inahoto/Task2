1. Workspace name: **Rakuten-API-Test**
2. Collection Name : **Dog Breed**
3. **Added 2 API- (1. To list all the Breeds and 2. To List Sub Breeds)**
4. '**List Sub Breed' API - under 'Tests' tabs i have perform the following validation:**
     1. Converted to Schema from API response
     2. Declared AJV Library to Load and read the API Schema
     3. Perform schema validation with ajv library
     4. Perform Data Validation for the dog Breed names (For this validation i have used array to store Breeds ans then given assertion to validate the data)
     5. Validate if 'english' breed is present in the response
     6. Validate if the response message is in Array
     7.  Validate the Response code is 200

5. **List All Breeds** API - under 'Tests' i have performed the following validation:**
     1. Capture the complete API Response , create Object.keys to capture the breeds value
     2. Create individual lists for each breed
     3. Used for each loop to iterate over the response and print the breed in console
     4. Validate if 'basenji'breed is present in the response
     5. Response Time Validation less than 200 milisecond
     6. Validate state code is 200
