# diveintech2.github.io

To add a user, we need to change 2 parts of the code (ocassionally 3, see bottom of page) : 

Part 1 : the profile (see example)
  - instead of typeMakerDesignOrFreeLance, put the words "makers" or "designers" or "freelancers"
  - instead of CityName1, put their City (CityName2, if it's San Francisco, or any 2 words city, write it this way: 'San Francisco')
  - instead of profileName, put their profile name (duh)
  - instead of twitterAdress, put their twitter url
  - instead of twitterDescription, put their twitter description
  - instead of twitterPic, put their twitter picture location (it should be saved in the img folder for now ... we can make a GET request to their API at some point!)

<!-- profile name -->
				<li class="mix typeMakerDesignOrFreeLance CityName1 radio3 CityName2">
                    <div class="image-container">
                    <div class="twitter">
                        <a href="twitterAddress" target="_blank">
                            <img class="icon icon-twitter" src="img/twitter.png" alt="profileName" data-pin-nopin="true">
                        </a>
                    </div>
                    <a href="twitterAddress" target="_blank">
                        <div class="name">profileName</div>
                        <div class="blurb">
                              twitter description
                        </div>
                        <img src="twitterPic" alt="profileName">
                    </a>
                    </div>
                </li>

Example :

<!-- Ari Vaniderstine -->
				<li class="mix makers Montreal radio2 Montreal">
                    <div class="image-container">
                        <div class="twitter">
                            <a href="https://twitter.com/imariari" target="_blank">
                                <img class="icon icon-twitter" src="img/twitter.png" alt="Ari Vaniderstine" data-pin-nopin="true"></a>
                        </div>
                        <div class="name">Ari Vaniderstine</div>
                        <a href="https://twitter.com/imariari" target="_blank">
                            <div class="blurb">
                            Technical consultant by trade; blogger and hacker by choice. I get excited about design, development, community, marketing, writing, evangelism, and hedgehogs.                   
                            </div>
                            <img src="img/img-2-ari.jpg" alt="Ari Vaniderstine">
                        </a>
                    </div>
                </li>


                
Part 2 : the city
  - cityName : put their city name (don't forget that theire is a . before the city name!)
  - increment the number of checbox if we add a new city : say we add Cracovia, that will be checkbox7

<!-- city name -->
	        			<li>
			<input class="filter" data-filter=".cityName" type="checkbox" id="checkbox6">
			<label class="checkbox-label" for="checkbox6">Belgrade</label>
		</li>

Example :

<!-- city name -->
	        			<li>
			<input class="filter" data-filter=".Belgrade" type="checkbox" id="checkbox6">
			<label class="checkbox-label" for="checkbox6">Belgrade</label>
		</li>
		
Part 3 : space between profile pics
- for any new row (pair of 4 profile pic added), add this at the end of the profile pic sections (just before where the city section starts)

<!-- city name -->
<li class="gap"></li>


                
                
