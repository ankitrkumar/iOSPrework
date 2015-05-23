This is the source repository for [iOS
Prework](http://prework.flatironschool.com/ios-development/) at The Flatiron School. Enjoy!

License
=======

Licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/ "Creative Commons License Page") License.


Quora Answer for my reference:(Author Joe Burgess)
<br>
<br>
<br>
I've been compiling the resources I used to learn iOS development for a while now. Now that I'm teaching an iOS course at Flatiron School I finally got around to actually cleaning it up and getting it out of an evernote note. I'm going to use it primarily for my students, but the goal for the the list was to get you up and coding as soon as possible and I figure a ton of people will find that useful.
<br><br>
The entire list is just a simple markdown file on github, so feel free to tell me I'm wrong by raising an issue, or adding content by sending a pull request.
<br><br>
iOS-TheGoodParts
<br><br>
The biggest issue when learning iOS is simply the firehose of information that is available, as well as the firehose of topics to research. In my list I give a pretty exhaustive list of resources for each topic, but here are the topics I view as some of the most important. I'd also recommend learning these topics in this order. 
<br><br>
My goal whenever I'm learning a new topic is layers of quality. From the very first topic you should be able to write a simple app. With every subsequent topic learned you should be able to make your app even more awesome. I really enjoy learning topics like this because I can get immediate gratification for my efforts. Instant gratification is the best :)
<br>
<br><br>
Basic iOS<br>
Learn how to make applications using the autogenerator tools of Xcode. These are things like storyboards and the Xcode generators like the master-details template. Inevitably this will be an application that uses a UITableView and then some sort of detail view with some buttons. Understand how connecting UI elements with the IBActions and instance variables works.

Objective-C<br>
The language of iOS. You can easily write apps without getting super familiar with Objective-C but you should learn some of the basic features of Objective-C. I'd make sure you understand @property and how method passing. In the end Objective-C is a pretty standard Objective Orientated language.

Object-oriented Principles<br>
Pretty much you need to learn and understand the Delegate and Protocol patterns. You'll use them constantly. Everything else is just icing on the cake

Core Data<br>
Besides reading tutorials/articles on the topic playing around with the core data Xcode template is a great way to understand the basics of Core Data. Core Data contains an insane amount of classes and interconnected parts, which makes it very difficult to get going with. As you're reading all this, keep reminding yourself that Core Data is not a database ORM.

API Integration<br>
Play around with Helios.io because it's super awesome and will get you started with networking and the incredibly complex world of dealing with that stuff on iOS. Eventually you'll move onto integrating other SDKs (like foursquare, instagram, twitter, etc) but just start simple and move forward.

Core Location<br>
This will be the first serious use of delegation. Really the two topics you need to understand are the MapKit view and the CLLocationManagerDelegate.

Mobile Design<br>
This is a slightly nebulous topic. I've provided some good resources on my github project, but the most important thing to learn is to never. ever. ever. ever. block the main UI thread. When you click something, the UI should always respond

Customizing UIKit<br>
Customizing the UI really adds an air of professionalism to your app. The big UI elements to learn how to customize are the navigationbar, uitableviewcells, buttons and the new collection view cells. These are the bread and butter of iOS apps and everyone customizes them.

Hardware<br>
iOS devices have a whole host of hardware to play with. To get going I would just focus on the camera/photo library. That's probably the only hardware pieces you'll end up using.

Core Animation<br>
Pretty much the point of Core Animation is for the cool factor. That's why I put it last in this list. I don't find that animation really adds much in terms of "features" but I think it's pretty cool and can be a lot of fun. The most important stuff to learn here when/how to use the transitions from UIView to UIView.
