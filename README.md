# Google-Calendar-API-Project
</p>Using Google Calendar API to access personal calendars and create events with a simple GUI.<p/>

</p>All installation information can also be found on [Google Calendar API Quickstart](https://console.cloud.google.com/welcome?authuser=1) <p/>

## Installations
</p>Java 1.8 or greater.<p/>
</p>Gradle 2.3 or greater.<p/>
</p>A Google Cloud project with the API enabled. To create a project and enable an API, refer to Create a project and enable the API.<p/>

## Creating a Google Cloud Project
Open [Google Cloud Console](https://console.cloud.google.com/welcome?authuser=1)
<img width="1430" alt="Screen Shot 2022-06-29 at 3 41 05 PM" src="https://user-images.githubusercontent.com/72324875/176814383-efb7e9bc-1f01-4f25-96fa-4ab8ec5ad3cd.png">
</p>At the top-left, click Menu > IAM & Admin > Create a Project.<p/>
<img width="1430" alt="Screen Shot 2022-06-29 at 3 41 05 PM" src="https://user-images.githubusercontent.com/72324875/176819275-32590c71-395c-4846-86d4-76008dd9ab87.png">
<img width="1422" alt="Screen Shot 2022-06-30 at 11 44 54 PM" src="https://user-images.githubusercontent.com/72324875/176819778-acf5eafd-1c47-4af6-8232-ea9c3b1aa840.png">
</p>Choose a Project ID (Can't be altered later on) and a location for the project<p/>
<img width="1411" alt="Screen Shot 2022-07-01 at 12 39 40 AM" src="https://user-images.githubusercontent.com/72324875/176824559-aa1fbcec-2949-4348-83b7-ab7fae456946.png">
</p>Click Create when you are satisfied<p/>

## Setting up the API
</p>After Creating your project you should be brought to something like this below <p/>
<img width="1425" alt="Screen Shot 2022-07-01 at 12 40 50 AM" src="https://user-images.githubusercontent.com/72324875/176824668-cb8e58ab-4e87-48ed-bcb3-152dc1dd06a9.png">
</p>Click on "Go to APIs Overview"<p/>
<img width="1425" alt="Screen Shot 2022-07-01 at 12 40 50 AM" src="https://user-images.githubusercontent.com/72324875/176827944-a9fd1065-a793-4047-833d-023b8134308b.png">
</p>Now go to "ENABLE APIS AND SERVICES"<p/>
<img width="1425" alt="Screen Shot 2022-07-01 at 1 11 36 AM" src="https://user-images.githubusercontent.com/72324875/176828118-cfcea8fc-ba90-42a1-96d8-a68956476cf0.png">
</p>In the searchbar type in "Google Calendar API"<p/>
<img width="1420" alt="Screen Shot 2022-07-01 at 1 13 59 AM" src="https://user-images.githubusercontent.com/72324875/176828272-f2bc4c97-1361-4c90-9644-508739cebd3c.png">
</p>You'll see two different results, however we only care about the first one<p/>
<img width="1426" alt="Screen Shot 2022-07-01 at 1 16 19 AM" src="https://user-images.githubusercontent.com/72324875/176828687-6d141b10-c214-41b9-836f-0094ed76eef5.png">
</p>After clicking on the first result, enable the API<p/>
<img width="1423" alt="Screen Shot 2022-07-01 at 1 18 19 AM" src="https://user-images.githubusercontent.com/72324875/176828817-1de39e62-0c99-4ffe-af11-9cea795dd328.png">

## Obtaining Credentials to use the API
</p>Now that we have created our project and enabled the API we're going to be using. It's time to obtain credentials grant us permission to use the API from Google.</p>


