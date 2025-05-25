1. Pull latest dev branch on career-advisor-app
2. Then run npx ampx sandbox on the career-advisor-app terminal
3. Before they synthesizing of the backend begins on the terminal
4. In your local career-advisor-app, you should have a file amplify_outputs.json
  - there, you should have a "url": "https://e6ru3it3hjbtvffmbk2y4jzv5m.appsync-api.us-west-2.amazonaws.com/graphql", 
  - get the e6ru3it3hjbtvffmbk2y4jzv5m id from that url
5. Go to https://us-west-2.console.aws.amazon.com/appsync/home?region=us-west-2#/apis:
  - look for the e6ru3it3hjbtvffmbk2y4jzv5m id from step #4 above
  - against that id, you will have API ID, like mine is alek4h7jlreffeoe5tocxgnx2u
  - copy that
6. Go to https://us-west-2.console.aws.amazon.com/dynamodbv2/home?region=us-west-2#dashboard
  - click on "View all tables"
  - filter by the id in step #5
  - confirm your tables are all there from resource.ts
7. In the careerCompass.ipynb, please replace this id from #6: API_ID = "alek4h7jlreffeoe5tocxgnx2u" in the top script and run all the populate data
8. Create a folder called Datasets on the main level and download all the files in this drive to it: https://drive.google.com/drive/folders/1fCwNm1LR6whsKwBTeCTHtisXiJhbJi6u
Run the script! :) 

Setting up python:

Packages I have installed under Python:
pip install -r requirements.txt