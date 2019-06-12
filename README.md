
Project develop from Microsoft Project Oxford (Vision)
# New Features!
  - Remove DefaultHttpClient
  - Add OkHttpClient
  - Working with Android Pie (9.0)


## Install
1. Add it in your root build.gradle at the end of repositories:

	   maven { url 'https://jitpack.io' }
		
2. Add the dependency

	   implementation 'com.github.eddydn:EDMTDevCognitiveVision:1.3'
	 
## Usage
1. Declare Vision Client 

	    VisionServiceClient visionServiceClient =
            new VisionServiceRestClient("Your API KEY",
                    "DEFAULT API ENDPOINT"); // Ex : Endpoint : https://eastasia.api.cognitive.microsoft.com/vision/v1.0
		

