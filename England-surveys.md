# England Surveys

From searching for 'wales gp practice ratings' [Google's top result](https://www.google.co.uk/search?newwindow=1&q=wales+gp+practice+ratings&oq=wales+gp+practice+ratings&gs_l=serp.3...161143.166786.0.167854.14.14.0.0.0.3.285.1616.8j5j1.14.0.msedr...0...1c.1.62.serp..6.8.946.ZBplzoc_c0A) is for the [Prince of Wales practice in London](http://www.nhs.uk/Services/GP/ReviewsAndRatings/DefaultView.aspx?id=36235).  Turns out there's an encoded number in the link that relates to the practice:

36900 - goes to a "this is hidden" page:
http://www.nhs.uk/Services/GP/ReviewsAndRatings/DefaultView.aspx?id=36900

30001 - goes to a dentists:
http://www.nhs.uk/Services/GP/ReviewsAndRatings/DefaultView.aspx?id=30001

30000 - goes to a health practice and the postcode is automatically added to the URL and the GP part changes to 'dentists':
http://www.nhs.uk/Services/dentists/Overview/DefaultView.aspx?id=30000_SS155TR

36901 - is another doctors
http://www.nhs.uk/Services/GP/ReviewsAndRatings/DefaultView.aspx?id=36901

It might be an idea to slowly ping loads of codes and store the output using wget or cURL

37201 is a doctors in Crewe (we're getting further north!) but it jumps around a lot
http://www.nhs.uk/Services/GP/ReviewsAndRatings/DefaultView.aspx?id=37201






